# Function: <code>obj_cgroup_uncharge</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
void obj_cgroup_uncharge(struct obj_cgroup *objcg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81309320)
Location: mm/memcontrol.c:3292
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_memcg_free_hook
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:memcg_slab_post_alloc_hook
```
**Symbols:**

```
ffffffff81309320-ffffffff81309330: obj_cgroup_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void obj_cgroup_uncharge(struct obj_cgroup *objcg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8130f8d0)
Location: mm/memcontrol.c:3124
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_memcg_free_hook
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:memcg_slab_post_alloc_hook
```
**Symbols:**

```
ffffffff8130f8d0-ffffffff8130f8e0: obj_cgroup_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void obj_cgroup_uncharge(struct obj_cgroup *objcg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8135ab50)
Location: mm/memcontrol.c:3292
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_memcg_free_hook
  - mm/percpu.c:pcpu_memcg_post_alloc_hook
  - mm/slub.c:memcg_slab_post_alloc_hook
```
**Symbols:**

```
ffffffff8135ab50-ffffffff8135ab65: obj_cgroup_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void obj_cgroup_uncharge(struct obj_cgroup *objcg, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813d5da4)
Location: mm/memcontrol.c:3296
Inline: True
Inline callers:
  - mm/memcontrol.c:obj_cgroup_uncharge_zswap
Direct callers:
  - mm/percpu.c:pcpu_memcg_post_alloc_hook
  - mm/slub.c:memcg_slab_post_alloc_hook
```
**Symbols:**

```
ffffffff813d41a0-ffffffff813d41bf: obj_cgroup_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void obj_cgroup_uncharge(struct obj_cgroup *objcg, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8145b7a9)
Location: mm/memcontrol.c:3396
Inline: True
Inline callers:
  - mm/memcontrol.c:obj_cgroup_uncharge_zswap
Direct callers:
  - mm/percpu.c:pcpu_memcg_post_alloc_hook
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__kmem_cache_free
  - mm/slub.c:memcg_slab_free_hook
  - mm/slub.c:memcg_slab_post_alloc_hook
```
**Symbols:**

```
ffffffff81459b70-ffffffff81459b8f: obj_cgroup_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void obj_cgroup_uncharge(struct obj_cgroup *objcg, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81491419)
Location: mm/memcontrol.c:3407
Inline: True
Inline callers:
  - mm/memcontrol.c:obj_cgroup_uncharge_zswap
Direct callers:
  - mm/percpu.c:pcpu_memcg_post_alloc_hook
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__kmem_cache_free
  - mm/slub.c:memcg_slab_free_hook
  - mm/slub.c:memcg_slab_post_alloc_hook
```
**Symbols:**

```
ffffffff8148f800-ffffffff8148f81f: obj_cgroup_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void obj_cgroup_uncharge(struct obj_cgroup *objcg, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814c0d89)
Location: mm/memcontrol.c:3599
Inline: True
Inline callers:
  - mm/memcontrol.c:obj_cgroup_uncharge_zswap
Direct callers:
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:__memcg_slab_free_hook
  - mm/slub.c:__memcg_slab_post_alloc_hook
```
**Symbols:**

```
ffffffff814bf040-ffffffff814bf05f: obj_cgroup_uncharge (STB_GLOBAL)
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
