# Function: <code>ftrace_lookup_ip</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct ftrace_func_entry *ftrace_lookup_ip(struct ftrace_hash *hash, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8113ff90)
Location: kernel/trace/ftrace.c:1226
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:t_next
  - kernel/trace/ftrace.c:t_next
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:__unregister_ftrace_function_probe
  - kernel/trace/ftrace.c:register_ftrace_function_probe
```
**Symbols:**

```
ffffffff8113ff90-ffffffff8113fff8: ftrace_lookup_ip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct ftrace_func_entry *ftrace_lookup_ip(struct ftrace_hash *hash, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81148620)
Location: kernel/trace/ftrace.c:1195
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:__unregister_ftrace_function_probe
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:t_next
  - kernel/trace/ftrace.c:t_next
```
**Symbols:**

```
ffffffff81148620-ffffffff8114867a: ftrace_lookup_ip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct ftrace_func_entry *ftrace_lookup_ip(struct ftrace_hash *hash, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811524d0)
Location: kernel/trace/ftrace.c:1201
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:__unregister_ftrace_function_probe
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:t_next
  - kernel/trace/ftrace.c:t_next
```
**Symbols:**

```
ffffffff811524d0-ffffffff8115252a: ftrace_lookup_ip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct ftrace_func_entry *ftrace_lookup_ip(struct ftrace_hash *hash, long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81156a70)
Location: kernel/trace/ftrace.c:1241
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:ftrace_func_mapper_add_ip
  - kernel/trace/ftrace.c:ftrace_func_mapper_find_ip
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:ftrace_push_return_trace
```
**Symbols:**

```
ffffffff81156a70-ffffffff81156ad3: ftrace_lookup_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct ftrace_func_entry *ftrace_lookup_ip(struct ftrace_hash *hash, long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811635e0)
Location: kernel/trace/ftrace.c:1217
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:ftrace_func_mapper_add_ip
  - kernel/trace/ftrace.c:ftrace_func_mapper_find_ip
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:ftrace_push_return_trace
```
**Symbols:**

```
ffffffff811635e0-ffffffff81163643: ftrace_lookup_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct ftrace_func_entry *ftrace_lookup_ip(struct ftrace_hash *hash, long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81172410)
Location: kernel/trace/ftrace.c:1206
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:ftrace_func_mapper_add_ip
  - kernel/trace/ftrace.c:ftrace_func_mapper_find_ip
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:ftrace_push_return_trace
```
**Symbols:**

```
ffffffff81172410-ffffffff8117247c: ftrace_lookup_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct ftrace_func_entry *ftrace_lookup_ip(struct ftrace_hash *hash, long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8117fe80)
Location: kernel/trace/ftrace.c:1155
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:ftrace_func_mapper_add_ip
  - kernel/trace/ftrace.c:ftrace_func_mapper_find_ip
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
**Symbols:**

```
ffffffff8117fe80-ffffffff8117feec: ftrace_lookup_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct ftrace_func_entry *ftrace_lookup_ip(struct ftrace_hash *hash, long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118cfa0)
Location: kernel/trace/ftrace.c:1152
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:ftrace_func_mapper_add_ip
  - kernel/trace/ftrace.c:ftrace_func_mapper_find_ip
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
**Symbols:**

```
ffffffff8118cfa0-ffffffff8118cff9: ftrace_lookup_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct ftrace_func_entry *ftrace_lookup_ip(struct ftrace_hash *hash, long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81198bb0)
Location: kernel/trace/ftrace.c:1153
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:ftrace_func_mapper_add_ip
  - kernel/trace/ftrace.c:ftrace_func_mapper_find_ip
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
**Symbols:**

```
ffffffff81198bb0-ffffffff81198c09: ftrace_lookup_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct ftrace_func_entry *ftrace_lookup_ip(struct ftrace_hash *hash, long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811ae970)
Location: kernel/trace/ftrace.c:1141
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:clear_func_from_hashes
  - kernel/trace/ftrace.c:clear_func_from_hashes
  - kernel/trace/ftrace.c:referenced_filters
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:ftrace_func_mapper_add_ip
  - kernel/trace/ftrace.c:ftrace_func_mapper_find_ip
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
**Symbols:**

```
ffffffff811ae970-ffffffff811ae9c9: ftrace_lookup_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct ftrace_func_entry *ftrace_lookup_ip(struct ftrace_hash *hash, long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811ac2d0)
Location: kernel/trace/ftrace.c:1140
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:clear_func_from_hashes
  - kernel/trace/ftrace.c:clear_func_from_hashes
  - kernel/trace/ftrace.c:referenced_filters
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:ftrace_func_mapper_add_ip
  - kernel/trace/ftrace.c:ftrace_func_mapper_find_ip
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
**Symbols:**

```
ffffffff811ac2d0-ffffffff811ac329: ftrace_lookup_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct ftrace_func_entry *ftrace_lookup_ip(struct ftrace_hash *hash, long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811ace10)
Location: kernel/trace/ftrace.c:1140
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:referenced_filters
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:ftrace_func_mapper_add_ip
  - kernel/trace/ftrace.c:ftrace_func_mapper_find_ip
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
**Symbols:**

```
ffffffff811ace10-ffffffff811ace6d: ftrace_lookup_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct ftrace_func_entry *ftrace_lookup_ip(struct ftrace_hash *hash, long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:1141
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:referenced_filters
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:ftrace_func_mapper_add_ip
  - kernel/trace/ftrace.c:ftrace_func_mapper_find_ip
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
**Symbols:**

```
ffffffff81cb43e8-ffffffff81cb440c: ftrace_lookup_ip.cold (STB_LOCAL)
ffffffff811d6a70-ffffffff811d6af1: ftrace_lookup_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct ftrace_func_entry *ftrace_lookup_ip(struct ftrace_hash *hash, long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:1135
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:referenced_filters
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:ftrace_func_mapper_add_ip
  - kernel/trace/ftrace.c:ftrace_func_mapper_find_ip
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:__ftrace_hash_rec_update
  - kernel/trace/ftrace.c:__ftrace_hash_rec_update
  - kernel/trace/ftrace.c:__ftrace_hash_rec_update
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
**Symbols:**

```
ffffffff81e653a6-ffffffff81e653ca: ftrace_lookup_ip.cold (STB_LOCAL)
ffffffff8120bf10-ffffffff8120bfa2: ftrace_lookup_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct ftrace_func_entry *ftrace_lookup_ip(struct ftrace_hash *hash, long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:1135
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ops_references_ip
  - kernel/trace/ftrace.c:ops_references_ip
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:ftrace_func_mapper_add_ip
  - kernel/trace/ftrace.c:ftrace_func_mapper_find_ip
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:__ftrace_hash_update_ipmodify
  - kernel/trace/ftrace.c:__ftrace_hash_update_ipmodify
  - kernel/trace/ftrace.c:__ftrace_hash_update_ipmodify
  - kernel/trace/ftrace.c:__ftrace_hash_update_ipmodify
  - kernel/trace/ftrace.c:__ftrace_hash_rec_update
  - kernel/trace/ftrace.c:__ftrace_hash_rec_update
  - kernel/trace/ftrace.c:__ftrace_hash_rec_update
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
**Symbols:**

```
ffffffff8205cd7e-ffffffff8205cda2: ftrace_lookup_ip.cold (STB_LOCAL)
ffffffff812549f0-ffffffff81254a82: ftrace_lookup_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct ftrace_func_entry *ftrace_lookup_ip(struct ftrace_hash *hash, long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:1166
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ops_references_ip
  - kernel/trace/ftrace.c:ops_references_ip
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:ftrace_func_mapper_add_ip
  - kernel/trace/ftrace.c:ftrace_func_mapper_find_ip
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:__ftrace_hash_update_ipmodify
  - kernel/trace/ftrace.c:__ftrace_hash_update_ipmodify
  - kernel/trace/ftrace.c:__ftrace_hash_update_ipmodify
  - kernel/trace/ftrace.c:__ftrace_hash_update_ipmodify
  - kernel/trace/ftrace.c:__ftrace_hash_rec_update
  - kernel/trace/ftrace.c:__ftrace_hash_rec_update
  - kernel/trace/ftrace.c:__ftrace_hash_rec_update
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
**Symbols:**

```
ffffffff820db6ac-ffffffff820db6d0: ftrace_lookup_ip.cold (STB_LOCAL)
ffffffff8126bd10-ffffffff8126bda2: ftrace_lookup_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct ftrace_func_entry *ftrace_lookup_ip(struct ftrace_hash *hash, long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:1166
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ops_references_ip
  - kernel/trace/ftrace.c:ops_references_ip
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:ftrace_func_mapper_add_ip
  - kernel/trace/ftrace.c:ftrace_func_mapper_find_ip
  - kernel/trace/ftrace.c:enter_record
  - kernel/trace/ftrace.c:__ftrace_hash_update_ipmodify
  - kernel/trace/ftrace.c:__ftrace_hash_update_ipmodify
  - kernel/trace/ftrace.c:__ftrace_hash_update_ipmodify
  - kernel/trace/ftrace.c:__ftrace_hash_update_ipmodify
  - kernel/trace/ftrace.c:__ftrace_hash_rec_update
  - kernel/trace/ftrace.c:__ftrace_hash_rec_update
  - kernel/trace/ftrace.c:__ftrace_hash_rec_update
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
**Symbols:**

```
ffffffff821b741d-ffffffff821b7441: ftrace_lookup_ip.cold (STB_LOCAL)
ffffffff81286260-ffffffff812862f2: ftrace_lookup_ip (STB_GLOBAL)
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
struct ftrace_func_entry *ftrace_lookup_ip(struct ftrace_hash *hash, long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffff800010211578)
Location: kernel/trace/ftrace.c:1153
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:ftrace_func_mapper_add_ip
  - kernel/trace/ftrace.c:ftrace_func_mapper_find_ip
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
**Symbols:**

```
ffff800010211578-ffff8000102115ec: ftrace_lookup_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct ftrace_func_entry *ftrace_lookup_ip(struct ftrace_hash *hash, long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c04500b8)
Location: kernel/trace/ftrace.c:1153
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:ftrace_func_mapper_add_ip
  - kernel/trace/ftrace.c:ftrace_func_mapper_find_ip
  - kernel/trace/ftrace.c:t_func_next
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
**Symbols:**

```
c04500b8-c045013c: ftrace_lookup_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct ftrace_func_entry *ftrace_lookup_ip(struct ftrace_hash *hash, long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c000000000290ff0)
Location: kernel/trace/ftrace.c:1153
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:ftrace_func_mapper_add_ip
  - kernel/trace/ftrace.c:ftrace_func_mapper_find_ip
  - kernel/trace/ftrace.c:t_func_next
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
**Symbols:**

```
c000000000290ff0-c000000000291098: ftrace_lookup_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct ftrace_func_entry *ftrace_lookup_ip(struct ftrace_hash *hash, long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffe000171b2a)
Location: kernel/trace/ftrace.c:1153
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:ftrace_func_mapper_add_ip
  - kernel/trace/ftrace.c:ftrace_func_mapper_find_ip
  - kernel/trace/ftrace.c:t_func_next
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
**Symbols:**

```
ffffffe000171b2a-ffffffe000171b88: ftrace_lookup_ip (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct ftrace_func_entry *ftrace_lookup_ip(struct ftrace_hash *hash, long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811911d0)
Location: kernel/trace/ftrace.c:1153
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:ftrace_func_mapper_add_ip
  - kernel/trace/ftrace.c:ftrace_func_mapper_find_ip
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
**Symbols:**

```
ffffffff811911d0-ffffffff81191229: ftrace_lookup_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct ftrace_func_entry *ftrace_lookup_ip(struct ftrace_hash *hash, long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811842e0)
Location: kernel/trace/ftrace.c:1153
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:ftrace_func_mapper_add_ip
  - kernel/trace/ftrace.c:ftrace_func_mapper_find_ip
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
**Symbols:**

```
ffffffff811842e0-ffffffff81184339: ftrace_lookup_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct ftrace_func_entry *ftrace_lookup_ip(struct ftrace_hash *hash, long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118efa0)
Location: kernel/trace/ftrace.c:1153
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:ftrace_func_mapper_add_ip
  - kernel/trace/ftrace.c:ftrace_func_mapper_find_ip
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
**Symbols:**

```
ffffffff8118efa0-ffffffff8118eff9: ftrace_lookup_ip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct ftrace_func_entry *ftrace_lookup_ip(struct ftrace_hash *hash, long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119cb50)
Location: kernel/trace/ftrace.c:1153
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:ftrace_func_mapper_add_ip
  - kernel/trace/ftrace.c:ftrace_func_mapper_find_ip
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
**Symbols:**

```
ffffffff8119cb50-ffffffff8119cba9: ftrace_lookup_ip (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
