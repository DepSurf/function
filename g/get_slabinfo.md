# Function: <code>get_slabinfo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void get_slabinfo(struct kmem_cache *s, struct slabinfo *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff811eeff0)
Location: mm/slub.c:5526
Inline: False
Direct callers:
  - mm/slab_common.c:memcg_accumulate_slabinfo
  - mm/slab_common.c:cache_show
```
**Symbols:**

```
ffffffff811eeff0-ffffffff811ef0a4: get_slabinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void get_slabinfo(struct kmem_cache *s, struct slabinfo *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8120e2a0)
Location: mm/slub.c:5753
Inline: False
Direct callers:
  - mm/slab_common.c:cache_show
  - mm/slab_common.c:memcg_accumulate_slabinfo
```
**Symbols:**

```
ffffffff8120e2a0-ffffffff8120e354: get_slabinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void get_slabinfo(struct kmem_cache *s, struct slabinfo *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812202e0)
Location: mm/slub.c:5722
Inline: False
Direct callers:
  - mm/slab_common.c:cache_show
  - mm/slab_common.c:memcg_accumulate_slabinfo
```
**Symbols:**

```
ffffffff812202e0-ffffffff81220394: get_slabinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void get_slabinfo(struct kmem_cache *s, struct slabinfo *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8122c010)
Location: mm/slub.c:5819
Inline: False
Direct callers:
  - mm/slab_common.c:cache_show
  - mm/slab_common.c:memcg_accumulate_slabinfo
```
**Symbols:**

```
ffffffff8122c010-ffffffff8122c0ca: get_slabinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void get_slabinfo(struct kmem_cache *s, struct slabinfo *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81247770)
Location: mm/slub.c:5837
Inline: False
Direct callers:
  - mm/slab_common.c:dump_unreclaimable_slab
  - mm/slab_common.c:cache_show
  - mm/slab_common.c:memcg_accumulate_slabinfo
```
**Symbols:**

```
ffffffff81247770-ffffffff8124782a: get_slabinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void get_slabinfo(struct kmem_cache *s, struct slabinfo *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8126a6d0)
Location: mm/slub.c:5847
Inline: False
Direct callers:
  - mm/slab_common.c:dump_unreclaimable_slab
  - mm/slab_common.c:cache_show
  - mm/slab_common.c:memcg_accumulate_slabinfo
```
**Symbols:**

```
ffffffff8126a6d0-ffffffff8126a77c: get_slabinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void get_slabinfo(struct kmem_cache *s, struct slabinfo *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8127ef60)
Location: mm/slub.c:5898
Inline: False
Direct callers:
  - mm/slab_common.c:dump_unreclaimable_slab
  - mm/slab_common.c:cache_show
  - mm/slab_common.c:memcg_accumulate_slabinfo
```
**Symbols:**

```
ffffffff8127ef60-ffffffff8127f00c: get_slabinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void get_slabinfo(struct kmem_cache *s, struct slabinfo *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8129ae00)
Location: mm/slub.c:5889
Inline: False
Direct callers:
  - mm/slab_common.c:memcg_slabinfo_show
  - mm/slab_common.c:memcg_slabinfo_show
  - mm/slab_common.c:dump_unreclaimable_slab
  - mm/slab_common.c:cache_show
  - mm/slab_common.c:memcg_accumulate_slabinfo
```
**Symbols:**

```
ffffffff8129ae00-ffffffff8129aeae: get_slabinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void get_slabinfo(struct kmem_cache *s, struct slabinfo *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812aacc0)
Location: mm/slub.c:5916
Inline: False
Direct callers:
  - mm/slab_common.c:memcg_slabinfo_show
  - mm/slab_common.c:memcg_slabinfo_show
  - mm/slab_common.c:dump_unreclaimable_slab
  - mm/slab_common.c:cache_show
  - mm/slab_common.c:memcg_accumulate_slabinfo
```
**Symbols:**

```
ffffffff812aacc0-ffffffff812aad6e: get_slabinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void get_slabinfo(struct kmem_cache *s, struct slabinfo *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812df460)
Location: mm/slub.c:5963
Inline: False
Direct callers:
  - mm/slab_common.c:memcg_slabinfo_show
  - mm/slab_common.c:memcg_slabinfo_show
  - mm/slab_common.c:dump_unreclaimable_slab
  - mm/slab_common.c:cache_show
  - mm/slab_common.c:memcg_accumulate_slabinfo
```
**Symbols:**

```
ffffffff812df460-ffffffff812df553: get_slabinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void get_slabinfo(struct kmem_cache *s, struct slabinfo *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812eb0d0)
Location: mm/slub.c:5755
Inline: False
Direct callers:
  - mm/slab_common.c:dump_unreclaimable_slab
  - mm/slab_common.c:cache_show
```
**Symbols:**

```
ffffffff812eb0d0-ffffffff812eb1c3: get_slabinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void get_slabinfo(struct kmem_cache *s, struct slabinfo *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812f2ba0)
Location: mm/slub.c:5820
Inline: False
Direct callers:
  - mm/slab_common.c:dump_unreclaimable_slab
  - mm/slab_common.c:slab_show
```
**Symbols:**

```
ffffffff812f2ba0-ffffffff812f2c93: get_slabinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void get_slabinfo(struct kmem_cache *s, struct slabinfo *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8133b8d0)
Location: mm/slub.c:6220
Inline: False
Direct callers:
  - mm/slab_common.c:dump_unreclaimable_slab
  - mm/slab_common.c:slab_show
```
**Symbols:**

```
ffffffff8133b8d0-ffffffff8133b9c3: get_slabinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void get_slabinfo(struct kmem_cache *s, struct slabinfo *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff813ae000)
Location: mm/slub.c:6301
Inline: False
Direct callers:
  - mm/slab_common.c:dump_unreclaimable_slab
  - mm/slab_common.c:slab_show
```
**Symbols:**

```
ffffffff813ae000-ffffffff813ae107: get_slabinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void get_slabinfo(struct kmem_cache *s, struct slabinfo *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8142e400)
Location: mm/slub.c:6474
Inline: False
Direct callers:
  - mm/slab_common.c:dump_unreclaimable_slab
  - mm/slab_common.c:slab_show
```
**Symbols:**

```
ffffffff8142e400-ffffffff8142e503: get_slabinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void get_slabinfo(struct kmem_cache *s, struct slabinfo *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81463b40)
Location: mm/slub.c:6488
Inline: False
Direct callers:
  - mm/slab_common.c:dump_unreclaimable_slab
  - mm/slab_common.c:slab_show
```
**Symbols:**

```
ffffffff81463b40-ffffffff81463c6f: get_slabinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void get_slabinfo(struct kmem_cache *s, struct slabinfo *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8145fd90)
Location: mm/slub.c:7099
Inline: False
Direct callers:
  - mm/slab_common.c:dump_unreclaimable_slab
  - mm/slab_common.c:slab_show
```
**Symbols:**

```
ffffffff8145fd90-ffffffff8145febf: get_slabinfo (STB_GLOBAL)
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
void get_slabinfo(struct kmem_cache *s, struct slabinfo *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff80001034cbf8)
Location: mm/slub.c:5916
Inline: False
Direct callers:
  - mm/slab_common.c:memcg_slabinfo_show
  - mm/slab_common.c:memcg_slabinfo_show
  - mm/slab_common.c:dump_unreclaimable_slab
  - mm/slab_common.c:cache_show
  - mm/slab_common.c:memcg_accumulate_slabinfo
```
**Symbols:**

```
ffff80001034cbf8-ffff80001034ccc8: get_slabinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void get_slabinfo(struct kmem_cache *s, struct slabinfo *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c055054c)
Location: mm/slub.c:5916
Inline: False
Direct callers:
  - mm/slab_common.c:memcg_slabinfo_show
  - mm/slab_common.c:memcg_slabinfo_show
  - mm/slab_common.c:dump_unreclaimable_slab
  - mm/slab_common.c:cache_show
  - mm/slab_common.c:cache_show
```
**Symbols:**

```
c055054c-c05505b4: get_slabinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void get_slabinfo(struct kmem_cache *s, struct slabinfo *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c00000000042ca10)
Location: mm/slub.c:5916
Inline: False
Direct callers:
  - mm/slab_common.c:memcg_slabinfo_show
  - mm/slab_common.c:memcg_slabinfo_show
  - mm/slab_common.c:dump_unreclaimable_slab
  - mm/slab_common.c:cache_show
  - mm/slab_common.c:memcg_accumulate_slabinfo
```
**Symbols:**

```
c00000000042ca10-c00000000042cb6c: get_slabinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void get_slabinfo(struct kmem_cache *s, struct slabinfo *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffe00023d9d2)
Location: mm/slub.c:5916
Inline: False
Direct callers:
  - mm/slab_common.c:memcg_slabinfo_show
  - mm/slab_common.c:memcg_slabinfo_show
  - mm/slab_common.c:dump_unreclaimable_slab
  - mm/slab_common.c:cache_show
  - mm/slab_common.c:memcg_accumulate_slabinfo
```
**Symbols:**

```
ffffffe00023d9d2-ffffffe00023da48: get_slabinfo (STB_GLOBAL)
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
void get_slabinfo(struct kmem_cache *s, struct slabinfo *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a32a0)
Location: mm/slub.c:5916
Inline: False
Direct callers:
  - mm/slab_common.c:memcg_slabinfo_show
  - mm/slab_common.c:memcg_slabinfo_show
  - mm/slab_common.c:dump_unreclaimable_slab
  - mm/slab_common.c:cache_show
  - mm/slab_common.c:memcg_accumulate_slabinfo
```
**Symbols:**

```
ffffffff812a32a0-ffffffff812a334e: get_slabinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void get_slabinfo(struct kmem_cache *s, struct slabinfo *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81294d70)
Location: mm/slub.c:5916
Inline: False
Direct callers:
  - mm/slab_common.c:memcg_slabinfo_show
  - mm/slab_common.c:memcg_slabinfo_show
  - mm/slab_common.c:dump_unreclaimable_slab
  - mm/slab_common.c:cache_show
  - mm/slab_common.c:memcg_accumulate_slabinfo
```
**Symbols:**

```
ffffffff81294d70-ffffffff81294e1e: get_slabinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void get_slabinfo(struct kmem_cache *s, struct slabinfo *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a10b0)
Location: mm/slub.c:5916
Inline: False
Direct callers:
  - mm/slab_common.c:memcg_slabinfo_show
  - mm/slab_common.c:memcg_slabinfo_show
  - mm/slab_common.c:dump_unreclaimable_slab
  - mm/slab_common.c:cache_show
  - mm/slab_common.c:memcg_accumulate_slabinfo
```
**Symbols:**

```
ffffffff812a10b0-ffffffff812a115e: get_slabinfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void get_slabinfo(struct kmem_cache *s, struct slabinfo *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812b1260)
Location: mm/slub.c:5916
Inline: False
Direct callers:
  - mm/slab_common.c:memcg_slabinfo_show
  - mm/slab_common.c:memcg_slabinfo_show
  - mm/slab_common.c:dump_unreclaimable_slab
  - mm/slab_common.c:cache_show
  - mm/slab_common.c:memcg_accumulate_slabinfo
```
**Symbols:**

```
ffffffff812b1260-ffffffff812b130e: get_slabinfo (STB_GLOBAL)
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
