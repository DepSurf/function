# Function: <code>mas_ascend</code>

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
<summary>In <code>6.2</code>: ✅</summary>

```c
int mas_ascend(struct ma_state *mas);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff82029700)
Location: lib/maple_tree.c:1049
Inline: False
Direct callers:
  - lib/maple_tree.c:mtree_alloc_rrange
  - lib/maple_tree.c:mtree_alloc_range
  - lib/maple_tree.c:mtree_alloc_range
  - lib/maple_tree.c:mas_empty_area_rev
  - lib/maple_tree.c:mas_empty_area_rev
  - lib/maple_tree.c:mas_empty_area
  - lib/maple_tree.c:mas_empty_area
  - lib/maple_tree.c:mas_next_node
  - lib/maple_tree.c:mas_prev_node
  - lib/maple_tree.c:mas_push_data
  - lib/maple_tree.c:mast_fill_bnode
  - lib/maple_tree.c:mas_destroy_rebalance
  - lib/maple_tree.c:mas_destroy_rebalance
```
**Symbols:**

```
ffffffff82029700-ffffffff8202997e: mas_ascend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mas_ascend(struct ma_state *mas);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff820aa0b0)
Location: lib/maple_tree.c:1094
Inline: False
Direct callers:
  - lib/maple_tree.c:mas_empty_area_rev
  - lib/maple_tree.c:mas_empty_area_rev
  - lib/maple_tree.c:mas_empty_area
  - lib/maple_tree.c:mas_empty_area
  - lib/maple_tree.c:mas_next_node
  - lib/maple_tree.c:mas_prev_node
  - lib/maple_tree.c:mas_push_data
  - lib/maple_tree.c:mast_fill_bnode
  - lib/maple_tree.c:mas_destroy_rebalance
  - lib/maple_tree.c:mas_destroy_rebalance
```
**Symbols:**

```
ffffffff820aa0b0-ffffffff820aa315: mas_ascend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mas_ascend(struct ma_state *mas);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff82181f20)
Location: lib/maple_tree.c:1051
Inline: False
Direct callers:
  - lib/maple_tree.c:mas_empty_area_rev
  - lib/maple_tree.c:mas_empty_area_rev
  - lib/maple_tree.c:mas_empty_area
  - lib/maple_tree.c:mas_empty_area
  - lib/maple_tree.c:mas_next_node
  - lib/maple_tree.c:mas_prev_node
  - lib/maple_tree.c:mas_push_data
  - lib/maple_tree.c:mast_fill_bnode
  - lib/maple_tree.c:mas_destroy_rebalance
  - lib/maple_tree.c:mas_destroy_rebalance
```
**Symbols:**

```
ffffffff82181f20-ffffffff82182193: mas_ascend (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
