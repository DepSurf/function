# Function: <code>__radix_tree_delete</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool __radix_tree_delete(struct radix_tree_root *root, struct radix_tree_node *node, void **slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff818f13d0)
Location: lib/radix-tree.c:1989
Inline: False
Direct callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_iter_delete
```
**Symbols:**

```
ffffffff818f13d0-ffffffff818f1463: __radix_tree_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool __radix_tree_delete(struct radix_tree_root *root, struct radix_tree_node *node, void **slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81977850)
Location: lib/radix-tree.c:1985
Inline: False
Direct callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_iter_delete
```
**Symbols:**

```
ffffffff81977850-ffffffff819778e1: __radix_tree_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool __radix_tree_delete(struct radix_tree_root *root, struct radix_tree_node *node, void **slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff819d3fa0)
Location: lib/radix-tree.c:1984
Inline: False
Direct callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_iter_delete
```
**Symbols:**

```
ffffffff819d3fa0-ffffffff819d402f: __radix_tree_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool __radix_tree_delete(struct xarray *root, struct xa_node *node, void **slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a0d080)
Location: lib/radix-tree.c:1386
Inline: False
Direct callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_iter_delete
```
**Symbols:**

```
ffffffff81a0d080-ffffffff81a0d15d: __radix_tree_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool __radix_tree_delete(struct xarray *root, struct xa_node *node, void **slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a7c9b0)
Location: lib/radix-tree.c:1373
Inline: False
Direct callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_iter_delete
```
**Symbols:**

```
ffffffff81a7c9b0-ffffffff81a7ca9c: __radix_tree_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool __radix_tree_delete(struct xarray *root, struct xa_node *node, void **slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81ab3ce0)
Location: lib/radix-tree.c:1373
Inline: False
Direct callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_iter_delete
```
**Symbols:**

```
ffffffff81ab3ce0-ffffffff81ab3dcc: __radix_tree_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool __radix_tree_delete(struct xarray *root, struct xa_node *node, void **slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815ee1f0)
Location: lib/radix-tree.c:1365
Inline: False
Direct callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_iter_delete
```
**Symbols:**

```
ffffffff815ee1f0-ffffffff815ee2d7: __radix_tree_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool __radix_tree_delete(struct xarray *root, struct xa_node *node, void **slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81612920)
Location: lib/radix-tree.c:1365
Inline: False
Direct callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_iter_delete
```
**Symbols:**

```
ffffffff81612920-ffffffff81612a07: __radix_tree_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool __radix_tree_delete(struct xarray *root, struct xa_node *node, void **slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815f5eb0)
Location: lib/radix-tree.c:1366
Inline: False
Direct callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_iter_delete
```
**Symbols:**

```
ffffffff815f5eb0-ffffffff815f5f8c: __radix_tree_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool __radix_tree_delete(struct xarray *root, struct xa_node *node, void **slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff816633a0)
Location: lib/radix-tree.c:1366
Inline: False
Direct callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_iter_delete
```
**Symbols:**

```
ffffffff816633a0-ffffffff8166349c: __radix_tree_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool __radix_tree_delete(struct xarray *root, struct xa_node *node, void **slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff8177d430)
Location: lib/radix-tree.c:1366
Inline: False
Direct callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_iter_delete
```
**Symbols:**

```
ffffffff8177d430-ffffffff8177d572: __radix_tree_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool __radix_tree_delete(struct xarray *root, struct xa_node *node, void **slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff8203a700)
Location: lib/radix-tree.c:1366
Inline: False
Direct callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_iter_delete
```
**Symbols:**

```
ffffffff8203a700-ffffffff8203a842: __radix_tree_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool __radix_tree_delete(struct xarray *root, struct xa_node *node, void **slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff820b8b70)
Location: lib/radix-tree.c:1364
Inline: False
Direct callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_iter_delete
```
**Symbols:**

```
ffffffff820b8b70-ffffffff820b8cb2: __radix_tree_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool __radix_tree_delete(struct xarray *root, struct xa_node *node, void **slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff82193480)
Location: lib/radix-tree.c:1364
Inline: False
Direct callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_iter_delete
```
**Symbols:**

```
ffffffff82193480-ffffffff821935c2: __radix_tree_delete (STB_LOCAL)
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
bool __radix_tree_delete(struct xarray *root, struct xa_node *node, void **slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffff800010d8dfe0)
Location: lib/radix-tree.c:1373
Inline: False
Direct callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_iter_delete
```
**Symbols:**

```
ffff800010d8dfe0-ffff800010d8e114: __radix_tree_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool __radix_tree_delete(struct xarray *root, struct xa_node *node, void **slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c0e886d8)
Location: lib/radix-tree.c:1373
Inline: False
Direct callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_iter_delete
```
**Symbols:**

```
c0e886d8-c0e88830: __radix_tree_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool __radix_tree_delete(struct xarray *root, struct xa_node *node, void **slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c000000000ed0a20)
Location: lib/radix-tree.c:1373
Inline: False
Direct callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_iter_delete
```
**Symbols:**

```
c000000000ed0a20-c000000000ed0c2c: __radix_tree_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool __radix_tree_delete(struct xarray *root, struct xa_node *node, void **slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffe0008b6c52)
Location: lib/radix-tree.c:1373
Inline: False
Direct callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_iter_delete
```
**Symbols:**

```
ffffffe0008b6c52-ffffffe0008b6d86: __radix_tree_delete (STB_LOCAL)
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
bool __radix_tree_delete(struct xarray *root, struct xa_node *node, void **slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a52b30)
Location: lib/radix-tree.c:1373
Inline: False
Direct callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_iter_delete
```
**Symbols:**

```
ffffffff81a52b30-ffffffff81a52c1c: __radix_tree_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool __radix_tree_delete(struct xarray *root, struct xa_node *node, void **slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a0fc30)
Location: lib/radix-tree.c:1373
Inline: False
Direct callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_iter_delete
```
**Symbols:**

```
ffffffff81a0fc30-ffffffff81a0fd1c: __radix_tree_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool __radix_tree_delete(struct xarray *root, struct xa_node *node, void **slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81abef20)
Location: lib/radix-tree.c:1373
Inline: False
Direct callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_iter_delete
```
**Symbols:**

```
ffffffff81abef20-ffffffff81abf00c: __radix_tree_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool __radix_tree_delete(struct xarray *root, struct xa_node *node, void **slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81acb3f0)
Location: lib/radix-tree.c:1373
Inline: False
Direct callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_iter_delete
```
**Symbols:**

```
ffffffff81acb3f0-ffffffff81acb4dc: __radix_tree_delete (STB_LOCAL)
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
