# Function: <code>mem_cgroup_from_slab_obj</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_slab_obj(void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:2990
Inline: False
Direct callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
  - mm/memcontrol.c:__mod_lruvec_kmem_state
```
**Symbols:**

```
ffffffff8206821b-ffffffff82068255: mem_cgroup_from_slab_obj.cold (STB_LOCAL)
ffffffff81458e20-ffffffff81458fd8: mem_cgroup_from_slab_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_slab_obj(void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:3000
Inline: False
Direct callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
  - mm/memcontrol.c:__mod_lruvec_kmem_state
```
**Symbols:**

```
ffffffff820e7b00-ffffffff820e7b3a: mem_cgroup_from_slab_obj.cold (STB_LOCAL)
ffffffff8148eab0-ffffffff8148ec68: mem_cgroup_from_slab_obj (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_slab_obj(void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:3115
Inline: False
Direct callers:
  - mm/list_lru.c:list_lru_del_obj
  - mm/list_lru.c:list_lru_add_obj
  - mm/memcontrol.c:__mod_lruvec_kmem_state
```
**Symbols:**

```
ffffffff821c4829-ffffffff821c4863: mem_cgroup_from_slab_obj.cold (STB_LOCAL)
ffffffff814be460-ffffffff814be615: mem_cgroup_from_slab_obj (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
