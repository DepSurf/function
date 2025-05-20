# Function: <code>on_each_cpu_cond</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void on_each_cpu_cond(bool (*cond_func)(int, void *), smp_call_func_t func, void *info, bool wait, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81103f70)
Location: kernel/smp.c:665
Inline: False
Direct callers:
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:list_locations
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_create
  - fs/buffer.c:invalidate_bh_lrus
```
**Symbols:**

```
ffffffff81103f70-ffffffff81104057: on_each_cpu_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void on_each_cpu_cond(bool (*cond_func)(int, void *), smp_call_func_t func, void *info, bool wait, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8110b380)
Location: kernel/smp.c:650
Inline: False
Direct callers:
  - mm/slub.c:validate_store
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:list_locations
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - fs/buffer.c:invalidate_bh_lrus
```
**Symbols:**

```
ffffffff8110b380-ffffffff8110b467: on_each_cpu_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void on_each_cpu_cond(bool (*cond_func)(int, void *), smp_call_func_t func, void *info, bool wait, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81112d10)
Location: kernel/smp.c:657
Inline: False
Direct callers:
  - mm/slub.c:validate_store
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:list_locations
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - fs/buffer.c:invalidate_bh_lrus
```
**Symbols:**

```
ffffffff81112d10-ffffffff81112e88: on_each_cpu_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void on_each_cpu_cond(bool (*cond_func)(int, void *), smp_call_func_t func, void *info, bool wait, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81114220)
Location: kernel/smp.c:668
Inline: False
Direct callers:
  - mm/slub.c:validate_store
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:list_locations
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - fs/buffer.c:invalidate_bh_lrus
```
**Symbols:**

```
ffffffff81114220-ffffffff81114373: on_each_cpu_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void on_each_cpu_cond(bool (*cond_func)(int, void *), smp_call_func_t func, void *info, bool wait, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8111f790)
Location: kernel/smp.c:670
Inline: False
Direct callers:
  - mm/slub.c:validate_store
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:list_locations
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - fs/buffer.c:invalidate_bh_lrus
```
**Symbols:**

```
ffffffff8111f790-ffffffff8111f8ca: on_each_cpu_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void on_each_cpu_cond(bool (*cond_func)(int, void *), smp_call_func_t func, void *info, bool wait, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8112cad0)
Location: kernel/smp.c:672
Inline: False
Direct callers:
  - mm/slub.c:validate_store
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:list_locations
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - fs/buffer.c:invalidate_bh_lrus
```
**Symbols:**

```
ffffffff8112cad0-ffffffff8112cc0a: on_each_cpu_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void on_each_cpu_cond(bool (*cond_func)(int, void *), smp_call_func_t func, void *info, bool wait, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff811384e0)
Location: kernel/smp.c:704
Inline: False
Direct callers:
  - mm/slub.c:validate_store
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:list_locations
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - fs/buffer.c:invalidate_bh_lrus
```
**Symbols:**

```
ffffffff811384e0-ffffffff811384fa: on_each_cpu_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void on_each_cpu_cond(bool (*cond_func)(int, void *), smp_call_func_t func, void *info, bool wait, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81143690)
Location: kernel/smp.c:717
Inline: False
Direct callers:
  - mm/slub.c:validate_store
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:list_locations
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - fs/buffer.c:invalidate_bh_lrus
```
**Symbols:**

```
ffffffff81143690-ffffffff811436aa: on_each_cpu_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void on_each_cpu_cond(bool (*cond_func)(int, void *), smp_call_func_t func, void *info, bool wait, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8114f1d0)
Location: kernel/smp.c:717
Inline: False
Direct callers:
  - mm/slub.c:validate_store
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:list_locations
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - fs/buffer.c:invalidate_bh_lrus
```
**Symbols:**

```
ffffffff8114f1d0-ffffffff8114f1ea: on_each_cpu_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void on_each_cpu_cond(smp_cond_func_t cond_func, smp_call_func_t func, void *info, bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8115fa40)
Location: kernel/smp.c:778
Inline: False
Direct callers:
  - mm/slub.c:validate_store
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:list_locations
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - fs/buffer.c:invalidate_bh_lrus
```
**Symbols:**

```
ffffffff8115fa40-ffffffff8115fa5a: on_each_cpu_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void on_each_cpu_cond(smp_cond_func_t cond_func, smp_call_func_t func, void *info, bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8115b9e0)
Location: kernel/smp.c:915
Inline: False
Direct callers:
  - mm/slub.c:validate_store
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:list_locations
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - fs/buffer.c:invalidate_bh_lrus
```
**Symbols:**

```
ffffffff8115b9e0-ffffffff8115b9fa: on_each_cpu_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812ed9bb)
Location: include/linux/smp.h:102
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:list_locations
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
```
```
In fs/buffer.c (ffffffff8136daa5)
Location: include/linux/smp.h:102
Inline: True
Inline callers:
  - fs/buffer.c:invalidate_bh_lrus
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813bc7b5)
Location: include/linux/smp.h:102
Inline: True
Inline callers:
  - fs/buffer.c:invalidate_bh_lrus
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81442ba5)
Location: include/linux/smp.h:102
Inline: True
Inline callers:
  - fs/buffer.c:invalidate_bh_lrus
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff814d1bc5)
Location: include/linux/smp.h:102
Inline: True
Inline callers:
  - fs/buffer.c:invalidate_bh_lrus
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff815084c5)
Location: include/linux/smp.h:102
Inline: True
Inline callers:
  - fs/buffer.c:invalidate_bh_lrus
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
In fs/buffer.c (ffffffff8153d335)
Location: include/linux/smp.h:102
Inline: True
Inline callers:
  - fs/buffer.c:invalidate_bh_lrus
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
void on_each_cpu_cond(bool (*cond_func)(int, void *), smp_call_func_t func, void *info, bool wait, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffff8000101bd8a8)
Location: kernel/smp.c:717
Inline: False
Direct callers:
  - mm/slub.c:validate_store
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:list_locations
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - fs/buffer.c:invalidate_bh_lrus
```
**Symbols:**

```
ffff8000101bd8a8-ffff8000101bd90c: on_each_cpu_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void on_each_cpu_cond(bool (*cond_func)(int, void *), smp_call_func_t func, void *info, bool wait, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (c0405b48)
Location: kernel/smp.c:717
Inline: False
Direct callers:
  - mm/slub.c:validate_store
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:list_locations
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - fs/buffer.c:invalidate_bh_lrus
```
**Symbols:**

```
c0405b48-c0405b80: on_each_cpu_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void on_each_cpu_cond(bool (*cond_func)(int, void *), smp_call_func_t func, void *info, bool wait, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (c000000000223d70)
Location: kernel/smp.c:717
Inline: False
Direct callers:
  - mm/slub.c:validate_store
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:list_locations
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - fs/buffer.c:invalidate_bh_lrus
```
**Symbols:**

```
c000000000223d70-c000000000223d8c: on_each_cpu_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void on_each_cpu_cond(bool (*cond_func)(int, void *), smp_call_func_t func, void *info, bool wait, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffe000140d5e)
Location: kernel/smp.c:717
Inline: False
Direct callers:
  - mm/slub.c:validate_store
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:list_locations
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - fs/buffer.c:invalidate_bh_lrus
```
**Symbols:**

```
ffffffe000140d5e-ffffffe000140db0: on_each_cpu_cond (STB_GLOBAL)
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
void on_each_cpu_cond(bool (*cond_func)(int, void *), smp_call_func_t func, void *info, bool wait, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff811477f0)
Location: kernel/smp.c:717
Inline: False
Direct callers:
  - mm/slub.c:validate_store
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:list_locations
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - fs/buffer.c:invalidate_bh_lrus
```
**Symbols:**

```
ffffffff811477f0-ffffffff8114780a: on_each_cpu_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void on_each_cpu_cond(bool (*cond_func)(int, void *), smp_call_func_t func, void *info, bool wait, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8113aaa0)
Location: kernel/smp.c:717
Inline: False
Direct callers:
  - mm/slub.c:validate_store
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:list_locations
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - fs/buffer.c:invalidate_bh_lrus
```
**Symbols:**

```
ffffffff8113aaa0-ffffffff8113aaba: on_each_cpu_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void on_each_cpu_cond(bool (*cond_func)(int, void *), smp_call_func_t func, void *info, bool wait, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff811456a0)
Location: kernel/smp.c:717
Inline: False
Direct callers:
  - mm/slub.c:validate_store
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:list_locations
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - fs/buffer.c:invalidate_bh_lrus
```
**Symbols:**

```
ffffffff811456a0-ffffffff811456ba: on_each_cpu_cond (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void on_each_cpu_cond(bool (*cond_func)(int, void *), smp_call_func_t func, void *info, bool wait, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff811522b0)
Location: kernel/smp.c:717
Inline: False
Direct callers:
  - mm/slub.c:validate_store
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:list_locations
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - fs/buffer.c:invalidate_bh_lrus
```
**Symbols:**

```
ffffffff811522b0-ffffffff811522ca: on_each_cpu_cond (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>gfp_t gfp_flags</code>
</li>
<li>
<b>Param type changed. </b>
<code>bool (*cond_func)(int, void *)</code> ➡️ <code>smp_cond_func_t cond_func</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
