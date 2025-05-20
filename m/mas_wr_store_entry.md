# Function: <code>mas_wr_store_entry</code>

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
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/maple_tree.c (ffffffff82037000)
Location: lib/maple_tree.c:4379
Inline: True
Direct callers:
  - lib/maple_tree.c:mtree_alloc_rrange
  - lib/maple_tree.c:mtree_alloc_range
  - lib/maple_tree.c:mtree_store_range
  - lib/maple_tree.c:mas_erase
  - lib/maple_tree.c:mas_store_prealloc
  - lib/maple_tree.c:mas_store_gfp
  - lib/maple_tree.c:mas_store
```
**Symbols:**

```
ffffffff82037000-ffffffff82037528: mas_wr_store_entry.isra.0 (STB_LOCAL)
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
In lib/maple_tree.c (ffffffff820b6180)
Location: lib/maple_tree.c:4371
Inline: True
Direct callers:
  - lib/maple_tree.c:mtree_store_range
  - lib/maple_tree.c:mas_erase
  - lib/maple_tree.c:mas_store_prealloc
  - lib/maple_tree.c:mas_store_gfp
  - lib/maple_tree.c:mas_store
```
**Symbols:**

```
ffffffff820b6180-ffffffff820b66a2: mas_wr_store_entry.isra.0 (STB_LOCAL)
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
In lib/maple_tree.c (ffffffff82190bfa)
Location: lib/maple_tree.c:4208
Inline: True
Inline callers:
  - lib/maple_tree.c:mtree_store_range
  - lib/maple_tree.c:mas_erase
Direct callers:
  - lib/maple_tree.c:mas_store_prealloc
  - lib/maple_tree.c:mas_store_gfp
  - lib/maple_tree.c:mas_store
```
**Symbols:**

```
ffffffff8218fb90-ffffffff8218fe41: mas_wr_store_entry.isra.0 (STB_LOCAL)
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
