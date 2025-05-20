# Function: <code>debugfs_slab_release</code>

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
void debugfs_slab_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8133b8a0)
Location: mm/slub.c:6196
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
**Symbols:**

```
ffffffff8133b8a0-ffffffff8133b8c3: debugfs_slab_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void debugfs_slab_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff813adfd0)
Location: mm/slub.c:6277
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
**Symbols:**

```
ffffffff813adfd0-ffffffff813adffd: debugfs_slab_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void debugfs_slab_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8142e3c0)
Location: mm/slub.c:6450
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
**Symbols:**

```
ffffffff8142e3c0-ffffffff8142e3ed: debugfs_slab_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void debugfs_slab_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81463b00)
Location: mm/slub.c:6464
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
**Symbols:**

```
ffffffff81463b00-ffffffff81463b23: debugfs_slab_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void debugfs_slab_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8145fd50)
Location: mm/slub.c:7075
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
**Symbols:**

```
ffffffff8145fd50-ffffffff8145fd73: debugfs_slab_release (STB_GLOBAL)
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
