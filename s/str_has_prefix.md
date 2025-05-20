# Function: <code>str_has_prefix</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119254d)
Location: include/linux/string.h:473
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_set_options
```
```
In kernel/trace/trace_stack.c (ffffffff828b43cf)
Location: include/linux/string.h:473
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:enable_stacktrace
```
```
In kernel/trace/trace_events.c (ffffffff811a1709)
Location: include/linux/string.h:473
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:f_show
```
```
In kernel/trace/trace_events_hist.c (ffffffff811b0db5)
Location: include/linux/string.h:473
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
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
```
In kernel/trace/trace_probe.c (ffffffff811bb323)
Location: include/linux/string.h:473
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119feb1)
Location: include/linux/string.h:480
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_set_options
```
```
In kernel/trace/trace_stack.c (ffffffff828cd1d0)
Location: include/linux/string.h:480
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:enable_stacktrace
```
```
In kernel/trace/trace_events.c (ffffffff811af639)
Location: include/linux/string.h:480
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:f_show
```
```
In kernel/trace/trace_events_hist.c (ffffffff811be1a3)
Location: include/linux/string.h:480
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:synth_event_create
  - kernel/trace/trace_events_hist.c:parse_synth_field
```
```
In kernel/trace/trace_probe.c (ffffffff811ca51e)
Location: include/linux/string.h:480
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff811081ea)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/power/main.c:state_store
```
```
In kernel/printk/printk.c (ffffffff81112124)
Location: include/linux/string.h:502
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8118b697)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_parse
```
```
In kernel/trace/trace.c (ffffffff811ab8a1)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_set_options
```
```
In kernel/trace/trace_stack.c (ffffffff828d56e4)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:enable_stacktrace
```
```
In kernel/trace/trace_events.c (ffffffff811bacb9)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:f_show
```
```
In kernel/trace/trace_events_hist.c (ffffffff811c98c8)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:synth_event_create
  - kernel/trace/trace_events_hist.c:parse_synth_field
```
```
In kernel/trace/trace_probe.c (ffffffff811d6250)
Location: include/linux/string.h:502
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81112a51)
Location: include/linux/string.h:539
Inline: True
Inline callers:
  - kernel/power/main.c:decode_state
```
```
In kernel/printk/printk.c (ffffffff8111d9e4)
Location: include/linux/string.h:539
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8119cce6)
Location: include/linux/string.h:539
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:parse_grep
```
```
In kernel/trace/trace.c (ffffffff811c4112)
Location: include/linux/string.h:539
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_set_options
```
```
In kernel/trace/trace_stack.c (ffffffff82cf5fed)
Location: include/linux/string.h:539
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:enable_stacktrace
```
```
In kernel/trace/trace_events.c (ffffffff811d5469)
Location: include/linux/string.h:539
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:f_show
```
```
In kernel/trace/trace_events_synth.c (ffffffff811dfee7)
Location: include/linux/string.h:539
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:parse_synth_field
```
```
In kernel/trace/trace_events_hist.c (ffffffff811e5506)
Location: include/linux/string.h:539
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_actions
  - kernel/trace/trace_events_hist.c:parse_actions
  - kernel/trace/trace_events_hist.c:parse_actions
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
```
```
In kernel/trace/trace_probe.c (ffffffff811f2a21)
Location: include/linux/string.h:539
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff8110fb21)
Location: include/linux/string.h:585
Inline: True
Inline callers:
  - kernel/power/main.c:decode_state
```
```
In kernel/printk/printk.c (ffffffff81118444)
Location: include/linux/string.h:585
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81199d26)
Location: include/linux/string.h:585
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:parse_grep
```
```
In kernel/trace/trace.c (ffffffff811c1d22)
Location: include/linux/string.h:585
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_set_options
```
```
In kernel/trace/trace_stack.c (ffffffff82fe2c03)
Location: include/linux/string.h:585
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:enable_stacktrace
```
```
In kernel/trace/trace_events.c (ffffffff811d25f9)
Location: include/linux/string.h:585
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:f_show
```
```
In kernel/trace/trace_events_synth.c (ffffffff811dd8d7)
Location: include/linux/string.h:585
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:parse_synth_field
```
```
In kernel/trace/trace_events_hist.c (ffffffff811e2f36)
Location: include/linux/string.h:585
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_actions
  - kernel/trace/trace_events_hist.c:parse_actions
  - kernel/trace/trace_events_hist.c:parse_actions
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
```
```
In kernel/trace/trace_probe.c (ffffffff811f13d1)
Location: include/linux/string.h:585
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff811107f9)
Location: include/linux/string.h:305
Inline: True
Inline callers:
  - kernel/power/main.c:state_store
```
```
In kernel/printk/printk.c (ffffffff81118a7a)
Location: include/linux/string.h:305
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8119aa97)
Location: include/linux/string.h:305
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:parse_grep
```
```
In kernel/trace/trace.c (ffffffff811c2d92)
Location: include/linux/string.h:305
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_set_options
```
```
In kernel/trace/trace_stack.c (ffffffff831ed227)
Location: include/linux/string.h:305
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:enable_stacktrace
```
```
In kernel/trace/trace_events.c (ffffffff811d41ad)
Location: include/linux/string.h:305
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:test_event_printk
```
```
In kernel/trace/trace_events_synth.c (ffffffff811ded32)
Location: include/linux/string.h:305
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:parse_synth_field
```
```
In kernel/trace/trace_events_hist.c (ffffffff811e5571)
Location: include/linux/string.h:305
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
```
```
In kernel/trace/trace_probe.c (ffffffff811f2288)
Location: include/linux/string.h:305
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff811301e9)
Location: include/linux/string.h:283
Inline: True
Inline callers:
  - kernel/power/main.c:state_store
```
```
In kernel/printk/printk.c (ffffffff811392ca)
Location: include/linux/string.h:283
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff811c4af7)
Location: include/linux/string.h:283
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:parse_grep
```
```
In kernel/trace/trace.c (ffffffff811eda91)
Location: include/linux/string.h:283
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_set_options
```
```
In kernel/trace/trace_stack.c (ffffffff832d1ea1)
Location: include/linux/string.h:283
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:enable_stacktrace
```
```
In kernel/trace/trace_events.c (ffffffff8120100d)
Location: include/linux/string.h:283
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:test_event_printk
```
```
In kernel/trace/trace_events_filter.c (ffffffff81205556)
Location: include/linux/string.h:283
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:parse_pred
```
```
In kernel/trace/trace_events_synth.c (ffffffff8120e615)
Location: include/linux/string.h:283
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:parse_synth_field
```
```
In kernel/trace/trace_events_hist.c (ffffffff81215c4a)
Location: include/linux/string.h:283
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
```
```
In kernel/trace/trace_probe.c (ffffffff81223478)
Location: include/linux/string.h:283
Inline: True
```
```
In mm/kfence/report.c (ffffffff8133ccff)
Location: include/linux/string.h:283
Inline: True
Inline callers:
  - mm/kfence/report.c:get_stack_skipnr
  - mm/kfence/report.c:get_stack_skipnr
  - mm/kfence/report.c:get_stack_skipnr
  - mm/kfence/report.c:get_stack_skipnr
  - mm/kfence/report.c:get_stack_skipnr
  - mm/kfence/report.c:get_stack_skipnr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff811519d2)
Location: include/linux/string.h:313
Inline: True
Inline callers:
  - kernel/power/main.c:state_store
```
```
In kernel/printk/printk.c (ffffffff8115b01e)
Location: include/linux/string.h:313
Inline: True
Inline callers:
  - kernel/printk/printk.c:__control_devkmsg
  - kernel/printk/printk.c:__control_devkmsg
  - kernel/printk/printk.c:__control_devkmsg
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff811f8357)
Location: include/linux/string.h:313
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:parse_grep
```
```
In kernel/trace/trace.c (ffffffff81225c72)
Location: include/linux/string.h:313
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_set_options
```
```
In kernel/trace/trace_stack.c (ffffffff83486195)
Location: include/linux/string.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:enable_stacktrace
```
```
In kernel/trace/trace_events.c (ffffffff8123c9d1)
Location: include/linux/string.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:test_event_printk
```
```
In kernel/trace/trace_events_filter.c (ffffffff81240db5)
Location: include/linux/string.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:parse_pred
```
```
In kernel/trace/trace_events_synth.c (ffffffff8124abc1)
Location: include/linux/string.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:parse_synth_field
```
```
In kernel/trace/trace_events_hist.c (ffffffff812538e0)
Location: include/linux/string.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
```
```
In kernel/trace/trace_probe.c (ffffffff812634ff)
Location: include/linux/string.h:313
Inline: True
```
```
In mm/kfence/report.c (ffffffff813b018b)
Location: include/linux/string.h:313
Inline: True
Inline callers:
  - mm/kfence/report.c:get_stack_skipnr
  - mm/kfence/report.c:get_stack_skipnr
  - mm/kfence/report.c:get_stack_skipnr
  - mm/kfence/report.c:get_stack_skipnr
  - mm/kfence/report.c:get_stack_skipnr
  - mm/kfence/report.c:get_stack_skipnr
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81180252)
Location: include/linux/string.h:356
Inline: True
Inline callers:
  - kernel/power/main.c:decode_state
```
```
In kernel/printk/printk.c (ffffffff8118d2fe)
Location: include/linux/string.h:356
Inline: True
Inline callers:
  - kernel/printk/printk.c:__control_devkmsg
  - kernel/printk/printk.c:__control_devkmsg
  - kernel/printk/printk.c:__control_devkmsg
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8123f797)
Location: include/linux/string.h:356
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:parse_grep
```
```
In kernel/trace/trace.c (ffffffff81270ed2)
Location: include/linux/string.h:356
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_set_options
```
```
In kernel/trace/trace_stack.c (ffffffff83eb5144)
Location: include/linux/string.h:356
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:enable_stacktrace
```
```
In kernel/trace/trace_events.c (ffffffff81289191)
Location: include/linux/string.h:356
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:test_event_printk
```
```
In kernel/trace/trace_events_filter.c (ffffffff8128e8b5)
Location: include/linux/string.h:356
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:parse_pred
```
```
In kernel/trace/trace_events_synth.c (ffffffff812997b1)
Location: include/linux/string.h:356
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:parse_synth_field
```
```
In kernel/trace/trace_events_hist.c (ffffffff812a2ea0)
Location: include/linux/string.h:356
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
```
```
In kernel/trace/trace_probe.c (ffffffff812b4f1f)
Location: include/linux/string.h:356
Inline: True
```
```
In mm/kfence/report.c (ffffffff814307a5)
Location: include/linux/string.h:356
Inline: True
Inline callers:
  - mm/kfence/report.c:get_stack_skipnr
  - mm/kfence/report.c:get_stack_skipnr
  - mm/kfence/report.c:get_stack_skipnr
  - mm/kfence/report.c:get_stack_skipnr
  - mm/kfence/report.c:get_stack_skipnr
  - mm/kfence/report.c:get_stack_skipnr
  - mm/kfence/report.c:get_stack_skipnr
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81191022)
Location: include/linux/string.h:357
Inline: True
Inline callers:
  - kernel/power/main.c:decode_state
```
```
In kernel/printk/printk.c (ffffffff8119eace)
Location: include/linux/string.h:357
Inline: True
Inline callers:
  - kernel/printk/printk.c:__control_devkmsg
  - kernel/printk/printk.c:__control_devkmsg
  - kernel/printk/printk.c:__control_devkmsg
```
```
In kernel/kprobes.c (ffffffff8124c60a)
Location: include/linux/string.h:357
Inline: True
Inline callers:
  - kernel/kprobes.c:is_cfi_preamble_symbol
  - kernel/kprobes.c:is_cfi_preamble_symbol
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81256807)
Location: include/linux/string.h:357
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:parse_grep
```
```
In kernel/trace/trace.c (ffffffff812881b2)
Location: include/linux/string.h:357
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_set_options
```
```
In kernel/trace/trace_stack.c (ffffffff836da734)
Location: include/linux/string.h:357
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:enable_stacktrace
```
```
In kernel/trace/trace_events.c (ffffffff812a5f7b)
Location: include/linux/string.h:357
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:test_event_printk
```
```
In kernel/trace/trace_events_filter.c (ffffffff812ab819)
Location: include/linux/string.h:357
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
```
```
In kernel/trace/trace_events_synth.c (ffffffff812b6b79)
Location: include/linux/string.h:357
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:parse_synth_field
```
```
In kernel/trace/trace_events_hist.c (ffffffff812c0d00)
Location: include/linux/string.h:357
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
```
```
In kernel/trace/trace_events_user.c (ffffffff812c3758)
Location: include/linux/string.h:357
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_show
  - kernel/trace/trace_events_user.c:user_event_create
  - kernel/trace/trace_events_user.c:user_event_set_print_fmt
  - kernel/trace/trace_events_user.c:user_event_set_print_fmt
  - kernel/trace/trace_events_user.c:user_field_set_string
  - kernel/trace/trace_events_user.c:user_event_parse_field
  - kernel/trace/trace_events_user.c:user_event_parse_field
  - kernel/trace/trace_events_user.c:user_event_parse_field
  - kernel/trace/trace_events_user.c:user_event_parse_field
  - kernel/trace/trace_events_user.c:user_event_parse_field
  - kernel/trace/trace_events_user.c:user_event_parse_field
  - kernel/trace/trace_events_user.c:user_event_parse_field
  - kernel/trace/trace_events_user.c:user_event_parse_field
  - kernel/trace/trace_events_user.c:user_field_size
  - kernel/trace/trace_events_user.c:user_field_size
  - kernel/trace/trace_events_user.c:user_field_size
  - kernel/trace/trace_events_user.c:user_field_size
```
```
In kernel/trace/trace_probe.c (ffffffff812d9462)
Location: include/linux/string.h:357
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_expand_meta_args
  - kernel/trace/trace_probe.c:traceprobe_expand_meta_args
```
```
In mm/kfence/report.c (ffffffff81466105)
Location: include/linux/string.h:357
Inline: True
Inline callers:
  - mm/kfence/report.c:get_stack_skipnr
  - mm/kfence/report.c:get_stack_skipnr
  - mm/kfence/report.c:get_stack_skipnr
  - mm/kfence/report.c:get_stack_skipnr
  - mm/kfence/report.c:get_stack_skipnr
  - mm/kfence/report.c:get_stack_skipnr
  - mm/kfence/report.c:get_stack_skipnr
```
```
In drivers/tty/serial/serial_base_bus.c (ffffffff81ac3e9d)
Location: include/linux/string.h:357
Inline: True
Inline callers:
  - drivers/tty/serial/serial_base_bus.c:serial_base_match
  - drivers/tty/serial/serial_base_bus.c:serial_base_match
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff8119f9e2)
Location: include/linux/string.h:398
Inline: True
Inline callers:
  - kernel/power/main.c:decode_state
```
```
In kernel/printk/printk.c (ffffffff811adc8e)
Location: include/linux/string.h:398
Inline: True
Inline callers:
  - kernel/printk/printk.c:__control_devkmsg
  - kernel/printk/printk.c:__control_devkmsg
  - kernel/printk/printk.c:__control_devkmsg
```
```
In kernel/kprobes.c (ffffffff8126650a)
Location: include/linux/string.h:398
Inline: True
Inline callers:
  - kernel/kprobes.c:is_cfi_preamble_symbol
  - kernel/kprobes.c:is_cfi_preamble_symbol
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81270687)
Location: include/linux/string.h:398
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:parse_grep
```
```
In kernel/trace/trace.c (ffffffff812a34d2)
Location: include/linux/string.h:398
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_set_options
```
```
In kernel/trace/trace_stack.c (ffffffff8390cca4)
Location: include/linux/string.h:398
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:enable_stacktrace
```
```
In kernel/trace/trace_events.c (ffffffff812c1a9b)
Location: include/linux/string.h:398
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:test_event_printk
```
```
In kernel/trace/trace_events_filter.c (ffffffff812c7958)
Location: include/linux/string.h:398
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
```
```
In kernel/trace/trace_events_synth.c (ffffffff812d31c9)
Location: include/linux/string.h:398
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:parse_synth_field
```
```
In kernel/trace/trace_events_hist.c (ffffffff812dd277)
Location: include/linux/string.h:398
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_actions
  - kernel/trace/trace_events_hist.c:parse_actions
  - kernel/trace/trace_events_hist.c:parse_actions
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
  - kernel/trace/trace_events_hist.c:parse_assignment
```
```
In kernel/trace/trace_events_user.c (ffffffff812dffb2)
Location: include/linux/string.h:398
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_show
  - kernel/trace/trace_events_user.c:user_event_create
  - kernel/trace/trace_events_user.c:user_event_set_print_fmt
  - kernel/trace/trace_events_user.c:user_event_set_print_fmt
  - kernel/trace/trace_events_user.c:user_field_set_string
  - kernel/trace/trace_events_user.c:user_event_parse_field
  - kernel/trace/trace_events_user.c:user_event_parse_field
  - kernel/trace/trace_events_user.c:user_event_parse_field
  - kernel/trace/trace_events_user.c:user_event_parse_field
  - kernel/trace/trace_events_user.c:user_event_parse_field
  - kernel/trace/trace_events_user.c:user_event_parse_field
  - kernel/trace/trace_events_user.c:user_event_parse_field
  - kernel/trace/trace_events_user.c:user_event_parse_field
  - kernel/trace/trace_events_user.c:user_field_size
  - kernel/trace/trace_events_user.c:user_field_size
  - kernel/trace/trace_events_user.c:user_field_size
  - kernel/trace/trace_events_user.c:user_field_size
```
```
In kernel/trace/trace_probe.c (ffffffff812f7395)
Location: include/linux/string.h:398
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_expand_meta_args
  - kernel/trace/trace_probe.c:traceprobe_expand_meta_args
```
```
In mm/kfence/report.c (ffffffff81495315)
Location: include/linux/string.h:398
Inline: True
Inline callers:
  - mm/kfence/report.c:get_stack_skipnr
  - mm/kfence/report.c:get_stack_skipnr
  - mm/kfence/report.c:get_stack_skipnr
  - mm/kfence/report.c:get_stack_skipnr
  - mm/kfence/report.c:get_stack_skipnr
  - mm/kfence/report.c:get_stack_skipnr
  - mm/kfence/report.c:get_stack_skipnr
```
```
In drivers/tty/serial/serial_base_bus.c (ffffffff81b16d3d)
Location: include/linux/string.h:398
Inline: True
Inline callers:
  - drivers/tty/serial/serial_base_bus.c:serial_base_match
  - drivers/tty/serial/serial_base_bus.c:serial_base_match
```
```
In drivers/base/property.c (ffffffff81b9b966)
Location: include/linux/string.h:398
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_name_eq
```
```
In drivers/gpu/drm/drm_modes.c (ffffffff81ca56d8)
Location: include/linux/string.h:398
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_modes.c:drm_mode_parse_cmdline_named_mode
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/module-plts.c (ffff8000100a3108)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - arch/arm64/kernel/module-plts.c:module_frob_arch_sections
```
```
In arch/arm64/mm/numa.c (ffff800011438940)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - arch/arm64/mm/numa.c:numa_parse_early_param
```
```
In kernel/power/main.c (ffff80001016f4b4)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/power/main.c:state_store
```
```
In kernel/printk/printk.c (ffff80001017246c)
Location: include/linux/string.h:502
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (ffff80001020299c)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_parse
```
```
In kernel/trace/trace.c (ffff8000102286a0)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_set_options
```
```
In kernel/trace/trace_stack.c (ffff80001144df70)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:enable_stacktrace
```
```
In kernel/trace/trace_events.c (ffff800010239358)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:f_show
```
```
In kernel/trace/trace_events_hist.c (ffff800010249838)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:synth_event_create
  - kernel/trace/trace_events_hist.c:parse_synth_field
```
```
In kernel/trace/trace_probe.c (ffff800010256610)
Location: include/linux/string.h:502
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (c03b9fd8)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/power/main.c:state_store
```
```
In kernel/printk/printk.c (c03c50f8)
Location: include/linux/string.h:502
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (c0441a44)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_parse
```
```
In kernel/trace/trace.c (c0465cdc)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_set_options
```
```
In kernel/trace/trace_stack.c (c15285d4)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:enable_stacktrace
```
```
In kernel/trace/trace_events.c (c0477958)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:f_show
```
```
In kernel/trace/trace_probe.c (c0489858)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:parse_probe_arg
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (c0000000001c7300)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/power/main.c:state_store
```
```
In kernel/printk/printk.c (c0000000001cbb38)
Location: include/linux/string.h:502
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (c00000000027c850)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_parse
```
```
In kernel/trace/trace.c (c0000000002af168)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_set_options
```
```
In kernel/trace/trace_stack.c (c000000001374828)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:enable_stacktrace
```
```
In kernel/trace/trace_events.c (c0000000002c6a1c)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:f_show
```
```
In kernel/trace/trace_events_hist.c (c0000000002e2f30)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:synth_event_create
  - kernel/trace/trace_events_hist.c:parse_synth_field
```
```
In kernel/trace/trace_probe.c (c0000000002f7550)
Location: include/linux/string.h:502
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (0)
Location: include/linux/string.h:502
Inline: True
```
```
In kernel/printk/printk.c (ffffffe00010e854)
Location: include/linux/string.h:502
Inline: True
```
```
In kernel/trace/trace.c (ffffffe000182fde)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_set_options
```
```
In kernel/trace/trace_stack.c (ffffffe00000e658)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:enable_stacktrace
```
```
In kernel/trace/trace_events.c (ffffffe000190292)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:f_show
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81101364)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/power/main.c:state_store
```
```
In kernel/printk/printk.c (ffffffff8110a704)
Location: include/linux/string.h:502
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81183cb7)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_parse
```
```
In kernel/trace/trace.c (ffffffff811a3ec1)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_set_options
```
```
In kernel/trace/trace_stack.c (ffffffff828be595)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:enable_stacktrace
```
```
In kernel/trace/trace_events.c (ffffffff811b32d9)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:f_show
```
```
In kernel/trace/trace_events_hist.c (ffffffff811c1ee8)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:synth_event_create
  - kernel/trace/trace_events_hist.c:parse_synth_field
```
```
In kernel/trace/trace_probe.c (ffffffff811ce870)
Location: include/linux/string.h:502
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810f16ea)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/power/main.c:state_store
```
```
In kernel/printk/printk.c (ffffffff810fb5e4)
Location: include/linux/string.h:502
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81176df7)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_parse
```
```
In kernel/trace/trace.c (ffffffff81196e91)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_set_options
```
```
In kernel/trace/trace_stack.c (ffffffff828b6c35)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:enable_stacktrace
```
```
In kernel/trace/trace_events.c (ffffffff811a60d9)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:f_show
```
```
In kernel/trace/trace_events_hist.c (ffffffff811b4cc8)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:synth_event_create
  - kernel/trace/trace_events_hist.c:parse_synth_field
```
```
In kernel/trace/trace_probe.c (ffffffff811c1640)
Location: include/linux/string.h:502
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810fe6ba)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/power/main.c:state_store
```
```
In kernel/printk/printk.c (ffffffff811085f4)
Location: include/linux/string.h:502
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81181a87)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_parse
```
```
In kernel/trace/trace.c (ffffffff811a1c91)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_set_options
```
```
In kernel/trace/trace_stack.c (ffffffff828d1318)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:enable_stacktrace
```
```
In kernel/trace/trace_events.c (ffffffff811b10a9)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:f_show
```
```
In kernel/trace/trace_events_hist.c (ffffffff811bfcb8)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:synth_event_create
  - kernel/trace/trace_events_hist.c:parse_synth_field
```
```
In kernel/trace/trace_probe.c (ffffffff811cc640)
Location: include/linux/string.h:502
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff8110997a)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/power/main.c:state_store
```
```
In kernel/printk/printk.c (ffffffff81113994)
Location: include/linux/string.h:502
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8118f3a7)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_parse
```
```
In kernel/trace/trace.c (ffffffff811afa21)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_set_options
```
```
In kernel/trace/trace_stack.c (ffffffff828d6739)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:enable_stacktrace
```
```
In kernel/trace/trace_events.c (ffffffff811bf149)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:f_show
```
```
In kernel/trace/trace_events_hist.c (ffffffff811cdd58)
Location: include/linux/string.h:502
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:action_parse
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
  - kernel/trace/trace_events_hist.c:synth_event_create
  - kernel/trace/trace_events_hist.c:parse_synth_field
```
```
In kernel/trace/trace_probe.c (ffffffff811da8a0)
Location: include/linux/string.h:502
Inline: True
```
</details>
</li>
</ul>

## Differences
