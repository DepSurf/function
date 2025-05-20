# Function: <code>__radix_tree_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __radix_tree_create(struct radix_tree_root *root, long unsigned int index, struct radix_tree_node **nodep, void ***slotp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff813eec30)
Location: lib/radix-tree.c:390
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - lib/radix-tree.c:radix_tree_insert
```
**Symbols:**

```
ffffffff813eec30-ffffffff813eee2c: __radix_tree_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __radix_tree_create(struct radix_tree_root *root, long unsigned int index, unsigned int order, struct radix_tree_node **nodep, void ***slotp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81435270)
Location: lib/radix-tree.c:553
Inline: False
Direct callers:
  - mm/filemap.c:page_cache_tree_insert
  - lib/radix-tree.c:__radix_tree_insert
```
**Symbols:**

```
ffffffff81435270-ffffffff814355af: __radix_tree_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __radix_tree_create(struct radix_tree_root *root, long unsigned int index, unsigned int order, struct radix_tree_node **nodep, void ***slotp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81451940)
Location: lib/radix-tree.c:694
Inline: False
Direct callers:
  - mm/filemap.c:page_cache_tree_insert
  - lib/radix-tree.c:radix_tree_join
  - lib/radix-tree.c:__radix_tree_insert
```
**Symbols:**

```
ffffffff81451940-ffffffff81451bf7: __radix_tree_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __radix_tree_create(struct radix_tree_root *root, long unsigned int index, unsigned int order, struct radix_tree_node **nodep, void ***slotp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff818f1910)
Location: lib/radix-tree.c:811
Inline: False
Direct callers:
  - mm/filemap.c:page_cache_tree_insert
  - lib/radix-tree.c:radix_tree_join
  - lib/radix-tree.c:__radix_tree_insert
```
**Symbols:**

```
ffffffff818f1910-ffffffff818f1add: __radix_tree_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __radix_tree_create(struct radix_tree_root *root, long unsigned int index, unsigned int order, struct radix_tree_node **nodep, void ***slotp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81977dc0)
Location: lib/radix-tree.c:810
Inline: False
Direct callers:
  - mm/filemap.c:page_cache_tree_insert
  - lib/radix-tree.c:radix_tree_join
  - lib/radix-tree.c:__radix_tree_insert
```
**Symbols:**

```
ffffffff81977dc0-ffffffff81977f8d: __radix_tree_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __radix_tree_create(struct radix_tree_root *root, long unsigned int index, unsigned int order, struct radix_tree_node **nodep, void ***slotp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff819d4500)
Location: lib/radix-tree.c:811
Inline: False
Direct callers:
  - mm/filemap.c:page_cache_tree_insert
  - lib/radix-tree.c:radix_tree_join
  - lib/radix-tree.c:__radix_tree_insert
```
**Symbols:**

```
ffffffff819d4500-ffffffff819d46ce: __radix_tree_create (STB_GLOBAL)
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
In lib/radix-tree.c (ffffffff81a0d41e)
Location: lib/radix-tree.c:620
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_insert
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
In lib/radix-tree.c (ffffffff81a7cd39)
Location: lib/radix-tree.c:607
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_insert
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
In lib/radix-tree.c (ffffffff81ab4069)
Location: lib/radix-tree.c:607
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __radix_tree_create(struct xarray *root, long unsigned int index, struct xa_node **nodep, void ***slotp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815ee040)
Location: lib/radix-tree.c:599
Inline: False
Direct callers:
  - lib/radix-tree.c:radix_tree_insert
```
**Symbols:**

```
ffffffff815ee040-ffffffff815ee18b: __radix_tree_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __radix_tree_create(struct xarray *root, long unsigned int index, struct xa_node **nodep, void ***slotp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81612770)
Location: lib/radix-tree.c:599
Inline: False
Direct callers:
  - lib/radix-tree.c:radix_tree_insert
```
**Symbols:**

```
ffffffff81612770-ffffffff816128bb: __radix_tree_create (STB_LOCAL)
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
In lib/radix-tree.c (ffffffff815f6623)
Location: lib/radix-tree.c:599
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_insert
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
In lib/radix-tree.c (ffffffff81663e83)
Location: lib/radix-tree.c:599
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_insert
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
In lib/radix-tree.c (ffffffff8177e0b2)
Location: lib/radix-tree.c:599
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_insert
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
In lib/radix-tree.c (ffffffff8203ac62)
Location: lib/radix-tree.c:599
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_insert
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
In lib/radix-tree.c (ffffffff820b9152)
Location: lib/radix-tree.c:598
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_insert
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
In lib/radix-tree.c (ffffffff82193a62)
Location: lib/radix-tree.c:598
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_insert
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
In lib/radix-tree.c (ffff800010d8e428)
Location: lib/radix-tree.c:607
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_insert
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
In lib/radix-tree.c (c0e88c28)
Location: lib/radix-tree.c:607
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_insert
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
In lib/radix-tree.c (c000000000ed107c)
Location: lib/radix-tree.c:607
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_insert
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
In lib/radix-tree.c (ffffffe0008b6ffc)
Location: lib/radix-tree.c:607
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_insert
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
In lib/radix-tree.c (ffffffff81a52eb9)
Location: lib/radix-tree.c:607
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_insert
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
In lib/radix-tree.c (ffffffff81a0ffb9)
Location: lib/radix-tree.c:607
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_insert
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
In lib/radix-tree.c (ffffffff81abf2a9)
Location: lib/radix-tree.c:607
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_insert
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
In lib/radix-tree.c (ffffffff81acb779)
Location: lib/radix-tree.c:607
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_insert
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int order</code>
</li>
<li>
<b>Param reordered. </b>
<code>root, index, nodep, slotp</code> ➡️ <code>root, index, order, nodep, slotp</code>
</li>
</ul>
</details>
</li>
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
