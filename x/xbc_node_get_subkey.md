# Function: <code>xbc_node_get_subkey</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate ⚠️</summary>

```c
struct xbc_node *xbc_node_get_subkey(struct xbc_node *node);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_boot.c (ffffffff832d2def)
Location: include/linux/bootconfig.h:161
Inline: False
Direct callers:
  - kernel/trace/trace_boot.c:trace_boot_init
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_hist_add_handlers
```
```
In lib/bootconfig.c (ffffffff832e955b)
Location: include/linux/bootconfig.h:161
Inline: False
Direct callers:
  - lib/bootconfig.c:xbc_node_find_next_leaf
  - lib/bootconfig.c:xbc_node_find_subkey
```
**Symbols:**

```
ffffffff832d2def-ffffffff832d2e0e: xbc_node_get_subkey (STB_LOCAL)
ffffffff832e955b-ffffffff832e957a: xbc_node_get_subkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate ⚠️</summary>

```c
struct xbc_node *xbc_node_get_subkey(struct xbc_node *node);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_boot.c (ffffffff8348727b)
Location: include/linux/bootconfig.h:171
Inline: False
Direct callers:
  - kernel/trace/trace_boot.c:trace_boot_init
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_hist_add_handlers
```
```
In lib/bootconfig.c (ffffffff834a0e37)
Location: include/linux/bootconfig.h:171
Inline: False
Direct callers:
  - lib/bootconfig.c:xbc_node_find_next_leaf
  - lib/bootconfig.c:xbc_node_find_subkey
```
**Symbols:**

```
ffffffff8348727b-ffffffff834872a0: xbc_node_get_subkey (STB_LOCAL)
ffffffff834a0e37-ffffffff834a0e5c: xbc_node_get_subkey (STB_LOCAL)
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
In kernel/trace/trace_boot.c (ffffffff83eb86de)
Location: include/linux/bootconfig.h:171
Inline: True
Inline callers:
  - kernel/trace/trace_boot.c:trace_boot_init
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_hist_add_handlers
```
```
In lib/bootconfig.c (ffffffff83edae25)
Location: include/linux/bootconfig.h:171
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_node_find_next_leaf
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
In kernel/trace/trace_boot.c (ffffffff836ddbce)
Location: include/linux/bootconfig.h:171
Inline: True
Inline callers:
  - kernel/trace/trace_boot.c:trace_boot_init
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_hist_add_handlers
```
```
In lib/bootconfig.c (ffffffff83700955)
Location: include/linux/bootconfig.h:171
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_node_find_next_leaf
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
In kernel/trace/trace_boot.c (ffffffff839101fe)
Location: include/linux/bootconfig.h:171
Inline: True
Inline callers:
  - kernel/trace/trace_boot.c:trace_boot_init
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_hist_add_handlers
```
```
In lib/bootconfig.c (ffffffff83934195)
Location: include/linux/bootconfig.h:171
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_node_find_next_leaf
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
