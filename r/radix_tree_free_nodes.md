# Function: <code>radix_tree_free_nodes</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
void radix_tree_free_nodes(struct radix_tree_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81450750)
Location: lib/radix-tree.c:754
Inline: False
Direct callers:
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:radix_tree_join
  - lib/radix-tree.c:__radix_tree_insert
```
**Symbols:**

```
ffffffff81450750-ffffffff81450838: radix_tree_free_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void radix_tree_free_nodes(struct radix_tree_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff818f0ed0)
Location: lib/radix-tree.c:871
Inline: False
Direct callers:
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:radix_tree_join
  - lib/radix-tree.c:__radix_tree_insert
```
**Symbols:**

```
ffffffff818f0ed0-ffffffff818f0f76: radix_tree_free_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void radix_tree_free_nodes(struct radix_tree_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81977320)
Location: lib/radix-tree.c:870
Inline: False
Direct callers:
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:radix_tree_join
  - lib/radix-tree.c:__radix_tree_insert
```
**Symbols:**

```
ffffffff81977320-ffffffff819773c6: radix_tree_free_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void radix_tree_free_nodes(struct radix_tree_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff819d3ab0)
Location: lib/radix-tree.c:871
Inline: False
Direct callers:
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:radix_tree_join
  - lib/radix-tree.c:__radix_tree_insert
```
**Symbols:**

```
ffffffff819d3ab0-ffffffff819d3b5e: radix_tree_free_nodes (STB_LOCAL)
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
In lib/radix-tree.c (ffffffff81a0ce25)
Location: lib/radix-tree.c:678
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
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
In lib/radix-tree.c (ffffffff81a7c78d)
Location: lib/radix-tree.c:665
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
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
In lib/radix-tree.c (ffffffff81ab3abd)
Location: lib/radix-tree.c:665
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void radix_tree_free_nodes(struct xa_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815edb30)
Location: lib/radix-tree.c:657
Inline: False
Direct callers:
  - lib/radix-tree.c:idr_destroy
```
**Symbols:**

```
ffffffff815edb30-ffffffff815edbc0: radix_tree_free_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void radix_tree_free_nodes(struct xa_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81612260)
Location: lib/radix-tree.c:657
Inline: False
Direct callers:
  - lib/radix-tree.c:idr_destroy
```
**Symbols:**

```
ffffffff81612260-ffffffff816122f0: radix_tree_free_nodes (STB_LOCAL)
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
In lib/radix-tree.c (ffffffff815f598b)
Location: lib/radix-tree.c:657
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
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
In lib/radix-tree.c (ffffffff81662deb)
Location: lib/radix-tree.c:657
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
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
In lib/radix-tree.c (ffffffff8177cf67)
Location: lib/radix-tree.c:657
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
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
In lib/radix-tree.c (ffffffff82039817)
Location: lib/radix-tree.c:657
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
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
In lib/radix-tree.c (ffffffff820b7b37)
Location: lib/radix-tree.c:656
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
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
In lib/radix-tree.c (ffffffff82192447)
Location: lib/radix-tree.c:656
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
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
In lib/radix-tree.c (ffff800010d8d774)
Location: lib/radix-tree.c:665
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
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
In lib/radix-tree.c (c0e87d54)
Location: lib/radix-tree.c:665
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
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
In lib/radix-tree.c (c000000000ecfda0)
Location: lib/radix-tree.c:665
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
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
In lib/radix-tree.c (ffffffe0008b69ee)
Location: lib/radix-tree.c:665
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
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
In lib/radix-tree.c (ffffffff81a5290d)
Location: lib/radix-tree.c:665
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
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
In lib/radix-tree.c (ffffffff81a0fa0d)
Location: lib/radix-tree.c:665
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
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
In lib/radix-tree.c (ffffffff81abecfd)
Location: lib/radix-tree.c:665
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
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
In lib/radix-tree.c (ffffffff81acb1bd)
Location: lib/radix-tree.c:665
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
