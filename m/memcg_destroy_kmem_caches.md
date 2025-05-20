# Function: <code>memcg_destroy_kmem_caches</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void memcg_destroy_kmem_caches(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811b4950)
Location: mm/slab_common.c:603
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_free
```
**Symbols:**

```
ffffffff811b4950-ffffffff811b4a36: memcg_destroy_kmem_caches (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void memcg_destroy_kmem_caches(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811cda10)
Location: mm/slab_common.c:608
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_free
```
**Symbols:**

```
ffffffff811cda10-ffffffff811cdaf0: memcg_destroy_kmem_caches (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void memcg_destroy_kmem_caches(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811ddb60)
Location: mm/slab_common.c:637
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_free
```
**Symbols:**

```
ffffffff811ddb60-ffffffff811ddc40: memcg_destroy_kmem_caches (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void memcg_destroy_kmem_caches(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811e78c0)
Location: mm/slab_common.c:720
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_free
```
**Symbols:**

```
ffffffff811e78c0-ffffffff811e794b: memcg_destroy_kmem_caches (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void memcg_destroy_kmem_caches(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811fdb00)
Location: mm/slab_common.c:729
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_free
```
**Symbols:**

```
ffffffff811fdb00-ffffffff811fdb8b: memcg_destroy_kmem_caches (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void memcg_destroy_kmem_caches(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8121ee30)
Location: mm/slab_common.c:758
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_free
```
**Symbols:**

```
ffffffff8121ee30-ffffffff8121eebb: memcg_destroy_kmem_caches (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void memcg_destroy_kmem_caches(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81231e10)
Location: mm/slab_common.c:785
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_free
```
**Symbols:**

```
ffffffff81231e10-ffffffff81231e9b: memcg_destroy_kmem_caches (STB_GLOBAL)
```
</details>
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
</ul>
