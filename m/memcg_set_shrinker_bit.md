# Function: <code>memcg_set_shrinker_bit</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void memcg_set_shrinker_bit(struct mem_cgroup *memcg, int nid, int shrinker_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812961f0)
Location: mm/memcontrol.c:426
Inline: False
Direct callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:list_lru_add
```
**Symbols:**

```
ffffffff812961f0-ffffffff81296229: memcg_set_shrinker_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void memcg_set_shrinker_bit(struct mem_cgroup *memcg, int nid, int shrinker_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b2530)
Location: mm/memcontrol.c:425
Inline: False
Direct callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:list_lru_add
```
**Symbols:**

```
ffffffff812b2530-ffffffff812b2568: memcg_set_shrinker_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void memcg_set_shrinker_bit(struct mem_cgroup *memcg, int nid, int shrinker_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c3f70)
Location: mm/memcontrol.c:433
Inline: False
Direct callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:list_lru_add
  - mm/huge_memory.c:deferred_split_huge_page
```
**Symbols:**

```
ffffffff812c3f70-ffffffff812c3fa8: memcg_set_shrinker_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void memcg_set_shrinker_bit(struct mem_cgroup *memcg, int nid, int shrinker_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812fa100)
Location: mm/memcontrol.c:424
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_slab_memcg
  - mm/list_lru.c:memcg_drain_list_lru_node
  - mm/list_lru.c:list_lru_add
  - mm/huge_memory.c:deferred_split_huge_page
```
**Symbols:**

```
ffffffff812fa100-ffffffff812fa138: memcg_set_shrinker_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void memcg_set_shrinker_bit(struct mem_cgroup *memcg, int nid, int shrinker_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81305f30)
Location: mm/memcontrol.c:510
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_slab_memcg
  - mm/list_lru.c:memcg_drain_list_lru_node
  - mm/list_lru.c:list_lru_add
  - mm/huge_memory.c:deferred_split_huge_page
```
**Symbols:**

```
ffffffff81305f30-ffffffff81305f6e: memcg_set_shrinker_bit (STB_GLOBAL)
```
</details>
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
void memcg_set_shrinker_bit(struct mem_cgroup *memcg, int nid, int shrinker_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff8000103669e0)
Location: mm/memcontrol.c:433
Inline: False
Direct callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:list_lru_add
  - mm/huge_memory.c:deferred_split_huge_page
```
**Symbols:**

```
ffff8000103669e0-ffff800010366a68: memcg_set_shrinker_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void memcg_set_shrinker_bit(struct mem_cgroup *memcg, int nid, int shrinker_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c05581f4)
Location: mm/memcontrol.c:433
Inline: False
Direct callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:list_lru_add
```
**Symbols:**

```
c05581f4-c0558254: memcg_set_shrinker_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void memcg_set_shrinker_bit(struct mem_cgroup *memcg, int nid, int shrinker_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c000000000453d60)
Location: mm/memcontrol.c:433
Inline: False
Direct callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:list_lru_add
  - mm/huge_memory.c:deferred_split_huge_page
```
**Symbols:**

```
c000000000453d60-c000000000453dd8: memcg_set_shrinker_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void memcg_set_shrinker_bit(struct mem_cgroup *memcg, int nid, int shrinker_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe000244d5e)
Location: mm/memcontrol.c:433
Inline: False
Direct callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:list_lru_add
```
**Symbols:**

```
ffffffe000244d5e-ffffffe000244dc2: memcg_set_shrinker_bit (STB_GLOBAL)
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
void memcg_set_shrinker_bit(struct mem_cgroup *memcg, int nid, int shrinker_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bc550)
Location: mm/memcontrol.c:433
Inline: False
Direct callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:list_lru_add
  - mm/huge_memory.c:deferred_split_huge_page
```
**Symbols:**

```
ffffffff812bc550-ffffffff812bc588: memcg_set_shrinker_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void memcg_set_shrinker_bit(struct mem_cgroup *memcg, int nid, int shrinker_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812ad6b0)
Location: mm/memcontrol.c:433
Inline: False
Direct callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:list_lru_add
  - mm/huge_memory.c:deferred_split_huge_page
```
**Symbols:**

```
ffffffff812ad6b0-ffffffff812ad6e8: memcg_set_shrinker_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void memcg_set_shrinker_bit(struct mem_cgroup *memcg, int nid, int shrinker_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812ba360)
Location: mm/memcontrol.c:433
Inline: False
Direct callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:list_lru_add
  - mm/huge_memory.c:deferred_split_huge_page
```
**Symbols:**

```
ffffffff812ba360-ffffffff812ba398: memcg_set_shrinker_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void memcg_set_shrinker_bit(struct mem_cgroup *memcg, int nid, int shrinker_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812caa20)
Location: mm/memcontrol.c:433
Inline: False
Direct callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:list_lru_add
  - mm/huge_memory.c:deferred_split_huge_page
```
**Symbols:**

```
ffffffff812caa20-ffffffff812caa72: memcg_set_shrinker_bit (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
