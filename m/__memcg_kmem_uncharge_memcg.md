# Function: <code>__memcg_kmem_uncharge_memcg</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __memcg_kmem_uncharge_memcg(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b56e0)
Location: mm/memcontrol.c:2863
Inline: False
Direct callers:
  - mm/slub.c:__free_slab
  - mm/memcontrol.c:__memcg_kmem_uncharge
```
**Symbols:**

```
ffffffff812b56e0-ffffffff812b5742: __memcg_kmem_uncharge_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __memcg_kmem_uncharge_memcg(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c7390)
Location: mm/memcontrol.c:3072
Inline: False
Direct callers:
  - mm/slub.c:__free_slab
  - mm/memcontrol.c:__memcg_kmem_uncharge
```
**Symbols:**

```
ffffffff812c7390-ffffffff812c73f2: __memcg_kmem_uncharge_memcg (STB_GLOBAL)
```
</details>
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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __memcg_kmem_uncharge_memcg(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff80001036a198)
Location: mm/memcontrol.c:3072
Inline: False
Direct callers:
  - mm/slub.c:__free_slab
  - mm/memcontrol.c:__memcg_kmem_uncharge
```
**Symbols:**

```
ffff80001036a198-ffff80001036a208: __memcg_kmem_uncharge_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __memcg_kmem_uncharge_memcg(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c055b670)
Location: mm/memcontrol.c:3072
Inline: False
Direct callers:
  - mm/slub.c:__free_slab
  - mm/memcontrol.c:__memcg_kmem_uncharge
```
**Symbols:**

```
c055b670-c055b6e8: __memcg_kmem_uncharge_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __memcg_kmem_uncharge_memcg(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c000000000459060)
Location: mm/memcontrol.c:3072
Inline: False
Direct callers:
  - mm/slub.c:__free_slab
  - mm/memcontrol.c:__memcg_kmem_uncharge
```
**Symbols:**

```
c000000000459060-c000000000459108: __memcg_kmem_uncharge_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __memcg_kmem_uncharge_memcg(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe000247a26)
Location: mm/memcontrol.c:3072
Inline: False
Direct callers:
  - mm/slub.c:__free_slab
  - mm/memcontrol.c:__memcg_kmem_uncharge
```
**Symbols:**

```
ffffffe000247a26-ffffffe000247ac2: __memcg_kmem_uncharge_memcg (STB_GLOBAL)
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
void __memcg_kmem_uncharge_memcg(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bf970)
Location: mm/memcontrol.c:3072
Inline: False
Direct callers:
  - mm/slub.c:__free_slab
  - mm/memcontrol.c:__memcg_kmem_uncharge
```
**Symbols:**

```
ffffffff812bf970-ffffffff812bf9d2: __memcg_kmem_uncharge_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __memcg_kmem_uncharge_memcg(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b0a50)
Location: mm/memcontrol.c:3072
Inline: False
Direct callers:
  - mm/slub.c:__free_slab
  - mm/memcontrol.c:__memcg_kmem_uncharge
```
**Symbols:**

```
ffffffff812b0a50-ffffffff812b0ab2: __memcg_kmem_uncharge_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __memcg_kmem_uncharge_memcg(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bd780)
Location: mm/memcontrol.c:3072
Inline: False
Direct callers:
  - mm/slub.c:__free_slab
  - mm/memcontrol.c:__memcg_kmem_uncharge
```
**Symbols:**

```
ffffffff812bd780-ffffffff812bd7e2: __memcg_kmem_uncharge_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __memcg_kmem_uncharge_memcg(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812ce0b0)
Location: mm/memcontrol.c:3072
Inline: False
Direct callers:
  - mm/slub.c:__free_slab
  - mm/memcontrol.c:__memcg_kmem_uncharge
```
**Symbols:**

```
ffffffff812ce0b0-ffffffff812ce112: __memcg_kmem_uncharge_memcg (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
