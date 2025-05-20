# Function: <code>lru_cache_disable</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void lru_cache_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8126f9f0)
Location: mm/swap.c:869
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/memory_hotplug.c:offline_pages
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_migrate_pages
  - mm/migrate.c:do_pages_move
```
**Symbols:**

```
ffffffff8126f9f0-ffffffff8126fa0c: lru_cache_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void lru_cache_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff812accd0)
Location: mm/swap.c:860
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/memory_hotplug.c:offline_pages
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_migrate_pages
  - mm/migrate.c:do_pages_move
```
**Symbols:**

```
ffffffff812accd0-ffffffff812accec: lru_cache_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void lru_cache_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81306dc0)
Location: mm/swap.c:868
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_contig_migrate_range
  - mm/memory_hotplug.c:offline_pages
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_migrate_pages
  - mm/migrate.c:do_pages_move
```
**Symbols:**

```
ffffffff81306dc0-ffffffff81306de7: lru_cache_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void lru_cache_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff813711b0)
Location: mm/swap.c:958
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_contig_migrate_range
  - mm/memory_hotplug.c:offline_pages
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_migrate_pages
  - mm/migrate.c:do_pages_move
```
**Symbols:**

```
ffffffff813711b0-ffffffff813711d7: lru_cache_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void lru_cache_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff813a3340)
Location: mm/swap.c:924
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_contig_migrate_range
  - mm/memory_hotplug.c:offline_pages
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_migrate_pages
  - mm/migrate.c:do_pages_move
```
**Symbols:**

```
ffffffff813a3340-ffffffff813a3367: lru_cache_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void lru_cache_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff813ccfb0)
Location: mm/swap.c:924
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_contig_migrate_range
  - mm/memory_hotplug.c:offline_pages
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_migrate_pages
  - mm/migrate.c:do_pages_move
```
**Symbols:**

```
ffffffff813ccfb0-ffffffff813ccfd7: lru_cache_disable (STB_GLOBAL)
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
