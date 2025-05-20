# Function: <code>mt_is_alloc</code>

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
In lib/maple_tree.c (ffffffff82038c33)
Location: lib/maple_tree.c:356
Inline: True
Inline callers:
  - lib/maple_tree.c:mtree_alloc_rrange
  - lib/maple_tree.c:mtree_alloc_range
  - lib/maple_tree.c:mas_expected_entries
  - lib/maple_tree.c:mas_wr_modify
  - lib/maple_tree.c:mas_wr_bnode
  - lib/maple_tree.c:mas_wr_slot_store
  - lib/maple_tree.c:mas_wr_node_store
  - lib/maple_tree.c:mast_fill_bnode
  - lib/maple_tree.c:mast_fill_bnode
  - lib/maple_tree.c:mas_destroy_rebalance
  - lib/maple_tree.c:mas_destroy_rebalance
  - lib/maple_tree.c:mas_destroy_rebalance
  - lib/maple_tree.c:mab_mas_cp
  - lib/maple_tree.c:mas_mab_cp
  - lib/maple_tree.c:mas_replace
  - lib/maple_tree.c:mas_ascend
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
In lib/maple_tree.c (ffffffff820b714e)
Location: lib/maple_tree.c:361
Inline: True
Inline callers:
  - lib/maple_tree.c:mtree_alloc_rrange
  - lib/maple_tree.c:mtree_alloc_range
  - lib/maple_tree.c:mas_expected_entries
  - lib/maple_tree.c:mas_wr_modify
  - lib/maple_tree.c:mas_wr_bnode
  - lib/maple_tree.c:mas_wr_node_store
  - lib/maple_tree.c:mast_fill_bnode
  - lib/maple_tree.c:mast_fill_bnode
  - lib/maple_tree.c:mas_destroy_rebalance
  - lib/maple_tree.c:mas_destroy_rebalance
  - lib/maple_tree.c:mas_destroy_rebalance
  - lib/maple_tree.c:mas_wmb_replace
  - lib/maple_tree.c:mab_mas_cp
  - lib/maple_tree.c:mas_mab_cp
  - lib/maple_tree.c:mas_replace
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
In lib/maple_tree.c (ffffffff821912dd)
Location: lib/maple_tree.c:381
Inline: True
Inline callers:
  - lib/maple_tree.c:mtree_alloc_rrange
  - lib/maple_tree.c:mtree_alloc_range
  - lib/maple_tree.c:mtree_store_range
  - lib/maple_tree.c:mas_erase
  - lib/maple_tree.c:mas_expected_entries
  - lib/maple_tree.c:mas_wr_bnode
  - lib/maple_tree.c:mas_wr_bnode
  - lib/maple_tree.c:mas_wr_append
  - lib/maple_tree.c:mas_wr_slot_store
  - lib/maple_tree.c:mas_wr_node_store
  - lib/maple_tree.c:mas_wr_node_store
  - lib/maple_tree.c:mast_fill_bnode
  - lib/maple_tree.c:mast_fill_bnode
  - lib/maple_tree.c:mas_split_final_node
  - lib/maple_tree.c:mas_destroy_rebalance
  - lib/maple_tree.c:mas_destroy_rebalance
  - lib/maple_tree.c:mas_destroy_rebalance
  - lib/maple_tree.c:mas_destroy_rebalance
  - lib/maple_tree.c:mas_topiary_replace
  - lib/maple_tree.c:mab_mas_cp
  - lib/maple_tree.c:mas_mab_cp
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
