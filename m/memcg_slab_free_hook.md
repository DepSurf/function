# Function: <code>memcg_slab_free_hook</code>

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
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff812e6969)
Location: mm/slab.h:337
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
```
**Symbols:**

```
ffffffff812e3f40-ffffffff812e4139: memcg_slab_free_hook.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff812ee129)
Location: mm/slab.h:335
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
```
**Symbols:**

```
ffffffff812ec5a0-ffffffff812ec7bb: memcg_slab_free_hook.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void memcg_slab_free_hook(struct kmem_cache *s_orig, void **p, int objects);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff8133a832)
Location: mm/slab.h:331
Inline: True
Direct callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
```
**Symbols:**

```
ffffffff81333930-ffffffff81333aff: memcg_slab_free_hook (STB_LOCAL)
ffffffff81cc1001-ffffffff81cc1074: memcg_slab_free_hook.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void memcg_slab_free_hook(struct kmem_cache *s_orig, void **p, int objects);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff813ac8cd)
Location: mm/slab.h:550
Inline: True
Direct callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
```
**Symbols:**

```
ffffffff813a5690-ffffffff813a58c6: memcg_slab_free_hook (STB_LOCAL)
ffffffff81e734d2-ffffffff81e7353d: memcg_slab_free_hook.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void memcg_slab_free_hook(struct kmem_cache *s, struct slab *slab, void **p, int objects);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff8142c069)
Location: mm/slab.h:556
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__kmem_cache_free
```
**Symbols:**

```
ffffffff81426010-ffffffff81426199: memcg_slab_free_hook (STB_LOCAL)
ffffffff82067409-ffffffff82067454: memcg_slab_free_hook.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void memcg_slab_free_hook(struct kmem_cache *s, struct slab *slab, void **p, int objects);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff814615ed)
Location: mm/slab.h:548
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__kmem_cache_free
```
**Symbols:**

```
ffffffff8145b1c0-ffffffff8145b349: memcg_slab_free_hook (STB_LOCAL)
ffffffff820e6cca-ffffffff820e6d15: memcg_slab_free_hook.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8145945b)
Location: mm/slub.c:2018
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct kmem_cache *s</code>
</li>
<li>
<b>Param added. </b>
<code>struct slab *slab</code>
</li>
<li>
<b>Param removed. </b>
<code>struct kmem_cache *s_orig</code>
</li>
<li>
<b>Param reordered. </b>
<code>s_orig, p, objects</code> ➡️ <code>s, slab, p, objects</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
