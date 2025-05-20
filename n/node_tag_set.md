# Function: <code>node_tag_set</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81452b86)
Location: lib/radix-tree.c:1325
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_iter_tag_set
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void node_tag_set(struct radix_tree_root *root, struct radix_tree_node *node, unsigned int tag, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff818f1240)
Location: lib/radix-tree.c:1394
Inline: True
Direct callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_iter_tag_set
```
**Symbols:**

```
ffffffff818f1240-ffffffff818f128b: node_tag_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void node_tag_set(struct radix_tree_root *root, struct radix_tree_node *node, unsigned int tag, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81977680)
Location: lib/radix-tree.c:1392
Inline: True
Direct callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_iter_tag_set
```
**Symbols:**

```
ffffffff81977680-ffffffff819776e2: node_tag_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void node_tag_set(struct radix_tree_root *root, struct radix_tree_node *node, unsigned int tag, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff819d3e20)
Location: lib/radix-tree.c:1393
Inline: True
Direct callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_iter_tag_set
```
**Symbols:**

```
ffffffff819d3e20-ffffffff819d3e6d: node_tag_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:959
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:946
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:946
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:938
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:938
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:939
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:939
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:939
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:939
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
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
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:938
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
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
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:938
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:946
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:946
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:946
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffe0008b6cf6)
Location: lib/radix-tree.c:946
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:946
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:946
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:946
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:946
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
