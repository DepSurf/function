# Function: <code>mas_mab_cp</code>

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
void mas_mab_cp(struct ma_state *mas, unsigned char mas_start, unsigned char mas_end, struct maple_big_node *b_node, unsigned char mab_start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff82026480)
Location: lib/maple_tree.c:1907
Inline: False
Direct callers:
  - lib/maple_tree.c:mas_push_data
  - lib/maple_tree.c:mas_push_data
  - lib/maple_tree.c:mast_fill_bnode
  - lib/maple_tree.c:mast_fill_bnode
  - lib/maple_tree.c:mas_store_b_node
  - lib/maple_tree.c:mas_store_b_node
```
**Symbols:**

```
ffffffff82026480-ffffffff8202692c: mas_mab_cp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void mas_mab_cp(struct ma_state *mas, unsigned char mas_start, unsigned char mas_end, struct maple_big_node *b_node, unsigned char mab_start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/maple_tree.c (0)
Location: lib/maple_tree.c:1967
Inline: False
Direct callers:
  - lib/maple_tree.c:mas_push_data
  - lib/maple_tree.c:mas_push_data
  - lib/maple_tree.c:mast_fill_bnode
  - lib/maple_tree.c:mast_fill_bnode
  - lib/maple_tree.c:mas_store_b_node
  - lib/maple_tree.c:mas_store_b_node
```
**Symbols:**

```
ffffffff820a6320-ffffffff820a68b8: mas_mab_cp (STB_LOCAL)
ffffffff82138825-ffffffff8213887d: mas_mab_cp.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void mas_mab_cp(struct ma_state *mas, unsigned char mas_start, unsigned char mas_end, struct maple_big_node *b_node, unsigned char mab_start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/maple_tree.c (0)
Location: lib/maple_tree.c:1922
Inline: False
Direct callers:
  - lib/maple_tree.c:mas_push_data
  - lib/maple_tree.c:mas_push_data
  - lib/maple_tree.c:mast_fill_bnode
  - lib/maple_tree.c:mast_fill_bnode
  - lib/maple_tree.c:mas_store_b_node
  - lib/maple_tree.c:mas_store_b_node
```
**Symbols:**

```
ffffffff8217f430-ffffffff8217f9c6: mas_mab_cp (STB_LOCAL)
ffffffff8221a7bf-ffffffff8221a817: mas_mab_cp.cold (STB_LOCAL)
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
