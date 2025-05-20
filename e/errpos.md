# Function: <code>errpos</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bfab1)
Location: kernel/trace/trace_events_hist.c:592
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
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
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
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
In kernel/trace/trace_events_hist.c (ffffffff811cb301)
Location: kernel/trace/trace_events_hist.c:599
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
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
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
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
In kernel/trace/trace_events_hist.c (ffffffff811e5332)
Location: kernel/trace/trace_events_hist.c:538
Inline: True
Inline callers:
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
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
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
<summary>In <code>5.11</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811dd5cf)
Location: kernel/trace/trace_events_synth.c:46
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
  - kernel/trace/trace_events_synth.c:__create_synth_event
  - kernel/trace/trace_events_synth.c:__create_synth_event
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
```
```
In kernel/trace/trace_events_hist.c (ffffffff811e2d62)
Location: kernel/trace/trace_events_hist.c:541
Inline: True
Inline callers:
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
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
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
<summary>In <code>5.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811deb04)
Location: kernel/trace/trace_events_synth.c:47
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
  - kernel/trace/trace_events_synth.c:__create_synth_event
  - kernel/trace/trace_events_synth.c:__create_synth_event
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
```
```
In kernel/trace/trace_events_hist.c (ffffffff811e3cf2)
Location: kernel/trace/trace_events_hist.c:554
Inline: True
Inline callers:
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
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
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
<summary>In <code>5.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff8120e3a7)
Location: kernel/trace/trace_events_synth.c:47
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
  - kernel/trace/trace_events_synth.c:__create_synth_event
  - kernel/trace/trace_events_synth.c:__create_synth_event
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
```
```
In kernel/trace/trace_events_hist.c (ffffffff81214012)
Location: kernel/trace/trace_events_hist.c:578
Inline: True
Inline callers:
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
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_action_params
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
<summary>In <code>5.19</code>: Collision, Selective Inline ⚠️</summary>

```c
int errpos(const char *str);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff8124a91f)
Location: kernel/trace/trace_events_synth.c:47
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
  - kernel/trace/trace_events_synth.c:__create_synth_event
  - kernel/trace/trace_events_synth.c:__create_synth_event
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
```
```
In kernel/trace/trace_events_hist.c (ffffffff81253126)
Location: kernel/trace/trace_events_hist.c:735
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
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
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:action_parse
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
  - kernel/trace/trace_events_hist.c:parse_assignment
```
**Symbols:**

```
ffffffff8124c1c0-ffffffff8124c1fd: errpos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
int errpos(const char *str);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff81299555)
Location: kernel/trace/trace_events_synth.c:49
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
  - kernel/trace/trace_events_synth.c:__create_synth_event
  - kernel/trace/trace_events_synth.c:__create_synth_event
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
```
```
In kernel/trace/trace_events_hist.c (ffffffff812a26b6)
Location: kernel/trace/trace_events_hist.c:768
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
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
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:action_parse
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
  - kernel/trace/trace_events_hist.c:parse_assignment
```
**Symbols:**

```
ffffffff8129a4f0-ffffffff8129a52d: errpos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
int errpos(const char *str);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff812b685e)
Location: kernel/trace/trace_events_synth.c:50
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
  - kernel/trace/trace_events_synth.c:__create_synth_event
  - kernel/trace/trace_events_synth.c:__create_synth_event
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
```
```
In kernel/trace/trace_events_hist.c (ffffffff812c0519)
Location: kernel/trace/trace_events_hist.c:765
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:create_actions
  - kernel/trace/trace_events_hist.c:create_actions
  - kernel/trace/trace_events_hist.c:create_sort_keys
  - kernel/trace/trace_events_hist.c:create_sort_keys
  - kernel/trace/trace_events_hist.c:create_sort_keys
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:create_var_fields
  - kernel/trace/trace_events_hist.c:create_key_fields
  - kernel/trace/trace_events_hist.c:__create_val_field
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:action_parse
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
  - kernel/trace/trace_events_hist.c:parse_assignment
```
**Symbols:**

```
ffffffff812b7c60-ffffffff812b7c9d: errpos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int errpos(const char *str);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff812d2eae)
Location: kernel/trace/trace_events_synth.c:50
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
  - kernel/trace/trace_events_synth.c:__create_synth_event
  - kernel/trace/trace_events_synth.c:__create_synth_event
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
  - kernel/trace/trace_events_synth.c:parse_synth_field
```
```
In kernel/trace/trace_events_hist.c (ffffffff812dcb69)
Location: kernel/trace/trace_events_hist.c:765
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
  - kernel/trace/trace_events_hist.c:create_actions
  - kernel/trace/trace_events_hist.c:create_actions
  - kernel/trace/trace_events_hist.c:create_sort_keys
  - kernel/trace/trace_events_hist.c:create_sort_keys
  - kernel/trace/trace_events_hist.c:create_sort_keys
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:parse_var_defs
  - kernel/trace/trace_events_hist.c:create_var_fields
  - kernel/trace/trace_events_hist.c:create_key_fields
  - kernel/trace/trace_events_hist.c:__create_val_field
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:action_parse
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
  - kernel/trace/trace_events_hist.c:parse_assignment
```
**Symbols:**

```
ffffffff812d42b0-ffffffff812d42ed: errpos (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffff80001024a714)
Location: kernel/trace/trace_events_hist.c:599
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
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
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
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
In kernel/trace/trace_events_hist.c (c0000000002e57dc)
Location: kernel/trace/trace_events_hist.c:599
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
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
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
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
In kernel/trace/trace_events_hist.c (ffffffff811c3921)
Location: kernel/trace/trace_events_hist.c:599
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
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
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
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
In kernel/trace/trace_events_hist.c (ffffffff811b6701)
Location: kernel/trace/trace_events_hist.c:599
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
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
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
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
In kernel/trace/trace_events_hist.c (ffffffff811c16f1)
Location: kernel/trace/trace_events_hist.c:599
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
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
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
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
In kernel/trace/trace_events_hist.c (ffffffff811cf791)
Location: kernel/trace/trace_events_hist.c:599
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
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
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:trace_action_create
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
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
