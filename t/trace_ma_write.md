# Function: <code>trace_ma_write</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff820375d9)
Location: include/trace/events/maple_tree.h:80
Inline: True
Inline callers:
  - lib/maple_tree.c:mtree_store_range
  - lib/maple_tree.c:mtree_store_range
  - lib/maple_tree.c:mas_store_prealloc
  - lib/maple_tree.c:mas_store_prealloc
  - lib/maple_tree.c:mas_store_gfp
  - lib/maple_tree.c:mas_store_gfp
  - lib/maple_tree.c:mas_store
  - lib/maple_tree.c:mas_store
  - lib/maple_tree.c:mas_wr_bnode
  - lib/maple_tree.c:mas_wr_bnode
  - lib/maple_tree.c:mas_wr_slot_store
  - lib/maple_tree.c:mas_wr_slot_store
  - lib/maple_tree.c:mas_wr_node_store
  - lib/maple_tree.c:mas_wr_node_store
  - lib/maple_tree.c:mas_is_span_wr
  - lib/maple_tree.c:mas_is_span_wr
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff820ac5f7)
Location: include/trace/events/maple_tree.h:80
Inline: True
Inline callers:
  - lib/maple_tree.c:mt_find
  - lib/maple_tree.c:mtree_erase
  - lib/maple_tree.c:mtree_store_range
  - lib/maple_tree.c:mtree_store_range
  - lib/maple_tree.c:mtree_load
  - lib/maple_tree.c:mas_store_prealloc
  - lib/maple_tree.c:mas_store_prealloc
  - lib/maple_tree.c:mas_store_gfp
  - lib/maple_tree.c:mas_store_gfp
  - lib/maple_tree.c:mas_store
  - lib/maple_tree.c:mas_store
  - lib/maple_tree.c:mas_wr_modify
  - lib/maple_tree.c:mas_wr_modify
  - lib/maple_tree.c:mas_wr_bnode
  - lib/maple_tree.c:mas_wr_bnode
  - lib/maple_tree.c:mas_wr_node_store
  - lib/maple_tree.c:mas_wr_node_store
  - lib/maple_tree.c:mas_is_span_wr
  - lib/maple_tree.c:mas_is_span_wr
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void trace_ma_write(const char *fn, struct ma_state *mas, long unsigned int piv, void *val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff8218df22)
Location: include/trace/events/maple_tree.h:80
Inline: True
Inline callers:
  - lib/maple_tree.c:mt_find
  - lib/maple_tree.c:mtree_erase
  - lib/maple_tree.c:mtree_store_range
  - lib/maple_tree.c:mtree_store_range
  - lib/maple_tree.c:mtree_load
  - lib/maple_tree.c:mas_store_prealloc
  - lib/maple_tree.c:mas_store_prealloc
  - lib/maple_tree.c:mas_store_gfp
  - lib/maple_tree.c:mas_store_gfp
  - lib/maple_tree.c:mas_store
  - lib/maple_tree.c:mas_store
  - lib/maple_tree.c:mas_wr_bnode
  - lib/maple_tree.c:mas_wr_bnode
  - lib/maple_tree.c:mas_wr_append
  - lib/maple_tree.c:mas_wr_append
  - lib/maple_tree.c:mas_wr_slot_store
  - lib/maple_tree.c:mas_wr_slot_store
  - lib/maple_tree.c:mas_wr_walk
  - lib/maple_tree.c:mas_wr_walk
Direct callers:
  - lib/maple_tree.c:mas_wr_node_store
```
**Symbols:**

```
ffffffff82180180-ffffffff8218021c: trace_ma_write (STB_LOCAL)
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
</ul>
