# Function: <code>vmem_altmap_offset</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vmem_altmap_offset(struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff8119e5c0)
Location: kernel/memremap.c:390
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__add_pages
```
**Symbols:**

```
ffffffff8119e5c0-ffffffff8119e5d3: vmem_altmap_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vmem_altmap_offset(struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff811adff0)
Location: kernel/memremap.c:400
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__add_pages
```
**Symbols:**

```
ffffffff811adff0-ffffffff811ae003: vmem_altmap_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vmem_altmap_offset(struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff811b5470)
Location: kernel/memremap.c:396
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__add_pages
```
**Symbols:**

```
ffffffff811b5470-ffffffff811b5483: vmem_altmap_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vmem_altmap_offset(struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff811c9560)
Location: kernel/memremap.c:468
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__add_pages
```
**Symbols:**

```
ffffffff811c9560-ffffffff811c9573: vmem_altmap_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vmem_altmap_offset(struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff811e9ad0)
Location: kernel/memremap.c:278
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:devm_memremap_pages_release
Direct callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__add_pages
```
**Symbols:**

```
ffffffff811e9b70-ffffffff811e9b83: vmem_altmap_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vmem_altmap_offset(struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/memremap.c (ffffffff811fa60e)
Location: kernel/memremap.c:269
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:devm_memremap_pages_release
Direct callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__add_pages
```
**Symbols:**

```
ffffffff811fa6e0-ffffffff811fa6f3: vmem_altmap_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vmem_altmap_offset(struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812c2ca8)
Location: mm/memremap.c:344
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages
  - mm/memremap.c:devm_memremap_pages_release
Direct callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__add_pages
```
**Symbols:**

```
ffffffff812c2d70-ffffffff812c2d8a: vmem_altmap_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vmem_altmap_offset(struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812d4b5b)
Location: mm/memremap.c:366
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
Direct callers:
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__add_pages
```
**Symbols:**

```
ffffffff812d4c20-ffffffff812d4c3a: vmem_altmap_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vmem_altmap_offset(struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff8130a6a4)
Location: mm/memremap.c:399
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
Direct callers:
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__add_pages
```
**Symbols:**

```
ffffffff8130a9f0-ffffffff8130aa0a: vmem_altmap_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vmem_altmap_offset(struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff813160a9)
Location: mm/memremap.c:448
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:pageunmap_range
  - mm/memremap.c:pgmap_pfn_valid
Direct callers:
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__add_pages
```
**Symbols:**

```
ffffffff813168d0-ffffffff813168ea: vmem_altmap_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vmem_altmap_offset(struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff8131c2de)
Location: mm/memremap.c:454
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:pgmap_pfn_valid
Direct callers:
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_range
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__add_pages
```
**Symbols:**

```
ffffffff8131cb20-ffffffff8131cb3a: vmem_altmap_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vmem_altmap_offset(struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff813695ca)
Location: mm/memremap.c:451
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:pgmap_pfn_valid
Direct callers:
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_range
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__add_pages
```
**Symbols:**

```
ffffffff81369e70-ffffffff81369e8a: vmem_altmap_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vmem_altmap_offset(struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff813e727e)
Location: mm/memremap.c:409
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:pfn_len
  - mm/memremap.c:pgmap_pfn_valid
Direct callers:
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_range
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__add_pages
```
**Symbols:**

```
ffffffff813e7ba0-ffffffff813e7bc0: vmem_altmap_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vmem_altmap_offset(struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff8146eee9)
Location: mm/memremap.c:425
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:pfn_len
  - mm/memremap.c:pgmap_pfn_valid
Direct callers:
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_range
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__add_pages
```
**Symbols:**

```
ffffffff8146f9b0-ffffffff8146f9d0: vmem_altmap_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vmem_altmap_offset(struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff814a36c3)
Location: mm/memremap.c:425
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:pfn_len
  - mm/memremap.c:pgmap_pfn_valid
Direct callers:
  - mm/mm_init.c:memmap_init_zone_device
  - mm/mm_init.c:memmap_init_range
  - mm/memory_hotplug.c:__add_pages
```
**Symbols:**

```
ffffffff814a4190-ffffffff814a41b0: vmem_altmap_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mm_init.c (ffffffff82228926)
Location: include/linux/mm.h:3875
Inline: True
Inline callers:
  - mm/mm_init.c:memmap_init_zone_device
  - mm/mm_init.c:memmap_init_range
```
```
In mm/memory_hotplug.c (ffffffff82228edf)
Location: include/linux/mm.h:3875
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__add_pages
```
```
In mm/memremap.c (ffffffff814d4563)
Location: include/linux/mm.h:3875
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:pfn_len
  - mm/memremap.c:pgmap_pfn_valid
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (0)
Location: include/linux/memremap.h:159
Inline: True
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
long unsigned int vmem_altmap_offset(struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memremap.c (c00000000046e43c)
Location: mm/memremap.c:366
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
Direct callers:
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__add_pages
```
**Symbols:**

```
c00000000046e5b0-c00000000046e5d8: vmem_altmap_offset (STB_GLOBAL)
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
long unsigned int vmem_altmap_offset(struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812cd13b)
Location: mm/memremap.c:366
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
Direct callers:
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__add_pages
```
**Symbols:**

```
ffffffff812cd200-ffffffff812cd21a: vmem_altmap_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vmem_altmap_offset(struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812bdfab)
Location: mm/memremap.c:366
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
Direct callers:
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__add_pages
```
**Symbols:**

```
ffffffff812be070-ffffffff812be08a: vmem_altmap_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vmem_altmap_offset(struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812caf4b)
Location: mm/memremap.c:366
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
Direct callers:
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__add_pages
```
**Symbols:**

```
ffffffff812cb010-ffffffff812cb02a: vmem_altmap_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vmem_altmap_offset(struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812dbc89)
Location: mm/memremap.c:366
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
Direct callers:
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__add_pages
```
**Symbols:**

```
ffffffff812dbd70-ffffffff812dbd8a: vmem_altmap_offset (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
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
