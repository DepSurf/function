# Function: <code>free_large_kmalloc</code>

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
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff813a7ee2)
Location: mm/slub.c:3565
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:build_detached_freelist
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void free_large_kmalloc(struct folio *folio, void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: mm/slab_common.c:932
Inline: False
Direct callers:
  - mm/slab_common.c:kfree
  - mm/slub.c:build_detached_freelist
```
**Symbols:**

```
ffffffff8206344f-ffffffff8206347e: free_large_kmalloc.cold (STB_LOCAL)
ffffffff813a21a0-ffffffff813a2249: free_large_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void free_large_kmalloc(struct folio *folio, void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: mm/slab_common.c:949
Inline: False
Direct callers:
  - mm/slab_common.c:kfree
  - mm/slub.c:build_detached_freelist
```
**Symbols:**

```
ffffffff820e2b7a-ffffffff820e2bab: free_large_kmalloc.cold (STB_LOCAL)
ffffffff813d5690-ffffffff813d5733: free_large_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void free_large_kmalloc(struct folio *folio, void *object);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:4367
Inline: False
Direct callers:
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kfree
```
**Symbols:**

```
ffffffff81454c80-ffffffff81454d3a: free_large_kmalloc (STB_LOCAL)
ffffffff821c1cae-ffffffff821c1cdb: free_large_kmalloc.cold (STB_LOCAL)
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
