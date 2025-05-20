# Function: <code>mem_hotplug_done</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void mem_hotplug_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81819aa1)
Location: mm/memory_hotplug.c:122
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:remove_memory
```
**Symbols:**

```
ffffffff811efd60-ffffffff811efd82: mem_hotplug_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void mem_hotplug_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81894864)
Location: mm/memory_hotplug.c:142
Inline: True
Inline callers:
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
**Symbols:**

```
ffffffff8120f1a0-ffffffff8120f1c2: mem_hotplug_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void mem_hotplug_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff818c8f54)
Location: mm/memory_hotplug.c:142
Inline: True
Inline callers:
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
Direct callers:
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:devm_memremap_pages_release
```
**Symbols:**

```
ffffffff81221270-ffffffff81221292: mem_hotplug_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void mem_hotplug_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff819004f0)
Location: mm/memory_hotplug.c:93
Inline: True
Inline callers:
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
Direct callers:
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:devm_memremap_pages_release
  - mm/page_alloc.c:numa_zonelist_order_handler
```
**Symbols:**

```
ffffffff8122c9e0-ffffffff8122c9fc: mem_hotplug_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void mem_hotplug_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8198a4c0)
Location: mm/memory_hotplug.c:95
Inline: True
Inline callers:
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
Direct callers:
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:devm_memremap_pages_release
  - mm/hmm.c:hmm_devmem_pages_create
  - mm/hmm.c:hmm_devmem_pages_create
  - mm/hmm.c:hmm_devmem_release
```
**Symbols:**

```
ffffffff81248210-ffffffff8124822c: mem_hotplug_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void mem_hotplug_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff819e6df2)
Location: mm/memory_hotplug.c:95
Inline: True
Inline callers:
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
Direct callers:
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:devm_memremap_pages_release
  - mm/hmm.c:hmm_devmem_pages_create
  - mm/hmm.c:hmm_devmem_pages_create
  - mm/hmm.c:hmm_devmem_release
```
**Symbols:**

```
ffffffff8126bc40-ffffffff8126bc5c: mem_hotplug_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void mem_hotplug_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81a22245)
Location: mm/memory_hotplug.c:95
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__remove_memory
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
Direct callers:
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:devm_memremap_pages_release
```
**Symbols:**

```
ffffffff81280540-ffffffff8128055c: mem_hotplug_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void mem_hotplug_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81a9158b)
Location: mm/memory_hotplug.c:97
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
Direct callers:
  - mm/memremap.c:devm_memremap_pages
  - mm/memremap.c:devm_memremap_pages
  - mm/memremap.c:devm_memremap_pages_release
```
**Symbols:**

```
ffffffff8129c880-ffffffff8129c89c: mem_hotplug_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void mem_hotplug_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81ac88aa)
Location: mm/memory_hotplug.c:97
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
Direct callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff812ac520-ffffffff812ac53c: mem_hotplug_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void mem_hotplug_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81bc132e)
Location: mm/memory_hotplug.c:94
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
Direct callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff812e15c0-ffffffff812e15dc: mem_hotplug_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void mem_hotplug_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81c3a487)
Location: mm/memory_hotplug.c:94
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
Direct callers:
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pageunmap_range
```
**Symbols:**

```
ffffffff812ec510-ffffffff812ec52c: mem_hotplug_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void mem_hotplug_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81c2c9e0)
Location: mm/memory_hotplug.c:104
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
Direct callers:
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff812c6db0-ffffffff812c6dcc: mem_hotplug_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void mem_hotplug_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81d4b139)
Location: mm/memory_hotplug.c:169
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
Direct callers:
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff8130b8a0-ffffffff8130b8bc: mem_hotplug_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void mem_hotplug_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81f1aa25)
Location: mm/memory_hotplug.c:186
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
Direct callers:
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff81374870-ffffffff81374892: mem_hotplug_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void mem_hotplug_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff820c28c5)
Location: mm/memory_hotplug.c:178
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
Direct callers:
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff813f2190-ffffffff813f21b2: mem_hotplug_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void mem_hotplug_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff82146665)
Location: mm/memory_hotplug.c:177
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
Direct callers:
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff81425c50-ffffffff81425c72: mem_hotplug_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void mem_hotplug_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff82228e4b)
Location: mm/memory_hotplug.c:245
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
Direct callers:
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_block_online
  - drivers/base/memory.c:memory_block_online
```
**Symbols:**

```
ffffffff81452e90-ffffffff81452eb2: mem_hotplug_done (STB_GLOBAL)
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
void mem_hotplug_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffff800010d9d360)
Location: mm/memory_hotplug.c:97
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffff80001034e010-ffff80001034e03c: mem_hotplug_done (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void mem_hotplug_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (c00000000042f1d4)
Location: mm/memory_hotplug.c:97
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
Direct callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
c00000000042e770-c00000000042e7b4: mem_hotplug_done (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void mem_hotplug_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81a6771a)
Location: mm/memory_hotplug.c:97
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
Direct callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff812a4b00-ffffffff812a4b1c: mem_hotplug_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void mem_hotplug_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81a241da)
Location: mm/memory_hotplug.c:97
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
Direct callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff812965d0-ffffffff812965ec: mem_hotplug_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void mem_hotplug_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81ad3b2a)
Location: mm/memory_hotplug.c:97
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
Direct callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff812a2910-ffffffff812a292c: mem_hotplug_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void mem_hotplug_done();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81ae001a)
Location: mm/memory_hotplug.c:97
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
Direct callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff812b2ba0-ffffffff812b2bbc: mem_hotplug_done (STB_GLOBAL)
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
