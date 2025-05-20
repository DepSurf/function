# Function: <code>put_online_mems</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void put_online_mems();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff811efbd0)
Location: mm/memory_hotplug.c:91
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_create
  - mm/slab_common.c:kmem_cache_create
  - mm/slab_common.c:kmem_cache_create
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_destroy_kmem_caches
  - mm/slub.c:show_slab_objects
  - mm/memory_hotplug.c:set_online_page_callback
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff811efbd0-ffffffff811efc4c: put_online_mems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void put_online_mems();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8120f010)
Location: mm/memory_hotplug.c:111
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_destroy_kmem_caches
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create
  - mm/slab_common.c:kmem_cache_create
  - mm/slab_common.c:kmem_cache_create
  - mm/slub.c:show_slab_objects
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff8120f010-ffffffff8120f08c: put_online_mems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void put_online_mems();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812210d0)
Location: mm/memory_hotplug.c:111
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_destroy_kmem_caches
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create
  - mm/slab_common.c:kmem_cache_create
  - mm/slab_common.c:kmem_cache_create
  - mm/slub.c:show_slab_objects
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff812210d0-ffffffff8122114c: put_online_mems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void put_online_mems();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8122c4db)
Location: mm/memory_hotplug.c:62
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_destroy_kmem_caches
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:kmemcg_deactivate_workfn
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create
  - mm/slab_common.c:kmem_cache_create
  - mm/slab_common.c:kmem_cache_create
  - mm/slab_common.c:kmem_cache_create
  - mm/slub.c:show_slab_objects
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff8122c990-ffffffff8122c9bc: put_online_mems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void put_online_mems();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81247cbb)
Location: mm/memory_hotplug.c:64
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_destroy_kmem_caches
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:kmemcg_deactivate_workfn
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create
  - mm/slab_common.c:kmem_cache_create
  - mm/slab_common.c:kmem_cache_create
  - mm/slab_common.c:kmem_cache_create
  - mm/slub.c:show_slab_objects
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff812481c0-ffffffff812481ed: put_online_mems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void put_online_mems();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8126baf0)
Location: mm/memory_hotplug.c:64
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_destroy_kmem_caches
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:kmemcg_deactivate_workfn
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slub.c:show_slab_objects
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff8126baf0-ffffffff8126bb1d: put_online_mems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void put_online_mems();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812803f0)
Location: mm/memory_hotplug.c:64
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_destroy_kmem_caches
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:kmemcg_deactivate_workfn
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slub.c:show_slab_objects
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff812803f0-ffffffff8128041d: put_online_mems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void put_online_mems();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8129c730)
Location: mm/memory_hotplug.c:66
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:kmemcg_workfn
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slub.c:show_slab_objects
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff8129c730-ffffffff8129c75c: put_online_mems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void put_online_mems();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812ac3d0)
Location: mm/memory_hotplug.c:66
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:kmemcg_workfn
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff812ac3d0-ffffffff812ac3fc: put_online_mems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void put_online_mems();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812e0857)
Location: mm/memory_hotplug.c:64
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:kmemcg_workfn
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff812e1560-ffffffff812e159c: put_online_mems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void put_online_mems();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812eb4e7)
Location: mm/memory_hotplug.c:64
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff812ec4b0-ffffffff812ec4ec: put_online_mems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void put_online_mems();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812c61f7)
Location: mm/memory_hotplug.c:74
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
Direct callers:
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff812c6d50-ffffffff812c6d8c: put_online_mems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void put_online_mems();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8130ac57)
Location: mm/memory_hotplug.c:139
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
Direct callers:
  - mm/migrate.c:migration_online_cpu
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff8130b840-ffffffff8130b87c: put_online_mems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void put_online_mems();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81373b08)
Location: mm/memory_hotplug.c:156
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
Direct callers:
  - mm/migrate.c:set_migration_target_nodes
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff813747d0-ffffffff81374834: put_online_mems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void put_online_mems();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff813f1238)
Location: mm/memory_hotplug.c:148
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
Direct callers:
  - mm/vmscan.c:lru_gen_change_state
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff813f20d0-ffffffff813f2134: put_online_mems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void put_online_mems();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81424c78)
Location: mm/memory_hotplug.c:147
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
Direct callers:
  - mm/vmscan.c:lru_gen_change_state
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff81425b90-ffffffff81425bf4: put_online_mems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void put_online_mems();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81451fb8)
Location: mm/memory_hotplug.c:215
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
Direct callers:
  - mm/vmscan.c:lru_gen_change_state
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff81452dd0-ffffffff81452e34: put_online_mems (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void put_online_mems();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffff80001034dda0)
Location: mm/memory_hotplug.c:66
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:kmemcg_workfn
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffff80001034df90-ffff80001034dfdc: put_online_mems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (0)
Location: include/linux/memory_hotplug.h:275
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void put_online_mems();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (c00000000042de7c)
Location: mm/memory_hotplug.c:66
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:kmemcg_workfn
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
c00000000042e6a0-c00000000042e718: put_online_mems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffe0001fd4ea)
Location: include/linux/memory_hotplug.h:275
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_destroy
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
void put_online_mems();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812a49b0)
Location: mm/memory_hotplug.c:66
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:kmemcg_workfn
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff812a49b0-ffffffff812a49dc: put_online_mems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void put_online_mems();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81296480)
Location: mm/memory_hotplug.c:66
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:kmemcg_workfn
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff81296480-ffffffff812964ac: put_online_mems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void put_online_mems();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812a27c0)
Location: mm/memory_hotplug.c:66
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:kmemcg_workfn
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff812a27c0-ffffffff812a27ec: put_online_mems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void put_online_mems();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812b2452)
Location: mm/memory_hotplug.c:66
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:kmemcg_workfn
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff812b2b30-ffffffff812b2b74: put_online_mems (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
