# Function: <code>mtree_alloc_range</code>

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
<summary>In <code>6.2</code>: ✅</summary>

```c
int mtree_alloc_range(struct maple_tree *mt, long unsigned int *startp, void *entry, long unsigned int size, long unsigned int min, long unsigned int max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff82038170)
Location: lib/maple_tree.c:6291
Inline: False
```
**Symbols:**

```
ffffffff82038170-ffffffff82038b9b: mtree_alloc_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mtree_alloc_range(struct maple_tree *mt, long unsigned int *startp, void *entry, long unsigned int size, long unsigned int min, long unsigned int max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff820b6fb0)
Location: lib/maple_tree.c:6341
Inline: False
```
**Symbols:**

```
ffffffff820b6fb0-ffffffff820b70e9: mtree_alloc_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mtree_alloc_range(struct maple_tree *mt, long unsigned int *startp, void *entry, long unsigned int size, long unsigned int min, long unsigned int max, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff82191120)
Location: lib/maple_tree.c:6408
Inline: False
```
**Symbols:**

```
ffffffff82191120-ffffffff82191276: mtree_alloc_range (STB_GLOBAL)
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
