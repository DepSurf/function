# Function: <code>free_ftrace_hash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_ftrace_hash(struct ftrace_hash *hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81140400)
Location: kernel/trace/ftrace.c:1315
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:__free_ftrace_hash_rcu
  - kernel/trace/ftrace.c:ftrace_hash_move
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:__unregister_ftrace_function_probe
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:register_ftrace_function_probe
```
**Symbols:**

```
ffffffff81140400-ffffffff8114051e: free_ftrace_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_ftrace_hash(struct ftrace_hash *hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81148aa0)
Location: kernel/trace/ftrace.c:1284
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:__unregister_ftrace_function_probe
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_hash_move
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:__free_ftrace_hash_rcu
```
**Symbols:**

```
ffffffff81148aa0-ffffffff81148bf7: free_ftrace_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_ftrace_hash(struct ftrace_hash *hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81152950)
Location: kernel/trace/ftrace.c:1290
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:__unregister_ftrace_function_probe
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_hash_move
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:__free_ftrace_hash_rcu
```
**Symbols:**

```
ffffffff81152950-ffffffff81152aa7: free_ftrace_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81159d95)
Location: kernel/trace/ftrace.c:1333
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:free_ftrace_func_mapper
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:__free_ftrace_hash_rcu
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:free_ftrace_func_mapper
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:__free_ftrace_hash_rcu
```
**Symbols:**

```
ffffffff81155e20-ffffffff81155f69: free_ftrace_hash.part.52 (STB_LOCAL)
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
In kernel/trace/ftrace.c (ffffffff81166895)
Location: kernel/trace/ftrace.c:1309
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:free_ftrace_func_mapper
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:__free_ftrace_hash_rcu
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:free_ftrace_func_mapper
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:__free_ftrace_hash_rcu
```
**Symbols:**

```
ffffffff811628c0-ffffffff81162a09: free_ftrace_hash.part.56 (STB_LOCAL)
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
In kernel/trace/ftrace.c (ffffffff81175595)
Location: kernel/trace/ftrace.c:1298
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:free_ftrace_func_mapper
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:__free_ftrace_hash_rcu
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:free_ftrace_func_mapper
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:__free_ftrace_hash_rcu
```
**Symbols:**

```
ffffffff81171790-ffffffff81171883: free_ftrace_hash.part.58 (STB_LOCAL)
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
In kernel/trace/ftrace.c (ffffffff811831d5)
Location: kernel/trace/ftrace.c:1247
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:free_ftrace_func_mapper
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:__free_ftrace_hash_rcu
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:free_ftrace_func_mapper
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:__free_ftrace_hash_rcu
```
**Symbols:**

```
ffffffff8117f100-ffffffff8117f1f3: free_ftrace_hash.part.56 (STB_LOCAL)
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
In kernel/trace/ftrace.c (ffffffff8118ff4b)
Location: kernel/trace/ftrace.c:1244
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:free_ftrace_func_mapper
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:__free_ftrace_hash_rcu
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:free_ftrace_func_mapper
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:__free_ftrace_hash_rcu
```
**Symbols:**

```
ffffffff8118bfd0-ffffffff8118c0a7: free_ftrace_hash.part.0 (STB_LOCAL)
ffffffff81191f5d-ffffffff81191f8f: free_ftrace_hash.part.0.cold (STB_LOCAL)
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
In kernel/trace/ftrace.c (ffffffff8119bf26)
Location: kernel/trace/ftrace.c:1245
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:free_ftrace_func_mapper
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:__free_ftrace_hash_rcu
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:free_ftrace_func_mapper
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:__free_ftrace_hash_rcu
```
**Symbols:**

```
ffffffff81197e70-ffffffff81197f68: free_ftrace_hash.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b28d2)
Location: kernel/trace/ftrace.c:1233
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:free_ftrace_func_mapper
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:__free_ftrace_hash_rcu
Direct callers:
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:free_ftrace_func_mapper
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:__free_ftrace_hash_rcu
```
**Symbols:**

```
ffffffff811adbe0-ffffffff811adccf: free_ftrace_hash.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b0342)
Location: kernel/trace/ftrace.c:1232
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:free_ftrace_func_mapper
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:__free_ftrace_hash_rcu
Direct callers:
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:free_ftrace_func_mapper
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:__free_ftrace_hash_rcu
```
**Symbols:**

```
ffffffff811ab4f0-ffffffff811ab5df: free_ftrace_hash.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b0c52)
Location: kernel/trace/ftrace.c:1232
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:free_ftrace_func_mapper
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:__free_ftrace_hash_rcu
Direct callers:
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:free_ftrace_func_mapper
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:__free_ftrace_hash_rcu
```
**Symbols:**

```
ffffffff811abf70-ffffffff811ac06f: free_ftrace_hash.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811daad2)
Location: kernel/trace/ftrace.c:1233
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:free_ftrace_func_mapper
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:__free_ftrace_hash_rcu
Direct callers:
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:free_ftrace_func_mapper
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:__free_ftrace_hash_rcu
```
**Symbols:**

```
ffffffff811d5bd0-ffffffff811d5cd9: free_ftrace_hash.part.0 (STB_LOCAL)
ffffffff81cb42d0-ffffffff81cb42f1: free_ftrace_hash.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff812109f6)
Location: kernel/trace/ftrace.c:1227
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:register_ftrace_direct_multi
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:free_ftrace_func_mapper
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:__free_ftrace_hash_rcu
Direct callers:
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:register_ftrace_direct_multi
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:free_ftrace_func_mapper
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:__free_ftrace_hash_rcu
```
**Symbols:**

```
ffffffff8120adf0-ffffffff8120af17: free_ftrace_hash.part.0 (STB_LOCAL)
ffffffff81e652a1-ffffffff81e652c2: free_ftrace_hash.part.0.cold (STB_LOCAL)
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
In kernel/trace/ftrace.c (ffffffff81259e76)
Location: kernel/trace/ftrace.c:1227
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:register_ftrace_direct_multi
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:free_ftrace_func_mapper
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:__free_ftrace_hash_rcu
Direct callers:
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:register_ftrace_direct_multi
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:free_ftrace_func_mapper
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:__free_ftrace_hash_rcu
```
**Symbols:**

```
ffffffff812533e0-ffffffff81253507: free_ftrace_hash.part.0 (STB_LOCAL)
ffffffff8205cc79-ffffffff8205cc9a: free_ftrace_hash.part.0.cold (STB_LOCAL)
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
In kernel/trace/ftrace.c (ffffffff81270738)
Location: kernel/trace/ftrace.c:1258
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:free_ftrace_func_mapper
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:__free_ftrace_hash_rcu
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:free_ftrace_func_mapper
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:__free_ftrace_hash_rcu
```
**Symbols:**

```
ffffffff8126a7a0-ffffffff8126a8d2: free_ftrace_hash.part.0 (STB_LOCAL)
ffffffff820db5b8-ffffffff820db5d9: free_ftrace_hash.part.0.cold (STB_LOCAL)
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
In kernel/trace/ftrace.c (ffffffff8128ab9e)
Location: kernel/trace/ftrace.c:1259
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:free_ftrace_func_mapper
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:__free_ftrace_hash_rcu
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:free_ftrace_func_mapper
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:__free_ftrace_hash_rcu
```
**Symbols:**

```
ffffffff81284950-ffffffff81284a82: free_ftrace_hash.part.0 (STB_LOCAL)
ffffffff821b728f-ffffffff821b72b0: free_ftrace_hash.part.0.cold (STB_LOCAL)
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
In kernel/trace/ftrace.c (ffff800010214d90)
Location: kernel/trace/ftrace.c:1245
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:free_ftrace_func_mapper
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:__free_ftrace_hash_rcu
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:free_ftrace_func_mapper
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:__free_ftrace_hash_rcu
```
**Symbols:**

```
ffff800010210538-ffff80001021063c: free_ftrace_hash.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (c0453afc)
Location: kernel/trace/ftrace.c:1245
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:free_ftrace_func_mapper
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:__free_ftrace_hash_rcu
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:free_ftrace_func_mapper
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:__free_ftrace_hash_rcu
```
**Symbols:**

```
c044f38c-c044f494: free_ftrace_hash.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (c000000000296288)
Location: kernel/trace/ftrace.c:1245
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:free_ftrace_func_mapper
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:__free_ftrace_hash_rcu
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:free_ftrace_func_mapper
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:__free_ftrace_hash_rcu
```
**Symbols:**

```
c00000000028fa20-c00000000028fbc0: free_ftrace_hash.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffe000174bde)
Location: kernel/trace/ftrace.c:1245
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:free_ftrace_func_mapper
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:__free_ftrace_hash_rcu
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:free_ftrace_func_mapper
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:__free_ftrace_hash_rcu
```
**Symbols:**

```
ffffffe000171114-ffffffe0001711fa: free_ftrace_hash.part.0 (STB_LOCAL)
```
</details>
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
In kernel/trace/ftrace.c (ffffffff81194546)
Location: kernel/trace/ftrace.c:1245
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:free_ftrace_func_mapper
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:__free_ftrace_hash_rcu
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:free_ftrace_func_mapper
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:__free_ftrace_hash_rcu
```
**Symbols:**

```
ffffffff81190490-ffffffff81190588: free_ftrace_hash.part.0 (STB_LOCAL)
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
In kernel/trace/ftrace.c (ffffffff81187656)
Location: kernel/trace/ftrace.c:1245
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:free_ftrace_func_mapper
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:__free_ftrace_hash_rcu
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:free_ftrace_func_mapper
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:__free_ftrace_hash_rcu
```
**Symbols:**

```
ffffffff81183820-ffffffff81183918: free_ftrace_hash.part.0 (STB_LOCAL)
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
In kernel/trace/ftrace.c (ffffffff81192316)
Location: kernel/trace/ftrace.c:1245
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:free_ftrace_func_mapper
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:__free_ftrace_hash_rcu
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:free_ftrace_func_mapper
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:__free_ftrace_hash_rcu
```
**Symbols:**

```
ffffffff8118e260-ffffffff8118e358: free_ftrace_hash.part.0 (STB_LOCAL)
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
In kernel/trace/ftrace.c (ffffffff8119fea6)
Location: kernel/trace/ftrace.c:1245
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:free_ftrace_func_mapper
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:__free_ftrace_hash_rcu
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:free_ftrace_func_mapper
  - kernel/trace/ftrace.c:process_mod_list
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:ftrace_free_filter
  - kernel/trace/ftrace.c:__free_ftrace_hash_rcu
```
**Symbols:**

```
ffffffff8119bdf0-ffffffff8119bee8: free_ftrace_hash.part.0 (STB_LOCAL)
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
</ul>
