# Function: <code>set_shrinker_bit</code>

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
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void set_shrinker_bit(struct mem_cgroup *memcg, int nid, int shrinker_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81276570)
Location: mm/vmscan.c:332
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_slab_memcg
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:list_lru_add
  - mm/huge_memory.c:deferred_split_huge_page
```
**Symbols:**

```
ffffffff81276570-ffffffff812765b1: set_shrinker_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void set_shrinker_bit(struct mem_cgroup *memcg, int nid, int shrinker_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812b3d90)
Location: mm/vmscan.c:336
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_slab_memcg
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:list_lru_add
  - mm/huge_memory.c:deferred_split_huge_page
```
**Symbols:**

```
ffffffff812b3d90-ffffffff812b3dd1: set_shrinker_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void set_shrinker_bit(struct mem_cgroup *memcg, int nid, int shrinker_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8130fd10)
Location: mm/vmscan.c:338
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_slab_memcg
  - mm/list_lru.c:memcg_reparent_list_lrus
  - mm/list_lru.c:list_lru_add
  - mm/huge_memory.c:deferred_split_huge_page
```
**Symbols:**

```
ffffffff8130fd10-ffffffff8130fd71: set_shrinker_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void set_shrinker_bit(struct mem_cgroup *memcg, int nid, int shrinker_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81383320)
Location: mm/vmscan.c:352
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_slab_memcg
  - mm/list_lru.c:memcg_reparent_list_lrus
  - mm/list_lru.c:list_lru_add
  - mm/huge_memory.c:deferred_split_huge_page
```
**Symbols:**

```
ffffffff81383320-ffffffff81383381: set_shrinker_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void set_shrinker_bit(struct mem_cgroup *memcg, int nid, int shrinker_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813b4b50)
Location: mm/vmscan.c:335
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_slab_memcg
  - mm/list_lru.c:memcg_reparent_list_lrus
  - mm/list_lru.c:list_lru_add
  - mm/huge_memory.c:deferred_split_folio
```
**Symbols:**

```
ffffffff813b4b50-ffffffff813b4bba: set_shrinker_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void set_shrinker_bit(struct mem_cgroup *memcg, int nid, int shrinker_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shrinker.c (ffffffff813e4830)
Location: mm/shrinker.c:194
Inline: True
Direct callers:
  - mm/shrinker.c:shrink_slab_memcg
  - mm/list_lru.c:memcg_reparent_list_lrus
  - mm/list_lru.c:list_lru_putback
  - mm/list_lru.c:list_lru_add
  - mm/huge_memory.c:deferred_split_folio
```
**Symbols:**

```
ffffffff813e4830-ffffffff813e48b5: set_shrinker_bit (STB_GLOBAL)
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
