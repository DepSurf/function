# Function: <code>radix_tree_maybe_preload_order</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int radix_tree_maybe_preload_order(gfp_t gfp_mask, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81435210)
Location: lib/radix-tree.c:418
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
```
**Symbols:**

```
ffffffff81435210-ffffffff81435263: radix_tree_maybe_preload_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int radix_tree_maybe_preload_order(gfp_t gfp_mask, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff814518e0)
Location: lib/radix-tree.c:472
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
```
**Symbols:**

```
ffffffff814518e0-ffffffff81451933: radix_tree_maybe_preload_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int radix_tree_maybe_preload_order(gfp_t gfp_mask, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff818f18b0)
Location: lib/radix-tree.c:558
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/swap_state.c:add_to_swap_cache
```
**Symbols:**

```
ffffffff818f18b0-ffffffff818f1903: radix_tree_maybe_preload_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int radix_tree_maybe_preload_order(gfp_t gfp_mask, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81977d60)
Location: lib/radix-tree.c:558
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/swap_state.c:add_to_swap_cache
```
**Symbols:**

```
ffffffff81977d60-ffffffff81977db4: radix_tree_maybe_preload_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int radix_tree_maybe_preload_order(gfp_t gfp_mask, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff819d44a0)
Location: lib/radix-tree.c:559
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/swap_state.c:add_to_swap_cache
```
**Symbols:**

```
ffffffff819d44a0-ffffffff819d44f4: radix_tree_maybe_preload_order (STB_GLOBAL)
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
</ul>
