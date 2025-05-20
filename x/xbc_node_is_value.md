# Function: <code>xbc_node_is_value</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff82d0a149)
Location: include/linux/bootconfig.h:47
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_parse_kv
  - lib/bootconfig.c:__xbc_add_key
  - lib/bootconfig.c:xbc_debug_dump
  - lib/bootconfig.c:xbc_node_compose_key_after
  - lib/bootconfig.c:xbc_node_find_next_leaf
  - lib/bootconfig.c:xbc_node_find_next_leaf
  - lib/bootconfig.c:xbc_node_find_value
  - lib/bootconfig.c:xbc_node_find_value
  - lib/bootconfig.c:xbc_node_find_child
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
In lib/bootconfig.c (ffffffff82ff7730)
Location: include/linux/bootconfig.h:50
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_parse_kv
  - lib/bootconfig.c:__xbc_add_key
  - lib/bootconfig.c:xbc_debug_dump
  - lib/bootconfig.c:xbc_node_compose_key_after
  - lib/bootconfig.c:xbc_node_find_next_leaf
  - lib/bootconfig.c:xbc_node_find_next_leaf
  - lib/bootconfig.c:xbc_node_find_value
  - lib/bootconfig.c:xbc_node_find_value
  - lib/bootconfig.c:xbc_node_find_child
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
In lib/bootconfig.c (ffffffff83202210)
Location: include/linux/bootconfig.h:50
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:__xbc_add_key
  - lib/bootconfig.c:xbc_debug_dump
  - lib/bootconfig.c:xbc_init
  - lib/bootconfig.c:xbc_node_compose_key_after
  - lib/bootconfig.c:xbc_node_find_next_leaf
  - lib/bootconfig.c:xbc_node_find_next_leaf
  - lib/bootconfig.c:xbc_node_find_value
  - lib/bootconfig.c:xbc_node_find_value
  - lib/bootconfig.c:xbc_node_find_child
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
In kernel/trace/trace_boot.c (ffffffff832d34c2)
Location: include/linux/bootconfig.h:70
Inline: True
Inline callers:
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:xbc_node_get_subkey
```
```
In fs/proc/bootconfig.c (ffffffff832e182a)
Location: include/linux/bootconfig.h:70
Inline: True
Inline callers:
  - fs/proc/bootconfig.c:copy_xbc_key_value_list
```
```
In lib/bootconfig.c (ffffffff832e997d)
Location: include/linux/bootconfig.h:70
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:__xbc_add_key
  - lib/bootconfig.c:xbc_debug_dump
  - lib/bootconfig.c:xbc_init
  - lib/bootconfig.c:xbc_node_compose_key_after
  - lib/bootconfig.c:xbc_node_get_subkey
  - lib/bootconfig.c:xbc_node_find_next_leaf
  - lib/bootconfig.c:xbc_node_find_next_leaf
  - lib/bootconfig.c:xbc_node_find_value
  - lib/bootconfig.c:xbc_node_find_value
  - lib/bootconfig.c:xbc_node_find_subkey
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
In kernel/trace/trace_boot.c (ffffffff834879f3)
Location: include/linux/bootconfig.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:xbc_node_get_subkey
```
```
In fs/proc/bootconfig.c (ffffffff83497990)
Location: include/linux/bootconfig.h:80
Inline: True
Inline callers:
  - fs/proc/bootconfig.c:copy_xbc_key_value_list
```
```
In lib/bootconfig.c (ffffffff834a12e1)
Location: include/linux/bootconfig.h:80
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_parse_tree
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:__xbc_add_key
  - lib/bootconfig.c:xbc_node_compose_key_after
  - lib/bootconfig.c:xbc_node_get_subkey
  - lib/bootconfig.c:xbc_node_find_next_leaf
  - lib/bootconfig.c:xbc_node_find_next_leaf
  - lib/bootconfig.c:xbc_node_find_value
  - lib/bootconfig.c:xbc_node_find_value
  - lib/bootconfig.c:xbc_node_find_subkey
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
In kernel/trace/trace_boot.c (ffffffff83eb86eb)
Location: include/linux/bootconfig.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_boot.c:trace_boot_init
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_hist_add_handlers
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
```
```
In fs/proc/bootconfig.c (ffffffff83eccfc8)
Location: include/linux/bootconfig.h:80
Inline: True
Inline callers:
  - fs/proc/bootconfig.c:copy_xbc_key_value_list
```
```
In lib/bootconfig.c (ffffffff83eda515)
Location: include/linux/bootconfig.h:80
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_parse_tree
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:__xbc_add_key
  - lib/bootconfig.c:xbc_node_compose_key_after
  - lib/bootconfig.c:xbc_node_find_next_leaf
  - lib/bootconfig.c:xbc_node_find_next_leaf
  - lib/bootconfig.c:xbc_node_find_next_leaf
  - lib/bootconfig.c:xbc_node_find_value
  - lib/bootconfig.c:xbc_node_find_value
  - lib/bootconfig.c:xbc_node_find_subkey
  - lib/bootconfig.c:xbc_node_find_subkey
  - lib/bootconfig.c:xbc_node_find_subkey
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
In kernel/trace/trace_boot.c (ffffffff836ddbdb)
Location: include/linux/bootconfig.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_boot.c:trace_boot_init
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_hist_add_handlers
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
```
```
In fs/proc/bootconfig.c (ffffffff836f2048)
Location: include/linux/bootconfig.h:80
Inline: True
Inline callers:
  - fs/proc/bootconfig.c:copy_xbc_key_value_list
```
```
In lib/bootconfig.c (ffffffff8370040a)
Location: include/linux/bootconfig.h:80
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_parse_kv
  - lib/bootconfig.c:__xbc_add_key
  - lib/bootconfig.c:xbc_node_compose_key_after
  - lib/bootconfig.c:xbc_node_find_next_leaf
  - lib/bootconfig.c:xbc_node_find_next_leaf
  - lib/bootconfig.c:xbc_node_find_next_leaf
  - lib/bootconfig.c:xbc_node_find_value
  - lib/bootconfig.c:xbc_node_find_value
  - lib/bootconfig.c:xbc_node_find_subkey
  - lib/bootconfig.c:xbc_node_find_subkey
  - lib/bootconfig.c:xbc_node_find_subkey
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
In kernel/trace/trace_boot.c (ffffffff8391020b)
Location: include/linux/bootconfig.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_boot.c:trace_boot_init
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_hist_add_handlers
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
```
```
In fs/proc/bootconfig.c (ffffffff839251dd)
Location: include/linux/bootconfig.h:80
Inline: True
Inline callers:
  - fs/proc/bootconfig.c:copy_xbc_key_value_list
```
```
In lib/bootconfig.c (ffffffff83933c4a)
Location: include/linux/bootconfig.h:80
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_parse_kv
  - lib/bootconfig.c:__xbc_add_key
  - lib/bootconfig.c:xbc_node_compose_key_after
  - lib/bootconfig.c:xbc_node_find_next_leaf
  - lib/bootconfig.c:xbc_node_find_next_leaf
  - lib/bootconfig.c:xbc_node_find_next_leaf
  - lib/bootconfig.c:xbc_node_find_value
  - lib/bootconfig.c:xbc_node_find_value
  - lib/bootconfig.c:xbc_node_find_subkey
  - lib/bootconfig.c:xbc_node_find_subkey
  - lib/bootconfig.c:xbc_node_find_subkey
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
