# Function: <code>memblock_is_region_reserved</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool memblock_is_region_reserved(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8181ed8d)
Location: mm/memblock.c:1571
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - mm/cma.c:cma_declare_contiguous
```
**Symbols:**

```
ffffffff8181ed8d-ffffffff8181edb2: memblock_is_region_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool memblock_is_region_reserved(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff818992b2)
Location: mm/memblock.c:1628
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - mm/cma.c:cma_declare_contiguous
```
**Symbols:**

```
ffffffff818992b2-ffffffff818992d4: memblock_is_region_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool memblock_is_region_reserved(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff818cd96a)
Location: mm/memblock.c:1633
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - mm/cma.c:cma_declare_contiguous
  - drivers/firmware/efi/efi.c:efi_mem_reserve
```
**Symbols:**

```
ffffffff818cd96a-ffffffff818cd98c: memblock_is_region_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool memblock_is_region_reserved(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81904e37)
Location: mm/memblock.c:1668
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - mm/cma.c:cma_init_reserved_mem
  - mm/cma.c:cma_declare_contiguous
  - drivers/firmware/efi/efi.c:efi_mem_reserve
```
**Symbols:**

```
ffffffff81904e37-ffffffff81904e59: memblock_is_region_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool memblock_is_region_reserved(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8198edc9)
Location: mm/memblock.c:1686
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - mm/cma.c:cma_init_reserved_mem
  - mm/cma.c:cma_declare_contiguous
  - drivers/firmware/efi/efi.c:efi_mem_reserve
```
**Symbols:**

```
ffffffff8198edc9-ffffffff8198edeb: memblock_is_region_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool memblock_is_region_reserved(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff819eb690)
Location: mm/memblock.c:1696
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - mm/cma.c:cma_init_reserved_mem
  - mm/cma.c:cma_declare_contiguous
  - drivers/firmware/efi/efi.c:efi_mem_reserve
```
**Symbols:**

```
ffffffff819eb690-ffffffff819eb6b2: memblock_is_region_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool memblock_is_region_reserved(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a26926)
Location: mm/memblock.c:1797
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - mm/cma.c:cma_init_reserved_mem
  - mm/cma.c:cma_declare_contiguous
  - drivers/firmware/efi/efi.c:efi_mem_reserve
```
**Symbols:**

```
ffffffff81a26926-ffffffff81a26948: memblock_is_region_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool memblock_is_region_reserved(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a970df)
Location: mm/memblock.c:1798
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - mm/cma.c:cma_init_reserved_mem
  - mm/cma.c:cma_declare_contiguous
  - drivers/firmware/efi/efi.c:efi_mem_reserve
```
**Symbols:**

```
ffffffff81a970df-ffffffff81a97101: memblock_is_region_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool memblock_is_region_reserved(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ace94f)
Location: mm/memblock.c:1798
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - mm/cma.c:cma_init_reserved_mem
  - mm/cma.c:cma_declare_contiguous
  - drivers/firmware/efi/efi.c:efi_mem_reserve
```
**Symbols:**

```
ffffffff81ace94f-ffffffff81ace971: memblock_is_region_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool memblock_is_region_reserved(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81bc7316)
Location: mm/memblock.c:1850
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - drivers/firmware/efi/efi.c:efi_mem_reserve
```
**Symbols:**

```
ffffffff81bc7316-ffffffff81bc7338: memblock_is_region_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool memblock_is_region_reserved(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81c40038)
Location: mm/memblock.c:1795
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - drivers/firmware/efi/efi.c:efi_mem_reserve
```
**Symbols:**

```
ffffffff81c40038-ffffffff81c4005a: memblock_is_region_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool memblock_is_region_reserved(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81c320f9)
Location: mm/memblock.c:1796
Inline: False
Direct callers:
  - init/initramfs.c:reserve_initrd_mem
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - drivers/firmware/efi/efi.c:efi_mem_reserve
```
**Symbols:**

```
ffffffff81c320f9-ffffffff81c3211b: memblock_is_region_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool memblock_is_region_reserved(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81d50b03)
Location: mm/memblock.c:1824
Inline: False
Direct callers:
  - init/initramfs.c:reserve_initrd_mem
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - drivers/firmware/efi/efi.c:efi_mem_reserve
```
**Symbols:**

```
ffffffff81d50b03-ffffffff81d50b1b: memblock_is_region_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool memblock_is_region_reserved(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81f20d00)
Location: mm/memblock.c:1831
Inline: False
Direct callers:
  - init/initramfs.c:reserve_initrd_mem
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - drivers/firmware/efi/efi.c:efi_mem_reserve
```
**Symbols:**

```
ffffffff81f20d00-ffffffff81f20d22: memblock_is_region_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool memblock_is_region_reserved(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff820ca850)
Location: mm/memblock.c:1849
Inline: False
Direct callers:
  - init/initramfs.c:reserve_initrd_mem
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - drivers/firmware/efi/efi.c:efi_mem_reserve
```
**Symbols:**

```
ffffffff820ca850-ffffffff820ca8c4: memblock_is_region_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool memblock_is_region_reserved(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8214eae0)
Location: mm/memblock.c:1871
Inline: False
Direct callers:
  - init/initramfs.c:reserve_initrd_mem
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - drivers/firmware/efi/efi.c:efi_mem_reserve
```
**Symbols:**

```
ffffffff8214eae0-ffffffff8214eb54: memblock_is_region_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool memblock_is_region_reserved(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff82231950)
Location: mm/memblock.c:1929
Inline: False
Direct callers:
  - init/initramfs.c:reserve_initrd_mem
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - drivers/firmware/efi/efi.c:efi_mem_reserve
```
**Symbols:**

```
ffffffff82231950-ffffffff822319c4: memblock_is_region_reserved (STB_GLOBAL)
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
bool memblock_is_region_reserved(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffff80001031d3b8)
Location: mm/memblock.c:1798
Inline: False
Direct callers:
  - arch/arm64/kernel/setup.c:reserve_memblock_reserved_regions
  - arch/arm64/mm/init.c:arm64_memblock_init
  - arch/arm64/mm/init.c:arm64_memblock_init
  - mm/cma.c:cma_init_reserved_mem
  - mm/cma.c:cma_declare_contiguous
  - drivers/firmware/efi/efi.c:efi_mem_reserve
```
**Symbols:**

```
ffff80001031d3b8-ffff80001031d448: memblock_is_region_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool memblock_is_region_reserved(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (c0536efc)
Location: mm/memblock.c:1798
Inline: False
Direct callers:
  - arch/arm/mm/init.c:arm_memblock_init
  - mm/cma.c:cma_init_reserved_mem
  - mm/cma.c:cma_declare_contiguous
  - drivers/firmware/efi/efi.c:efi_mem_reserve
```
**Symbols:**

```
c0536efc-c0536f80: memblock_is_region_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool memblock_is_region_reserved(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (c0000000003f1210)
Location: mm/memblock.c:1798
Inline: False
Direct callers:
  - mm/cma.c:cma_init_reserved_mem
  - mm/cma.c:cma_declare_contiguous
```
**Symbols:**

```
c0000000003f1210-c0000000003f12a0: memblock_is_region_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool memblock_is_region_reserved(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffe000048b36)
Location: mm/memblock.c:1798
Inline: False
Direct callers:
  - mm/cma.c:cma_init_reserved_mem
  - mm/cma.c:cma_declare_contiguous
```
**Symbols:**

```
ffffffe000048b36-ffffffe000048b62: memblock_is_region_reserved (STB_GLOBAL)
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
bool memblock_is_region_reserved(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a6d7bf)
Location: mm/memblock.c:1798
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - mm/cma.c:cma_init_reserved_mem
  - mm/cma.c:cma_declare_contiguous
  - drivers/firmware/efi/efi.c:efi_mem_reserve
```
**Symbols:**

```
ffffffff81a6d7bf-ffffffff81a6d7e1: memblock_is_region_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool memblock_is_region_reserved(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81a29d06)
Location: mm/memblock.c:1798
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - mm/cma.c:cma_init_reserved_mem
  - mm/cma.c:cma_declare_contiguous
  - drivers/firmware/efi/efi.c:efi_mem_reserve
```
**Symbols:**

```
ffffffff81a29d06-ffffffff81a29d28: memblock_is_region_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool memblock_is_region_reserved(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ad9bcf)
Location: mm/memblock.c:1798
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - mm/cma.c:cma_init_reserved_mem
  - mm/cma.c:cma_declare_contiguous
  - drivers/firmware/efi/efi.c:efi_mem_reserve
```
**Symbols:**

```
ffffffff81ad9bcf-ffffffff81ad9bf1: memblock_is_region_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool memblock_is_region_reserved(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ae6085)
Location: mm/memblock.c:1798
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - mm/cma.c:cma_init_reserved_mem
  - mm/cma.c:cma_declare_contiguous
  - drivers/firmware/efi/efi.c:efi_mem_reserve
```
**Symbols:**

```
ffffffff81ae6085-ffffffff81ae60a7: memblock_is_region_reserved (STB_GLOBAL)
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
