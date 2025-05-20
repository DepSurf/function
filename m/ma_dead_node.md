# Function: <code>ma_dead_node</code>

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
In lib/maple_tree.c (ffffffff82030ab6)
Location: lib/maple_tree.c:536
Inline: True
Inline callers:
  - lib/maple_tree.c:mt_find
  - lib/maple_tree.c:mtree_load
  - lib/maple_tree.c:mas_erase
  - lib/maple_tree.c:mas_destroy
  - lib/maple_tree.c:mas_prev_entry
  - lib/maple_tree.c:mas_prev_entry
  - lib/maple_tree.c:mas_prev_entry
  - lib/maple_tree.c:mas_next_entry
  - lib/maple_tree.c:mas_next_entry
  - lib/maple_tree.c:mas_next_entry
  - lib/maple_tree.c:mas_next_entry
  - lib/maple_tree.c:mas_next_entry
  - lib/maple_tree.c:mas_next_entry
  - lib/maple_tree.c:mas_next_node
  - lib/maple_tree.c:mas_next_node
  - lib/maple_tree.c:mas_next_node
  - lib/maple_tree.c:mas_prev_node
  - lib/maple_tree.c:mas_prev_node
  - lib/maple_tree.c:mas_prev_node
  - lib/maple_tree.c:mas_prev_node
  - lib/maple_tree.c:mas_ascend
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
In lib/maple_tree.c (ffffffff820ab2f4)
Location: lib/maple_tree.c:532
Inline: True
Inline callers:
  - lib/maple_tree.c:mtree_load
  - lib/maple_tree.c:mtree_load
  - lib/maple_tree.c:mas_destroy
  - lib/maple_tree.c:mas_empty_area_rev
  - lib/maple_tree.c:mas_empty_area
  - lib/maple_tree.c:mas_empty_area
  - lib/maple_tree.c:mas_empty_area
  - lib/maple_tree.c:mas_empty_area
  - lib/maple_tree.c:mas_rev_awalk
  - lib/maple_tree.c:mas_next_slot
  - lib/maple_tree.c:mas_next_slot
  - lib/maple_tree.c:mas_next_slot
  - lib/maple_tree.c:mas_next_node
  - lib/maple_tree.c:mas_next_node
  - lib/maple_tree.c:mas_next_node
  - lib/maple_tree.c:mas_next_node
  - lib/maple_tree.c:mas_next_node
  - lib/maple_tree.c:mas_prev_slot
  - lib/maple_tree.c:mas_prev_slot
  - lib/maple_tree.c:mas_prev_slot
  - lib/maple_tree.c:mas_prev_node
  - lib/maple_tree.c:mas_prev_node
  - lib/maple_tree.c:mas_prev_node
  - lib/maple_tree.c:mas_prev_node
  - lib/maple_tree.c:mas_prev_node
  - lib/maple_tree.c:mas_push_data
  - lib/maple_tree.c:mas_destroy_rebalance
  - lib/maple_tree.c:mtree_range_walk
  - lib/maple_tree.c:mtree_range_walk
  - lib/maple_tree.c:mast_topiary
  - lib/maple_tree.c:mas_ascend
  - lib/maple_tree.c:mas_ascend
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff8218dccf)
Location: lib/maple_tree.c:554
Inline: True
Inline callers:
  - lib/maple_tree.c:mt_find
  - lib/maple_tree.c:mtree_load
  - lib/maple_tree.c:mas_erase
  - lib/maple_tree.c:mas_destroy
  - lib/maple_tree.c:mas_empty_area_rev
  - lib/maple_tree.c:mas_empty_area
  - lib/maple_tree.c:mas_empty_area
  - lib/maple_tree.c:mas_empty_area
  - lib/maple_tree.c:mas_empty_area
  - lib/maple_tree.c:mas_walk
  - lib/maple_tree.c:mas_next_slot
  - lib/maple_tree.c:mas_next_slot
  - lib/maple_tree.c:mas_next_slot
  - lib/maple_tree.c:mas_next_slot
  - lib/maple_tree.c:mas_next_node
  - lib/maple_tree.c:mas_next_node
  - lib/maple_tree.c:mas_next_node
  - lib/maple_tree.c:mas_next_node
  - lib/maple_tree.c:mas_next_node
  - lib/maple_tree.c:mas_prev_slot
  - lib/maple_tree.c:mas_prev_slot
  - lib/maple_tree.c:mas_prev_slot
  - lib/maple_tree.c:mas_prev_slot
  - lib/maple_tree.c:mas_prev_node
  - lib/maple_tree.c:mas_prev_node
  - lib/maple_tree.c:mas_prev_node
  - lib/maple_tree.c:mas_prev_node
  - lib/maple_tree.c:mas_push_data
  - lib/maple_tree.c:mas_ascend
  - lib/maple_tree.c:mas_ascend
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
