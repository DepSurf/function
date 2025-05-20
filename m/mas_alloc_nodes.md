# Function: <code>mas_alloc_nodes</code>

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
void mas_alloc_nodes(struct ma_state *mas, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff820280e0)
Location: lib/maple_tree.c:1211
Inline: False
Direct callers:
  - lib/maple_tree.c:mtree_insert_range
  - lib/maple_tree.c:mtree_insert_range
  - lib/maple_tree.c:mtree_store_range
  - lib/maple_tree.c:mtree_store_range
  - lib/maple_tree.c:mas_preallocate
```
**Symbols:**

```
ffffffff820280e0-ffffffff8202835d: mas_alloc_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mas_alloc_nodes(struct ma_state *mas, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff820a99c0)
Location: lib/maple_tree.c:1262
Inline: False
Direct callers:
  - lib/maple_tree.c:mtree_insert_range
  - lib/maple_tree.c:mtree_insert_range
  - lib/maple_tree.c:mtree_store_range
  - lib/maple_tree.c:mtree_store_range
  - lib/maple_tree.c:mas_preallocate
```
**Symbols:**

```
ffffffff820a99c0-ffffffff820a9c48: mas_alloc_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mas_alloc_nodes(struct ma_state *mas, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff82181420)
Location: lib/maple_tree.c:1221
Inline: False
Direct callers:
  - lib/maple_tree.c:mtree_insert_range
  - lib/maple_tree.c:mtree_insert_range
  - lib/maple_tree.c:mas_node_count_gfp
```
**Symbols:**

```
ffffffff82181420-ffffffff8218164c: mas_alloc_nodes (STB_LOCAL)
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
