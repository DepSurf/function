# Function: <code>mt_in_rcu</code>

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
In lib/maple_tree.c (ffffffff82028633)
Location: include/linux/maple_tree.h:595
Inline: True
Inline callers:
  - lib/maple_tree.c:mtree_destroy
  - lib/maple_tree.c:mas_wr_node_store
  - lib/maple_tree.c:mas_reuse_node
  - lib/maple_tree.c:mas_destroy_rebalance
  - lib/maple_tree.c:mas_replace
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
In kernel/fork.c (ffffffff810f272e)
Location: include/linux/maple_tree.h:604
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In mm/mmap.c (ffffffff813fe474)
Location: include/linux/maple_tree.h:604
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
```
```
In lib/maple_tree.c (ffffffff820a847e)
Location: include/linux/maple_tree.h:604
Inline: True
Inline callers:
  - lib/maple_tree.c:mtree_destroy
  - lib/maple_tree.c:mas_wr_modify
  - lib/maple_tree.c:mas_wr_node_store
  - lib/maple_tree.c:mas_reuse_node
  - lib/maple_tree.c:mas_destroy_rebalance
  - lib/maple_tree.c:mas_wmb_replace
  - lib/maple_tree.c:mas_wmb_replace
  - lib/maple_tree.c:mas_replace
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
In kernel/fork.c (ffffffff810fb212)
Location: include/linux/maple_tree.h:786
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In mm/mmap.c (ffffffff8142a862)
Location: include/linux/maple_tree.h:786
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
```
```
In lib/maple_tree.c (ffffffff821813db)
Location: include/linux/maple_tree.h:786
Inline: True
Inline callers:
  - lib/maple_tree.c:mtree_destroy
  - lib/maple_tree.c:mas_preallocate
  - lib/maple_tree.c:mas_wr_bnode
  - lib/maple_tree.c:mas_wr_append
  - lib/maple_tree.c:mas_wr_slot_store
  - lib/maple_tree.c:mas_wr_node_store
  - lib/maple_tree.c:mas_wr_node_store
  - lib/maple_tree.c:mas_reuse_node
  - lib/maple_tree.c:mas_destroy_rebalance
  - lib/maple_tree.c:mas_destroy_rebalance
  - lib/maple_tree.c:mas_topiary_replace
  - lib/maple_tree.c:mas_topiary_replace
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
