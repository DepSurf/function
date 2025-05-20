# Function: <code>delete_node</code>

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
void delete_node(struct radix_tree_root *root, struct radix_tree_node *node, radix_tree_update_node_t update_node, void *private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81451200)
Location: lib/radix-tree.c:648
Inline: False
Direct callers:
  - lib/radix-tree.c:__radix_tree_delete_node
  - lib/radix-tree.c:__radix_tree_replace
```
**Symbols:**

```
ffffffff81451200-ffffffff814513fb: delete_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool delete_node(struct radix_tree_root *root, struct radix_tree_node *node, radix_tree_update_node_t update_node, void *private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff818f0fb0)
Location: lib/radix-tree.c:753
Inline: False
Direct callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:__radix_tree_delete_node
  - lib/radix-tree.c:__radix_tree_replace
```
**Symbols:**

```
ffffffff818f0fb0-ffffffff818f11a6: delete_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool delete_node(struct radix_tree_root *root, struct radix_tree_node *node, radix_tree_update_node_t update_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81977400)
Location: lib/radix-tree.c:752
Inline: False
Direct callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:__radix_tree_delete_node
  - lib/radix-tree.c:__radix_tree_replace
```
**Symbols:**

```
ffffffff81977400-ffffffff819775eb: delete_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool delete_node(struct radix_tree_root *root, struct radix_tree_node *node, radix_tree_update_node_t update_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff819d3ba0)
Location: lib/radix-tree.c:753
Inline: False
Direct callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:__radix_tree_delete_node
  - lib/radix-tree.c:__radix_tree_replace
```
**Symbols:**

```
ffffffff819d3ba0-ffffffff819d3d86: delete_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool delete_node(struct xarray *root, struct xa_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a0cbe0)
Location: lib/radix-tree.c:565
Inline: False
Direct callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:__radix_tree_replace
```
**Symbols:**

```
ffffffff81a0cbe0-ffffffff81a0cdd4: delete_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool delete_node(struct xarray *root, struct xa_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a7c560)
Location: lib/radix-tree.c:552
Inline: False
Direct callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:__radix_tree_replace
```
**Symbols:**

```
ffffffff81a7c560-ffffffff81a7c74d: delete_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool delete_node(struct xarray *root, struct xa_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81ab3890)
Location: lib/radix-tree.c:552
Inline: False
Direct callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:__radix_tree_replace
```
**Symbols:**

```
ffffffff81ab3890-ffffffff81ab3a7d: delete_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool delete_node(struct xarray *root, struct xa_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815edce0)
Location: lib/radix-tree.c:544
Inline: False
Direct callers:
  - lib/radix-tree.c:__radix_tree_delete
```
**Symbols:**

```
ffffffff815edce0-ffffffff815edecf: delete_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool delete_node(struct xarray *root, struct xa_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81612410)
Location: lib/radix-tree.c:544
Inline: False
Direct callers:
  - lib/radix-tree.c:__radix_tree_delete
```
**Symbols:**

```
ffffffff81612410-ffffffff816125ff: delete_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool delete_node(struct xarray *root, struct xa_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815f5af0)
Location: lib/radix-tree.c:544
Inline: False
Direct callers:
  - lib/radix-tree.c:__radix_tree_delete
```
**Symbols:**

```
ffffffff815f5af0-ffffffff815f5cdf: delete_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool delete_node(struct xarray *root, struct xa_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81662f60)
Location: lib/radix-tree.c:544
Inline: False
Direct callers:
  - lib/radix-tree.c:__radix_tree_delete
```
**Symbols:**

```
ffffffff81662f60-ffffffff81663172: delete_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool delete_node(struct xarray *root, struct xa_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff8177cce0)
Location: lib/radix-tree.c:544
Inline: False
Direct callers:
  - lib/radix-tree.c:__radix_tree_delete
```
**Symbols:**

```
ffffffff8177cce0-ffffffff8177cf13: delete_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool delete_node(struct xarray *root, struct xa_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff8203a4b0)
Location: lib/radix-tree.c:544
Inline: False
Direct callers:
  - lib/radix-tree.c:__radix_tree_delete
```
**Symbols:**

```
ffffffff8203a4b0-ffffffff8203a6ed: delete_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool delete_node(struct xarray *root, struct xa_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff820b8910)
Location: lib/radix-tree.c:543
Inline: False
Direct callers:
  - lib/radix-tree.c:__radix_tree_delete
```
**Symbols:**

```
ffffffff820b8910-ffffffff820b8b51: delete_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool delete_node(struct xarray *root, struct xa_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff82193220)
Location: lib/radix-tree.c:543
Inline: False
Direct callers:
  - lib/radix-tree.c:__radix_tree_delete
```
**Symbols:**

```
ffffffff82193220-ffffffff82193461: delete_node (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
bool delete_node(struct xarray *root, struct xa_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffff800010d8d548)
Location: lib/radix-tree.c:552
Inline: False
Direct callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:__radix_tree_replace
```
**Symbols:**

```
ffff800010d8d548-ffff800010d8d738: delete_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool delete_node(struct xarray *root, struct xa_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c0e87a48)
Location: lib/radix-tree.c:552
Inline: False
Direct callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:__radix_tree_replace
```
**Symbols:**

```
c0e87a48-c0e87d14: delete_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool delete_node(struct xarray *root, struct xa_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c000000000ecfa50)
Location: lib/radix-tree.c:552
Inline: False
Direct callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:__radix_tree_replace
```
**Symbols:**

```
c000000000ecfa50-c000000000ecfd48: delete_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool delete_node(struct xarray *root, struct xa_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffe0008b67f4)
Location: lib/radix-tree.c:552
Inline: False
Direct callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:__radix_tree_replace
```
**Symbols:**

```
ffffffe0008b67f4-ffffffe0008b6998: delete_node (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
bool delete_node(struct xarray *root, struct xa_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a526e0)
Location: lib/radix-tree.c:552
Inline: False
Direct callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:__radix_tree_replace
```
**Symbols:**

```
ffffffff81a526e0-ffffffff81a528cd: delete_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool delete_node(struct xarray *root, struct xa_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a0f7e0)
Location: lib/radix-tree.c:552
Inline: False
Direct callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:__radix_tree_replace
```
**Symbols:**

```
ffffffff81a0f7e0-ffffffff81a0f9cd: delete_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool delete_node(struct xarray *root, struct xa_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81abead0)
Location: lib/radix-tree.c:552
Inline: False
Direct callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:__radix_tree_replace
```
**Symbols:**

```
ffffffff81abead0-ffffffff81abecbd: delete_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool delete_node(struct xarray *root, struct xa_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81acaf90)
Location: lib/radix-tree.c:552
Inline: False
Direct callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:__radix_tree_replace
```
**Symbols:**

```
ffffffff81acaf90-ffffffff81acb17d: delete_node (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>void *private</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>radix_tree_update_node_t update_node</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct radix_tree_root *root</code> ➡️ <code>struct xarray *root</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct radix_tree_node *node</code> ➡️ <code>struct xa_node *node</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
