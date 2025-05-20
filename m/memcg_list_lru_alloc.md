# Function: <code>memcg_list_lru_alloc</code>

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
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int memcg_list_lru_alloc(struct mem_cgroup *memcg, struct list_lru *lru, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/list_lru.c (0)
Location: mm/list_lru.c:472
Inline: False
```
**Symbols:**

```
ffffffff81e6d99a-ffffffff81e6d9ae: memcg_list_lru_alloc.cold (STB_LOCAL)
ffffffff813358a0-ffffffff81335be2: memcg_list_lru_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int memcg_list_lru_alloc(struct mem_cgroup *memcg, struct list_lru *lru, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/list_lru.c (0)
Location: mm/list_lru.c:472
Inline: False
```
**Symbols:**

```
ffffffff82063cb5-ffffffff82063cc9: memcg_list_lru_alloc.cold (STB_LOCAL)
ffffffff813ac660-ffffffff813ac9a2: memcg_list_lru_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int memcg_list_lru_alloc(struct mem_cgroup *memcg, struct list_lru *lru, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/list_lru.c (0)
Location: mm/list_lru.c:472
Inline: False
```
**Symbols:**

```
ffffffff820e33ac-ffffffff820e33c0: memcg_list_lru_alloc.cold (STB_LOCAL)
ffffffff813e0a00-ffffffff813e0d42: memcg_list_lru_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int memcg_list_lru_alloc(struct mem_cgroup *memcg, struct list_lru *lru, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/list_lru.c (0)
Location: mm/list_lru.c:473
Inline: False
Direct callers:
  - mm/slub.c:__memcg_slab_pre_alloc_hook
  - mm/zswap.c:zswap_store
```
**Symbols:**

```
ffffffff821bfe0c-ffffffff821bfe20: memcg_list_lru_alloc.cold (STB_LOCAL)
ffffffff8140b2d0-ffffffff8140b612: memcg_list_lru_alloc (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
