# Function: <code>destroy_hist_field</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811719e4)
Location: kernel/trace/trace_events_hist.c:342
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_field
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
In kernel/trace/trace_events_hist.c (ffffffff8117d154)
Location: kernel/trace/trace_events_hist.c:342
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_field
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
In kernel/trace/trace_events_hist.c (ffffffff81180669)
Location: kernel/trace/trace_events_hist.c:343
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_field
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8118df99)
Location: kernel/trace/trace_events_hist.c:368
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_field
Direct callers:
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_field
```
**Symbols:**

```
ffffffff8118df30-ffffffff8118df70: destroy_hist_field.part.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811a24ef)
Location: kernel/trace/trace_events_hist.c:2143
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:onmax_destroy
  - kernel/trace/trace_events_hist.c:onmax_destroy
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_var_ref
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:onmax_destroy
  - kernel/trace/trace_events_hist.c:onmax_destroy
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_var_ref
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
```
**Symbols:**

```
ffffffff8119df10-ffffffff8119df6e: destroy_hist_field.part.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811b0c77)
Location: kernel/trace/trace_events_hist.c:2236
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:onmax_destroy
  - kernel/trace/trace_events_hist.c:onmax_destroy
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_var_ref
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:onmax_destroy
  - kernel/trace/trace_events_hist.c:onmax_destroy
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_var_ref
  - kernel/trace/trace_events_hist.c:create_hist_field
```
**Symbols:**

```
ffffffff811ac170-ffffffff811ac1cc: destroy_hist_field.part.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bcd6d)
Location: kernel/trace/trace_events_hist.c:2390
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:track_data_destroy
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_var_ref
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:track_data_destroy
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_var_ref
  - kernel/trace/trace_events_hist.c:create_hist_field
```
**Symbols:**

```
ffffffff811ba460-ffffffff811ba4bc: destroy_hist_field.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c949c)
Location: kernel/trace/trace_events_hist.c:2472
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:track_data_destroy
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_var_ref
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:track_data_destroy
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_var_ref
  - kernel/trace/trace_events_hist.c:create_hist_field
```
**Symbols:**

```
ffffffff811c5ab0-ffffffff811c5b1e: destroy_hist_field.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void destroy_hist_field(struct hist_field *hist_field, unsigned int level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e4ef6)
Location: kernel/trace/trace_events_hist.c:1567
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:create_key_field
  - kernel/trace/trace_events_hist.c:track_data_destroy
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_var_ref
  - kernel/trace/trace_events_hist.c:destroy_hist_fields
Direct callers:
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:create_key_field
  - kernel/trace/trace_events_hist.c:track_data_destroy
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_var_ref
  - kernel/trace/trace_events_hist.c:destroy_hist_fields
```
**Symbols:**

```
ffffffff811e48d0-ffffffff811e4970: destroy_hist_field.part.0 (STB_LOCAL)
ffffffff811e4970-ffffffff811e498c: destroy_hist_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void destroy_hist_field(struct hist_field *hist_field, unsigned int level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e2926)
Location: kernel/trace/trace_events_hist.c:1577
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:create_key_field
  - kernel/trace/trace_events_hist.c:track_data_destroy
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_var_ref
  - kernel/trace/trace_events_hist.c:destroy_hist_fields
Direct callers:
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:create_key_field
  - kernel/trace/trace_events_hist.c:track_data_destroy
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_var_ref
  - kernel/trace/trace_events_hist.c:destroy_hist_fields
```
**Symbols:**

```
ffffffff811e2300-ffffffff811e23a0: destroy_hist_field.part.0 (STB_LOCAL)
ffffffff811e23a0-ffffffff811e23bc: destroy_hist_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void destroy_hist_field(struct hist_field *hist_field, unsigned int level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e3789)
Location: kernel/trace/trace_events_hist.c:1601
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:create_key_field
  - kernel/trace/trace_events_hist.c:track_data_destroy
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_var_ref
Direct callers:
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:create_key_field
  - kernel/trace/trace_events_hist.c:track_data_destroy
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_var_ref
```
**Symbols:**

```
ffffffff811e35e0-ffffffff811e3680: destroy_hist_field.part.0 (STB_LOCAL)
ffffffff811e3680-ffffffff811e369c: destroy_hist_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void destroy_hist_field(struct hist_field *hist_field, unsigned int level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff81213930)
Location: kernel/trace/trace_events_hist.c:1639
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:create_key_fields
  - kernel/trace/trace_events_hist.c:track_data_destroy
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_var_ref
Direct callers:
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:create_key_fields
  - kernel/trace/trace_events_hist.c:track_data_destroy
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_var_ref
```
**Symbols:**

```
ffffffff81213760-ffffffff81213803: destroy_hist_field.part.0 (STB_LOCAL)
ffffffff81213810-ffffffff8121382c: destroy_hist_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void destroy_hist_field(struct hist_field *hist_field, unsigned int level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8124f4f0)
Location: kernel/trace/trace_events_hist.c:1883
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:create_key_fields
  - kernel/trace/trace_events_hist.c:track_data_destroy
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_var_ref
Direct callers:
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:create_key_fields
  - kernel/trace/trace_events_hist.c:track_data_destroy
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_var_ref
```
**Symbols:**

```
ffffffff8124f310-ffffffff8124f3b6: destroy_hist_field.part.0 (STB_LOCAL)
ffffffff8124f3c0-ffffffff8124f3ec: destroy_hist_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8129e670)
Location: kernel/trace/trace_events_hist.c:1919
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:create_key_fields
  - kernel/trace/trace_events_hist.c:track_data_destroy
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_var_ref
Direct callers:
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:create_key_fields
  - kernel/trace/trace_events_hist.c:track_data_destroy
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_var_ref
```
**Symbols:**

```
ffffffff8129e4a0-ffffffff8129e546: destroy_hist_field.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812bc2f0)
Location: kernel/trace/trace_events_hist.c:1926
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:create_key_fields
  - kernel/trace/trace_events_hist.c:track_data_destroy
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_var_ref
Direct callers:
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:create_key_fields
  - kernel/trace/trace_events_hist.c:track_data_destroy
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_var_ref
```
**Symbols:**

```
ffffffff812bc120-ffffffff812bc1c6: destroy_hist_field.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812d87e0)
Location: kernel/trace/trace_events_hist.c:1919
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:create_key_fields
  - kernel/trace/trace_events_hist.c:track_data_destroy
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_var_ref
Direct callers:
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:create_key_fields
  - kernel/trace/trace_events_hist.c:track_data_destroy
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_var_ref
```
**Symbols:**

```
ffffffff812d8610-ffffffff812d86b6: destroy_hist_field.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffff800010248794)
Location: kernel/trace/trace_events_hist.c:2472
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:track_data_destroy
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_var_ref
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:track_data_destroy
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_var_ref
  - kernel/trace/trace_events_hist.c:create_hist_field
```
**Symbols:**

```
ffff800010245e58-ffff800010245ee4: destroy_hist_field.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (c0000000002e29e8)
Location: kernel/trace/trace_events_hist.c:2472
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:track_data_destroy
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_var_ref
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:track_data_destroy
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_var_ref
  - kernel/trace/trace_events_hist.c:create_hist_field
```
**Symbols:**

```
c0000000002d9d70-c0000000002d9e40: destroy_hist_field.part.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c1abc)
Location: kernel/trace/trace_events_hist.c:2472
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:track_data_destroy
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_var_ref
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:track_data_destroy
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_var_ref
  - kernel/trace/trace_events_hist.c:create_hist_field
```
**Symbols:**

```
ffffffff811be0d0-ffffffff811be13e: destroy_hist_field.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811b489c)
Location: kernel/trace/trace_events_hist.c:2472
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:track_data_destroy
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_var_ref
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:track_data_destroy
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_var_ref
  - kernel/trace/trace_events_hist.c:create_hist_field
```
**Symbols:**

```
ffffffff811b0eb0-ffffffff811b0f1e: destroy_hist_field.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bf88c)
Location: kernel/trace/trace_events_hist.c:2472
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:track_data_destroy
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_var_ref
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:track_data_destroy
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_var_ref
  - kernel/trace/trace_events_hist.c:create_hist_field
```
**Symbols:**

```
ffffffff811bbea0-ffffffff811bbf0e: destroy_hist_field.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811cd92c)
Location: kernel/trace/trace_events_hist.c:2472
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:track_data_destroy
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_var_ref
  - kernel/trace/trace_events_hist.c:create_hist_field
  - kernel/trace/trace_events_hist.c:create_hist_field
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:track_data_destroy
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:create_var_ref
  - kernel/trace/trace_events_hist.c:create_hist_field
```
**Symbols:**

```
ffffffff811c9f40-ffffffff811c9fae: destroy_hist_field.part.0 (STB_LOCAL)
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
</ul>
