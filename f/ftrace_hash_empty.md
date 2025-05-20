# Function: <code>ftrace_hash_empty</code>

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
In kernel/trace/ftrace.c (ffffffff8113ff93)
Location: kernel/trace/ftrace.c:1220
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_lookup_ip
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:ftrace_hash_move
  - kernel/trace/ftrace.c:ftrace_hash_move
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_process_locs
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
In kernel/trace/ftrace.c (ffffffff8114d6dd)
Location: kernel/trace/ftrace.c:1189
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:ftrace_hash_move
  - kernel/trace/ftrace.c:ftrace_hash_move
  - kernel/trace/ftrace.c:ftrace_lookup_ip
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
In kernel/trace/ftrace.c (ffffffff8115761d)
Location: kernel/trace/ftrace.c:1195
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:ftrace_hash_move
  - kernel/trace/ftrace.c:ftrace_hash_move
  - kernel/trace/ftrace.c:ftrace_lookup_ip
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8115a799)
Location: kernel/trace/trace.h:795
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:g_start
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:__ftrace_hash_move
  - kernel/trace/ftrace.c:ftrace_lookup_ip
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8116f7c7)
Location: kernel/trace/trace.h:795
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff81172476)
Location: kernel/trace/trace.h:795
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811674eb)
Location: kernel/trace/trace.h:797
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:g_start
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:__ftrace_hash_move
  - kernel/trace/ftrace.c:ftrace_lookup_ip
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8117c8b7)
Location: kernel/trace/trace.h:797
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8117f616)
Location: kernel/trace/trace.h:797
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8117626b)
Location: kernel/trace/trace.h:803
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:g_start
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:__ftrace_hash_move
  - kernel/trace/ftrace.c:ftrace_lookup_ip
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8118b9c7)
Location: kernel/trace/trace.h:803
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8118e782)
Location: kernel/trace/trace.h:803
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81183eab)
Location: kernel/trace/trace.h:843
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:g_start
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:__ftrace_hash_move
  - kernel/trace/ftrace.c:ftrace_lookup_ip
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811993b2)
Location: kernel/trace/trace.h:843
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8119be3b)
Location: kernel/trace/trace.h:843
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
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
In kernel/trace/ftrace.c (ffffffff81190c20)
Location: kernel/trace/trace.h:888
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:g_start
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:__ftrace_hash_move
  - kernel/trace/ftrace.c:ftrace_lookup_ip
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811a6fb7)
Location: kernel/trace/trace.h:888
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811a9ab8)
Location: kernel/trace/trace.h:888
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
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
In kernel/trace/ftrace.c (ffffffff8119cc20)
Location: kernel/trace/trace.h:889
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:g_start
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:__ftrace_hash_move
  - kernel/trace/ftrace.c:ftrace_lookup_ip
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811b27a7)
Location: kernel/trace/trace.h:889
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811b52a8)
Location: kernel/trace/trace.h:889
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
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
In kernel/trace/ftrace.c (ffffffff811aeb6f)
Location: kernel/trace/trace.h:945
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:referenced_filters
  - kernel/trace/ftrace.c:referenced_filters
  - kernel/trace/ftrace.c:referenced_filters
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:g_start
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:ftrace_lookup_ip
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811cbae7)
Location: kernel/trace/trace.h:945
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811cdfd9)
Location: kernel/trace/trace.h:945
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
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
In kernel/trace/ftrace.c (ffffffff811ac4ce)
Location: kernel/trace/trace.h:794
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:referenced_filters
  - kernel/trace/ftrace.c:referenced_filters
  - kernel/trace/ftrace.c:referenced_filters
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:g_start
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:ftrace_lookup_ip
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811c91c7)
Location: kernel/trace/trace.h:794
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811cb4b9)
Location: kernel/trace/trace.h:794
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
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
In kernel/trace/ftrace.c (ffffffff811ad03d)
Location: kernel/trace/trace.h:797
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:referenced_filters
  - kernel/trace/ftrace.c:referenced_filters
  - kernel/trace/ftrace.c:referenced_filters
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:g_start
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:ftrace_lookup_ip
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811c9dd7)
Location: kernel/trace/trace.h:797
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811cc7d3)
Location: kernel/trace/trace.h:797
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
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
In kernel/trace/ftrace.c (ffffffff811d6ccb)
Location: kernel/trace/trace.h:803
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:referenced_filters
  - kernel/trace/ftrace.c:referenced_filters
  - kernel/trace/ftrace.c:referenced_filters
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:g_start
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:hash_contains_ip
  - kernel/trace/ftrace.c:hash_contains_ip
  - kernel/trace/ftrace.c:ftrace_lookup_ip
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811f5967)
Location: kernel/trace/trace.h:803
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811f8efb)
Location: kernel/trace/trace.h:803
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
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
In kernel/trace/ftrace.c (ffffffff81210c45)
Location: kernel/trace/trace.h:811
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:referenced_filters
  - kernel/trace/ftrace.c:referenced_filters
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:g_start
  - kernel/trace/ftrace.c:register_ftrace_direct_multi
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:ftrace_startup
  - kernel/trace/ftrace.c:ftrace_add_rec_direct
  - kernel/trace/ftrace.c:__ftrace_hash_rec_update
  - kernel/trace/ftrace.c:__ftrace_hash_rec_update
  - kernel/trace/ftrace.c:__ftrace_hash_rec_update
  - kernel/trace/ftrace.c:hash_contains_ip
  - kernel/trace/ftrace.c:hash_contains_ip
  - kernel/trace/ftrace.c:ftrace_lookup_ip
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8122f7ca)
Location: kernel/trace/trace.h:811
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff81232d11)
Location: kernel/trace/trace.h:811
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
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
In kernel/trace/ftrace.c (ffffffff8125a0d5)
Location: kernel/trace/trace.h:810
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ops_references_ip
  - kernel/trace/ftrace.c:ops_references_ip
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:g_start
  - kernel/trace/ftrace.c:register_ftrace_direct_multi
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:ftrace_startup
  - kernel/trace/ftrace.c:ftrace_add_rec_direct
  - kernel/trace/ftrace.c:__ftrace_hash_rec_update
  - kernel/trace/ftrace.c:__ftrace_hash_rec_update
  - kernel/trace/ftrace.c:__ftrace_hash_rec_update
  - kernel/trace/ftrace.c:hash_contains_ip
  - kernel/trace/ftrace.c:hash_contains_ip
  - kernel/trace/ftrace.c:ftrace_lookup_ip
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8127b94a)
Location: kernel/trace/trace.h:810
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8127f46e)
Location: kernel/trace/trace.h:810
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
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
In kernel/trace/ftrace.c (ffffffff81271421)
Location: kernel/trace/trace.h:830
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ops_references_ip
  - kernel/trace/ftrace.c:ops_references_ip
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:g_start
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:ftrace_startup
  - kernel/trace/ftrace.c:__ftrace_hash_rec_update
  - kernel/trace/ftrace.c:__ftrace_hash_rec_update
  - kernel/trace/ftrace.c:__ftrace_hash_rec_update
  - kernel/trace/ftrace.c:hash_contains_ip
  - kernel/trace/ftrace.c:hash_contains_ip
  - kernel/trace/ftrace.c:ftrace_lookup_ip
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8129346a)
Location: kernel/trace/trace.h:830
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8129bffe)
Location: kernel/trace/trace.h:830
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
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
In kernel/trace/ftrace.c (ffffffff8128b8a4)
Location: kernel/trace/trace.h:848
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ops_references_ip
  - kernel/trace/ftrace.c:ops_references_ip
  - kernel/trace/ftrace.c:g_start
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:ftrace_startup
  - kernel/trace/ftrace.c:__ftrace_hash_rec_update
  - kernel/trace/ftrace.c:__ftrace_hash_rec_update
  - kernel/trace/ftrace.c:__ftrace_hash_rec_update
  - kernel/trace/ftrace.c:hash_contains_ip
  - kernel/trace/ftrace.c:hash_contains_ip
  - kernel/trace/ftrace.c:__ftrace_hash_move
  - kernel/trace/ftrace.c:ftrace_lookup_ip
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff812ae44a)
Location: kernel/trace/trace.h:848
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff812b76de)
Location: kernel/trace/trace.h:848
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
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
In kernel/trace/ftrace.c (ffff800010215a38)
Location: kernel/trace/trace.h:889
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:g_start
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:__ftrace_hash_move
  - kernel/trace/ftrace.c:ftrace_lookup_ip
```
```
In kernel/trace/trace_sched_wakeup.c (ffff8000102315b8)
Location: kernel/trace/trace.h:889
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffff80001023314c)
Location: kernel/trace/trace.h:889
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
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
In kernel/trace/ftrace.c (c04547c8)
Location: kernel/trace/trace.h:889
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:g_start
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:hash_contains_ip
  - kernel/trace/ftrace.c:hash_contains_ip
  - kernel/trace/ftrace.c:__ftrace_hash_move
  - kernel/trace/ftrace.c:ftrace_lookup_ip
```
```
In kernel/trace/trace_sched_wakeup.c (c046c3cc)
Location: kernel/trace/trace.h:889
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (c046eec8)
Location: kernel/trace/trace.h:889
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
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
In kernel/trace/ftrace.c (c0000000002974b0)
Location: kernel/trace/trace.h:889
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:g_start
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:hash_contains_ip
  - kernel/trace/ftrace.c:hash_contains_ip
  - kernel/trace/ftrace.c:__ftrace_hash_move
  - kernel/trace/ftrace.c:ftrace_lookup_ip
```
```
In kernel/trace/trace_sched_wakeup.c (c0000000002ba850)
Location: kernel/trace/trace.h:889
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (c0000000002be010)
Location: kernel/trace/trace.h:889
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
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
In kernel/trace/ftrace.c (ffffffe0001756f8)
Location: kernel/trace/trace.h:889
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:g_start
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:hash_contains_ip
  - kernel/trace/ftrace.c:hash_contains_ip
  - kernel/trace/ftrace.c:__ftrace_hash_move
  - kernel/trace/ftrace.c:ftrace_lookup_ip
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffe000188614)
Location: kernel/trace/trace.h:889
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffe00018a76c)
Location: kernel/trace/trace.h:889
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
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
In kernel/trace/ftrace.c (ffffffff81195240)
Location: kernel/trace/trace.h:889
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:g_start
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:__ftrace_hash_move
  - kernel/trace/ftrace.c:ftrace_lookup_ip
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811aadc7)
Location: kernel/trace/trace.h:889
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811ad8c8)
Location: kernel/trace/trace.h:889
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
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
In kernel/trace/ftrace.c (ffffffff81188350)
Location: kernel/trace/trace.h:889
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:g_start
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:__ftrace_hash_move
  - kernel/trace/ftrace.c:ftrace_lookup_ip
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8119dd17)
Location: kernel/trace/trace.h:889
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811a0727)
Location: kernel/trace/trace.h:889
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
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
In kernel/trace/ftrace.c (ffffffff81193010)
Location: kernel/trace/trace.h:889
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:g_start
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:__ftrace_hash_move
  - kernel/trace/ftrace.c:ftrace_lookup_ip
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811a8b97)
Location: kernel/trace/trace.h:889
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811ab698)
Location: kernel/trace/trace.h:889
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
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
In kernel/trace/ftrace.c (ffffffff811a0ba0)
Location: kernel/trace/trace.h:889
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:g_start
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:__ftrace_hash_move
  - kernel/trace/ftrace.c:ftrace_lookup_ip
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811b69f8)
Location: kernel/trace/trace.h:889
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811b9538)
Location: kernel/trace/trace.h:889
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
</details>
</li>
</ul>

## Differences
