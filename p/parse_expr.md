# Function: <code>parse_expr</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
struct hist_field *parse_expr(struct hist_trigger_data *hist_data, struct trace_event_file *file, char *str, long unsigned int flags, char *var_name, unsigned int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811a0b30)
Location: kernel/trace/trace_events_hist.c:2688
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:__create_val_field
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
```
**Symbols:**

```
ffffffff811a0b30-ffffffff811a0f86: parse_expr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct hist_field *parse_expr(struct hist_trigger_data *hist_data, struct trace_event_file *file, char *str, long unsigned int flags, char *var_name, unsigned int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811ae270)
Location: kernel/trace/trace_events_hist.c:2804
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:__create_val_field
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
```
**Symbols:**

```
ffffffff811ae270-ffffffff811ae6e5: parse_expr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct hist_field *parse_expr(struct hist_trigger_data *hist_data, struct trace_event_file *file, char *str, long unsigned int flags, char *var_name, unsigned int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bc230)
Location: kernel/trace/trace_events_hist.c:2961
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:__create_val_field
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
```
**Symbols:**

```
ffffffff811bc230-ffffffff811bc6e2: parse_expr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct hist_field *parse_expr(struct hist_trigger_data *hist_data, struct trace_event_file *file, char *str, long unsigned int flags, char *var_name, unsigned int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c7a90)
Location: kernel/trace/trace_events_hist.c:3074
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:__create_val_field
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
```
**Symbols:**

```
ffffffff811c7a90-ffffffff811c7f42: parse_expr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct hist_field *parse_expr(struct hist_trigger_data *hist_data, struct trace_event_file *file, char *str, long unsigned int flags, char *var_name, unsigned int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e5a10)
Location: kernel/trace/trace_events_hist.c:2169
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_key_field
  - kernel/trace/trace_events_hist.c:__create_val_field
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
```
**Symbols:**

```
ffffffff811e5a10-ffffffff811e5f15: parse_expr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct hist_field *parse_expr(struct hist_trigger_data *hist_data, struct trace_event_file *file, char *str, long unsigned int flags, char *var_name, unsigned int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e3440)
Location: kernel/trace/trace_events_hist.c:2179
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_key_field
  - kernel/trace/trace_events_hist.c:__create_val_field
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
```
**Symbols:**

```
ffffffff811e3440-ffffffff811e3945: parse_expr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct hist_field *parse_expr(struct hist_trigger_data *hist_data, struct trace_event_file *file, char *str, long unsigned int flags, char *var_name, unsigned int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e4970)
Location: kernel/trace/trace_events_hist.c:2222
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_key_field
  - kernel/trace/trace_events_hist.c:__create_val_field
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_unary
```
**Symbols:**

```
ffffffff811e4970-ffffffff811e4e62: parse_expr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct hist_field *parse_expr(struct hist_trigger_data *hist_data, struct trace_event_file *file, char *str, long unsigned int flags, char *var_name, unsigned int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff81214b90)
Location: kernel/trace/trace_events_hist.c:2275
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_key_fields
  - kernel/trace/trace_events_hist.c:create_val_fields
  - kernel/trace/trace_events_hist.c:create_var_field
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_unary
```
**Symbols:**

```
ffffffff81214b90-ffffffff81215127: parse_expr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct hist_field *parse_expr(struct hist_trigger_data *hist_data, struct trace_event_file *file, char *str, long unsigned int flags, char *var_name, unsigned int *n_subexprs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff81251ad0)
Location: kernel/trace/trace_events_hist.c:2588
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_key_fields
  - kernel/trace/trace_events_hist.c:__create_val_field
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_unary
```
**Symbols:**

```
ffffffff81251ad0-ffffffff812522c7: parse_expr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct hist_field *parse_expr(struct hist_trigger_data *hist_data, struct trace_event_file *file, char *str, long unsigned int flags, char *var_name, unsigned int *n_subexprs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812a0de0)
Location: kernel/trace/trace_events_hist.c:2638
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_key_fields
  - kernel/trace/trace_events_hist.c:__create_val_field
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_unary
```
**Symbols:**

```
ffffffff812a0de0-ffffffff812a15d4: parse_expr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct hist_field *parse_expr(struct hist_trigger_data *hist_data, struct trace_event_file *file, char *str, long unsigned int flags, char *var_name, unsigned int *n_subexprs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812be9d0)
Location: kernel/trace/trace_events_hist.c:2660
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_key_fields
  - kernel/trace/trace_events_hist.c:__create_val_field
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_unary
```
**Symbols:**

```
ffffffff812be9d0-ffffffff812bf1ba: parse_expr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct hist_field *parse_expr(struct hist_trigger_data *hist_data, struct trace_event_file *file, char *str, long unsigned int flags, char *var_name, unsigned int *n_subexprs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812db030)
Location: kernel/trace/trace_events_hist.c:2653
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_key_fields
  - kernel/trace/trace_events_hist.c:__create_val_field
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_unary
```
**Symbols:**

```
ffffffff812db030-ffffffff812db81a: parse_expr (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct hist_field *parse_expr(struct hist_trigger_data *hist_data, struct trace_event_file *file, char *str, long unsigned int flags, char *var_name, unsigned int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffff800010247d30)
Location: kernel/trace/trace_events_hist.c:3074
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:__create_val_field
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
```
**Symbols:**

```
ffff800010247d30-ffff800010248194: parse_expr (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct hist_field *parse_expr(struct hist_trigger_data *hist_data, struct trace_event_file *file, char *str, long unsigned int flags, char *var_name, unsigned int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (c0000000002e1890)
Location: kernel/trace/trace_events_hist.c:3074
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:__create_val_field
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
```
**Symbols:**

```
c0000000002e1890-c0000000002e1eac: parse_expr (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
struct hist_field *parse_expr(struct hist_trigger_data *hist_data, struct trace_event_file *file, char *str, long unsigned int flags, char *var_name, unsigned int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c00b0)
Location: kernel/trace/trace_events_hist.c:3074
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:__create_val_field
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
```
**Symbols:**

```
ffffffff811c00b0-ffffffff811c0562: parse_expr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct hist_field *parse_expr(struct hist_trigger_data *hist_data, struct trace_event_file *file, char *str, long unsigned int flags, char *var_name, unsigned int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811b2e90)
Location: kernel/trace/trace_events_hist.c:3074
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:__create_val_field
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
```
**Symbols:**

```
ffffffff811b2e90-ffffffff811b3342: parse_expr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct hist_field *parse_expr(struct hist_trigger_data *hist_data, struct trace_event_file *file, char *str, long unsigned int flags, char *var_name, unsigned int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bde80)
Location: kernel/trace/trace_events_hist.c:3074
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:__create_val_field
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
```
**Symbols:**

```
ffffffff811bde80-ffffffff811be332: parse_expr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct hist_field *parse_expr(struct hist_trigger_data *hist_data, struct trace_event_file *file, char *str, long unsigned int flags, char *var_name, unsigned int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811cbf20)
Location: kernel/trace/trace_events_hist.c:3074
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:__create_val_field
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
```
**Symbols:**

```
ffffffff811cbf20-ffffffff811cc3d2: parse_expr (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
