# Function: <code>__shutdown_memcg_cache</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int __shutdown_memcg_cache(struct kmem_cache *s, struct list_head *release, bool *need_rcu_barrier);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811b3070)
Location: mm/slab_common.c:591
Inline: True
Direct callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_destroy_kmem_caches
```
**Symbols:**

```
ffffffff811b3070-ffffffff811b3118: __shutdown_memcg_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int __shutdown_memcg_cache(struct kmem_cache *s, struct list_head *release, bool *need_rcu_barrier);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811ccad0)
Location: mm/slab_common.c:596
Inline: True
Direct callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_destroy_kmem_caches
```
**Symbols:**

```
ffffffff811ccad0-ffffffff811ccb78: __shutdown_memcg_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int __shutdown_memcg_cache(struct kmem_cache *s, struct list_head *release, bool *need_rcu_barrier);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811dcbc0)
Location: mm/slab_common.c:625
Inline: True
Direct callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_destroy_kmem_caches
```
**Symbols:**

```
ffffffff811dcbc0-ffffffff811dcc68: __shutdown_memcg_cache (STB_LOCAL)
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
