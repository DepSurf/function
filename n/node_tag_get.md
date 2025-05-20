# Function: <code>node_tag_get</code>

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
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (ffffffff818f1690)
Location: lib/radix-tree.c:1138
Inline: True
Direct callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:__radix_tree_replace
```
**Symbols:**

```
ffffffff818f1690-ffffffff818f16b3: node_tag_get.constprop.18 (STB_LOCAL)
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
In lib/radix-tree.c (ffffffff81977b40)
Location: lib/radix-tree.c:1137
Inline: True
Direct callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:__radix_tree_replace
```
**Symbols:**

```
ffffffff81977b40-ffffffff81977b62: node_tag_get.constprop.18 (STB_LOCAL)
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
In lib/radix-tree.c (ffffffff819d43f0)
Location: lib/radix-tree.c:1138
Inline: True
Direct callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:__radix_tree_replace
```
**Symbols:**

```
ffffffff819d43f0-ffffffff819d4413: node_tag_get.constprop.18 (STB_LOCAL)
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
In lib/radix-tree.c (ffffffff81a0d240)
Location: lib/radix-tree.c:856
Inline: True
Direct callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:__radix_tree_replace
  - lib/radix-tree.c:__radix_tree_replace
```
**Symbols:**

```
ffffffff81a0d240-ffffffff81a0d263: node_tag_get.constprop.17 (STB_LOCAL)
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
In lib/radix-tree.c (ffffffff81a7cac0)
Location: lib/radix-tree.c:843
Inline: True
Direct callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:__radix_tree_replace
  - lib/radix-tree.c:__radix_tree_replace
```
**Symbols:**

```
ffffffff81a7cac0-ffffffff81a7cade: node_tag_get.constprop.0 (STB_LOCAL)
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
In lib/radix-tree.c (ffffffff81ab3df0)
Location: lib/radix-tree.c:843
Inline: True
Direct callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:__radix_tree_replace
  - lib/radix-tree.c:__radix_tree_replace
```
**Symbols:**

```
ffffffff81ab3df0-ffffffff81ab3e0e: node_tag_get.constprop.0 (STB_LOCAL)
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
In lib/radix-tree.c (ffffffff815eed39)
Location: lib/radix-tree.c:835
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_replace_slot
  - lib/radix-tree.c:radix_tree_replace_slot
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
In lib/radix-tree.c (ffffffff81613489)
Location: lib/radix-tree.c:835
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_replace_slot
  - lib/radix-tree.c:radix_tree_replace_slot
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
In lib/radix-tree.c (ffffffff815f6ae4)
Location: lib/radix-tree.c:835
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_replace_slot
  - lib/radix-tree.c:radix_tree_replace_slot
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
In lib/radix-tree.c (ffffffff816641e4)
Location: lib/radix-tree.c:835
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_replace_slot
  - lib/radix-tree.c:radix_tree_replace_slot
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
In lib/radix-tree.c (ffffffff8177e481)
Location: lib/radix-tree.c:835
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_delete_item
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
In lib/radix-tree.c (ffffffff8203b081)
Location: lib/radix-tree.c:835
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_delete_item
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
In lib/radix-tree.c (ffffffff820b9561)
Location: lib/radix-tree.c:834
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_delete_item
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
In lib/radix-tree.c (ffffffff82193e71)
Location: lib/radix-tree.c:834
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_delete_item
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
In lib/radix-tree.c (ffff800010d8e8bc)
Location: lib/radix-tree.c:843
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:__radix_tree_replace
  - lib/radix-tree.c:__radix_tree_replace
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
In lib/radix-tree.c (c0e88fd4)
Location: lib/radix-tree.c:843
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:__radix_tree_replace
  - lib/radix-tree.c:__radix_tree_replace
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
In lib/radix-tree.c (c000000000ed155c)
Location: lib/radix-tree.c:843
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:__radix_tree_replace
  - lib/radix-tree.c:__radix_tree_replace
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
In lib/radix-tree.c (ffffffe0008b72c6)
Location: lib/radix-tree.c:843
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:__radix_tree_replace
  - lib/radix-tree.c:__radix_tree_replace
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
In lib/radix-tree.c (ffffffff81a52c40)
Location: lib/radix-tree.c:843
Inline: True
Direct callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:__radix_tree_replace
  - lib/radix-tree.c:__radix_tree_replace
```
**Symbols:**

```
ffffffff81a52c40-ffffffff81a52c5e: node_tag_get.constprop.0 (STB_LOCAL)
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
In lib/radix-tree.c (ffffffff81a0fd40)
Location: lib/radix-tree.c:843
Inline: True
Direct callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:__radix_tree_replace
  - lib/radix-tree.c:__radix_tree_replace
```
**Symbols:**

```
ffffffff81a0fd40-ffffffff81a0fd5e: node_tag_get.constprop.0 (STB_LOCAL)
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
In lib/radix-tree.c (ffffffff81abf030)
Location: lib/radix-tree.c:843
Inline: True
Direct callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:__radix_tree_replace
  - lib/radix-tree.c:__radix_tree_replace
```
**Symbols:**

```
ffffffff81abf030-ffffffff81abf04e: node_tag_get.constprop.0 (STB_LOCAL)
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
In lib/radix-tree.c (ffffffff81acb500)
Location: lib/radix-tree.c:843
Inline: True
Direct callers:
  - lib/radix-tree.c:radix_tree_delete_item
  - lib/radix-tree.c:__radix_tree_replace
  - lib/radix-tree.c:__radix_tree_replace
```
**Symbols:**

```
ffffffff81acb500-ffffffff81acb51e: node_tag_get.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
