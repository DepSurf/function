# Function: <code>node_tag_clear</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void node_tag_clear(struct radix_tree_root *root, struct radix_tree_node *node, unsigned int tag, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81435000)
Location: lib/radix-tree.c:790
Inline: True
Direct callers:
  - lib/radix-tree.c:radix_tree_replace_clear_tags
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_tag_clear
```
**Symbols:**

```
ffffffff81435000-ffffffff8143505a: node_tag_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void node_tag_clear(struct radix_tree_root *root, struct radix_tree_node *node, unsigned int tag, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81451400)
Location: lib/radix-tree.c:1305
Inline: True
Direct callers:
  - lib/radix-tree.c:radix_tree_clear_tags
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_tag_clear
```
**Symbols:**

```
ffffffff81451400-ffffffff8145145a: node_tag_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void node_tag_clear(struct radix_tree_root *root, struct radix_tree_node *node, unsigned int tag, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff818f1290)
Location: lib/radix-tree.c:1463
Inline: True
Direct callers:
  - lib/radix-tree.c:radix_tree_clear_tags
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_iter_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
```
**Symbols:**

```
ffffffff818f1290-ffffffff818f12ea: node_tag_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void node_tag_clear(struct radix_tree_root *root, struct radix_tree_node *node, unsigned int tag, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff819776f0)
Location: lib/radix-tree.c:1461
Inline: True
Direct callers:
  - lib/radix-tree.c:radix_tree_clear_tags
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_iter_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
```
**Symbols:**

```
ffffffff819776f0-ffffffff81977763: node_tag_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void node_tag_clear(struct radix_tree_root *root, struct radix_tree_node *node, unsigned int tag, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff819d3e70)
Location: lib/radix-tree.c:1462
Inline: True
Direct callers:
  - lib/radix-tree.c:radix_tree_clear_tags
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_iter_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
```
**Symbols:**

```
ffffffff819d3e70-ffffffff819d3eca: node_tag_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void node_tag_clear(struct xarray *root, struct xa_node *node, unsigned int tag, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a0cec0)
Location: lib/radix-tree.c:1016
Inline: True
Direct callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_iter_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
```
**Symbols:**

```
ffffffff81a0cec0-ffffffff81a0cf1a: node_tag_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void node_tag_clear(struct xarray *root, struct xa_node *node, unsigned int tag, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a7c810)
Location: lib/radix-tree.c:1003
Inline: True
Direct callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_iter_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
```
**Symbols:**

```
ffffffff81a7c810-ffffffff81a7c864: node_tag_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void node_tag_clear(struct xarray *root, struct xa_node *node, unsigned int tag, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81ab3b40)
Location: lib/radix-tree.c:1003
Inline: True
Direct callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_iter_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
```
**Symbols:**

```
ffffffff81ab3b40-ffffffff81ab3b94: node_tag_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void node_tag_clear(struct xarray *root, struct xa_node *node, unsigned int tag, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815ee190)
Location: lib/radix-tree.c:995
Inline: True
Direct callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_iter_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
```
**Symbols:**

```
ffffffff815ee190-ffffffff815ee1ec: node_tag_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void node_tag_clear(struct xarray *root, struct xa_node *node, unsigned int tag, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff816128c0)
Location: lib/radix-tree.c:995
Inline: True
Direct callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_iter_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
```
**Symbols:**

```
ffffffff816128c0-ffffffff8161291c: node_tag_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void node_tag_clear(struct xarray *root, struct xa_node *node, unsigned int tag, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815f5e50)
Location: lib/radix-tree.c:996
Inline: True
Direct callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_iter_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
```
**Symbols:**

```
ffffffff815f5e50-ffffffff815f5ea8: node_tag_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void node_tag_clear(struct xarray *root, struct xa_node *node, unsigned int tag, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (ffffffff8166336c)
Location: lib/radix-tree.c:996
Inline: True
Direct callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_iter_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
```
**Symbols:**

```
ffffffff81663320-ffffffff8166339b: node_tag_clear (STB_LOCAL)
ffffffff81cdf523-ffffffff81cdf562: node_tag_clear.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void node_tag_clear(struct xarray *root, struct xa_node *node, unsigned int tag, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:996
Inline: False
Direct callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_iter_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
```
**Symbols:**

```
ffffffff8177d390-ffffffff8177d42d: node_tag_clear (STB_LOCAL)
ffffffff81ea5ce3-ffffffff81ea5d22: node_tag_clear.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void node_tag_clear(struct xarray *root, struct xa_node *node, unsigned int tag, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (ffffffff82039c9d)
Location: lib/radix-tree.c:996
Inline: True
Direct callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_iter_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
```
**Symbols:**

```
ffffffff82039c40-ffffffff82039cdd: node_tag_clear (STB_LOCAL)
ffffffff820b7652-ffffffff820b7691: node_tag_clear.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void node_tag_clear(struct xarray *root, struct xa_node *node, unsigned int tag, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (ffffffff820b7fef)
Location: lib/radix-tree.c:995
Inline: True
Direct callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_iter_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
```
**Symbols:**

```
ffffffff820b7f60-ffffffff820b80a1: node_tag_clear (STB_LOCAL)
ffffffff82138b53-ffffffff82138b6b: node_tag_clear.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void node_tag_clear(struct xarray *root, struct xa_node *node, unsigned int tag, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (ffffffff821928ff)
Location: lib/radix-tree.c:995
Inline: True
Direct callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_iter_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
```
**Symbols:**

```
ffffffff82192870-ffffffff821929b1: node_tag_clear (STB_LOCAL)
ffffffff8221a8f8-ffffffff8221a910: node_tag_clear.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void node_tag_clear(struct xarray *root, struct xa_node *node, unsigned int tag, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffff800010d8ddf8)
Location: lib/radix-tree.c:1003
Inline: True
Direct callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_iter_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
```
**Symbols:**

```
ffff800010d8ddf8-ffff800010d8dea0: node_tag_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void node_tag_clear(struct xarray *root, struct xa_node *node, unsigned int tag, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c0e884b4)
Location: lib/radix-tree.c:1003
Inline: True
Direct callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_iter_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
```
**Symbols:**

```
c0e884b4-c0e88598: node_tag_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void node_tag_clear(struct xarray *root, struct xa_node *node, unsigned int tag, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c000000000ed0720)
Location: lib/radix-tree.c:1003
Inline: True
Direct callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_iter_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
```
**Symbols:**

```
c000000000ed0720-c000000000ed0838: node_tag_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void node_tag_clear(struct xarray *root, struct xa_node *node, unsigned int tag, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffe0008b6a5e)
Location: lib/radix-tree.c:1003
Inline: True
Direct callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_iter_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
```
**Symbols:**

```
ffffffe0008b6a5e-ffffffe0008b6b16: node_tag_clear (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void node_tag_clear(struct xarray *root, struct xa_node *node, unsigned int tag, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a52990)
Location: lib/radix-tree.c:1003
Inline: True
Direct callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_iter_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
```
**Symbols:**

```
ffffffff81a52990-ffffffff81a529e4: node_tag_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void node_tag_clear(struct xarray *root, struct xa_node *node, unsigned int tag, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a0fa90)
Location: lib/radix-tree.c:1003
Inline: True
Direct callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_iter_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
```
**Symbols:**

```
ffffffff81a0fa90-ffffffff81a0fae4: node_tag_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void node_tag_clear(struct xarray *root, struct xa_node *node, unsigned int tag, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81abed80)
Location: lib/radix-tree.c:1003
Inline: True
Direct callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_iter_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
```
**Symbols:**

```
ffffffff81abed80-ffffffff81abedd4: node_tag_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void node_tag_clear(struct xarray *root, struct xa_node *node, unsigned int tag, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81acb240)
Location: lib/radix-tree.c:1003
Inline: True
Direct callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_iter_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
```
**Symbols:**

```
ffffffff81acb240-ffffffff81acb294: node_tag_clear (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
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
