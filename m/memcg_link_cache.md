# Function: <code>memcg_link_cache</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void memcg_link_cache(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811e7070)
Location: mm/slab_common.c:224
Inline: True
Direct callers:
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_cache
  - mm/slub.c:bootstrap
```
**Symbols:**

```
ffffffff811e7070-ffffffff811e7110: memcg_link_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void memcg_link_cache(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811fd2c0)
Location: mm/slab_common.c:233
Inline: True
Direct callers:
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_cache
  - mm/slub.c:bootstrap
```
**Symbols:**

```
ffffffff811fd2c0-ffffffff811fd360: memcg_link_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void memcg_link_cache(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8121e5c0)
Location: mm/slab_common.c:224
Inline: True
Direct callers:
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_cache
  - mm/slub.c:bootstrap
```
**Symbols:**

```
ffffffff8121e5c0-ffffffff8121e660: memcg_link_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void memcg_link_cache(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff812315a0)
Location: mm/slab_common.c:224
Inline: True
Direct callers:
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_cache
  - mm/slub.c:bootstrap
```
**Symbols:**

```
ffffffff812315a0-ffffffff81231640: memcg_link_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void memcg_link_cache(struct kmem_cache *s, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81241980)
Location: mm/slab_common.c:235
Inline: True
Direct callers:
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_cache
  - mm/slub.c:bootstrap
```
**Symbols:**

```
ffffffff81241980-ffffffff81241a4e: memcg_link_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void memcg_link_cache(struct kmem_cache *s, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8124fe20)
Location: mm/slab_common.c:238
Inline: True
Direct callers:
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_cache
  - mm/slub.c:bootstrap
```
**Symbols:**

```
ffffffff8124fe20-ffffffff8124feee: memcg_link_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void memcg_link_cache(struct kmem_cache *s, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8127e450)
Location: mm/slab_common.c:238
Inline: True
Direct callers:
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_cache
  - mm/slub.c:bootstrap
```
**Symbols:**

```
ffffffff8127e450-ffffffff8127e521: memcg_link_cache (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void memcg_link_cache(struct kmem_cache *s, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffff8000102e6d70)
Location: mm/slab_common.c:238
Inline: True
Direct callers:
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_cache
  - mm/slub.c:bootstrap
```
**Symbols:**

```
ffff8000102e6d70-ffff8000102e6e64: memcg_link_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void memcg_link_cache(struct kmem_cache *s, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (c050af70)
Location: mm/slab_common.c:238
Inline: True
Direct callers:
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_cache
  - mm/slub.c:bootstrap
```
**Symbols:**

```
c050af70-c050b054: memcg_link_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void memcg_link_cache(struct kmem_cache *s, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (c0000000003a87f0)
Location: mm/slab_common.c:238
Inline: True
Direct callers:
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_cache
  - mm/slub.c:bootstrap
```
**Symbols:**

```
c0000000003a87f0-c0000000003a8920: memcg_link_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void memcg_link_cache(struct kmem_cache *s, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffe0001fcacc)
Location: mm/slab_common.c:238
Inline: True
Direct callers:
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_cache
  - mm/slub.c:bootstrap
```
**Symbols:**

```
ffffffe0001fcacc-ffffffe0001fcb9c: memcg_link_cache (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void memcg_link_cache(struct kmem_cache *s, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81248470)
Location: mm/slab_common.c:238
Inline: True
Direct callers:
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_cache
  - mm/slub.c:bootstrap
```
**Symbols:**

```
ffffffff81248470-ffffffff8124853e: memcg_link_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void memcg_link_cache(struct kmem_cache *s, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8123b420)
Location: mm/slab_common.c:238
Inline: True
Direct callers:
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_cache
  - mm/slub.c:bootstrap
```
**Symbols:**

```
ffffffff8123b420-ffffffff8123b4ee: memcg_link_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void memcg_link_cache(struct kmem_cache *s, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81246210)
Location: mm/slab_common.c:238
Inline: True
Direct callers:
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_cache
  - mm/slub.c:bootstrap
```
**Symbols:**

```
ffffffff81246210-ffffffff812462de: memcg_link_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void memcg_link_cache(struct kmem_cache *s, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81255a00)
Location: mm/slab_common.c:238
Inline: True
Direct callers:
  - mm/slab_common.c:create_kmalloc_cache
  - mm/slab_common.c:create_cache
  - mm/slub.c:bootstrap
```
**Symbols:**

```
ffffffff81255a00-ffffffff81255ae7: memcg_link_cache (STB_GLOBAL)
```
</details>
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
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mem_cgroup *memcg</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
