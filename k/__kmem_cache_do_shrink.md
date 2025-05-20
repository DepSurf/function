# Function: <code>__kmem_cache_do_shrink</code>

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
int __kmem_cache_do_shrink(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8133a070)
Location: mm/slub.c:4567
Inline: False
Direct callers:
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmem_cache_shrink
```
**Symbols:**

```
ffffffff8133a070-ffffffff8133a2a3: __kmem_cache_do_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __kmem_cache_do_shrink(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff813abdc0)
Location: mm/slub.c:4599
Inline: False
Direct callers:
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmem_cache_shrink
```
**Symbols:**

```
ffffffff813abdc0-ffffffff813ac020: __kmem_cache_do_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __kmem_cache_do_shrink(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff814294a0)
Location: mm/slub.c:4776
Inline: False
Direct callers:
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmem_cache_shrink
```
**Symbols:**

```
ffffffff814294a0-ffffffff81429734: __kmem_cache_do_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __kmem_cache_do_shrink(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8145e7f0)
Location: mm/slub.c:4791
Inline: False
Direct callers:
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmem_cache_shrink
```
**Symbols:**

```
ffffffff8145e7f0-ffffffff8145eb20: __kmem_cache_do_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __kmem_cache_do_shrink(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8145cec0)
Location: mm/slub.c:5401
Inline: False
Direct callers:
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmem_cache_shrink
```
**Symbols:**

```
ffffffff8145cec0-ffffffff8145d1f5: __kmem_cache_do_shrink (STB_LOCAL)
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
