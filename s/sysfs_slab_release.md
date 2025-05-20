# Function: <code>sysfs_slab_release</code>

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
void sysfs_slab_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8122bff0)
Location: mm/slub.c:5732
Inline: False
Direct callers:
  - mm/slab_common.c:shutdown_cache
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
**Symbols:**

```
ffffffff8122bff0-ffffffff8122c00f: sysfs_slab_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sysfs_slab_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81247750)
Location: mm/slub.c:5750
Inline: False
Direct callers:
  - mm/slab_common.c:shutdown_cache
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
**Symbols:**

```
ffffffff81247750-ffffffff8124776f: sysfs_slab_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sysfs_slab_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8126a6b0)
Location: mm/slub.c:5760
Inline: False
Direct callers:
  - mm/slab_common.c:shutdown_cache
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
**Symbols:**

```
ffffffff8126a6b0-ffffffff8126a6ce: sysfs_slab_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sysfs_slab_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8127ef40)
Location: mm/slub.c:5811
Inline: False
Direct callers:
  - mm/slab_common.c:shutdown_cache
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
**Symbols:**

```
ffffffff8127ef40-ffffffff8127ef5e: sysfs_slab_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sysfs_slab_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8129ade0)
Location: mm/slub.c:5802
Inline: False
Direct callers:
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
**Symbols:**

```
ffffffff8129ade0-ffffffff8129adfe: sysfs_slab_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sysfs_slab_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812aaca0)
Location: mm/slub.c:5829
Inline: False
Direct callers:
  - mm/slab_common.c:shutdown_cache
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
**Symbols:**

```
ffffffff812aaca0-ffffffff812aacbe: sysfs_slab_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sysfs_slab_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812df440)
Location: mm/slub.c:5876
Inline: False
Direct callers:
  - mm/slab_common.c:shutdown_cache
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
**Symbols:**

```
ffffffff812df440-ffffffff812df45e: sysfs_slab_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sysfs_slab_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812eb0b0)
Location: mm/slub.c:5668
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
**Symbols:**

```
ffffffff812eb0b0-ffffffff812eb0ce: sysfs_slab_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sysfs_slab_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812f2b80)
Location: mm/slub.c:5733
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
**Symbols:**

```
ffffffff812f2b80-ffffffff812f2b9e: sysfs_slab_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sysfs_slab_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8133b880)
Location: mm/slub.c:5954
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
**Symbols:**

```
ffffffff8133b880-ffffffff8133b89e: sysfs_slab_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sysfs_slab_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff813adfa0)
Location: mm/slub.c:6005
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
**Symbols:**

```
ffffffff813adfa0-ffffffff813adfca: sysfs_slab_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sysfs_slab_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8142e380)
Location: mm/slub.c:6174
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
**Symbols:**

```
ffffffff8142e380-ffffffff8142e3aa: sysfs_slab_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sysfs_slab_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81463ac0)
Location: mm/slub.c:6188
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
**Symbols:**

```
ffffffff81463ac0-ffffffff81463aea: sysfs_slab_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sysfs_slab_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8145fd10)
Location: mm/slub.c:6799
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
**Symbols:**

```
ffffffff8145fd10-ffffffff8145fd3a: sysfs_slab_release (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void sysfs_slab_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff80001034cbb0)
Location: mm/slub.c:5829
Inline: False
Direct callers:
  - mm/slab_common.c:shutdown_cache
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
**Symbols:**

```
ffff80001034cbb0-ffff80001034cbf8: sysfs_slab_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sysfs_slab_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c0550518)
Location: mm/slub.c:5829
Inline: False
Direct callers:
  - mm/slab_common.c:shutdown_cache
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
**Symbols:**

```
c0550518-c055054c: sysfs_slab_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sysfs_slab_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c00000000042c9c0)
Location: mm/slub.c:5829
Inline: False
Direct callers:
  - mm/slab_common.c:shutdown_cache
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
**Symbols:**

```
c00000000042c9c0-c00000000042ca0c: sysfs_slab_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sysfs_slab_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffe00023d98e)
Location: mm/slub.c:5829
Inline: False
Direct callers:
  - mm/slab_common.c:shutdown_cache
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
**Symbols:**

```
ffffffe00023d98e-ffffffe00023d9d2: sysfs_slab_release (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void sysfs_slab_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a3280)
Location: mm/slub.c:5829
Inline: False
Direct callers:
  - mm/slab_common.c:shutdown_cache
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
**Symbols:**

```
ffffffff812a3280-ffffffff812a329e: sysfs_slab_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sysfs_slab_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81294d50)
Location: mm/slub.c:5829
Inline: False
Direct callers:
  - mm/slab_common.c:shutdown_cache
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
**Symbols:**

```
ffffffff81294d50-ffffffff81294d6e: sysfs_slab_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sysfs_slab_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a1090)
Location: mm/slub.c:5829
Inline: False
Direct callers:
  - mm/slab_common.c:shutdown_cache
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
**Symbols:**

```
ffffffff812a1090-ffffffff812a10ae: sysfs_slab_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sysfs_slab_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812b1240)
Location: mm/slub.c:5829
Inline: False
Direct callers:
  - mm/slab_common.c:shutdown_cache
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
**Symbols:**

```
ffffffff812b1240-ffffffff812b125e: sysfs_slab_release (STB_GLOBAL)
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
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
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
