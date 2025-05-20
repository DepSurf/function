# Function: <code>create_hist_field</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct hist_field *create_hist_field(struct ftrace_event_field *field, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff81172f60)
Location: kernel/trace/trace_events_hist.c:347
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
```
**Symbols:**

```
ffffffff81172f60-ffffffff811730f0: create_hist_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct hist_field *create_hist_field(struct ftrace_event_field *field, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8117e760)
Location: kernel/trace/trace_events_hist.c:347
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
**Symbols:**

```
ffffffff8117e760-ffffffff8117e8f0: create_hist_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct hist_field *create_hist_field(struct ftrace_event_field *field, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff81181350)
Location: kernel/trace/trace_events_hist.c:348
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
**Symbols:**

```
ffffffff81181350-ffffffff811814c0: create_hist_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct hist_field *create_hist_field(struct ftrace_event_field *field, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8118eca0)
Location: kernel/trace/trace_events_hist.c:385
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_hist_field
```
**Symbols:**

```
ffffffff8118eca0-ffffffff8118ee4b: create_hist_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct hist_field *create_hist_field(struct hist_trigger_data *hist_data, struct ftrace_event_field *field, long unsigned int flags, char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811a0240)
Location: kernel/trace/trace_events_hist.c:2164
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_var_ref
  - kernel/trace/trace_events_hist.c:create_hist_field
```
**Symbols:**

```
ffffffff811a0240-ffffffff811a0539: create_hist_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct hist_field *create_hist_field(struct hist_trigger_data *hist_data, struct ftrace_event_field *field, long unsigned int flags, char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811ac260)
Location: kernel/trace/trace_events_hist.c:2256
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_var_ref
  - kernel/trace/trace_events_hist.c:create_hist_field
```
**Symbols:**

```
ffffffff811ac260-ffffffff811ac567: create_hist_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct hist_field *create_hist_field(struct hist_trigger_data *hist_data, struct ftrace_event_field *field, long unsigned int flags, char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811ba4c0)
Location: kernel/trace/trace_events_hist.c:2410
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_var_ref
  - kernel/trace/trace_events_hist.c:create_hist_field
```
**Symbols:**

```
ffffffff811ba4c0-ffffffff811ba7ae: create_hist_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct hist_field *create_hist_field(struct hist_trigger_data *hist_data, struct ftrace_event_field *field, long unsigned int flags, char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c5b20)
Location: kernel/trace/trace_events_hist.c:2492
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_var_ref
  - kernel/trace/trace_events_hist.c:create_hist_field
```
**Symbols:**

```
ffffffff811c5b20-ffffffff811c5e2b: create_hist_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct hist_field *create_hist_field(struct hist_trigger_data *hist_data, struct ftrace_event_field *field, long unsigned int flags, char *var_name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e6528)
Location: kernel/trace/trace_events_hist.c:1587
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_key_field
  - kernel/trace/trace_events_hist.c:create_var_ref
Direct callers:
  - kernel/trace/trace_events_hist.c:create_val_fields
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_hist_field
```
**Symbols:**

```
ffffffff811e4990-ffffffff811e4cb9: create_hist_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct hist_field *create_hist_field(struct hist_trigger_data *hist_data, struct ftrace_event_field *field, long unsigned int flags, char *var_name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e3ea8)
Location: kernel/trace/trace_events_hist.c:1597
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_key_field
  - kernel/trace/trace_events_hist.c:create_var_ref
Direct callers:
  - kernel/trace/trace_events_hist.c:create_val_fields
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_hist_field
```
**Symbols:**

```
ffffffff811e23c0-ffffffff811e26e9: create_hist_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct hist_field *create_hist_field(struct hist_trigger_data *hist_data, struct ftrace_event_field *field, long unsigned int flags, char *var_name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e52fe)
Location: kernel/trace/trace_events_hist.c:1621
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_key_field
  - kernel/trace/trace_events_hist.c:create_var_ref
Direct callers:
  - kernel/trace/trace_events_hist.c:create_val_fields
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_hist_field
```
**Symbols:**

```
ffffffff811e3f50-ffffffff811e427b: create_hist_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct hist_field *create_hist_field(struct hist_trigger_data *hist_data, struct ftrace_event_field *field, long unsigned int flags, char *var_name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff81215736)
Location: kernel/trace/trace_events_hist.c:1659
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_key_fields
  - kernel/trace/trace_events_hist.c:create_val_fields
  - kernel/trace/trace_events_hist.c:create_var_ref
Direct callers:
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_hist_field
```
**Symbols:**

```
ffffffff812144a0-ffffffff812147d6: create_hist_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct hist_field *create_hist_field(struct hist_trigger_data *hist_data, struct ftrace_event_field *field, long unsigned int flags, char *var_name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812539d9)
Location: kernel/trace/trace_events_hist.c:1903
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_key_fields
  - kernel/trace/trace_events_hist.c:create_var_ref
Direct callers:
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_hist_field
```
**Symbols:**

```
ffffffff81250a00-ffffffff81250d8a: create_hist_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct hist_field *create_hist_field(struct hist_trigger_data *hist_data, struct ftrace_event_field *field, long unsigned int flags, char *var_name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812a214a)
Location: kernel/trace/trace_events_hist.c:1939
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_key_fields
  - kernel/trace/trace_events_hist.c:create_val_fields
  - kernel/trace/trace_events_hist.c:create_var_ref
Direct callers:
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_hist_field
```
**Symbols:**

```
ffffffff8129fc80-ffffffff8129ffc4: create_hist_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct hist_field *create_hist_field(struct hist_trigger_data *hist_data, struct ftrace_event_field *field, long unsigned int flags, char *var_name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812bf370)
Location: kernel/trace/trace_events_hist.c:1946
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_val_fields
  - kernel/trace/trace_events_hist.c:create_var_ref
Direct callers:
  - kernel/trace/trace_events_hist.c:create_key_fields
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_hist_field
```
**Symbols:**

```
ffffffff812bd460-ffffffff812bd7cc: create_hist_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct hist_field *create_hist_field(struct hist_trigger_data *hist_data, struct ftrace_event_field *field, long unsigned int flags, char *var_name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812d9937)
Location: kernel/trace/trace_events_hist.c:1939
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_var_ref
Direct callers:
  - kernel/trace/trace_events_hist.c:create_key_fields
  - kernel/trace/trace_events_hist.c:create_val_fields
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_hist_field
```
**Symbols:**

```
ffffffff812d9a60-ffffffff812d9dfb: create_hist_field (STB_LOCAL)
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
struct hist_field *create_hist_field(struct hist_trigger_data *hist_data, struct ftrace_event_field *field, long unsigned int flags, char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffff800010245ee8)
Location: kernel/trace/trace_events_hist.c:2492
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_var_ref
  - kernel/trace/trace_events_hist.c:create_hist_field
```
**Symbols:**

```
ffff800010245ee8-ffff8000102461e0: create_hist_field (STB_LOCAL)
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
struct hist_field *create_hist_field(struct hist_trigger_data *hist_data, struct ftrace_event_field *field, long unsigned int flags, char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (c0000000002dfa20)
Location: kernel/trace/trace_events_hist.c:2492
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_var_ref
  - kernel/trace/trace_events_hist.c:create_hist_field
```
**Symbols:**

```
c0000000002dfa20-c0000000002dfe10: create_hist_field (STB_LOCAL)
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
struct hist_field *create_hist_field(struct hist_trigger_data *hist_data, struct ftrace_event_field *field, long unsigned int flags, char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811be140)
Location: kernel/trace/trace_events_hist.c:2492
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_var_ref
  - kernel/trace/trace_events_hist.c:create_hist_field
```
**Symbols:**

```
ffffffff811be140-ffffffff811be44b: create_hist_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct hist_field *create_hist_field(struct hist_trigger_data *hist_data, struct ftrace_event_field *field, long unsigned int flags, char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811b0f20)
Location: kernel/trace/trace_events_hist.c:2492
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_var_ref
  - kernel/trace/trace_events_hist.c:create_hist_field
```
**Symbols:**

```
ffffffff811b0f20-ffffffff811b122b: create_hist_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct hist_field *create_hist_field(struct hist_trigger_data *hist_data, struct ftrace_event_field *field, long unsigned int flags, char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bbf10)
Location: kernel/trace/trace_events_hist.c:2492
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_var_ref
  - kernel/trace/trace_events_hist.c:create_hist_field
```
**Symbols:**

```
ffffffff811bbf10-ffffffff811bc21b: create_hist_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct hist_field *create_hist_field(struct hist_trigger_data *hist_data, struct ftrace_event_field *field, long unsigned int flags, char *var_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c9fb0)
Location: kernel/trace/trace_events_hist.c:2492
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_var_ref
  - kernel/trace/trace_events_hist.c:create_hist_field
```
**Symbols:**

```
ffffffff811c9fb0-ffffffff811ca2bb: create_hist_field (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct hist_trigger_data *hist_data</code>
</li>
<li>
<b>Param added. </b>
<code>char *var_name</code>
</li>
<li>
<b>Param reordered. </b>
<code>field, flags</code> ➡️ <code>hist_data, field, flags, var_name</code>
</li>
</ul>
</details>
</li>
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
