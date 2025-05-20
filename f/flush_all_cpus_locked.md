# Function: <code>flush_all_cpus_locked</code>

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
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void flush_all_cpus_locked(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:2674
Inline: False
Direct callers:
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:validate_slab_cache
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
```
**Symbols:**

```
ffffffff813330c0-ffffffff8133327c: flush_all_cpus_locked (STB_LOCAL)
ffffffff81cc0ea6-ffffffff81cc0eba: flush_all_cpus_locked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void flush_all_cpus_locked(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:2716
Inline: False
Direct callers:
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:validate_slab_cache
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
```
**Symbols:**

```
ffffffff813a4900-ffffffff813a4ac9: flush_all_cpus_locked (STB_LOCAL)
ffffffff81e7340f-ffffffff81e73424: flush_all_cpus_locked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void flush_all_cpus_locked(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:2805
Inline: False
Direct callers:
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:validate_slab_cache
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
```
**Symbols:**

```
ffffffff814251c0-ffffffff814253a5: flush_all_cpus_locked (STB_LOCAL)
ffffffff82067338-ffffffff8206734d: flush_all_cpus_locked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void flush_all_cpus_locked(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:2815
Inline: False
Direct callers:
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:validate_slab_cache
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
```
**Symbols:**

```
ffffffff8145a570-ffffffff8145a755: flush_all_cpus_locked (STB_LOCAL)
ffffffff820e6bfb-ffffffff820e6c10: flush_all_cpus_locked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void flush_all_cpus_locked(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:3089
Inline: False
Direct callers:
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:validate_slab_cache
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
```
**Symbols:**

```
ffffffff81455640-ffffffff81455825: flush_all_cpus_locked (STB_LOCAL)
ffffffff821c1cfb-ffffffff821c1d10: flush_all_cpus_locked.cold (STB_LOCAL)
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
