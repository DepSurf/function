# Function: <code>iomem_map_sanity_check</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int iomem_map_sanity_check(resource_size_t addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81087930)
Location: kernel/resource.c:1430
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat.c:io_reserve_memtype
```
**Symbols:**

```
ffffffff81087930-ffffffff810879f1: iomem_map_sanity_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int iomem_map_sanity_check(resource_size_t addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108a830)
Location: kernel/resource.c:1500
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat.c:io_reserve_memtype
```
**Symbols:**

```
ffffffff8108a830-ffffffff8108a8f1: iomem_map_sanity_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int iomem_map_sanity_check(resource_size_t addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108f780)
Location: kernel/resource.c:1500
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat.c:io_reserve_memtype
```
**Symbols:**

```
ffffffff8108f780-ffffffff8108f841: iomem_map_sanity_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int iomem_map_sanity_check(resource_size_t addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108c720)
Location: kernel/resource.c:1500
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat.c:io_reserve_memtype
```
**Symbols:**

```
ffffffff8108c720-ffffffff8108c7e1: iomem_map_sanity_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int iomem_map_sanity_check(resource_size_t addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81093460)
Location: kernel/resource.c:1518
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat.c:io_reserve_memtype
```
**Symbols:**

```
ffffffff81093460-ffffffff81093521: iomem_map_sanity_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int iomem_map_sanity_check(resource_size_t addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/resource.c (0)
Location: kernel/resource.c:1500
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat.c:io_reserve_memtype
```
**Symbols:**

```
ffffffff8109700e-ffffffff8109702f: iomem_map_sanity_check.cold.17 (STB_LOCAL)
ffffffff81096e90-ffffffff81096f44: iomem_map_sanity_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int iomem_map_sanity_check(resource_size_t addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/resource.c (0)
Location: kernel/resource.c:1509
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat.c:io_reserve_memtype
```
**Symbols:**

```
ffffffff8109f33e-ffffffff8109f35f: iomem_map_sanity_check.cold.17 (STB_LOCAL)
ffffffff8109f1c0-ffffffff8109f274: iomem_map_sanity_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int iomem_map_sanity_check(resource_size_t addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/resource.c (0)
Location: kernel/resource.c:1532
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat.c:io_reserve_memtype
```
**Symbols:**

```
ffffffff810a39ef-ffffffff810a3a11: iomem_map_sanity_check.cold (STB_LOCAL)
ffffffff810a37f0-ffffffff810a389b: iomem_map_sanity_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int iomem_map_sanity_check(resource_size_t addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/resource.c (0)
Location: kernel/resource.c:1532
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat.c:io_reserve_memtype
```
**Symbols:**

```
ffffffff810a9fe3-ffffffff810aa005: iomem_map_sanity_check.cold (STB_LOCAL)
ffffffff810a9e20-ffffffff810a9ecb: iomem_map_sanity_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int iomem_map_sanity_check(resource_size_t addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/resource.c (0)
Location: kernel/resource.c:1537
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
```
**Symbols:**

```
ffffffff810b1b8e-ffffffff810b1bad: iomem_map_sanity_check.cold (STB_LOCAL)
ffffffff810b19c0-ffffffff810b1a6e: iomem_map_sanity_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int iomem_map_sanity_check(resource_size_t addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/resource.c (0)
Location: kernel/resource.c:1610
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
```
**Symbols:**

```
ffffffff81bdb877-ffffffff81bdb896: iomem_map_sanity_check.cold (STB_LOCAL)
ffffffff810ad280-ffffffff810ad32e: iomem_map_sanity_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int iomem_map_sanity_check(resource_size_t addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/resource.c (0)
Location: kernel/resource.c:1663
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
```
**Symbols:**

```
ffffffff81bcd969-ffffffff81bcd988: iomem_map_sanity_check.cold (STB_LOCAL)
ffffffff810ae480-ffffffff810ae52e: iomem_map_sanity_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int iomem_map_sanity_check(resource_size_t addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/resource.c (0)
Location: kernel/resource.c:1663
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
```
**Symbols:**

```
ffffffff81ca4351-ffffffff81ca4370: iomem_map_sanity_check.cold (STB_LOCAL)
ffffffff810c0000-ffffffff810c00ae: iomem_map_sanity_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int iomem_map_sanity_check(resource_size_t addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/resource.c (0)
Location: kernel/resource.c:1650
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
```
**Symbols:**

```
ffffffff81e53be2-ffffffff81e53c04: iomem_map_sanity_check.cold (STB_LOCAL)
ffffffff810d7560-ffffffff810d761f: iomem_map_sanity_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int iomem_map_sanity_check(resource_size_t addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810f6fb0)
Location: kernel/resource.c:1642
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
```
**Symbols:**

```
ffffffff810f6fb0-ffffffff810f70bd: iomem_map_sanity_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int iomem_map_sanity_check(resource_size_t addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff811033b0)
Location: kernel/resource.c:1642
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
```
**Symbols:**

```
ffffffff811033b0-ffffffff811034bd: iomem_map_sanity_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int iomem_map_sanity_check(resource_size_t addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8110cd10)
Location: kernel/resource.c:1697
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
```
**Symbols:**

```
ffffffff8110cd10-ffffffff8110ce1d: iomem_map_sanity_check (STB_GLOBAL)
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
int iomem_map_sanity_check(resource_size_t addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffff800010101ce8)
Location: kernel/resource.c:1532
Inline: False
```
**Symbols:**

```
ffff800010101ce8-ffff800010101e38: iomem_map_sanity_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int iomem_map_sanity_check(resource_size_t addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c035e098)
Location: kernel/resource.c:1532
Inline: False
```
**Symbols:**

```
c035e098-c035e1a8: iomem_map_sanity_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int iomem_map_sanity_check(resource_size_t addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c0000000001496f0)
Location: kernel/resource.c:1532
Inline: False
```
**Symbols:**

```
c0000000001496f0-c00000000014982c: iomem_map_sanity_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int iomem_map_sanity_check(resource_size_t addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffe0000c8d1c)
Location: kernel/resource.c:1532
Inline: False
```
**Symbols:**

```
ffffffe0000c8d1c-ffffffe0000c8de4: iomem_map_sanity_check (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int iomem_map_sanity_check(resource_size_t addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/resource.c (0)
Location: kernel/resource.c:1532
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat.c:io_reserve_memtype
```
**Symbols:**

```
ffffffff810a3903-ffffffff810a3925: iomem_map_sanity_check.cold (STB_LOCAL)
ffffffff810a3740-ffffffff810a37eb: iomem_map_sanity_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int iomem_map_sanity_check(resource_size_t addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/resource.c (0)
Location: kernel/resource.c:1532
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat.c:io_reserve_memtype
```
**Symbols:**

```
ffffffff810922e3-ffffffff81092305: iomem_map_sanity_check.cold (STB_LOCAL)
ffffffff81092120-ffffffff810921cb: iomem_map_sanity_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int iomem_map_sanity_check(resource_size_t addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/resource.c (0)
Location: kernel/resource.c:1532
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat.c:io_reserve_memtype
```
**Symbols:**

```
ffffffff810a38b3-ffffffff810a38d5: iomem_map_sanity_check.cold (STB_LOCAL)
ffffffff810a36f0-ffffffff810a379b: iomem_map_sanity_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int iomem_map_sanity_check(resource_size_t addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/resource.c (0)
Location: kernel/resource.c:1532
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat.c:io_reserve_memtype
```
**Symbols:**

```
ffffffff810ab971-ffffffff810ab993: iomem_map_sanity_check.cold (STB_LOCAL)
ffffffff810ab7a0-ffffffff810ab84a: iomem_map_sanity_check (STB_GLOBAL)
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
