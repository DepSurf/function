# Function: <code>__kmem_cache_shutdown</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __kmem_cache_shutdown(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff811edeb0)
Location: mm/slub.c:3482
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_destroy
```
**Symbols:**

```
ffffffff811edeb0-ffffffff811ee160: __kmem_cache_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __kmem_cache_shutdown(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8120d370)
Location: mm/slub.c:3655
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_destroy
```
**Symbols:**

```
ffffffff8120d370-ffffffff8120d6bf: __kmem_cache_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __kmem_cache_shutdown(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8121f3d0)
Location: mm/slub.c:3677
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_destroy
```
**Symbols:**

```
ffffffff8121f3d0-ffffffff8121f71b: __kmem_cache_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __kmem_cache_shutdown(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8122ab90)
Location: mm/slub.c:3681
Inline: False
Direct callers:
  - mm/slab_common.c:shutdown_cache
```
**Symbols:**

```
ffffffff8122ab90-ffffffff8122af42: __kmem_cache_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __kmem_cache_shutdown(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81246290)
Location: mm/slub.c:3697
Inline: False
Direct callers:
  - mm/slab_common.c:shutdown_cache
```
**Symbols:**

```
ffffffff81246290-ffffffff81246642: __kmem_cache_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int __kmem_cache_shutdown(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:3688
Inline: False
Direct callers:
  - mm/slab_common.c:shutdown_cache
```
**Symbols:**

```
ffffffff8126b216-ffffffff8126b34f: __kmem_cache_shutdown.cold.99 (STB_LOCAL)
ffffffff81269760-ffffffff812699bb: __kmem_cache_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int __kmem_cache_shutdown(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:3739
Inline: False
Direct callers:
  - mm/slab_common.c:shutdown_cache
```
**Symbols:**

```
ffffffff8127faaa-ffffffff8127fbe0: __kmem_cache_shutdown.cold.101 (STB_LOCAL)
ffffffff8127e030-ffffffff8127e278: __kmem_cache_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __kmem_cache_shutdown(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:3746
Inline: False
```
**Symbols:**

```
ffffffff8129b9f6-ffffffff8129bb19: __kmem_cache_shutdown.cold (STB_LOCAL)
ffffffff81299e60-ffffffff8129a09b: __kmem_cache_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int __kmem_cache_shutdown(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:3756
Inline: False
Direct callers:
  - mm/slab_common.c:shutdown_cache
```
**Symbols:**

```
ffffffff812ab86f-ffffffff812ab992: __kmem_cache_shutdown.cold (STB_LOCAL)
ffffffff812a9d20-ffffffff812a9f5b: __kmem_cache_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __kmem_cache_shutdown(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812debc0)
Location: mm/slub.c:3833
Inline: False
Direct callers:
  - mm/slab_common.c:shutdown_cache
```
**Symbols:**

```
ffffffff812debc0-ffffffff812dec82: __kmem_cache_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __kmem_cache_shutdown(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812ea9c0)
Location: mm/slub.c:3921
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_destroy
```
**Symbols:**

```
ffffffff812ea9c0-ffffffff812eaa52: __kmem_cache_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __kmem_cache_shutdown(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:3948
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_destroy
```
**Symbols:**

```
ffffffff81bdba1a-ffffffff81bdbb49: __kmem_cache_shutdown.cold (STB_LOCAL)
ffffffff812f2260-ffffffff812f241b: __kmem_cache_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __kmem_cache_shutdown(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:4286
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_destroy
```
**Symbols:**

```
ffffffff81cc1c13-ffffffff81cc1dc2: __kmem_cache_shutdown.cold (STB_LOCAL)
ffffffff8133b1a0-ffffffff8133b33e: __kmem_cache_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __kmem_cache_shutdown(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff813ad9e0)
Location: mm/slub.c:4323
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_destroy
```
**Symbols:**

```
ffffffff813ad9e0-ffffffff813ada6c: __kmem_cache_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __kmem_cache_shutdown(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8142dd50)
Location: mm/slub.c:4609
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_destroy
```
**Symbols:**

```
ffffffff8142dd50-ffffffff8142dddc: __kmem_cache_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __kmem_cache_shutdown(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81463470)
Location: mm/slub.c:4624
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_destroy
```
**Symbols:**

```
ffffffff81463470-ffffffff81463509: __kmem_cache_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __kmem_cache_shutdown(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8145f6c0)
Location: mm/slub.c:5228
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_destroy
```
**Symbols:**

```
ffffffff8145f6c0-ffffffff8145f759: __kmem_cache_shutdown (STB_GLOBAL)
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
int __kmem_cache_shutdown(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff80001034b8c8)
Location: mm/slub.c:3756
Inline: False
Direct callers:
  - mm/slab_common.c:shutdown_cache
```
**Symbols:**

```
ffff80001034b8c8-ffff80001034bc48: __kmem_cache_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __kmem_cache_shutdown(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c054f7b4)
Location: mm/slub.c:3756
Inline: False
Direct callers:
  - mm/slab_common.c:shutdown_cache
```
**Symbols:**

```
c054f7b4-c054fb10: __kmem_cache_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __kmem_cache_shutdown(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c00000000042afa0)
Location: mm/slub.c:3756
Inline: False
Direct callers:
  - mm/slab_common.c:shutdown_cache
```
**Symbols:**

```
c00000000042afa0-c00000000042b460: __kmem_cache_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __kmem_cache_shutdown(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffe00023cdc4)
Location: mm/slub.c:3756
Inline: False
Direct callers:
  - mm/slab_common.c:shutdown_cache
```
**Symbols:**

```
ffffffe00023cdc4-ffffffe00023d0e6: __kmem_cache_shutdown (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int __kmem_cache_shutdown(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:3756
Inline: False
Direct callers:
  - mm/slab_common.c:shutdown_cache
```
**Symbols:**

```
ffffffff812a3e4f-ffffffff812a3f72: __kmem_cache_shutdown.cold (STB_LOCAL)
ffffffff812a2300-ffffffff812a253b: __kmem_cache_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int __kmem_cache_shutdown(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:3756
Inline: False
Direct callers:
  - mm/slab_common.c:shutdown_cache
```
**Symbols:**

```
ffffffff8129591f-ffffffff81295a42: __kmem_cache_shutdown.cold (STB_LOCAL)
ffffffff81293de0-ffffffff81294010: __kmem_cache_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int __kmem_cache_shutdown(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:3756
Inline: False
Direct callers:
  - mm/slab_common.c:shutdown_cache
```
**Symbols:**

```
ffffffff812a1c5f-ffffffff812a1d82: __kmem_cache_shutdown.cold (STB_LOCAL)
ffffffff812a0110-ffffffff812a034b: __kmem_cache_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int __kmem_cache_shutdown(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:3756
Inline: False
Direct callers:
  - mm/slab_common.c:shutdown_cache
```
**Symbols:**

```
ffffffff812b1e1a-ffffffff812b1f4b: __kmem_cache_shutdown.cold (STB_LOCAL)
ffffffff812b0250-ffffffff812b0482: __kmem_cache_shutdown (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
