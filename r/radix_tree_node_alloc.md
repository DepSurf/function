# Function: <code>radix_tree_node_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct radix_tree_node *radix_tree_node_alloc(struct radix_tree_root *root);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff813eeb20)
Location: lib/radix-tree.c:181
Inline: True
Direct callers:
  - lib/radix-tree.c:__radix_tree_create
  - lib/radix-tree.c:__radix_tree_create
```
**Symbols:**

```
ffffffff813eeb20-ffffffff813eeb8c: radix_tree_node_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct radix_tree_node *radix_tree_node_alloc(struct radix_tree_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81434300)
Location: lib/radix-tree.c:265
Inline: False
Direct callers:
  - lib/radix-tree.c:__radix_tree_create
  - lib/radix-tree.c:__radix_tree_create
```
**Symbols:**

```
ffffffff81434300-ffffffff81434384: radix_tree_node_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (ffffffff81451770)
Location: lib/radix-tree.c:290
Inline: True
Direct callers:
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:__radix_tree_create
  - lib/radix-tree.c:__radix_tree_create
```
**Symbols:**

```
ffffffff81451770-ffffffff81451829: radix_tree_node_alloc.constprop.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (ffffffff818f15d0)
Location: lib/radix-tree.c:377
Inline: True
Direct callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:__radix_tree_create
  - lib/radix-tree.c:radix_tree_extend
```
**Symbols:**

```
ffffffff818f15d0-ffffffff818f168b: radix_tree_node_alloc.constprop.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (ffffffff81977a80)
Location: lib/radix-tree.c:377
Inline: True
Direct callers:
  - lib/radix-tree.c:idr_get_free_cmn
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:__radix_tree_create
  - lib/radix-tree.c:radix_tree_extend
```
**Symbols:**

```
ffffffff81977a80-ffffffff81977b3b: radix_tree_node_alloc.constprop.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (ffffffff819d4140)
Location: lib/radix-tree.c:378
Inline: True
Direct callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:__radix_tree_create
  - lib/radix-tree.c:radix_tree_extend
```
**Symbols:**

```
ffffffff819d4140-ffffffff819d41fb: radix_tree_node_alloc.constprop.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (ffffffff81a0d180)
Location: lib/radix-tree.c:255
Inline: True
Direct callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_extend
```
**Symbols:**

```
ffffffff81a0d180-ffffffff81a0d23b: radix_tree_node_alloc.constprop.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (ffffffff81a7cae0)
Location: lib/radix-tree.c:242
Inline: True
Direct callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_extend
```
**Symbols:**

```
ffffffff81a7cae0-ffffffff81a7cb9f: radix_tree_node_alloc.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (ffffffff81ab3e10)
Location: lib/radix-tree.c:242
Inline: True
Direct callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_extend
```
**Symbols:**

```
ffffffff81ab3e10-ffffffff81ab3ecf: radix_tree_node_alloc.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (ffffffff815edc20)
Location: lib/radix-tree.c:234
Inline: True
Direct callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:__radix_tree_create
  - lib/radix-tree.c:radix_tree_extend
```
**Symbols:**

```
ffffffff815edc20-ffffffff815edcdf: radix_tree_node_alloc.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (ffffffff81612350)
Location: lib/radix-tree.c:234
Inline: True
Direct callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:__radix_tree_create
  - lib/radix-tree.c:radix_tree_extend
```
**Symbols:**

```
ffffffff81612350-ffffffff8161240f: radix_tree_node_alloc.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (ffffffff815f5a30)
Location: lib/radix-tree.c:234
Inline: True
Direct callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_extend
```
**Symbols:**

```
ffffffff815f5a30-ffffffff815f5aef: radix_tree_node_alloc.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (ffffffff81662ea0)
Location: lib/radix-tree.c:234
Inline: True
Direct callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_extend
```
**Symbols:**

```
ffffffff81662ea0-ffffffff81662f5f: radix_tree_node_alloc.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (ffffffff8177d0c0)
Location: lib/radix-tree.c:234
Inline: True
Direct callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_extend
```
**Symbols:**

```
ffffffff8177d0c0-ffffffff8177d1a4: radix_tree_node_alloc.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (ffffffff82039950)
Location: lib/radix-tree.c:234
Inline: True
Direct callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_extend
```
**Symbols:**

```
ffffffff82039950-ffffffff82039a34: radix_tree_node_alloc.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (ffffffff820b7c70)
Location: lib/radix-tree.c:233
Inline: True
Direct callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_extend
```
**Symbols:**

```
ffffffff820b7c70-ffffffff820b7d54: radix_tree_node_alloc.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (ffffffff82192580)
Location: lib/radix-tree.c:233
Inline: True
Direct callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_extend
```
**Symbols:**

```
ffffffff82192580-ffffffff82192664: radix_tree_node_alloc.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (ffff800010d8e150)
Location: lib/radix-tree.c:242
Inline: True
Direct callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_extend
```
**Symbols:**

```
ffff800010d8e150-ffff800010d8e234: radix_tree_node_alloc.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (c0e88994)
Location: lib/radix-tree.c:242
Inline: True
Direct callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_extend
```
**Symbols:**

```
c0e88994-c0e88a7c: radix_tree_node_alloc.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (c000000000ed0c80)
Location: lib/radix-tree.c:242
Inline: True
Direct callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_extend
```
**Symbols:**

```
c000000000ed0c80-c000000000ed0da4: radix_tree_node_alloc.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (ffffffe0008b6dac)
Location: lib/radix-tree.c:242
Inline: True
Direct callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_extend
```
**Symbols:**

```
ffffffe0008b6dac-ffffffe0008b6e72: radix_tree_node_alloc.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (ffffffff81a52c60)
Location: lib/radix-tree.c:242
Inline: True
Direct callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_extend
```
**Symbols:**

```
ffffffff81a52c60-ffffffff81a52d1f: radix_tree_node_alloc.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (ffffffff81a0fd60)
Location: lib/radix-tree.c:242
Inline: True
Direct callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_extend
```
**Symbols:**

```
ffffffff81a0fd60-ffffffff81a0fe1f: radix_tree_node_alloc.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (ffffffff81abf050)
Location: lib/radix-tree.c:242
Inline: True
Direct callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_extend
```
**Symbols:**

```
ffffffff81abf050-ffffffff81abf10f: radix_tree_node_alloc.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (ffffffff81acb520)
Location: lib/radix-tree.c:242
Inline: True
Direct callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_extend
```
**Symbols:**

```
ffffffff81acb520-ffffffff81acb5df: radix_tree_node_alloc.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
</ul>
