# Function: <code>mem_hotplug_begin</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void mem_hotplug_begin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff811efd10)
Location: mm/memory_hotplug.c:107
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:remove_memory
```
**Symbols:**

```
ffffffff811efd10-ffffffff811efd60: mem_hotplug_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void mem_hotplug_begin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8120f150)
Location: mm/memory_hotplug.c:127
Inline: False
Direct callers:
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
**Symbols:**

```
ffffffff8120f150-ffffffff8120f1a0: mem_hotplug_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mem_hotplug_begin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81221210)
Location: mm/memory_hotplug.c:127
Inline: False
Direct callers:
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:devm_memremap_pages_release
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
**Symbols:**

```
ffffffff81221210-ffffffff81221261: mem_hotplug_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void mem_hotplug_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81900480)
Location: mm/memory_hotplug.c:87
Inline: True
Inline callers:
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
Direct callers:
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:devm_memremap_pages_release
  - mm/page_alloc.c:numa_zonelist_order_handler
```
**Symbols:**

```
ffffffff8122c9c0-ffffffff8122c9dc: mem_hotplug_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void mem_hotplug_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8198a450)
Location: mm/memory_hotplug.c:89
Inline: True
Inline callers:
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
Direct callers:
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:devm_memremap_pages_release
  - mm/hmm.c:hmm_devmem_pages_create
  - mm/hmm.c:hmm_devmem_release
```
**Symbols:**

```
ffffffff812481f0-ffffffff8124820c: mem_hotplug_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void mem_hotplug_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff819e6d7c)
Location: mm/memory_hotplug.c:89
Inline: True
Inline callers:
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
Direct callers:
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:devm_memremap_pages_release
  - mm/hmm.c:hmm_devmem_pages_create
  - mm/hmm.c:hmm_devmem_release
```
**Symbols:**

```
ffffffff8126bc20-ffffffff8126bc3c: mem_hotplug_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void mem_hotplug_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81a221cc)
Location: mm/memory_hotplug.c:89
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__remove_memory
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
Direct callers:
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:devm_memremap_pages_release
```
**Symbols:**

```
ffffffff81280520-ffffffff8128053c: mem_hotplug_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void mem_hotplug_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81a9155f)
Location: mm/memory_hotplug.c:91
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
Direct callers:
  - mm/memremap.c:devm_memremap_pages
  - mm/memremap.c:devm_memremap_pages_release
```
**Symbols:**

```
ffffffff8129c860-ffffffff8129c87c: mem_hotplug_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void mem_hotplug_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81ac8912)
Location: mm/memory_hotplug.c:91
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
Direct callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff812ac500-ffffffff812ac51c: mem_hotplug_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void mem_hotplug_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81bc12eb)
Location: mm/memory_hotplug.c:88
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
Direct callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff812e15a0-ffffffff812e15bc: mem_hotplug_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void mem_hotplug_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81c3a453)
Location: mm/memory_hotplug.c:88
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
Direct callers:
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pageunmap_range
```
**Symbols:**

```
ffffffff812ec4f0-ffffffff812ec50c: mem_hotplug_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void mem_hotplug_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81c2c9ab)
Location: mm/memory_hotplug.c:98
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
Direct callers:
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff812c6d90-ffffffff812c6dac: mem_hotplug_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void mem_hotplug_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81d4b102)
Location: mm/memory_hotplug.c:163
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
Direct callers:
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff8130b880-ffffffff8130b89c: mem_hotplug_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void mem_hotplug_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81f1a9ee)
Location: mm/memory_hotplug.c:180
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
Direct callers:
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff81374840-ffffffff81374862: mem_hotplug_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void mem_hotplug_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff820c288e)
Location: mm/memory_hotplug.c:172
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
Direct callers:
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff813f2150-ffffffff813f2172: mem_hotplug_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void mem_hotplug_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8214662e)
Location: mm/memory_hotplug.c:171
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
Direct callers:
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff81425c10-ffffffff81425c32: mem_hotplug_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void mem_hotplug_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff82228dbc)
Location: mm/memory_hotplug.c:239
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
Direct callers:
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_block_online
  - drivers/base/memory.c:memory_block_online
```
**Symbols:**

```
ffffffff81452e50-ffffffff81452e72: mem_hotplug_begin (STB_GLOBAL)
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
void mem_hotplug_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffff800010d9d2a8)
Location: mm/memory_hotplug.c:91
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffff80001034dfe0-ffff80001034e00c: mem_hotplug_begin (STB_GLOBAL)
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
void mem_hotplug_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (c00000000042f268)
Location: mm/memory_hotplug.c:91
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
Direct callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
c00000000042e720-c00000000042e764: mem_hotplug_begin (STB_GLOBAL)
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
void mem_hotplug_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81a67782)
Location: mm/memory_hotplug.c:91
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
Direct callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff812a4ae0-ffffffff812a4afc: mem_hotplug_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void mem_hotplug_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81a24242)
Location: mm/memory_hotplug.c:91
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
Direct callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff812965b0-ffffffff812965cc: mem_hotplug_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void mem_hotplug_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81ad3b92)
Location: mm/memory_hotplug.c:91
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
Direct callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff812a28f0-ffffffff812a290c: mem_hotplug_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void mem_hotplug_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81ae0082)
Location: mm/memory_hotplug.c:91
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
Direct callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff812b2b80-ffffffff812b2b9c: mem_hotplug_begin (STB_GLOBAL)
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
