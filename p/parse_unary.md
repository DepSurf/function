# Function: <code>parse_unary</code>

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
In kernel/trace/trace_events_hist.c (ffffffff811a0c17)
Location: kernel/trace/trace_events_hist.c:2585
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_expr
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
In kernel/trace/trace_events_hist.c (ffffffff811ae357)
Location: kernel/trace/trace_events_hist.c:2701
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_expr
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
In kernel/trace/trace_events_hist.c (ffffffff811bc434)
Location: kernel/trace/trace_events_hist.c:2857
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_expr
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
In kernel/trace/trace_events_hist.c (ffffffff811c7c94)
Location: kernel/trace/trace_events_hist.c:2970
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_expr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e5c6b)
Location: kernel/trace/trace_events_hist.c:2065
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_expr
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
In kernel/trace/trace_events_hist.c (ffffffff811e369b)
Location: kernel/trace/trace_events_hist.c:2075
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_expr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct hist_field *parse_unary(struct hist_trigger_data *hist_data, struct trace_event_file *file, char *str, long unsigned int flags, char *var_name, unsigned int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e4780)
Location: kernel/trace/trace_events_hist.c:2111
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:parse_expr
```
**Symbols:**

```
ffffffff811e4780-ffffffff811e4962: parse_unary (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct hist_field *parse_unary(struct hist_trigger_data *hist_data, struct trace_event_file *file, char *str, long unsigned int flags, char *var_name, unsigned int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff81215490)
Location: kernel/trace/trace_events_hist.c:2162
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:parse_expr
```
**Symbols:**

```
ffffffff81215490-ffffffff81215689: parse_unary (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct hist_field *parse_unary(struct hist_trigger_data *hist_data, struct trace_event_file *file, char *str, long unsigned int flags, char *var_name, unsigned int *n_subexprs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff81252860)
Location: kernel/trace/trace_events_hist.c:2456
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:parse_expr
```
**Symbols:**

```
ffffffff81252860-ffffffff81252b0c: parse_unary (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct hist_field *parse_unary(struct hist_trigger_data *hist_data, struct trace_event_file *file, char *str, long unsigned int flags, char *var_name, unsigned int *n_subexprs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812a1dd0)
Location: kernel/trace/trace_events_hist.c:2506
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:parse_expr
```
**Symbols:**

```
ffffffff812a1dd0-ffffffff812a207c: parse_unary (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct hist_field *parse_unary(struct hist_trigger_data *hist_data, struct trace_event_file *file, char *str, long unsigned int flags, char *var_name, unsigned int *n_subexprs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812bfa40)
Location: kernel/trace/trace_events_hist.c:2528
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:parse_expr
```
**Symbols:**

```
ffffffff812bfa40-ffffffff812bfcdb: parse_unary (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct hist_field *parse_unary(struct hist_trigger_data *hist_data, struct trace_event_file *file, char *str, long unsigned int flags, char *var_name, unsigned int *n_subexprs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812dc060)
Location: kernel/trace/trace_events_hist.c:2521
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:parse_expr
```
**Symbols:**

```
ffffffff812dc060-ffffffff812dc2fb: parse_unary (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffff800010247fec)
Location: kernel/trace/trace_events_hist.c:2970
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_expr
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
In kernel/trace/trace_events_hist.c (c0000000002e1b34)
Location: kernel/trace/trace_events_hist.c:2970
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_expr
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
In kernel/trace/trace_events_hist.c (ffffffff811c02b4)
Location: kernel/trace/trace_events_hist.c:2970
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_expr
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
In kernel/trace/trace_events_hist.c (ffffffff811b3094)
Location: kernel/trace/trace_events_hist.c:2970
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_expr
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
In kernel/trace/trace_events_hist.c (ffffffff811be084)
Location: kernel/trace/trace_events_hist.c:2970
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_expr
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
In kernel/trace/trace_events_hist.c (ffffffff811cc124)
Location: kernel/trace/trace_events_hist.c:2970
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_expr
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int *n_subexprs</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int level</code>
</li>
</ul>
</details>
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
