# Function: <code>mem_cgroup_kmem_disabled</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool mem_cgroup_kmem_disabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:259
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc_chunk
```
**Symbols:**

```
ffffffff81cc289c-ffffffff81cc28bc: mem_cgroup_kmem_disabled.cold (STB_LOCAL)
ffffffff81356280-ffffffff81356298: mem_cgroup_kmem_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool mem_cgroup_kmem_disabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:258
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/slab_common.c:new_kmalloc_cache
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
```
**Symbols:**

```
ffffffff81e74e2e-ffffffff81e74e58: mem_cgroup_kmem_disabled.cold (STB_LOCAL)
ffffffff813cee40-ffffffff813cee62: mem_cgroup_kmem_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool mem_cgroup_kmem_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff81455154)
Location: mm/memcontrol.c:251
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_online
Direct callers:
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/slab_common.c:new_kmalloc_cache
```
**Symbols:**

```
ffffffff8206813b-ffffffff82068165: mem_cgroup_kmem_disabled.cold (STB_LOCAL)
ffffffff81453f70-ffffffff81453f92: mem_cgroup_kmem_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool mem_cgroup_kmem_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff8148b054)
Location: mm/memcontrol.c:255
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_online
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_memcg_post_alloc_hook
  - mm/percpu.c:pcpu_memcg_post_alloc_hook
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/slab_common.c:new_kmalloc_cache
```
**Symbols:**

```
ffffffff820e7a25-ffffffff820e7a4f: mem_cgroup_kmem_disabled.cold (STB_LOCAL)
ffffffff81489d10-ffffffff81489d32: mem_cgroup_kmem_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool mem_cgroup_kmem_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff814ba95c)
Location: mm/memcontrol.c:259
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_online
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/slab_common.c:new_kmalloc_cache
```
**Symbols:**

```
ffffffff821c4739-ffffffff821c4763: mem_cgroup_kmem_disabled.cold (STB_LOCAL)
ffffffff814b94f0-ffffffff814b9512: mem_cgroup_kmem_disabled (STB_GLOBAL)
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
