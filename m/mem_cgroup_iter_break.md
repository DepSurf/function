# Function: <code>mem_cgroup_iter_break</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup *root, struct mem_cgroup *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff811fb230)
Location: mm/memcontrol.c:995
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
Direct callers:
  - mm/vmscan.c:shrink_zone
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
ffffffff811fb230-ffffffff811fb266: mem_cgroup_iter_break.part.43 (STB_LOCAL)
ffffffff811feb60-ffffffff811feb89: mem_cgroup_iter_break (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup *root, struct mem_cgroup *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff81223ac8)
Location: mm/memcontrol.c:879
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_out_of_memory
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
**Symbols:**

```
ffffffff8121edb0-ffffffff8121ede5: mem_cgroup_iter_break.part.44 (STB_LOCAL)
ffffffff81222b50-ffffffff81222b79: mem_cgroup_iter_break (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup *root, struct mem_cgroup *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff81235fbd)
Location: mm/memcontrol.c:881
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_scan_tasks
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_scan_tasks
```
**Symbols:**

```
ffffffff812312c0-ffffffff812312f5: mem_cgroup_iter_break.part.46 (STB_LOCAL)
ffffffff81234e40-ffffffff81234e69: mem_cgroup_iter_break (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup *root, struct mem_cgroup *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff81241a3b)
Location: mm/memcontrol.c:851
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_scan_tasks
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_scan_tasks
```
**Symbols:**

```
ffffffff8123caf0-ffffffff8123cb25: mem_cgroup_iter_break.part.47 (STB_LOCAL)
ffffffff812408c0-ffffffff812408ea: mem_cgroup_iter_break (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup *root, struct mem_cgroup *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff8126178b)
Location: mm/memcontrol.c:865
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_scan_tasks
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_scan_tasks
```
**Symbols:**

```
ffffffff8125bf80-ffffffff8125bfb9: mem_cgroup_iter_break.part.50 (STB_LOCAL)
ffffffff812605e0-ffffffff8126060a: mem_cgroup_iter_break (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup *root, struct mem_cgroup *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff812857ad)
Location: mm/memcontrol.c:836
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_scan_tasks
Direct callers:
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
ffffffff8127f8e0-ffffffff8127f918: mem_cgroup_iter_break.part.52 (STB_LOCAL)
ffffffff812847b0-ffffffff812847d9: mem_cgroup_iter_break (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup *root, struct mem_cgroup *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff8129a6b7)
Location: mm/memcontrol.c:1025
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
Direct callers:
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
ffffffff81294480-ffffffff812944b8: mem_cgroup_iter_break.part.52 (STB_LOCAL)
ffffffff812996c0-ffffffff812996e9: mem_cgroup_iter_break (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup *root, struct mem_cgroup *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff812b594e)
Location: mm/memcontrol.c:1142
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
```
**Symbols:**

```
ffffffff812b0b50-ffffffff812b0b87: mem_cgroup_iter_break.part.0 (STB_LOCAL)
ffffffff812b4a10-ffffffff812b4a39: mem_cgroup_iter_break (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup *root, struct mem_cgroup *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff812c75fe)
Location: mm/memcontrol.c:1153
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:memcg_expand_shrinker_maps
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:memcg_expand_shrinker_maps
```
**Symbols:**

```
ffffffff812c25b0-ffffffff812c25e7: mem_cgroup_iter_break.part.0 (STB_LOCAL)
ffffffff812c64e0-ffffffff812c6509: mem_cgroup_iter_break (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup *root, struct mem_cgroup *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812fae0e)
Location: mm/memcontrol.c:1118
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:memcg_expand_shrinker_maps
```
**Symbols:**

```
ffffffff812faec0-ffffffff812faf09: mem_cgroup_iter_break (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup *root, struct mem_cgroup *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81306d5a)
Location: mm/memcontrol.c:1243
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:memcg_expand_shrinker_maps
```
**Symbols:**

```
ffffffff81307f70-ffffffff81307fc6: mem_cgroup_iter_break (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup *root, struct mem_cgroup *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8130faa9)
Location: mm/memcontrol.c:1070
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
Direct callers:
  - mm/vmscan.c:prealloc_shrinker
```
**Symbols:**

```
ffffffff8130e6e0-ffffffff8130e736: mem_cgroup_iter_break (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup *root, struct mem_cgroup *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8135ad36)
Location: mm/memcontrol.c:1125
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
Direct callers:
  - mm/vmscan.c:prealloc_shrinker
```
**Symbols:**

```
ffffffff81359500-ffffffff81359556: mem_cgroup_iter_break (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup *root, struct mem_cgroup *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813d4433)
Location: mm/memcontrol.c:1105
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
Direct callers:
  - mm/vmscan.c:prealloc_shrinker
```
**Symbols:**

```
ffffffff813d1490-ffffffff813d150b: mem_cgroup_iter_break (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup *root, struct mem_cgroup *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81459e23)
Location: mm/memcontrol.c:1185
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
Direct callers:
  - mm/vmscan.c:lru_gen_seq_stop
  - mm/vmscan.c:lru_gen_seq_stop
  - mm/vmscan.c:__prealloc_shrinker
```
**Symbols:**

```
ffffffff814568e0-ffffffff8145695b: mem_cgroup_iter_break (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup *root, struct mem_cgroup *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8148fadc)
Location: mm/memcontrol.c:1210
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
Direct callers:
  - mm/vmscan.c:lru_gen_seq_stop
  - mm/vmscan.c:lru_gen_seq_stop
  - mm/vmscan.c:lru_gen_age_node
  - mm/vmscan.c:__prealloc_shrinker
```
**Symbols:**

```
ffffffff8148c170-ffffffff8148c1eb: mem_cgroup_iter_break (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup *root, struct mem_cgroup *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814bf30c)
Location: mm/memcontrol.c:1261
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
Direct callers:
  - mm/vmscan.c:lru_gen_seq_stop
  - mm/vmscan.c:lru_gen_seq_stop
  - mm/vmscan.c:lru_gen_age_node
  - mm/shrinker.c:shrinker_alloc
  - mm/zswap.c:zswap_pool_destroy
  - mm/zswap.c:shrink_worker
```
**Symbols:**

```
ffffffff814bbac0-ffffffff814bbb3b: mem_cgroup_iter_break (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup *root, struct mem_cgroup *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffff80001036a408)
Location: mm/memcontrol.c:1153
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:memcg_expand_shrinker_maps
```
**Symbols:**

```
ffff800010365278-ffff8000103652bc: mem_cgroup_iter_break.part.0 (STB_LOCAL)
ffff800010369220-ffff80001036926c: mem_cgroup_iter_break (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup *root, struct mem_cgroup *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (c055b8c8)
Location: mm/memcontrol.c:1153
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:memcg_expand_shrinker_maps
```
**Symbols:**

```
c0556be8-c0556c70: mem_cgroup_iter_break.part.0 (STB_LOCAL)
c055a724-c055a760: mem_cgroup_iter_break (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup *root, struct mem_cgroup *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (c000000000459448)
Location: mm/memcontrol.c:1153
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:memcg_expand_shrinker_maps
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:memcg_expand_shrinker_maps
```
**Symbols:**

```
c0000000004517b0-c000000000451874: mem_cgroup_iter_break.part.0 (STB_LOCAL)
c000000000457820-c000000000457864: mem_cgroup_iter_break (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup *root, struct mem_cgroup *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffe000247c7e)
Location: mm/memcontrol.c:1153
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:memcg_expand_shrinker_maps
```
**Symbols:**

```
ffffffe000243850-ffffffe0002438c4: mem_cgroup_iter_break.part.0 (STB_LOCAL)
ffffffe000246d64-ffffffe000246da8: mem_cgroup_iter_break (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup *root, struct mem_cgroup *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff812bfbde)
Location: mm/memcontrol.c:1153
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:memcg_expand_shrinker_maps
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:memcg_expand_shrinker_maps
```
**Symbols:**

```
ffffffff812bab90-ffffffff812babc7: mem_cgroup_iter_break.part.0 (STB_LOCAL)
ffffffff812beac0-ffffffff812beae9: mem_cgroup_iter_break (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup *root, struct mem_cgroup *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff812b0cbe)
Location: mm/memcontrol.c:1153
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:memcg_expand_shrinker_maps
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:memcg_expand_shrinker_maps
```
**Symbols:**

```
ffffffff812abd40-ffffffff812abd77: mem_cgroup_iter_break.part.0 (STB_LOCAL)
ffffffff812afbb0-ffffffff812afbd9: mem_cgroup_iter_break (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup *root, struct mem_cgroup *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff812bd9ee)
Location: mm/memcontrol.c:1153
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:memcg_expand_shrinker_maps
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:memcg_expand_shrinker_maps
```
**Symbols:**

```
ffffffff812b89a0-ffffffff812b89d7: mem_cgroup_iter_break.part.0 (STB_LOCAL)
ffffffff812bc8d0-ffffffff812bc8f9: mem_cgroup_iter_break (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mem_cgroup_iter_break(struct mem_cgroup *root, struct mem_cgroup *prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff812ce32e)
Location: mm/memcontrol.c:1153
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:memcg_expand_shrinker_maps
Direct callers:
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:memcg_expand_shrinker_maps
```
**Symbols:**

```
ffffffff812c92c0-ffffffff812c930f: mem_cgroup_iter_break.part.0 (STB_LOCAL)
ffffffff812cd0b0-ffffffff812cd0d9: mem_cgroup_iter_break (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
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
