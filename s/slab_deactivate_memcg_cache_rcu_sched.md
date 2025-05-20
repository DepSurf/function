# Function: <code>slab_deactivate_memcg_cache_rcu_sched</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void slab_deactivate_memcg_cache_rcu_sched(struct kmem_cache *s, void (*deact_fn)(struct kmem_cache *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811e77a0)
Location: mm/slab_common.c:678
Inline: False
Direct callers:
  - mm/slub.c:__kmemcg_cache_deactivate
```
**Symbols:**

```
ffffffff811e77a0-ffffffff811e7801: slab_deactivate_memcg_cache_rcu_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void slab_deactivate_memcg_cache_rcu_sched(struct kmem_cache *s, void (*deact_fn)(struct kmem_cache *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811fd9e0)
Location: mm/slab_common.c:687
Inline: False
Direct callers:
  - mm/slub.c:__kmemcg_cache_deactivate
```
**Symbols:**

```
ffffffff811fd9e0-ffffffff811fda43: slab_deactivate_memcg_cache_rcu_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void slab_deactivate_memcg_cache_rcu_sched(struct kmem_cache *s, void (*deact_fn)(struct kmem_cache *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8121ed10)
Location: mm/slab_common.c:713
Inline: False
Direct callers:
  - mm/slub.c:__kmemcg_cache_deactivate
```
**Symbols:**

```
ffffffff8121ed10-ffffffff8121ed80: slab_deactivate_memcg_cache_rcu_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void slab_deactivate_memcg_cache_rcu_sched(struct kmem_cache *s, void (*deact_fn)(struct kmem_cache *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81231cf0)
Location: mm/slab_common.c:740
Inline: False
Direct callers:
  - mm/slub.c:__kmemcg_cache_deactivate
```
**Symbols:**

```
ffffffff81231cf0-ffffffff81231d60: slab_deactivate_memcg_cache_rcu_sched (STB_GLOBAL)
```
</details>
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
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
