# Function: <code>__radix_tree_delete_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool __radix_tree_delete_node(struct radix_tree_root *root, struct radix_tree_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff813ef140)
Location: lib/radix-tree.c:1326
Inline: False
Direct callers:
  - mm/filemap.c:__delete_from_page_cache
  - mm/workingset.c:shadow_lru_isolate
  - lib/radix-tree.c:radix_tree_delete_item
```
**Symbols:**

```
ffffffff813ef140-ffffffff813ef28a: __radix_tree_delete_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool __radix_tree_delete_node(struct radix_tree_root *root, struct radix_tree_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff814358f0)
Location: lib/radix-tree.c:1476
Inline: False
Direct callers:
  - mm/filemap.c:__delete_from_page_cache
  - mm/workingset.c:shadow_lru_isolate
  - lib/radix-tree.c:radix_tree_delete_item
```
**Symbols:**

```
ffffffff814358f0-ffffffff81435a3a: __radix_tree_delete_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __radix_tree_delete_node(struct radix_tree_root *root, struct radix_tree_node *node, radix_tree_update_node_t update_node, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81452bd0)
Location: lib/radix-tree.c:1837
Inline: False
Direct callers:
  - mm/workingset.c:shadow_lru_isolate
```
**Symbols:**

```
ffffffff81452bd0-ffffffff81452bdb: __radix_tree_delete_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __radix_tree_delete_node(struct radix_tree_root *root, struct radix_tree_node *node, radix_tree_update_node_t update_node, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff818f2aa0)
Location: lib/radix-tree.c:1981
Inline: False
Direct callers:
  - mm/workingset.c:shadow_lru_isolate
```
**Symbols:**

```
ffffffff818f2aa0-ffffffff818f2aab: __radix_tree_delete_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __radix_tree_delete_node(struct radix_tree_root *root, struct radix_tree_node *node, radix_tree_update_node_t update_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81978f40)
Location: lib/radix-tree.c:1978
Inline: False
Direct callers:
  - mm/workingset.c:shadow_lru_isolate
```
**Symbols:**

```
ffffffff81978f40-ffffffff81978f4b: __radix_tree_delete_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __radix_tree_delete_node(struct radix_tree_root *root, struct radix_tree_node *node, radix_tree_update_node_t update_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff819d55f0)
Location: lib/radix-tree.c:1977
Inline: False
Direct callers:
  - mm/workingset.c:shadow_lru_isolate
```
**Symbols:**

```
ffffffff819d55f0-ffffffff819d55fb: __radix_tree_delete_node (STB_GLOBAL)
```
</details>
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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>radix_tree_update_node_t update_node</code>
</li>
<li>
<b>Param added. </b>
<code>void *private</code>
</li>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
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
</ul>
