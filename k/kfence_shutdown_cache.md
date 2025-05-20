# Function: <code>kfence_shutdown_cache</code>

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
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (0)
Location: include/linux/kfence.h:209
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void kfence_shutdown_cache(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/core.c (ffffffff8133c590)
Location: mm/kfence/core.c:682
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
**Symbols:**

```
ffffffff8133c590-ffffffff8133c6de: kfence_shutdown_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void kfence_shutdown_cache(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/core.c (ffffffff813af7f0)
Location: mm/kfence/core.c:921
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
**Symbols:**

```
ffffffff813af7f0-ffffffff813af94a: kfence_shutdown_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kfence_shutdown_cache(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/core.c (ffffffff8142fda0)
Location: mm/kfence/core.c:900
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
**Symbols:**

```
ffffffff8142fda0-ffffffff8142fefa: kfence_shutdown_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kfence_shutdown_cache(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/core.c (ffffffff81465730)
Location: mm/kfence/core.c:938
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
**Symbols:**

```
ffffffff81465730-ffffffff8146588a: kfence_shutdown_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kfence_shutdown_cache(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/core.c (ffffffff81494a20)
Location: mm/kfence/core.c:980
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
**Symbols:**

```
ffffffff81494a20-ffffffff81494b6f: kfence_shutdown_cache (STB_GLOBAL)
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
