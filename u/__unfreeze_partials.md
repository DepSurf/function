# Function: <code>__unfreeze_partials</code>

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
<summary>In <code>5.15</code>: ✅</summary>

```c
void __unfreeze_partials(struct kmem_cache *s, struct page *partial_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81336d80)
Location: mm/slub.c:2447
Inline: False
Direct callers:
  - mm/slub.c:slub_cpu_dead
  - mm/slub.c:flush_cpu_slab
  - mm/slub.c:put_cpu_partial
```
**Symbols:**

```
ffffffff81336d80-ffffffff81336eea: __unfreeze_partials (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __unfreeze_partials(struct kmem_cache *s, struct slab *partial_slab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff813a8640)
Location: mm/slub.c:2493
Inline: False
Direct callers:
  - mm/slub.c:slub_cpu_dead
  - mm/slub.c:put_cpu_partial
  - mm/slub.c:unfreeze_partials
```
**Symbols:**

```
ffffffff813a8640-ffffffff813a882c: __unfreeze_partials (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __unfreeze_partials(struct kmem_cache *s, struct slab *partial_slab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81429020)
Location: mm/slub.c:2582
Inline: False
Direct callers:
  - mm/slub.c:bootstrap
  - mm/slub.c:slub_cpu_dead
  - mm/slub.c:put_cpu_partial
  - mm/slub.c:unfreeze_partials
```
**Symbols:**

```
ffffffff81429020-ffffffff8142920c: __unfreeze_partials (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __unfreeze_partials(struct kmem_cache *s, struct slab *partial_slab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8145e360)
Location: mm/slub.c:2592
Inline: False
Direct callers:
  - mm/slub.c:bootstrap
  - mm/slub.c:slub_cpu_dead
  - mm/slub.c:put_cpu_partial
  - mm/slub.c:unfreeze_partials
```
**Symbols:**

```
ffffffff8145e360-ffffffff8145e554: __unfreeze_partials (STB_LOCAL)
```
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct slab *partial_slab</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *partial_page</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
