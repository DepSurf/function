# Function: <code>get_online_mems</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void get_online_mems();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff811efb80)
Location: mm/memory_hotplug.c:79
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_create
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_destroy_kmem_caches
  - mm/slub.c:show_slab_objects
  - mm/memory_hotplug.c:set_online_page_callback
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff811efb80-ffffffff811efbc1: get_online_mems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void get_online_mems();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8120efc0)
Location: mm/memory_hotplug.c:99
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_destroy_kmem_caches
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create
  - mm/slub.c:show_slab_objects
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff8120efc0-ffffffff8120f001: get_online_mems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void get_online_mems();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81221080)
Location: mm/memory_hotplug.c:99
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_destroy_kmem_caches
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create
  - mm/slub.c:show_slab_objects
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff81221080-ffffffff812210c1: get_online_mems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void get_online_mems();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8122c48f)
Location: mm/memory_hotplug.c:57
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
  - mm/slub.c:show_slab_objects
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff8122c950-ffffffff8122c984: get_online_mems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void get_online_mems();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81247c6f)
Location: mm/memory_hotplug.c:59
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
  - mm/slub.c:show_slab_objects
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff81248180-ffffffff812481b4: get_online_mems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void get_online_mems();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8126bba5)
Location: mm/memory_hotplug.c:59
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
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slub.c:show_slab_objects
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff8126bab0-ffffffff8126bae4: get_online_mems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void get_online_mems();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812804a5)
Location: mm/memory_hotplug.c:59
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
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slub.c:show_slab_objects
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff812803b0-ffffffff812803e4: get_online_mems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void get_online_mems();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8129c7e5)
Location: mm/memory_hotplug.c:61
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:kmemcg_workfn
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slub.c:show_slab_objects
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff8129c6f0-ffffffff8129c724: get_online_mems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void get_online_mems();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812ac485)
Location: mm/memory_hotplug.c:61
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
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff812ac390-ffffffff812ac3c4: get_online_mems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void get_online_mems();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812e0805)
Location: mm/memory_hotplug.c:59
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
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff812e1520-ffffffff812e1554: get_online_mems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void get_online_mems();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812eb495)
Location: mm/memory_hotplug.c:59
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
Direct callers:
  - mm/slab_common.c:kmem_cache_shrink
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff812ec470-ffffffff812ec4a4: get_online_mems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void get_online_mems();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812c61a5)
Location: mm/memory_hotplug.c:69
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
Direct callers:
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff812c6d10-ffffffff812c6d44: get_online_mems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void get_online_mems();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8130ac05)
Location: mm/memory_hotplug.c:134
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
ffffffff8130b800-ffffffff8130b834: get_online_mems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void get_online_mems();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81373aa5)
Location: mm/memory_hotplug.c:151
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
ffffffff81374770-ffffffff813747cf: get_online_mems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void get_online_mems();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff813f11d5)
Location: mm/memory_hotplug.c:143
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
ffffffff813f2060-ffffffff813f20bf: get_online_mems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void get_online_mems();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81424c15)
Location: mm/memory_hotplug.c:142
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
ffffffff81425b20-ffffffff81425b7f: get_online_mems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void get_online_mems();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81451f55)
Location: mm/memory_hotplug.c:210
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
ffffffff81452d60-ffffffff81452dbf: get_online_mems (STB_GLOBAL)
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
void get_online_mems();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffff80001034dd48)
Location: mm/memory_hotplug.c:61
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
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffff80001034df38-ffff80001034df8c: get_online_mems (STB_GLOBAL)
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
Location: include/linux/memory_hotplug.h:274
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void get_online_mems();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (c00000000042de04)
Location: mm/memory_hotplug.c:61
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
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
c00000000042e610-c00000000042e6a0: get_online_mems (STB_GLOBAL)
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
In mm/slab_common.c (0)
Location: include/linux/memory_hotplug.h:274
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void get_online_mems();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812a4a65)
Location: mm/memory_hotplug.c:61
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
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff812a4970-ffffffff812a49a4: get_online_mems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void get_online_mems();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81296535)
Location: mm/memory_hotplug.c:61
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
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff81296440-ffffffff81296474: get_online_mems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void get_online_mems();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812a2875)
Location: mm/memory_hotplug.c:61
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
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff812a2780-ffffffff812a27b4: get_online_mems (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void get_online_mems();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812b23f5)
Location: mm/memory_hotplug.c:61
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
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff812b2ae0-ffffffff812b2b26: get_online_mems (STB_GLOBAL)
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
