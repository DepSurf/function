# Function: <code>ioremap_page_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/ioremap.c (ffffffff813eb060)
Location: lib/ioremap.c:123
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
```
**Symbols:**

```
ffffffff813eb060-ffffffff813eb413: ioremap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/ioremap.c (ffffffff814313e0)
Location: lib/ioremap.c:123
Inline: True
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
```
**Symbols:**

```
ffffffff814313e0-ffffffff8143176b: ioremap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/ioremap.c (ffffffff8144d650)
Location: lib/ioremap.c:123
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
```
**Symbols:**

```
ffffffff8144d650-ffffffff8144d9db: ioremap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/ioremap.c (ffffffff818ed300)
Location: lib/ioremap.c:156
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
```
**Symbols:**

```
ffffffff818ed300-ffffffff818ed687: ioremap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/ioremap.c (ffffffff81973410)
Location: lib/ioremap.c:159
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff81973410-ffffffff81973805: ioremap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/ioremap.c (ffffffff819cf8a0)
Location: lib/ioremap.c:159
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff819cf8a0-ffffffff819cfcc4: ioremap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/ioremap.c (ffffffff81a08ce0)
Location: lib/ioremap.c:199
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff81a08ce0-ffffffff81a0922c: ioremap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/ioremap.c (ffffffff81a78aa0)
Location: lib/ioremap.c:210
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff81a78aa0-ffffffff81a78bc4: ioremap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/ioremap.c (ffffffff81aafe50)
Location: lib/ioremap.c:210
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff81aafe50-ffffffff81aaff74: ioremap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/ioremap.c (ffffffff815e9c80)
Location: lib/ioremap.c:220
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff815e9c80-ffffffff815e9f60: ioremap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ioremap.c (ffffffff812b81b0)
Location: mm/ioremap.c:222
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff812b81b0-ffffffff812b87e1: ioremap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ioremap.c (ffffffff812bdca0)
Location: mm/ioremap.c:31
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff812bdca0-ffffffff812bdcb7: ioremap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812fe8d0)
Location: mm/vmalloc.c:314
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff812fe8d0-ffffffff812fe8ec: ioremap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff813659b0)
Location: mm/vmalloc.c:315
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff813659b0-ffffffff813659db: ioremap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff813e14c0)
Location: mm/vmalloc.c:318
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff813e14c0-ffffffff813e14eb: ioremap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81416230)
Location: mm/vmalloc.c:307
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff81416230-ffffffff8141625b: ioremap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81442d00)
Location: mm/vmalloc.c:307
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff81442d00-ffffffff81442d2b: ioremap_page_range (STB_GLOBAL)
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
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/ioremap.c (ffff800010d89490)
Location: lib/ioremap.c:210
Inline: False
Direct callers:
  - arch/arm64/mm/ioremap.c:__ioremap_caller
  - drivers/pci/pci.c:pci_remap_iospace
```
**Symbols:**

```
ffff800010d89490-ffff800010d89930: ioremap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/ioremap.c (c0e84268)
Location: lib/ioremap.c:210
Inline: False
Direct callers:
  - arch/arm/mm/ioremap.c:__arm_ioremap_pfn_caller
  - arch/arm/mm/ioremap.c:ioremap_page
  - drivers/pci/pci.c:pci_remap_iospace
```
**Symbols:**

```
c0e84268-c0e84440: ioremap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/ioremap.c (c000000000eca500)
Location: lib/ioremap.c:210
Inline: False
Direct callers:
  - arch/powerpc/mm/ioremap.c:do_ioremap
  - arch/powerpc/mm/ioremap_64.c:__ioremap_at
```
**Symbols:**

```
c000000000eca500-c000000000eca704: ioremap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/ioremap.c (ffffffe0008b30a6)
Location: lib/ioremap.c:210
Inline: False
Direct callers:
  - arch/riscv/mm/ioremap.c:ioremap
  - drivers/pci/pci.c:pci_remap_iospace
```
**Symbols:**

```
ffffffe0008b30a6-ffffffe0008b3290: ioremap_page_range (STB_GLOBAL)
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
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/ioremap.c (ffffffff81a4eca0)
Location: lib/ioremap.c:210
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff81a4eca0-ffffffff81a4edc4: ioremap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/ioremap.c (ffffffff81a0bda0)
Location: lib/ioremap.c:210
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff81a0bda0-ffffffff81a0bec4: ioremap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/ioremap.c (ffffffff81abb090)
Location: lib/ioremap.c:210
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff81abb090-ffffffff81abb1b4: ioremap_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ioremap_page_range(long unsigned int addr, long unsigned int end, phys_addr_t phys_addr, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/ioremap.c (ffffffff81ac74e0)
Location: lib/ioremap.c:210
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff81ac74e0-ffffffff81ac75fe: ioremap_page_range (STB_GLOBAL)
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
