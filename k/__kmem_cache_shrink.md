# Function: <code>__kmem_cache_shrink</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __kmem_cache_shrink(struct kmem_cache *s, bool deactivate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff811ee160)
Location: mm/slub.c:3647
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slub.c:slab_memory_callback
```
**Symbols:**

```
ffffffff811ee160-ffffffff811ee3d9: __kmem_cache_shrink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __kmem_cache_shrink(struct kmem_cache *s, bool deactivate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8120d760)
Location: mm/slub.c:3871
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slub.c:slab_memory_callback
```
**Symbols:**

```
ffffffff8120d760-ffffffff8120d9dc: __kmem_cache_shrink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __kmem_cache_shrink(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8121f7c0)
Location: mm/slub.c:3893
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slub.c:slab_memory_callback
```
**Symbols:**

```
ffffffff8121f7c0-ffffffff8121fa1a: __kmem_cache_shrink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __kmem_cache_shrink(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8122aff0)
Location: mm/slub.c:3898
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slub.c:slab_memory_callback
```
**Symbols:**

```
ffffffff8122aff0-ffffffff8122b2b9: __kmem_cache_shrink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __kmem_cache_shrink(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812466f0)
Location: mm/slub.c:3914
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slub.c:slab_memory_callback
```
**Symbols:**

```
ffffffff812466f0-ffffffff812469b9: __kmem_cache_shrink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __kmem_cache_shrink(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81269ad0)
Location: mm/slub.c:3923
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slub.c:slab_memory_callback
```
**Symbols:**

```
ffffffff81269ad0-ffffffff81269d5f: __kmem_cache_shrink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __kmem_cache_shrink(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8127e390)
Location: mm/slub.c:3975
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slub.c:slab_memory_callback
```
**Symbols:**

```
ffffffff8127e390-ffffffff8127e61f: __kmem_cache_shrink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __kmem_cache_shrink(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8129a1c0)
Location: mm/slub.c:3972
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
```
**Symbols:**

```
ffffffff8129a1c0-ffffffff8129a407: __kmem_cache_shrink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __kmem_cache_shrink(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812aa080)
Location: mm/slub.c:3990
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
```
**Symbols:**

```
ffffffff812aa080-ffffffff812aa2c7: __kmem_cache_shrink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __kmem_cache_shrink(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812deda0)
Location: mm/slub.c:4067
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
```
**Symbols:**

```
ffffffff812deda0-ffffffff812defe4: __kmem_cache_shrink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __kmem_cache_shrink(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812eab70)
Location: mm/slub.c:4154
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slub.c:slab_memory_callback
```
**Symbols:**

```
ffffffff812eab70-ffffffff812eadb4: __kmem_cache_shrink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __kmem_cache_shrink(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812f2620)
Location: mm/slub.c:4227
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slub.c:slab_memory_callback
```
**Symbols:**

```
ffffffff812f2620-ffffffff812f2864: __kmem_cache_shrink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __kmem_cache_shrink(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8133b750)
Location: mm/slub.c:4628
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink
```
**Symbols:**

```
ffffffff8133b750-ffffffff8133b77e: __kmem_cache_shrink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __kmem_cache_shrink(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff813ade20)
Location: mm/slub.c:4660
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink
```
**Symbols:**

```
ffffffff813ade20-ffffffff813ade53: __kmem_cache_shrink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __kmem_cache_shrink(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8142e1c0)
Location: mm/slub.c:4838
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink
```
**Symbols:**

```
ffffffff8142e1c0-ffffffff8142e1f3: __kmem_cache_shrink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __kmem_cache_shrink(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81463900)
Location: mm/slub.c:4853
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink
```
**Symbols:**

```
ffffffff81463900-ffffffff81463933: __kmem_cache_shrink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __kmem_cache_shrink(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8145fb50)
Location: mm/slub.c:5464
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink
```
**Symbols:**

```
ffffffff8145fb50-ffffffff8145fb83: __kmem_cache_shrink (STB_GLOBAL)
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
int __kmem_cache_shrink(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff80001034bdb8)
Location: mm/slub.c:3990
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
```
**Symbols:**

```
ffff80001034bdb8-ffff80001034c090: __kmem_cache_shrink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __kmem_cache_shrink(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c054fc6c)
Location: mm/slub.c:3990
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
```
**Symbols:**

```
c054fc6c-c054fe74: __kmem_cache_shrink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __kmem_cache_shrink(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c00000000042b610)
Location: mm/slub.c:3990
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
```
**Symbols:**

```
c00000000042b610-c00000000042b934: __kmem_cache_shrink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __kmem_cache_shrink(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffe00023d228)
Location: mm/slub.c:3990
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
```
**Symbols:**

```
ffffffe00023d228-ffffffe00023d416: __kmem_cache_shrink (STB_GLOBAL)
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
int __kmem_cache_shrink(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a2660)
Location: mm/slub.c:3990
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
```
**Symbols:**

```
ffffffff812a2660-ffffffff812a28a7: __kmem_cache_shrink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __kmem_cache_shrink(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81294130)
Location: mm/slub.c:3990
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
```
**Symbols:**

```
ffffffff81294130-ffffffff81294377: __kmem_cache_shrink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __kmem_cache_shrink(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a0470)
Location: mm/slub.c:3990
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
```
**Symbols:**

```
ffffffff812a0470-ffffffff812a06b7: __kmem_cache_shrink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __kmem_cache_shrink(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812b05b0)
Location: mm/slub.c:3990
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
```
**Symbols:**

```
ffffffff812b05b0-ffffffff812b07f7: __kmem_cache_shrink (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool deactivate</code>
</li>
</ul>
</details>
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
