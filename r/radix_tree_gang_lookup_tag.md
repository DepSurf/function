# Function: <code>radix_tree_gang_lookup_tag</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int radix_tree_gang_lookup_tag(struct radix_tree_root *root, void **results, long unsigned int first_index, unsigned int max_items, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff813ee8e0)
Location: lib/radix-tree.c:1093
Inline: False
```
**Symbols:**

```
ffffffff813ee8e0-ffffffff813ee9d4: radix_tree_gang_lookup_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int radix_tree_gang_lookup_tag(struct radix_tree_root *root, void **results, long unsigned int first_index, unsigned int max_items, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81434a20)
Location: lib/radix-tree.c:1235
Inline: False
```
**Symbols:**

```
ffffffff81434a20-ffffffff81434bc6: radix_tree_gang_lookup_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int radix_tree_gang_lookup_tag(struct radix_tree_root *root, void **results, long unsigned int first_index, unsigned int max_items, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81450f40)
Location: lib/radix-tree.c:1764
Inline: False
```
**Symbols:**

```
ffffffff81450f40-ffffffff81451096: radix_tree_gang_lookup_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int radix_tree_gang_lookup_tag(const struct radix_tree_root *root, void **results, long unsigned int first_index, unsigned int max_items, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff818f0b80)
Location: lib/radix-tree.c:1908
Inline: False
```
**Symbols:**

```
ffffffff818f0b80-ffffffff818f0cdd: radix_tree_gang_lookup_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int radix_tree_gang_lookup_tag(const struct radix_tree_root *root, void **results, long unsigned int first_index, unsigned int max_items, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81976fd0)
Location: lib/radix-tree.c:1906
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request
```
**Symbols:**

```
ffffffff81976fd0-ffffffff8197712d: radix_tree_gang_lookup_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int radix_tree_gang_lookup_tag(const struct radix_tree_root *root, void **results, long unsigned int first_index, unsigned int max_items, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff819d3770)
Location: lib/radix-tree.c:1905
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request
```
**Symbols:**

```
ffffffff819d3770-ffffffff819d38cc: radix_tree_gang_lookup_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int radix_tree_gang_lookup_tag(const struct xarray *root, void **results, long unsigned int first_index, unsigned int max_items, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a0c7c0)
Location: lib/radix-tree.c:1324
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request
```
**Symbols:**

```
ffffffff81a0c7c0-ffffffff81a0c8bb: radix_tree_gang_lookup_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int radix_tree_gang_lookup_tag(const struct xarray *root, void **results, long unsigned int first_index, unsigned int max_items, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a7c1f0)
Location: lib/radix-tree.c:1311
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request
```
**Symbols:**

```
ffffffff81a7c1f0-ffffffff81a7c2ef: radix_tree_gang_lookup_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int radix_tree_gang_lookup_tag(const struct xarray *root, void **results, long unsigned int first_index, unsigned int max_items, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81ab3520)
Location: lib/radix-tree.c:1311
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request
```
**Symbols:**

```
ffffffff81ab3520-ffffffff81ab361f: radix_tree_gang_lookup_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int radix_tree_gang_lookup_tag(const struct xarray *root, void **results, long unsigned int first_index, unsigned int max_items, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815ee720)
Location: lib/radix-tree.c:1303
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request
```
**Symbols:**

```
ffffffff815ee720-ffffffff815ee823: radix_tree_gang_lookup_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int radix_tree_gang_lookup_tag(const struct xarray *root, void **results, long unsigned int first_index, unsigned int max_items, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81612e70)
Location: lib/radix-tree.c:1303
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request
```
**Symbols:**

```
ffffffff81612e70-ffffffff81612f73: radix_tree_gang_lookup_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int radix_tree_gang_lookup_tag(const struct xarray *root, void **results, long unsigned int first_index, unsigned int max_items, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815f6350)
Location: lib/radix-tree.c:1304
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request
```
**Symbols:**

```
ffffffff815f6350-ffffffff815f645d: radix_tree_gang_lookup_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
unsigned int radix_tree_gang_lookup_tag(const struct xarray *root, void **results, long unsigned int first_index, unsigned int max_items, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:1304
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request
```
**Symbols:**

```
ffffffff81cdf721-ffffffff81cdf74d: radix_tree_gang_lookup_tag.cold (STB_LOCAL)
ffffffff81663920-ffffffff81663a3c: radix_tree_gang_lookup_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
unsigned int radix_tree_gang_lookup_tag(const struct xarray *root, void **results, long unsigned int first_index, unsigned int max_items, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:1304
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request
```
**Symbols:**

```
ffffffff81ea5ec9-ffffffff81ea5ef5: radix_tree_gang_lookup_tag.cold (STB_LOCAL)
ffffffff8177dab0-ffffffff8177dbfa: radix_tree_gang_lookup_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
unsigned int radix_tree_gang_lookup_tag(const struct xarray *root, void **results, long unsigned int first_index, unsigned int max_items, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:1304
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request
```
**Symbols:**

```
ffffffff820b783c-ffffffff820b7868: radix_tree_gang_lookup_tag.cold (STB_LOCAL)
ffffffff8203a210-ffffffff8203a35a: radix_tree_gang_lookup_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
unsigned int radix_tree_gang_lookup_tag(const struct xarray *root, void **results, long unsigned int first_index, unsigned int max_items, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:1302
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request
```
**Symbols:**

```
ffffffff82138caa-ffffffff82138cd6: radix_tree_gang_lookup_tag.cold (STB_LOCAL)
ffffffff820b8670-ffffffff820b87ba: radix_tree_gang_lookup_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
unsigned int radix_tree_gang_lookup_tag(const struct xarray *root, void **results, long unsigned int first_index, unsigned int max_items, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/radix-tree.c (0)
Location: lib/radix-tree.c:1302
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request
```
**Symbols:**

```
ffffffff8221aa4f-ffffffff8221aa7b: radix_tree_gang_lookup_tag.cold (STB_LOCAL)
ffffffff82192f80-ffffffff821930ca: radix_tree_gang_lookup_tag (STB_GLOBAL)
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
unsigned int radix_tree_gang_lookup_tag(const struct xarray *root, void **results, long unsigned int first_index, unsigned int max_items, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffff800010d8dba8)
Location: lib/radix-tree.c:1311
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request
```
**Symbols:**

```
ffff800010d8dba8-ffff800010d8dce4: radix_tree_gang_lookup_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int radix_tree_gang_lookup_tag(const struct xarray *root, void **results, long unsigned int first_index, unsigned int max_items, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c0e8826c)
Location: lib/radix-tree.c:1311
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request
```
**Symbols:**

```
c0e8826c-c0e883a4: radix_tree_gang_lookup_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int radix_tree_gang_lookup_tag(const struct xarray *root, void **results, long unsigned int first_index, unsigned int max_items, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c000000000ed03d0)
Location: lib/radix-tree.c:1311
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request
```
**Symbols:**

```
c000000000ed03d0-c000000000ed057c: radix_tree_gang_lookup_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int radix_tree_gang_lookup_tag(const struct xarray *root, void **results, long unsigned int first_index, unsigned int max_items, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffe0008b6412)
Location: lib/radix-tree.c:1311
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request
```
**Symbols:**

```
ffffffe0008b6412-ffffffe0008b6548: radix_tree_gang_lookup_tag (STB_GLOBAL)
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
unsigned int radix_tree_gang_lookup_tag(const struct xarray *root, void **results, long unsigned int first_index, unsigned int max_items, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a52370)
Location: lib/radix-tree.c:1311
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request
```
**Symbols:**

```
ffffffff81a52370-ffffffff81a5246f: radix_tree_gang_lookup_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int radix_tree_gang_lookup_tag(const struct xarray *root, void **results, long unsigned int first_index, unsigned int max_items, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a0f470)
Location: lib/radix-tree.c:1311
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request
```
**Symbols:**

```
ffffffff81a0f470-ffffffff81a0f56f: radix_tree_gang_lookup_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int radix_tree_gang_lookup_tag(const struct xarray *root, void **results, long unsigned int first_index, unsigned int max_items, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81abe760)
Location: lib/radix-tree.c:1311
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request
```
**Symbols:**

```
ffffffff81abe760-ffffffff81abe85f: radix_tree_gang_lookup_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int radix_tree_gang_lookup_tag(const struct xarray *root, void **results, long unsigned int first_index, unsigned int max_items, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81acac00)
Location: lib/radix-tree.c:1311
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request
```
**Symbols:**

```
ffffffff81acac00-ffffffff81acacff: radix_tree_gang_lookup_tag (STB_GLOBAL)
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
