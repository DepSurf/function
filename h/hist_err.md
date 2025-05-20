# Function: <code>hist_err</code>

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
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811a20e2)
Location: kernel/trace/trace_events_hist.c:367
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:hist_err_event
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:hist_err_event
```
**Symbols:**

```
ffffffff8119d160-ffffffff8119d218: hist_err.part.10 (STB_LOCAL)
ffffffff811a44e6-ffffffff811a450a: hist_err.part.10.cold.46 (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff811b1311)
Location: kernel/trace/trace_events_hist.c:433
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:hist_err_event
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:hist_err_event
```
**Symbols:**

```
ffffffff811ab5a0-ffffffff811ab658: hist_err.part.11 (STB_LOCAL)
ffffffff811b2618-ffffffff811b263c: hist_err.part.11.cold.46 (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff811bfa46)
Location: kernel/trace/trace_events_hist.c:622
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:find_event_var
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
In kernel/trace/trace_events_hist.c (ffffffff811cb296)
Location: kernel/trace/trace_events_hist.c:629
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:find_event_var
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
In kernel/trace/trace_events_hist.c (ffffffff811e5341)
Location: kernel/trace/trace_events_hist.c:568
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:create_sort_keys
  - kernel/trace/trace_events_hist.c:create_sort_keys
  - kernel/trace/trace_events_hist.c:create_sort_keys
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:create_var_fields
  - kernel/trace/trace_events_hist.c:create_key_field
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:track_data_create
  - kernel/trace/trace_events_hist.c:track_data_create
  - kernel/trace/trace_events_hist.c:track_data_create
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_field
  - kernel/trace/trace_events_hist.c:parse_field
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:find_match_var
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
In kernel/trace/trace_events_hist.c (ffffffff811e2d71)
Location: kernel/trace/trace_events_hist.c:571
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:create_sort_keys
  - kernel/trace/trace_events_hist.c:create_sort_keys
  - kernel/trace/trace_events_hist.c:create_sort_keys
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:create_key_field
  - kernel/trace/trace_events_hist.c:create_var_field
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:track_data_create
  - kernel/trace/trace_events_hist.c:track_data_create
  - kernel/trace/trace_events_hist.c:track_data_create
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_field
  - kernel/trace/trace_events_hist.c:parse_field
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:find_match_var
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
In kernel/trace/trace_events_hist.c (ffffffff811e3d01)
Location: kernel/trace/trace_events_hist.c:584
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:create_sort_keys
  - kernel/trace/trace_events_hist.c:create_sort_keys
  - kernel/trace/trace_events_hist.c:create_sort_keys
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:create_var_fields
  - kernel/trace/trace_events_hist.c:create_key_field
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:track_data_create
  - kernel/trace/trace_events_hist.c:track_data_create
  - kernel/trace/trace_events_hist.c:track_data_create
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_field
  - kernel/trace/trace_events_hist.c:parse_field
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:find_event_var
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
In kernel/trace/trace_events_hist.c (ffffffff81214021)
Location: kernel/trace/trace_events_hist.c:608
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:create_sort_keys
  - kernel/trace/trace_events_hist.c:create_sort_keys
  - kernel/trace/trace_events_hist.c:create_sort_keys
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:create_key_fields
  - kernel/trace/trace_events_hist.c:create_var_field
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:track_data_create
  - kernel/trace/trace_events_hist.c:track_data_create
  - kernel/trace/trace_events_hist.c:track_data_create
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_field
  - kernel/trace/trace_events_hist.c:parse_field
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:find_event_var
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void hist_err(struct trace_array *tr, u8 err_type, u16 err_pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8125314a)
Location: kernel/trace/trace_events_hist.c:778
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:create_actions
  - kernel/trace/trace_events_hist.c:create_actions
  - kernel/trace/trace_events_hist.c:create_actions
  - kernel/trace/trace_events_hist.c:create_sort_keys
  - kernel/trace/trace_events_hist.c:create_sort_keys
  - kernel/trace/trace_events_hist.c:create_sort_keys
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:create_var_fields
  - kernel/trace/trace_events_hist.c:create_key_fields
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_field
  - kernel/trace/trace_events_hist.c:parse_field
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:find_event_var
Direct callers:
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_assignment
```
**Symbols:**

```
ffffffff8124c200-ffffffff8124c259: hist_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void hist_err(struct trace_array *tr, u8 err_type, u16 err_pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812a26da)
Location: kernel/trace/trace_events_hist.c:811
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:create_actions
  - kernel/trace/trace_events_hist.c:create_actions
  - kernel/trace/trace_events_hist.c:create_actions
  - kernel/trace/trace_events_hist.c:create_sort_keys
  - kernel/trace/trace_events_hist.c:create_sort_keys
  - kernel/trace/trace_events_hist.c:create_sort_keys
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:create_var_fields
  - kernel/trace/trace_events_hist.c:create_key_fields
  - kernel/trace/trace_events_hist.c:create_val_fields
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_field
  - kernel/trace/trace_events_hist.c:parse_field
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:find_event_var
Direct callers:
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_assignment
```
**Symbols:**

```
ffffffff8129a540-ffffffff8129a599: hist_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void hist_err(struct trace_array *tr, u8 err_type, u16 err_pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812c0539)
Location: kernel/trace/trace_events_hist.c:808
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:create_actions
  - kernel/trace/trace_events_hist.c:create_actions
  - kernel/trace/trace_events_hist.c:create_actions
  - kernel/trace/trace_events_hist.c:create_sort_keys
  - kernel/trace/trace_events_hist.c:create_sort_keys
  - kernel/trace/trace_events_hist.c:create_sort_keys
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:create_var_fields
  - kernel/trace/trace_events_hist.c:create_key_fields
  - kernel/trace/trace_events_hist.c:create_val_fields
  - kernel/trace/trace_events_hist.c:__create_val_field
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_field
  - kernel/trace/trace_events_hist.c:parse_field
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:find_event_var
Direct callers:
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_assignment
```
**Symbols:**

```
ffffffff812b7cb0-ffffffff812b7d09: hist_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void hist_err(struct trace_array *tr, u8 err_type, u16 err_pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812dcb89)
Location: kernel/trace/trace_events_hist.c:801
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:create_actions
  - kernel/trace/trace_events_hist.c:create_actions
  - kernel/trace/trace_events_hist.c:create_actions
  - kernel/trace/trace_events_hist.c:create_sort_keys
  - kernel/trace/trace_events_hist.c:create_sort_keys
  - kernel/trace/trace_events_hist.c:create_sort_keys
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:create_var_fields
  - kernel/trace/trace_events_hist.c:create_key_fields
  - kernel/trace/trace_events_hist.c:create_val_fields
  - kernel/trace/trace_events_hist.c:__create_val_field
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_field
  - kernel/trace/trace_events_hist.c:parse_field
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:find_event_var
Direct callers:
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_assignment
```
**Symbols:**

```
ffffffff812d4300-ffffffff812d4359: hist_err (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffff80001024a670)
Location: kernel/trace/trace_events_hist.c:629
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:find_event_var
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
In kernel/trace/trace_events_hist.c (c0000000002e56d4)
Location: kernel/trace/trace_events_hist.c:629
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:find_event_var
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
In kernel/trace/trace_events_hist.c (ffffffff811c38b6)
Location: kernel/trace/trace_events_hist.c:629
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:find_event_var
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
In kernel/trace/trace_events_hist.c (ffffffff811b6696)
Location: kernel/trace/trace_events_hist.c:629
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:find_event_var
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
In kernel/trace/trace_events_hist.c (ffffffff811c1686)
Location: kernel/trace/trace_events_hist.c:629
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:find_event_var
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
In kernel/trace/trace_events_hist.c (ffffffff811cf726)
Location: kernel/trace/trace_events_hist.c:629
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:create_hist_fields
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:parse_action_params
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_atom
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:find_event_var
```
</details>
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
