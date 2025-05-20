# Function: <code>arch_add_memory</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int arch_add_memory(int nid, u64 start, u64 size, bool for_device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81068d70)
Location: arch/x86/mm/init_64.c:690
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff81068d70-ffffffff81068e5c: arch_add_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int arch_add_memory(int nid, u64 start, u64 size, bool for_device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810689c0)
Location: arch/x86/mm/init_64.c:654
Inline: False
Direct callers:
  - kernel/memremap.c:devm_memremap_pages
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff810689c0-ffffffff81068aa3: arch_add_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int arch_add_memory(int nid, u64 start, u64 size, bool for_device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8106c610)
Location: arch/x86/mm/init_64.c:644
Inline: False
Direct callers:
  - kernel/memremap.c:devm_memremap_pages
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff8106c610-ffffffff8106c6f3: arch_add_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int arch_add_memory(int nid, u64 start, u64 size, bool want_memblock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8106ba20)
Location: arch/x86/mm/init_64.c:775
Inline: False
Direct callers:
  - kernel/memremap.c:devm_memremap_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff8106ba20-ffffffff8106baae: arch_add_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int arch_add_memory(int nid, u64 start, u64 size, bool want_memblock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81071210)
Location: arch/x86/mm/init_64.c:790
Inline: False
Direct callers:
  - kernel/memremap.c:devm_memremap_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
  - mm/hmm.c:hmm_devmem_pages_create
```
**Symbols:**

```
ffffffff81071210-ffffffff8107125b: arch_add_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int arch_add_memory(int nid, u64 start, u64 size, struct vmem_altmap *altmap, bool want_memblock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81073f90)
Location: arch/x86/mm/init_64.c:801
Inline: False
Direct callers:
  - kernel/memremap.c:devm_memremap_pages
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
  - mm/hmm.c:hmm_devmem_pages_create
```
**Symbols:**

```
ffffffff81073f90-ffffffff81073fe5: arch_add_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int arch_add_memory(int nid, u64 start, u64 size, struct vmem_altmap *altmap, bool want_memblock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81079e80)
Location: arch/x86/mm/init_64.c:794
Inline: False
Direct callers:
  - kernel/memremap.c:devm_memremap_pages
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff81079e80-ffffffff81079ed5: arch_add_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int arch_add_memory(int nid, u64 start, u64 size, struct mhp_restrictions *restrictions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107dbb0)
Location: arch/x86/mm/init_64.c:861
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memremap.c:devm_memremap_pages
```
**Symbols:**

```
ffffffff8107dbb0-ffffffff8107dbfa: arch_add_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int arch_add_memory(int nid, u64 start, u64 size, struct mhp_restrictions *restrictions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107ec40)
Location: arch/x86/mm/init_64.c:861
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
ffffffff8107ec40-ffffffff8107ec8a: arch_add_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int arch_add_memory(int nid, u64 start, u64 size, struct mhp_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810855e0)
Location: arch/x86/mm/init_64.c:869
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
ffffffff810855e0-ffffffff8108562d: arch_add_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int arch_add_memory(int nid, u64 start, u64 size, struct mhp_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81086690)
Location: arch/x86/mm/init_64.c:863
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memremap.c:pagemap_range
```
**Symbols:**

```
ffffffff81086690-ffffffff810866dd: arch_add_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int arch_add_memory(int nid, u64 start, u64 size, struct mhp_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81087410)
Location: arch/x86/mm/init_64.c:963
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memremap.c:pagemap_range
```
**Symbols:**

```
ffffffff81087410-ffffffff8108745e: arch_add_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int arch_add_memory(int nid, u64 start, u64 size, struct mhp_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81096740)
Location: arch/x86/mm/init_64.c:964
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memremap.c:pagemap_range
```
**Symbols:**

```
ffffffff81096740-ffffffff8109678e: arch_add_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int arch_add_memory(int nid, u64 start, u64 size, struct mhp_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810a9050)
Location: arch/x86/mm/init_64.c:964
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memremap.c:pagemap_range
```
**Symbols:**

```
ffffffff810a9050-ffffffff810a90aa: arch_add_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int arch_add_memory(int nid, u64 start, u64 size, struct mhp_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810c2750)
Location: arch/x86/mm/init_64.c:965
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memremap.c:pagemap_range
```
**Symbols:**

```
ffffffff810c2750-ffffffff810c27aa: arch_add_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int arch_add_memory(int nid, u64 start, u64 size, struct mhp_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810c5e30)
Location: arch/x86/mm/init_64.c:965
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memremap.c:pagemap_range
```
**Symbols:**

```
ffffffff810c5e30-ffffffff810c5e8a: arch_add_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int arch_add_memory(int nid, u64 start, u64 size, struct mhp_params *params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810ce280)
Location: arch/x86/mm/init_64.c:965
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:create_altmaps_and_memory_blocks
  - mm/memremap.c:pagemap_range
```
**Symbols:**

```
ffffffff810ce280-ffffffff810ce2da: arch_add_memory (STB_GLOBAL)
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
int arch_add_memory(int nid, u64 start, u64 size, struct mhp_restrictions *restrictions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/mmu.c (ffff8000100af5b8)
Location: arch/arm64/mm/mmu.c:1053
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffff8000100af5b8-ffff8000100af6dc: arch_add_memory (STB_GLOBAL)
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
int arch_add_memory(int nid, u64 start, u64 size, struct mhp_restrictions *restrictions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/mem.c (c000000000087640)
Location: arch/powerpc/mm/mem.c:128
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
c000000000087640-c000000000087734: arch_add_memory (STB_GLOBAL)
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
int arch_add_memory(int nid, u64 start, u64 size, struct mhp_restrictions *restrictions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107dc40)
Location: arch/x86/mm/init_64.c:861
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
ffffffff8107dc40-ffffffff8107dc8a: arch_add_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int arch_add_memory(int nid, u64 start, u64 size, struct mhp_restrictions *restrictions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8106cf40)
Location: arch/x86/mm/init_64.c:861
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
ffffffff8106cf40-ffffffff8106cf8a: arch_add_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int arch_add_memory(int nid, u64 start, u64 size, struct mhp_restrictions *restrictions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107dbf0)
Location: arch/x86/mm/init_64.c:861
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
ffffffff8107dbf0-ffffffff8107dc3a: arch_add_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int arch_add_memory(int nid, u64 start, u64 size, struct mhp_restrictions *restrictions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107fce0)
Location: arch/x86/mm/init_64.c:861
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
ffffffff8107fce0-ffffffff8107fd2a: arch_add_memory (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool want_memblock</code>
</li>
<li>
<b>Param removed. </b>
<code>bool for_device</code>
</li>
</ul>
</details>
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
<li>
<b>Param reordered. </b>
<code>nid, start, size, want_memblock</code> ➡️ <code>nid, start, size, altmap, want_memblock</code>
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
<code>struct mhp_restrictions *restrictions</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vmem_altmap *altmap</code>
</li>
<li>
<b>Param removed. </b>
<code>bool want_memblock</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mhp_params *params</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mhp_restrictions *restrictions</code>
</li>
</ul>
</details>
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
