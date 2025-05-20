# Function: <code>mas_leaf_max_gap</code>

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
long unsigned int mas_leaf_max_gap(struct ma_state *mas);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff82029140)
Location: lib/maple_tree.c:1453
Inline: False
Direct callers:
  - lib/maple_tree.c:mast_fill_bnode
  - lib/maple_tree.c:mast_fill_bnode
  - lib/maple_tree.c:mas_destroy_rebalance
  - lib/maple_tree.c:mas_destroy_rebalance
  - lib/maple_tree.c:mas_destroy_rebalance
```
**Symbols:**

```
ffffffff82029140-ffffffff8202935e: mas_leaf_max_gap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int mas_leaf_max_gap(struct ma_state *mas);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff820a84d0)
Location: lib/maple_tree.c:1509
Inline: False
Direct callers:
  - lib/maple_tree.c:mast_fill_bnode
  - lib/maple_tree.c:mast_fill_bnode
  - lib/maple_tree.c:mas_destroy_rebalance
  - lib/maple_tree.c:mas_destroy_rebalance
  - lib/maple_tree.c:mas_destroy_rebalance
```
**Symbols:**

```
ffffffff820a84d0-ffffffff820a86e3: mas_leaf_max_gap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int mas_leaf_max_gap(struct ma_state *mas);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff8217ec60)
Location: lib/maple_tree.c:1469
Inline: False
Direct callers:
  - lib/maple_tree.c:mast_fill_bnode
  - lib/maple_tree.c:mast_fill_bnode
  - lib/maple_tree.c:mas_destroy_rebalance
  - lib/maple_tree.c:mas_destroy_rebalance
  - lib/maple_tree.c:mas_destroy_rebalance
```
**Symbols:**

```
ffffffff8217ec60-ffffffff8217eeaa: mas_leaf_max_gap (STB_LOCAL)
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
