# Function: <code>mas_store_b_node</code>

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
void mas_store_b_node(struct ma_wr_state *wr_mas, struct maple_big_node *b_node, unsigned char offset_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff82027270)
Location: lib/maple_tree.c:2116
Inline: False
Direct callers:
  - lib/maple_tree.c:mas_wr_bnode
```
**Symbols:**

```
ffffffff82027270-ffffffff820276f8: mas_store_b_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mas_store_b_node(struct ma_wr_state *wr_mas, struct maple_big_node *b_node, unsigned char offset_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff820a7380)
Location: lib/maple_tree.c:2176
Inline: False
Direct callers:
  - lib/maple_tree.c:mas_wr_bnode
```
**Symbols:**

```
ffffffff820a7380-ffffffff820a7808: mas_store_b_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mas_store_b_node(struct ma_wr_state *wr_mas, struct maple_big_node *b_node, unsigned char offset_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff82180350)
Location: lib/maple_tree.c:2067
Inline: False
Direct callers:
  - lib/maple_tree.c:mas_wr_bnode
```
**Symbols:**

```
ffffffff82180350-ffffffff821807c0: mas_store_b_node (STB_LOCAL)
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
