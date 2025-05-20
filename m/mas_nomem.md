# Function: <code>mas_nomem</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
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
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool mas_nomem(struct ma_state *mas, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff8203693f)
Location: lib/maple_tree.c:6115
Inline: True
Inline callers:
  - lib/maple_tree.c:mtree_insert_range
  - lib/maple_tree.c:mtree_store_range
Direct callers:
  - lib/maple_tree.c:mtree_alloc_rrange
  - lib/maple_tree.c:mtree_alloc_range
  - lib/maple_tree.c:mas_erase
  - lib/maple_tree.c:mas_store_gfp
```
**Symbols:**

```
ffffffff82037b10-ffffffff82037b99: mas_nomem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool mas_nomem(struct ma_state *mas, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff820b58bf)
Location: lib/maple_tree.c:6165
Inline: True
Inline callers:
  - lib/maple_tree.c:mtree_insert_range
  - lib/maple_tree.c:mtree_store_range
Direct callers:
  - lib/maple_tree.c:mtree_alloc_rrange
  - lib/maple_tree.c:mtree_alloc_range
  - lib/maple_tree.c:mas_erase
  - lib/maple_tree.c:mas_store_gfp
```
**Symbols:**

```
ffffffff820b6b80-ffffffff820b6c04: mas_nomem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool mas_nomem(struct ma_state *mas, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff8218fa46)
Location: lib/maple_tree.c:6232
Inline: True
Inline callers:
  - lib/maple_tree.c:mtree_insert_range
Direct callers:
  - lib/maple_tree.c:mtree_alloc_rrange
  - lib/maple_tree.c:mtree_alloc_range
  - lib/maple_tree.c:mtree_store_range
  - lib/maple_tree.c:mas_erase
  - lib/maple_tree.c:mas_store_gfp
```
**Symbols:**

```
ffffffff82190030-ffffffff821900b3: mas_nomem (STB_GLOBAL)
```
</details>
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
