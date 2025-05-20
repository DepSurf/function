# Function: <code>obj_cgroup_charge</code>

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
int obj_cgroup_charge(struct obj_cgroup *objcg, gfp_t gfp, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813091c0)
Location: mm/memcontrol.c:3252
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff813091c0-ffffffff81309319: obj_cgroup_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int obj_cgroup_charge(struct obj_cgroup *objcg, gfp_t gfp, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8130f800)
Location: mm/memcontrol.c:3093
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff8130f800-ffffffff8130f8c3: obj_cgroup_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int obj_cgroup_charge(struct obj_cgroup *objcg, gfp_t gfp, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8135aa30)
Location: mm/memcontrol.c:3248
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
```
**Symbols:**

```
ffffffff8135aa30-ffffffff8135ab4a: obj_cgroup_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int obj_cgroup_charge(struct obj_cgroup *objcg, gfp_t gfp, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813d4020)
Location: mm/memcontrol.c:3252
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/memcontrol.c:obj_cgroup_charge_zswap
```
**Symbols:**

```
ffffffff813d4020-ffffffff813d4191: obj_cgroup_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int obj_cgroup_charge(struct obj_cgroup *objcg, gfp_t gfp, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814599e0)
Location: mm/memcontrol.c:3352
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:__kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc
  - mm/memcontrol.c:obj_cgroup_charge_zswap
```
**Symbols:**

```
ffffffff814599e0-ffffffff81459b51: obj_cgroup_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int obj_cgroup_charge(struct obj_cgroup *objcg, gfp_t gfp, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8148f670)
Location: mm/memcontrol.c:3363
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:__kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc
  - mm/memcontrol.c:obj_cgroup_charge_zswap
```
**Symbols:**

```
ffffffff8148f670-ffffffff8148f7e1: obj_cgroup_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int obj_cgroup_charge(struct obj_cgroup *objcg, gfp_t gfp, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814beeb0)
Location: mm/memcontrol.c:3555
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmalloc_node_trace
  - mm/slub.c:kmalloc_trace
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc
  - mm/memcontrol.c:obj_cgroup_charge_zswap
```
**Symbols:**

```
ffffffff814beeb0-ffffffff814bf021: obj_cgroup_charge (STB_GLOBAL)
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
