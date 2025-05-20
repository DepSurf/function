# Function: <code>folio_lock_anon_vma_read</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct anon_vma *folio_lock_anon_vma_read(struct folio *folio, struct rmap_walk_control *rwc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/rmap.c (0)
Location: mm/rmap.c:536
Inline: False
```
**Symbols:**

```
ffffffff81e6ea1d-ffffffff81e6ea32: folio_lock_anon_vma_read.cold (STB_LOCAL)
ffffffff8135fdf0-ffffffff8135ff19: folio_lock_anon_vma_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct anon_vma *folio_lock_anon_vma_read(struct folio *folio, struct rmap_walk_control *rwc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/rmap.c (0)
Location: mm/rmap.c:536
Inline: False
```
**Symbols:**

```
ffffffff8206496a-ffffffff8206497f: folio_lock_anon_vma_read.cold (STB_LOCAL)
ffffffff813dacd0-ffffffff813dae49: folio_lock_anon_vma_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct anon_vma *folio_lock_anon_vma_read(struct folio *folio, struct rmap_walk_control *rwc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/rmap.c (0)
Location: mm/rmap.c:538
Inline: False
Direct callers:
  - mm/memory-failure.c:collect_procs_anon
  - mm/memory-failure.c:collect_procs_anon
```
**Symbols:**

```
ffffffff820e406f-ffffffff820e4084: folio_lock_anon_vma_read.cold (STB_LOCAL)
ffffffff8140f410-ffffffff8140f589: folio_lock_anon_vma_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct anon_vma *folio_lock_anon_vma_read(struct folio *folio, struct rmap_walk_control *rwc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/rmap.c (0)
Location: mm/rmap.c:544
Inline: False
Direct callers:
  - mm/memory-failure.c:collect_procs_anon
```
**Symbols:**

```
ffffffff821c0cae-ffffffff821c0cc3: folio_lock_anon_vma_read.cold (STB_LOCAL)
ffffffff8143bdc0-ffffffff8143bf97: folio_lock_anon_vma_read (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
