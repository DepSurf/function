# Function: <code>radix_tree_gang_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int radix_tree_gang_lookup(struct radix_tree_root *root, void **results, long unsigned int first_index, unsigned int max_items);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff813ee720)
Location: lib/radix-tree.c:1011
Inline: False
Direct callers:
  - drivers/block/brd.c:brd_free_pages
```
**Symbols:**

```
ffffffff813ee720-ffffffff813ee7f8: radix_tree_gang_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int radix_tree_gang_lookup(struct radix_tree_root *root, void **results, long unsigned int first_index, unsigned int max_items);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff814347b0)
Location: lib/radix-tree.c:1153
Inline: False
Direct callers:
  - drivers/block/brd.c:brd_free_pages
```
**Symbols:**

```
ffffffff814347b0-ffffffff814348fb: radix_tree_gang_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int radix_tree_gang_lookup(struct radix_tree_root *root, void **results, long unsigned int first_index, unsigned int max_items);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81450d30)
Location: lib/radix-tree.c:1682
Inline: False
```
**Symbols:**

```
ffffffff81450d30-ffffffff81450e36: radix_tree_gang_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int radix_tree_gang_lookup(const struct radix_tree_root *root, void **results, long unsigned int first_index, unsigned int max_items);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff818f0970)
Location: lib/radix-tree.c:1826
Inline: False
```
**Symbols:**

```
ffffffff818f0970-ffffffff818f0a7f: radix_tree_gang_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int radix_tree_gang_lookup(const struct radix_tree_root *root, void **results, long unsigned int first_index, unsigned int max_items);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81976dc0)
Location: lib/radix-tree.c:1824
Inline: False
```
**Symbols:**

```
ffffffff81976dc0-ffffffff81976ecf: radix_tree_gang_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int radix_tree_gang_lookup(const struct radix_tree_root *root, void **results, long unsigned int first_index, unsigned int max_items);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff819d3560)
Location: lib/radix-tree.c:1823
Inline: False
```
**Symbols:**

```
ffffffff819d3560-ffffffff819d3668: radix_tree_gang_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int radix_tree_gang_lookup(const struct xarray *root, void **results, long unsigned int first_index, unsigned int max_items);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a0c6e0)
Location: lib/radix-tree.c:1284
Inline: False
```
**Symbols:**

```
ffffffff81a0c6e0-ffffffff81a0c7b3: radix_tree_gang_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int radix_tree_gang_lookup(const struct xarray *root, void **results, long unsigned int first_index, unsigned int max_items);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a7c110)
Location: lib/radix-tree.c:1271
Inline: False
```
**Symbols:**

```
ffffffff81a7c110-ffffffff81a7c1e3: radix_tree_gang_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int radix_tree_gang_lookup(const struct xarray *root, void **results, long unsigned int first_index, unsigned int max_items);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81ab3440)
Location: lib/radix-tree.c:1271
Inline: False
```
**Symbols:**

```
ffffffff81ab3440-ffffffff81ab3513: radix_tree_gang_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int radix_tree_gang_lookup(const struct xarray *root, void **results, long unsigned int first_index, unsigned int max_items);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815ee640)
Location: lib/radix-tree.c:1263
Inline: False
```
**Symbols:**

```
ffffffff815ee640-ffffffff815ee713: radix_tree_gang_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int radix_tree_gang_lookup(const struct xarray *root, void **results, long unsigned int first_index, unsigned int max_items);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81612d90)
Location: lib/radix-tree.c:1263
Inline: False
```
**Symbols:**

```
ffffffff81612d90-ffffffff81612e63: radix_tree_gang_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int radix_tree_gang_lookup(const struct xarray *root, void **results, long unsigned int first_index, unsigned int max_items);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815f6270)
Location: lib/radix-tree.c:1264
Inline: False
```
**Symbols:**

```
ffffffff815f6270-ffffffff815f6343: radix_tree_gang_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int radix_tree_gang_lookup(const struct xarray *root, void **results, long unsigned int first_index, unsigned int max_items);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81663840)
Location: lib/radix-tree.c:1264
Inline: False
```
**Symbols:**

```
ffffffff81663840-ffffffff81663913: radix_tree_gang_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int radix_tree_gang_lookup(const struct xarray *root, void **results, long unsigned int first_index, unsigned int max_items);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff8177d990)
Location: lib/radix-tree.c:1264
Inline: False
```
**Symbols:**

```
ffffffff8177d990-ffffffff8177daae: radix_tree_gang_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int radix_tree_gang_lookup(const struct xarray *root, void **results, long unsigned int first_index, unsigned int max_items);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff8203a0e0)
Location: lib/radix-tree.c:1264
Inline: False
```
**Symbols:**

```
ffffffff8203a0e0-ffffffff8203a1fe: radix_tree_gang_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int radix_tree_gang_lookup(const struct xarray *root, void **results, long unsigned int first_index, unsigned int max_items);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff820b8540)
Location: lib/radix-tree.c:1262
Inline: False
```
**Symbols:**

```
ffffffff820b8540-ffffffff820b865e: radix_tree_gang_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int radix_tree_gang_lookup(const struct xarray *root, void **results, long unsigned int first_index, unsigned int max_items);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff82192e50)
Location: lib/radix-tree.c:1262
Inline: False
```
**Symbols:**

```
ffffffff82192e50-ffffffff82192f6e: radix_tree_gang_lookup (STB_GLOBAL)
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
unsigned int radix_tree_gang_lookup(const struct xarray *root, void **results, long unsigned int first_index, unsigned int max_items);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffff800010d8da98)
Location: lib/radix-tree.c:1271
Inline: False
```
**Symbols:**

```
ffff800010d8da98-ffff800010d8dba8: radix_tree_gang_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int radix_tree_gang_lookup(const struct xarray *root, void **results, long unsigned int first_index, unsigned int max_items);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c0e8816c)
Location: lib/radix-tree.c:1271
Inline: False
```
**Symbols:**

```
c0e8816c-c0e8826c: radix_tree_gang_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int radix_tree_gang_lookup(const struct xarray *root, void **results, long unsigned int first_index, unsigned int max_items);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c000000000ed0240)
Location: lib/radix-tree.c:1271
Inline: False
```
**Symbols:**

```
c000000000ed0240-c000000000ed03cc: radix_tree_gang_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int radix_tree_gang_lookup(const struct xarray *root, void **results, long unsigned int first_index, unsigned int max_items);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffe0008b6362)
Location: lib/radix-tree.c:1271
Inline: False
```
**Symbols:**

```
ffffffe0008b6362-ffffffe0008b6412: radix_tree_gang_lookup (STB_GLOBAL)
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
unsigned int radix_tree_gang_lookup(const struct xarray *root, void **results, long unsigned int first_index, unsigned int max_items);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a52290)
Location: lib/radix-tree.c:1271
Inline: False
```
**Symbols:**

```
ffffffff81a52290-ffffffff81a52363: radix_tree_gang_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int radix_tree_gang_lookup(const struct xarray *root, void **results, long unsigned int first_index, unsigned int max_items);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a0f390)
Location: lib/radix-tree.c:1271
Inline: False
```
**Symbols:**

```
ffffffff81a0f390-ffffffff81a0f463: radix_tree_gang_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int radix_tree_gang_lookup(const struct xarray *root, void **results, long unsigned int first_index, unsigned int max_items);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81abe680)
Location: lib/radix-tree.c:1271
Inline: False
```
**Symbols:**

```
ffffffff81abe680-ffffffff81abe753: radix_tree_gang_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int radix_tree_gang_lookup(const struct xarray *root, void **results, long unsigned int first_index, unsigned int max_items);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81acab20)
Location: lib/radix-tree.c:1271
Inline: False
```
**Symbols:**

```
ffffffff81acab20-ffffffff81acabf3: radix_tree_gang_lookup (STB_GLOBAL)
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
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct radix_tree_root *root</code> ➡️ <code>const struct radix_tree_root *root</code>
</li>
</ul>
</details>
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
<code>const struct radix_tree_root *root</code> ➡️ <code>const struct xarray *root</code>
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
