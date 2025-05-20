# Function: <code>mab_mas_cp</code>

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
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void mab_mas_cp(struct maple_big_node *b_node, unsigned char mab_start, unsigned char mab_end, struct ma_state *mas, bool new_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/maple_tree.c (0)
Location: lib/maple_tree.c:1987
Inline: False
Direct callers:
  - lib/maple_tree.c:mas_wr_bnode
  - lib/maple_tree.c:mas_reuse_node
```
**Symbols:**

```
ffffffff82026a00-ffffffff82026f2d: mab_mas_cp (STB_LOCAL)
ffffffff820b749d-ffffffff820b74e0: mab_mas_cp.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void mab_mas_cp(struct maple_big_node *b_node, unsigned char mab_start, unsigned char mab_end, struct ma_state *mas, bool new_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/maple_tree.c (0)
Location: lib/maple_tree.c:2047
Inline: False
Direct callers:
  - lib/maple_tree.c:mas_wr_bnode
  - lib/maple_tree.c:mas_reuse_node
```
**Symbols:**

```
ffffffff820a6b40-ffffffff820a70b7: mab_mas_cp (STB_LOCAL)
ffffffff821388e8-ffffffff82138929: mab_mas_cp.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mab_mas_cp(struct maple_big_node *b_node, unsigned char mab_start, unsigned char mab_end, struct ma_state *mas, bool new_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff8217f9e0)
Location: lib/maple_tree.c:1988
Inline: False
Direct callers:
  - lib/maple_tree.c:mas_wr_bnode
  - lib/maple_tree.c:mas_reuse_node
  - lib/maple_tree.c:mast_split_data
  - lib/maple_tree.c:mast_split_data
  - lib/maple_tree.c:mas_split_final_node
```
**Symbols:**

```
ffffffff8217f9e0-ffffffff8217fe5b: mab_mas_cp (STB_LOCAL)
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
