# Function: <code>mas_wr_node_store</code>

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
bool mas_wr_node_store(struct ma_wr_state *wr_mas);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/maple_tree.c (0)
Location: lib/maple_tree.c:4059
Inline: False
Direct callers:
  - lib/maple_tree.c:mas_wr_modify
  - lib/maple_tree.c:mas_wr_modify
```
**Symbols:**

```
ffffffff8202f5c0-ffffffff8202fdca: mas_wr_node_store (STB_LOCAL)
ffffffff820b74e0-ffffffff820b7549: mas_wr_node_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool mas_wr_node_store(struct ma_wr_state *wr_mas, unsigned char new_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/maple_tree.c (0)
Location: lib/maple_tree.c:4078
Inline: False
Direct callers:
  - lib/maple_tree.c:mas_wr_modify
```
**Symbols:**

```
ffffffff820af890-ffffffff820aff7b: mas_wr_node_store (STB_LOCAL)
ffffffff82138929-ffffffff821389e9: mas_wr_node_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool mas_wr_node_store(struct ma_wr_state *wr_mas, unsigned char new_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff821859d0)
Location: lib/maple_tree.c:3883
Inline: False
Direct callers:
  - lib/maple_tree.c:mtree_store_range
  - lib/maple_tree.c:mas_erase
```
**Symbols:**

```
ffffffff821859d0-ffffffff8218610f: mas_wr_node_store (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned char new_end</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
