# Function: <code>try_to_free_mem_cgroup_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup *memcg, long unsigned int nr_pages, gfp_t gfp_mask, bool may_swap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811a5210)
Location: mm/vmscan.c:2900
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_resize_limit
  - mm/memcontrol.c:mem_cgroup_resize_memsw_limit
  - mm/memcontrol.c:mem_cgroup_handle_over_high
```
**Symbols:**

```
ffffffff811a5210-ffffffff811a538c: try_to_free_mem_cgroup_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup *memcg, long unsigned int nr_pages, gfp_t gfp_mask, bool may_swap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811bbcd0)
Location: mm/vmscan.c:3017
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffffffff811bbcd0-ffffffff811bbe52: try_to_free_mem_cgroup_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup *memcg, long unsigned int nr_pages, gfp_t gfp_mask, bool may_swap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811cc390)
Location: mm/vmscan.c:3026
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffffffff811cc390-ffffffff811cc529: try_to_free_mem_cgroup_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup *memcg, long unsigned int nr_pages, gfp_t gfp_mask, bool may_swap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811d4f70)
Location: mm/vmscan.c:3093
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffffffff811d4f70-ffffffff811d5156: try_to_free_mem_cgroup_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup *memcg, long unsigned int nr_pages, gfp_t gfp_mask, bool may_swap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811ea4a0)
Location: mm/vmscan.c:3117
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffffffff811ea4a0-ffffffff811ea68c: try_to_free_mem_cgroup_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup *memcg, long unsigned int nr_pages, gfp_t gfp_mask, bool may_swap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8120bc60)
Location: mm/vmscan.c:3126
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffffffff8120bc60-ffffffff8120be4e: try_to_free_mem_cgroup_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup *memcg, long unsigned int nr_pages, gfp_t gfp_mask, bool may_swap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8121e920)
Location: mm/vmscan.c:3303
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffffffff8121e920-ffffffff8121eb0b: try_to_free_mem_cgroup_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup *memcg, long unsigned int nr_pages, gfp_t gfp_mask, bool may_swap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122dfe0)
Location: mm/vmscan.c:3263
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffffffff8122dfe0-ffffffff8122e1e6: try_to_free_mem_cgroup_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup *memcg, long unsigned int nr_pages, gfp_t gfp_mask, bool may_swap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8123c170)
Location: mm/vmscan.c:3349
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffffffff8123c170-ffffffff8123c376: try_to_free_mem_cgroup_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup *memcg, long unsigned int nr_pages, gfp_t gfp_mask, bool may_swap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8126a760)
Location: mm/vmscan.c:3323
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffffffff8126a760-ffffffff8126a963: try_to_free_mem_cgroup_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup *memcg, long unsigned int nr_pages, gfp_t gfp_mask, bool may_swap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81275200)
Location: mm/vmscan.c:3327
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffffffff81275200-ffffffff812753c5: try_to_free_mem_cgroup_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup *memcg, long unsigned int nr_pages, gfp_t gfp_mask, bool may_swap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8127a510)
Location: mm/vmscan.c:3525
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffffffff8127a510-ffffffff8127a6e6: try_to_free_mem_cgroup_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup *memcg, long unsigned int nr_pages, gfp_t gfp_mask, bool may_swap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812b8560)
Location: mm/vmscan.c:3682
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge_memcg
```
**Symbols:**

```
ffffffff812b8560-ffffffff812b8750: try_to_free_mem_cgroup_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup *memcg, long unsigned int nr_pages, gfp_t gfp_mask, bool may_swap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81313f40)
Location: mm/vmscan.c:3825
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_reclaim
  - mm/memcontrol.c:memory_reclaim
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge_memcg
```
**Symbols:**

```
ffffffff81313f40-ffffffff81314175: try_to_free_mem_cgroup_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup *memcg, long unsigned int nr_pages, gfp_t gfp_mask, unsigned int reclaim_options);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81387fe0)
Location: mm/vmscan.c:6761
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_reclaim
  - mm/memcontrol.c:memory_reclaim
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge_memcg
```
**Symbols:**

```
ffffffff81387fe0-ffffffff8138822a: try_to_free_mem_cgroup_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup *memcg, long unsigned int nr_pages, gfp_t gfp_mask, unsigned int reclaim_options);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813ba2c0)
Location: mm/vmscan.c:7124
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_reclaim
  - mm/memcontrol.c:memory_reclaim
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge_memcg
```
**Symbols:**

```
ffffffff813ba2c0-ffffffff813ba502: try_to_free_mem_cgroup_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup *memcg, long unsigned int nr_pages, gfp_t gfp_mask, unsigned int reclaim_options);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813e33e0)
Location: mm/vmscan.c:6491
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_reclaim
  - mm/memcontrol.c:memory_reclaim
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:reclaim_high
```
**Symbols:**

```
ffffffff813e33e0-ffffffff813e3622: try_to_free_mem_cgroup_pages (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup *memcg, long unsigned int nr_pages, gfp_t gfp_mask, bool may_swap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffff8000102cd380)
Location: mm/vmscan.c:3349
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffff8000102cd380-ffff8000102cd5f0: try_to_free_mem_cgroup_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup *memcg, long unsigned int nr_pages, gfp_t gfp_mask, bool may_swap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c04f7460)
Location: mm/vmscan.c:3349
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
c04f7460-c04f76f0: try_to_free_mem_cgroup_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup *memcg, long unsigned int nr_pages, gfp_t gfp_mask, bool may_swap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c00000000038ad90)
Location: mm/vmscan.c:3349
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
c00000000038ad90-c00000000038b05c: try_to_free_mem_cgroup_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup *memcg, long unsigned int nr_pages, gfp_t gfp_mask, bool may_swap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffe0001ebbd4)
Location: mm/vmscan.c:3349
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffffffe0001ebbd4-ffffffe0001ebde0: try_to_free_mem_cgroup_pages (STB_GLOBAL)
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
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup *memcg, long unsigned int nr_pages, gfp_t gfp_mask, bool may_swap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812347c0)
Location: mm/vmscan.c:3349
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffffffff812347c0-ffffffff812349c6: try_to_free_mem_cgroup_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup *memcg, long unsigned int nr_pages, gfp_t gfp_mask, bool may_swap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81227830)
Location: mm/vmscan.c:3349
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffffffff81227830-ffffffff81227a36: try_to_free_mem_cgroup_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup *memcg, long unsigned int nr_pages, gfp_t gfp_mask, bool may_swap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81232560)
Location: mm/vmscan.c:3349
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffffffff81232560-ffffffff81232766: try_to_free_mem_cgroup_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int try_to_free_mem_cgroup_pages(struct mem_cgroup *memcg, long unsigned int nr_pages, gfp_t gfp_mask, bool may_swap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812419f0)
Location: mm/vmscan.c:3349
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffffffff812419f0-ffffffff81241c27: try_to_free_mem_cgroup_pages (STB_GLOBAL)
```
</details>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int reclaim_options</code>
</li>
<li>
<b>Param removed. </b>
<code>bool may_swap</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
