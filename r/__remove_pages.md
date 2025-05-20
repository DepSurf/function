# Function: <code>__remove_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __remove_pages(struct zone *zone, long unsigned int phys_start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff811ef340)
Location: mm/memory_hotplug.c:765
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
```
**Symbols:**

```
ffffffff811ef340-ffffffff811ef875: __remove_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __remove_pages(struct zone *zone, long unsigned int phys_start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8120e610)
Location: mm/memory_hotplug.c:825
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
```
**Symbols:**

```
ffffffff8120e610-ffffffff8120eb7e: __remove_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __remove_pages(struct zone *zone, long unsigned int phys_start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81220650)
Location: mm/memory_hotplug.c:811
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
```
**Symbols:**

```
ffffffff81220650-ffffffff81220ba4: __remove_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __remove_pages(struct zone *zone, long unsigned int phys_start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8122caa0)
Location: mm/memory_hotplug.c:565
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
```
**Symbols:**

```
ffffffff8122caa0-ffffffff8122cfe7: __remove_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __remove_pages(struct zone *zone, long unsigned int phys_start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812482d0)
Location: mm/memory_hotplug.c:574
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
  - mm/hmm.c:hmm_devmem_release
```
**Symbols:**

```
ffffffff812482d0-ffffffff8124883c: __remove_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int __remove_pages(struct zone *zone, long unsigned int phys_start_pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (0)
Location: mm/memory_hotplug.c:553
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
  - mm/hmm.c:hmm_devmem_release
```
**Symbols:**

```
ffffffff8126c832-ffffffff8126c85b: __remove_pages.cold.32 (STB_LOCAL)
ffffffff8126bd00-ffffffff8126c263: __remove_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int __remove_pages(struct zone *zone, long unsigned int phys_start_pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (0)
Location: mm/memory_hotplug.c:553
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
  - kernel/memremap.c:devm_memremap_pages_release
```
**Symbols:**

```
ffffffff81281161-ffffffff8128118a: __remove_pages.cold.33 (STB_LOCAL)
ffffffff81280600-ffffffff81280b10: __remove_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __remove_pages(struct zone *zone, long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8129c940)
Location: mm/memory_hotplug.c:541
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
  - mm/memremap.c:devm_memremap_pages_release
```
**Symbols:**

```
ffffffff8129c940-ffffffff8129cf12: __remove_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __remove_pages(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812ac5e0)
Location: mm/memory_hotplug.c:520
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff812ac5e0-ffffffff812ac6ef: __remove_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __remove_pages(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812e1680)
Location: mm/memory_hotplug.c:534
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff812e1680-ffffffff812e1767: __remove_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __remove_pages(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812ec5d0)
Location: mm/memory_hotplug.c:534
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
  - mm/memremap.c:pageunmap_range
```
**Symbols:**

```
ffffffff812ec5d0-ffffffff812ec6b7: __remove_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __remove_pages(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812c6e70)
Location: mm/memory_hotplug.c:576
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff812c6e70-ffffffff812c6f5c: __remove_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __remove_pages(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8130b8c0)
Location: mm/memory_hotplug.c:519
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff8130b8c0-ffffffff8130b9ac: __remove_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __remove_pages(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff813748a0)
Location: mm/memory_hotplug.c:530
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff813748a0-ffffffff813749b4: __remove_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __remove_pages(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff813f21d0)
Location: mm/memory_hotplug.c:518
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff813f21d0-ffffffff813f22eb: __remove_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __remove_pages(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81425c90)
Location: mm/memory_hotplug.c:505
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff81425c90-ffffffff81425d29: __remove_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __remove_pages(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81452ed0)
Location: mm/memory_hotplug.c:573
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff81452ed0-ffffffff81452f69: __remove_pages (STB_GLOBAL)
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
void __remove_pages(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffff80001034e1a8)
Location: mm/memory_hotplug.c:520
Inline: False
Direct callers:
  - arch/arm64/mm/mmu.c:arch_remove_memory
```
**Symbols:**

```
ffff80001034e1a8-ffff80001034e2d0: __remove_pages (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __remove_pages(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (c00000000042e8e0)
Location: mm/memory_hotplug.c:520
Inline: False
Direct callers:
  - arch/powerpc/mm/mem.c:arch_remove_memory
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
c00000000042e8e0-c00000000042ea8c: __remove_pages (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void __remove_pages(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812a4bc0)
Location: mm/memory_hotplug.c:520
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff812a4bc0-ffffffff812a4ccf: __remove_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __remove_pages(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81296690)
Location: mm/memory_hotplug.c:520
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff81296690-ffffffff8129679f: __remove_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __remove_pages(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812a29d0)
Location: mm/memory_hotplug.c:520
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff812a29d0-ffffffff812a2adf: __remove_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __remove_pages(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812b2c60)
Location: mm/memory_hotplug.c:520
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_remove_memory
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff812b2c60-ffffffff812b2d66: __remove_pages (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vmem_altmap *altmap</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int pfn</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int phys_start_pfn</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct zone *zone</code>
</li>
<li>
<b>Param reordered. </b>
<code>zone, pfn, nr_pages, altmap</code> ➡️ <code>pfn, nr_pages, altmap</code>
</li>
</ul>
</details>
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
