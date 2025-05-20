# Function: <code>arch_memremap_can_ram_remap</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool arch_memremap_can_ram_remap(resource_size_t phys_addr, long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81074330)
Location: arch/x86/mm/ioremap.c:644
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:phys_mem_access_encrypted
  - kernel/memremap.c:memremap
```
**Symbols:**

```
ffffffff81074330-ffffffff810743e0: arch_memremap_can_ram_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool arch_memremap_can_ram_remap(resource_size_t phys_addr, long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81076d30)
Location: arch/x86/mm/ioremap.c:644
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:phys_mem_access_encrypted
  - kernel/iomem.c:memremap
```
**Symbols:**

```
ffffffff81076d30-ffffffff81076de8: arch_memremap_can_ram_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool arch_memremap_can_ram_remap(resource_size_t phys_addr, long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff8107d3c0)
Location: arch/x86/mm/ioremap.c:652
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:phys_mem_access_encrypted
  - kernel/iomem.c:memremap
```
**Symbols:**

```
ffffffff8107d3c0-ffffffff8107d478: arch_memremap_can_ram_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool arch_memremap_can_ram_remap(resource_size_t phys_addr, long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81080c70)
Location: arch/x86/mm/ioremap.c:677
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:phys_mem_access_encrypted
  - kernel/iomem.c:memremap
```
**Symbols:**

```
ffffffff81080c70-ffffffff81080d21: arch_memremap_can_ram_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool arch_memremap_can_ram_remap(resource_size_t phys_addr, long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81081d30)
Location: arch/x86/mm/ioremap.c:699
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:phys_mem_access_encrypted
  - kernel/iomem.c:memremap
```
**Symbols:**

```
ffffffff81081d30-ffffffff81081de1: arch_memremap_can_ram_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool arch_memremap_can_ram_remap(resource_size_t phys_addr, long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81088e85)
Location: arch/x86/mm/ioremap.c:710
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:phys_mem_access_encrypted
Direct callers:
  - arch/x86/mm/ioremap.c:phys_mem_access_encrypted
  - kernel/iomem.c:try_ram_remap
```
**Symbols:**

```
ffffffff81088c80-ffffffff81088da8: arch_memremap_can_ram_remap.part.0 (STB_LOCAL)
ffffffff81088e50-ffffffff81088e7c: arch_memremap_can_ram_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool arch_memremap_can_ram_remap(resource_size_t phys_addr, long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810890c5)
Location: arch/x86/mm/ioremap.c:710
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:phys_mem_access_encrypted
Direct callers:
  - arch/x86/mm/ioremap.c:phys_mem_access_encrypted
  - kernel/iomem.c:try_ram_remap
```
**Symbols:**

```
ffffffff81088ec0-ffffffff81088fe8: arch_memremap_can_ram_remap.part.0 (STB_LOCAL)
ffffffff81089090-ffffffff810890bc: arch_memremap_can_ram_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool arch_memremap_can_ram_remap(resource_size_t phys_addr, long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81089d45)
Location: arch/x86/mm/ioremap.c:693
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:phys_mem_access_encrypted
Direct callers:
  - arch/x86/mm/ioremap.c:phys_mem_access_encrypted
  - kernel/iomem.c:memremap
```
**Symbols:**

```
ffffffff81089b40-ffffffff81089c68: arch_memremap_can_ram_remap.part.0 (STB_LOCAL)
ffffffff81089d10-ffffffff81089d3c: arch_memremap_can_ram_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool arch_memremap_can_ram_remap(resource_size_t phys_addr, long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81099215)
Location: arch/x86/mm/ioremap.c:738
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:phys_mem_access_encrypted
Direct callers:
  - arch/x86/mm/ioremap.c:phys_mem_access_encrypted
  - kernel/iomem.c:memremap
```
**Symbols:**

```
ffffffff81098fe0-ffffffff81099140: arch_memremap_can_ram_remap.part.0 (STB_LOCAL)
ffffffff81ca0f2c-ffffffff81ca0f4e: arch_memremap_can_ram_remap.part.0.cold (STB_LOCAL)
ffffffff810991e0-ffffffff8109920c: arch_memremap_can_ram_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool arch_memremap_can_ram_remap(resource_size_t phys_addr, long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810abe74)
Location: arch/x86/mm/ioremap.c:744
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:phys_mem_access_encrypted
  - kernel/iomem.c:try_ram_remap
```
**Symbols:**

```
ffffffff81e504f0-ffffffff81e50512: arch_memremap_can_ram_remap.cold (STB_LOCAL)
ffffffff810abe40-ffffffff810abfe0: arch_memremap_can_ram_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool arch_memremap_can_ram_remap(resource_size_t phys_addr, long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810c5bd0)
Location: arch/x86/mm/ioremap.c:753
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:phys_mem_access_encrypted
  - kernel/iomem.c:try_ram_remap
```
**Symbols:**

```
ffffffff810c5bd0-ffffffff810c5d8a: arch_memremap_can_ram_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool arch_memremap_can_ram_remap(resource_size_t phys_addr, long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810c9340)
Location: arch/x86/mm/ioremap.c:758
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:phys_mem_access_encrypted
  - kernel/iomem.c:try_ram_remap
```
**Symbols:**

```
ffffffff810c9340-ffffffff810c94fa: arch_memremap_can_ram_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool arch_memremap_can_ram_remap(resource_size_t phys_addr, long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810d17a0)
Location: arch/x86/mm/ioremap.c:758
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:phys_mem_access_encrypted
  - kernel/iomem.c:try_ram_remap
```
**Symbols:**

```
ffffffff810d17a0-ffffffff810d195a: arch_memremap_can_ram_remap (STB_GLOBAL)
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
In kernel/iomem.c (0)
Location: kernel/iomem.c:23
Inline: True
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
In kernel/iomem.c (0)
Location: kernel/iomem.c:23
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/iomem.c (0)
Location: kernel/iomem.c:23
Inline: True
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
In kernel/iomem.c (0)
Location: kernel/iomem.c:23
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
bool arch_memremap_can_ram_remap(resource_size_t phys_addr, long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81080d30)
Location: arch/x86/mm/ioremap.c:699
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:phys_mem_access_encrypted
  - kernel/iomem.c:memremap
```
**Symbols:**

```
ffffffff81080d30-ffffffff81080de1: arch_memremap_can_ram_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool arch_memremap_can_ram_remap(resource_size_t phys_addr, long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff8106fc80)
Location: arch/x86/mm/ioremap.c:699
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:phys_mem_access_encrypted
  - kernel/iomem.c:memremap
```
**Symbols:**

```
ffffffff8106fc80-ffffffff8106fd31: arch_memremap_can_ram_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool arch_memremap_can_ram_remap(resource_size_t phys_addr, long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81080ce0)
Location: arch/x86/mm/ioremap.c:699
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:phys_mem_access_encrypted
  - kernel/iomem.c:memremap
```
**Symbols:**

```
ffffffff81080ce0-ffffffff81080d91: arch_memremap_can_ram_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool arch_memremap_can_ram_remap(resource_size_t phys_addr, long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81082e00)
Location: arch/x86/mm/ioremap.c:699
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:phys_mem_access_encrypted
  - kernel/iomem.c:memremap
```
**Symbols:**

```
ffffffff81082e00-ffffffff81082eb1: arch_memremap_can_ram_remap (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
