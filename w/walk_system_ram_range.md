# Function: <code>walk_system_ram_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void *arg, int (*func)(long unsigned int, long unsigned int, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81086ee0)
Location: kernel/resource.c:453
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat.c:pat_pagerange_is_ram
  - kernel/resource.c:page_is_ram
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - fs/proc/kcore.c:kcore_update_ram
```
**Symbols:**

```
ffffffff81086ee0-ffffffff81086fc1: walk_system_ram_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void *arg, int (*func)(long unsigned int, long unsigned int, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81089f00)
Location: kernel/resource.c:479
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat.c:pat_pagerange_is_ram
  - kernel/resource.c:page_is_ram
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - fs/proc/kcore.c:kcore_update_ram
```
**Symbols:**

```
ffffffff81089f00-ffffffff81089fdc: walk_system_ram_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void *arg, int (*func)(long unsigned int, long unsigned int, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108ee50)
Location: kernel/resource.c:479
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat.c:pat_pagerange_is_ram
  - kernel/resource.c:page_is_ram
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - fs/proc/kcore.c:kcore_update_ram
```
**Symbols:**

```
ffffffff8108ee50-ffffffff8108ef2c: walk_system_ram_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void *arg, int (*func)(long unsigned int, long unsigned int, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108be10)
Location: kernel/resource.c:479
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat.c:pat_pagerange_is_ram
  - kernel/resource.c:page_is_ram
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - fs/proc/kcore.c:kcore_update_ram
```
**Symbols:**

```
ffffffff8108be10-ffffffff8108bee7: walk_system_ram_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void *arg, int (*func)(long unsigned int, long unsigned int, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81092b50)
Location: kernel/resource.c:496
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:pat_pagerange_is_ram
  - kernel/resource.c:page_is_ram
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - fs/proc/kcore.c:kcore_update_ram
```
**Symbols:**

```
ffffffff81092b50-ffffffff81092c29: walk_system_ram_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void *arg, int (*func)(long unsigned int, long unsigned int, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81096570)
Location: kernel/resource.c:464
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:pat_pagerange_is_ram
  - kernel/resource.c:page_is_ram
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - fs/proc/kcore.c:kcore_update_ram
```
**Symbols:**

```
ffffffff81096570-ffffffff81096649: walk_system_ram_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void *arg, int (*func)(long unsigned int, long unsigned int, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8109e880)
Location: kernel/resource.c:458
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:pat_pagerange_is_ram
  - kernel/resource.c:page_is_ram
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - fs/proc/kcore.c:kcore_update_ram
```
**Symbols:**

```
ffffffff8109e880-ffffffff8109e951: walk_system_ram_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void *arg, int (*func)(long unsigned int, long unsigned int, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a2ed0)
Location: kernel/resource.c:475
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:pat_pagerange_is_ram
  - kernel/resource.c:page_is_ram
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - fs/proc/kcore.c:kcore_update_ram
```
**Symbols:**

```
ffffffff810a2ed0-ffffffff810a2f9e: walk_system_ram_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void *arg, int (*func)(long unsigned int, long unsigned int, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a9510)
Location: kernel/resource.c:475
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:pat_pagerange_is_ram
  - kernel/resource.c:page_is_ram
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - fs/proc/kcore.c:kcore_update_ram
```
**Symbols:**

```
ffffffff810a9510-ffffffff810a95de: walk_system_ram_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void *arg, int (*func)(long unsigned int, long unsigned int, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810b0c37)
Location: kernel/resource.c:475
Inline: True
Inline callers:
  - kernel/resource.c:page_is_ram
Direct callers:
  - arch/x86/mm/pat/memtype.c:pat_pagerange_is_ram
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff810b1100-ffffffff810b11ce: walk_system_ram_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void *arg, int (*func)(long unsigned int, long unsigned int, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810ac397)
Location: kernel/resource.c:482
Inline: True
Inline callers:
  - kernel/resource.c:page_is_ram
Direct callers:
  - arch/x86/mm/pat/memtype.c:pat_pagerange_is_ram
  - mm/memory_hotplug.c:offline_pages
```
**Symbols:**

```
ffffffff810ac860-ffffffff810ac92e: walk_system_ram_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void *arg, int (*func)(long unsigned int, long unsigned int, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810ad207)
Location: kernel/resource.c:465
Inline: True
Inline callers:
  - kernel/resource.c:page_is_ram
Direct callers:
  - arch/x86/mm/pat/memtype.c:pat_pagerange_is_ram
  - mm/memory_hotplug.c:offline_pages
```
**Symbols:**

```
ffffffff810ada50-ffffffff810adb19: walk_system_ram_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void *arg, int (*func)(long unsigned int, long unsigned int, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810bed77)
Location: kernel/resource.c:465
Inline: True
Inline callers:
  - kernel/resource.c:page_is_ram
Direct callers:
  - arch/x86/mm/pat/memtype.c:pat_pagerange_is_ram
  - mm/memory_hotplug.c:offline_pages
```
**Symbols:**

```
ffffffff810bf5d0-ffffffff810bf699: walk_system_ram_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void *arg, int (*func)(long unsigned int, long unsigned int, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810d6434)
Location: kernel/resource.c:452
Inline: True
Inline callers:
  - kernel/resource.c:page_is_ram
Direct callers:
  - arch/x86/mm/pat/memtype.c:pat_pagerange_is_ram
  - mm/memory_hotplug.c:offline_pages
```
**Symbols:**

```
ffffffff810d69e0-ffffffff810d6acb: walk_system_ram_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void *arg, int (*func)(long unsigned int, long unsigned int, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810f54a4)
Location: kernel/resource.c:452
Inline: True
Inline callers:
  - kernel/resource.c:page_is_ram
Direct callers:
  - arch/x86/mm/pat/memtype.c:pat_pagerange_is_ram
  - mm/memory_hotplug.c:offline_pages
```
**Symbols:**

```
ffffffff810f6400-ffffffff810f64eb: walk_system_ram_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void *arg, int (*func)(long unsigned int, long unsigned int, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff811018e4)
Location: kernel/resource.c:452
Inline: True
Inline callers:
  - kernel/resource.c:page_is_ram
Direct callers:
  - arch/x86/mm/pat/memtype.c:pat_pagerange_is_ram
  - mm/memory_hotplug.c:offline_pages
```
**Symbols:**

```
ffffffff81102850-ffffffff8110293b: walk_system_ram_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void *arg, int (*func)(long unsigned int, long unsigned int, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8110b034)
Location: kernel/resource.c:507
Inline: True
Inline callers:
  - kernel/resource.c:page_is_ram
Direct callers:
  - arch/x86/mm/pat/memtype.c:pat_pagerange_is_ram
  - kernel/dma/direct.c:dma_direct_all_ram_mapped
  - mm/memory_hotplug.c:offline_pages
```
**Symbols:**

```
ffffffff8110c180-ffffffff8110c26b: walk_system_ram_range (STB_GLOBAL)
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
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void *arg, int (*func)(long unsigned int, long unsigned int, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffff8000101012f0)
Location: kernel/resource.c:475
Inline: False
Direct callers:
  - kernel/resource.c:page_is_ram
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - fs/proc/kcore.c:kcore_update_ram
```
**Symbols:**

```
ffff8000101012f0-ffff8000101013dc: walk_system_ram_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void *arg, int (*func)(long unsigned int, long unsigned int, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c035d924)
Location: kernel/resource.c:475
Inline: False
Direct callers:
  - kernel/resource.c:page_is_ram
```
**Symbols:**

```
c035d924-c035da20: walk_system_ram_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void *arg, int (*func)(long unsigned int, long unsigned int, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c0000000001489f0)
Location: kernel/resource.c:475
Inline: False
Direct callers:
  - arch/powerpc/platforms/pseries/iommu.c:enable_ddw
  - kernel/resource.c:page_is_ram
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - fs/proc/kcore.c:kcore_update_ram
```
**Symbols:**

```
c0000000001489f0-c000000000148b40: walk_system_ram_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void *arg, int (*func)(long unsigned int, long unsigned int, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffe0000c8686)
Location: kernel/resource.c:475
Inline: False
Direct callers:
  - kernel/resource.c:page_is_ram
  - fs/proc/kcore.c:kcore_update_ram
```
**Symbols:**

```
ffffffe0000c8686-ffffffe0000c8722: walk_system_ram_range (STB_GLOBAL)
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
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void *arg, int (*func)(long unsigned int, long unsigned int, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a2e30)
Location: kernel/resource.c:475
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:pat_pagerange_is_ram
  - kernel/resource.c:page_is_ram
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - fs/proc/kcore.c:kcore_update_ram
```
**Symbols:**

```
ffffffff810a2e30-ffffffff810a2efe: walk_system_ram_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void *arg, int (*func)(long unsigned int, long unsigned int, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81091810)
Location: kernel/resource.c:475
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:pat_pagerange_is_ram
  - kernel/resource.c:page_is_ram
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - fs/proc/kcore.c:kcore_update_ram
```
**Symbols:**

```
ffffffff81091810-ffffffff810918de: walk_system_ram_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void *arg, int (*func)(long unsigned int, long unsigned int, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a2de0)
Location: kernel/resource.c:475
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:pat_pagerange_is_ram
  - kernel/resource.c:page_is_ram
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - fs/proc/kcore.c:kcore_update_ram
```
**Symbols:**

```
ffffffff810a2de0-ffffffff810a2eae: walk_system_ram_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void *arg, int (*func)(long unsigned int, long unsigned int, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810aae80)
Location: kernel/resource.c:475
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:pat_pagerange_is_ram
  - kernel/resource.c:page_is_ram
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - fs/proc/kcore.c:kcore_update_ram
```
**Symbols:**

```
ffffffff810aae80-ffffffff810aaf4e: walk_system_ram_range (STB_GLOBAL)
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
