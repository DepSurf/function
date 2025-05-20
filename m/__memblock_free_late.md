# Function: <code>__memblock_free_late</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __memblock_free_late(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81f8b4f5)
Location: mm/memblock.c:1414
Inline: False
Direct callers:
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
```
**Symbols:**

```
ffffffff81f8b4f5-ffffffff81f8b57b: __memblock_free_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __memblock_free_late(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81fb5139)
Location: mm/memblock.c:1415
Inline: False
Direct callers:
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
```
**Symbols:**

```
ffffffff81fb5139-ffffffff81fb51bf: __memblock_free_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __memblock_free_late(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ff1b20)
Location: mm/memblock.c:1415
Inline: False
Direct callers:
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
```
**Symbols:**

```
ffffffff81ff1b20-ffffffff81ff1ba0: __memblock_free_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __memblock_free_late(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff820d3f9b)
Location: mm/memblock.c:1437
Inline: False
Direct callers:
  - mm/memblock.c:memblock_discard
  - mm/memblock.c:memblock_discard
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
```
**Symbols:**

```
ffffffff820d3f9b-ffffffff820d4020: __memblock_free_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __memblock_free_late(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff826dca3e)
Location: mm/memblock.c:1455
Inline: False
Direct callers:
  - mm/memblock.c:memblock_discard
  - mm/memblock.c:memblock_discard
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
```
**Symbols:**

```
ffffffff826dca3e-ffffffff826dcac3: __memblock_free_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __memblock_free_late(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff82706f7d)
Location: mm/memblock.c:1465
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - mm/memblock.c:memblock_discard
  - mm/memblock.c:memblock_discard
```
**Symbols:**

```
ffffffff82706f7d-ffffffff82706ffb: __memblock_free_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __memblock_free_late(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828be16b)
Location: mm/memblock.c:1565
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - mm/memblock.c:memblock_discard
  - mm/memblock.c:memblock_discard
  - drivers/firmware/efi/apple-properties.c:map_properties
```
**Symbols:**

```
ffffffff828be16b-ffffffff828be224: __memblock_free_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __memblock_free_late(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828d733e)
Location: mm/memblock.c:1566
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - mm/memblock.c:memblock_discard
  - mm/memblock.c:memblock_discard
  - drivers/firmware/efi/apple-properties.c:map_properties
```
**Symbols:**

```
ffffffff828d733e-ffffffff828d73f7: __memblock_free_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __memblock_free_late(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828df7af)
Location: mm/memblock.c:1566
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - mm/memblock.c:memblock_discard
  - mm/memblock.c:memblock_discard
  - drivers/firmware/efi/apple-properties.c:map_properties
```
**Symbols:**

```
ffffffff828df7af-ffffffff828df868: __memblock_free_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __memblock_free_late(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff82cfcd6b)
Location: mm/memblock.c:1620
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - mm/memblock.c:memblock_discard
  - mm/memblock.c:memblock_discard
  - drivers/firmware/efi/memmap.c:__efi_memmap_free
  - drivers/firmware/efi/apple-properties.c:map_properties
```
**Symbols:**

```
ffffffff82cfcd6b-ffffffff82cfce24: __memblock_free_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __memblock_free_late(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff82fe97ee)
Location: mm/memblock.c:1582
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - mm/memblock.c:memblock_discard
  - mm/memblock.c:memblock_discard
  - drivers/firmware/efi/memmap.c:__efi_memmap_free
  - drivers/firmware/efi/apple-properties.c:map_properties
```
**Symbols:**

```
ffffffff82fe97ee-ffffffff82fe98a7: __memblock_free_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __memblock_free_late(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff831f3e97)
Location: mm/memblock.c:1583
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - kernel/dma/swiotlb.c:swiotlb_exit
  - mm/memblock.c:memblock_discard
  - mm/memblock.c:memblock_discard
  - drivers/firmware/efi/memmap.c:__efi_memmap_free
  - drivers/firmware/efi/apple-properties.c:map_properties
```
**Symbols:**

```
ffffffff831f3e97-ffffffff831f3f50: __memblock_free_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __memblock_free_late(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff832da1dd)
Location: mm/memblock.c:1606
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - mm/memblock.c:memblock_discard
  - mm/memblock.c:memblock_discard
  - mm/kfence/core.c:kfence_init_pool
  - drivers/firmware/efi/memmap.c:__efi_memmap_free
  - drivers/firmware/efi/apple-properties.c:map_properties
```
**Symbols:**

```
ffffffff832da1dd-ffffffff832da296: __memblock_free_late (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __memblock_free_late(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffff800011458820)
Location: mm/memblock.c:1566
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
```
**Symbols:**

```
ffff800011458820-ffff80001145890c: __memblock_free_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __memblock_free_late(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (c1532788)
Location: mm/memblock.c:1566
Inline: False
```
**Symbols:**

```
c1532788-c15328a0: __memblock_free_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __memblock_free_late(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (c00000000138206c)
Location: mm/memblock.c:1566
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
```
**Symbols:**

```
c00000000138206c-c000000001382184: __memblock_free_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __memblock_free_late(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffe000016ee2)
Location: mm/memblock.c:1566
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - mm/memblock.c:memblock_discard
  - mm/memblock.c:memblock_discard
```
**Symbols:**

```
ffffffe000016ee2-ffffffe000016f94: __memblock_free_late (STB_GLOBAL)
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
void __memblock_free_late(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828c8663)
Location: mm/memblock.c:1566
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - mm/memblock.c:memblock_discard
  - mm/memblock.c:memblock_discard
  - drivers/firmware/efi/apple-properties.c:map_properties
```
**Symbols:**

```
ffffffff828c8663-ffffffff828c871c: __memblock_free_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __memblock_free_late(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828c0d88)
Location: mm/memblock.c:1566
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - mm/memblock.c:memblock_discard
  - mm/memblock.c:memblock_discard
  - drivers/firmware/efi/apple-properties.c:map_properties
```
**Symbols:**

```
ffffffff828c0d88-ffffffff828c0e41: __memblock_free_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __memblock_free_late(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828db3e3)
Location: mm/memblock.c:1566
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - mm/memblock.c:memblock_discard
  - mm/memblock.c:memblock_discard
  - drivers/firmware/efi/apple-properties.c:map_properties
```
**Symbols:**

```
ffffffff828db3e3-ffffffff828db49c: __memblock_free_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __memblock_free_late(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828e0804)
Location: mm/memblock.c:1566
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - mm/memblock.c:memblock_discard
  - mm/memblock.c:memblock_discard
  - drivers/firmware/efi/apple-properties.c:map_properties
```
**Symbols:**

```
ffffffff828e0804-ffffffff828e08bd: __memblock_free_late (STB_GLOBAL)
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
