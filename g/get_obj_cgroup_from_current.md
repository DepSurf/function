# Function: <code>get_obj_cgroup_from_current</code>

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
struct obj_cgroup *get_obj_cgroup_from_current();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81308c80)
Location: mm/memcontrol.c:3000
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff81308c80-ffffffff81308df3: get_obj_cgroup_from_current (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct obj_cgroup *get_obj_cgroup_from_current();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8130f545)
Location: mm/memcontrol.c:2832
Inline: True
Inline callers:
  - mm/memcontrol.c:__memcg_kmem_charge_page
Direct callers:
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff8130f3c0-ffffffff8130f533: get_obj_cgroup_from_current (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct obj_cgroup *get_obj_cgroup_from_current();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8135a435)
Location: mm/memcontrol.c:2900
Inline: True
Inline callers:
  - mm/memcontrol.c:__memcg_kmem_charge_page
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
ffffffff8135a2b0-ffffffff8135a423: get_obj_cgroup_from_current (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct obj_cgroup *get_obj_cgroup_from_current();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813d39d5)
Location: mm/memcontrol.c:2911
Inline: True
Inline callers:
  - mm/memcontrol.c:__memcg_kmem_charge_page
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
ffffffff813d3700-ffffffff813d37f1: get_obj_cgroup_from_current (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct obj_cgroup *get_obj_cgroup_from_current();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81459365)
Location: mm/memcontrol.c:3011
Inline: True
Inline callers:
  - mm/memcontrol.c:__memcg_kmem_charge_page
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/memalloc.c:bpf_mem_alloc_init
  - kernel/bpf/memalloc.c:bpf_mem_alloc_init
  - mm/percpu.c:pcpu_alloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:__kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc
```
**Symbols:**

```
ffffffff814590f0-ffffffff814591e1: get_obj_cgroup_from_current (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct obj_cgroup *get_obj_cgroup_from_current();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8148eff5)
Location: mm/memcontrol.c:3021
Inline: True
Inline callers:
  - mm/memcontrol.c:__memcg_kmem_charge_page
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/memalloc.c:bpf_mem_alloc_init
  - kernel/bpf/memalloc.c:bpf_mem_alloc_init
  - mm/percpu.c:pcpu_alloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:__kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc
```
**Symbols:**

```
ffffffff8148ed80-ffffffff8148ee71: get_obj_cgroup_from_current (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81310612)
Location: include/linux/memcontrol.h:1817
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/memalloc.c (ffffffff81372d24)
Location: include/linux/memcontrol.h:1817
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_alloc_init
  - kernel/bpf/memalloc.c:bpf_mem_alloc_init
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
</ul>
