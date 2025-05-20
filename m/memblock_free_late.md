# Function: <code>memblock_free_late</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff81f9e7f9)
Location: include/linux/bootmem.h:235
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff81fc9c7e)
Location: include/linux/bootmem.h:239
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff82006c65)
Location: include/linux/bootmem.h:240
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff820e7c9c)
Location: include/linux/bootmem.h:240
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff826f0a0c)
Location: include/linux/bootmem.h:252
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff826f8016)
Location: include/linux/bootmem.h:252
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff828a7a6f)
Location: include/linux/memblock.h:423
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
```
```
In kernel/dma/swiotlb.c (ffffffff828aef46)
Location: include/linux/memblock.h:423
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
```
```
In drivers/firmware/efi/apple-properties.c (ffffffff828f3de4)
Location: include/linux/memblock.h:423
Inline: True
Inline callers:
  - drivers/firmware/efi/apple-properties.c:map_properties
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff828c0183)
Location: include/linux/memblock.h:416
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
```
```
In kernel/dma/swiotlb.c (ffffffff828c7a75)
Location: include/linux/memblock.h:416
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
```
```
In drivers/firmware/efi/apple-properties.c (ffffffff8290f708)
Location: include/linux/memblock.h:416
Inline: True
Inline callers:
  - drivers/firmware/efi/apple-properties.c:map_properties
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff828c6625)
Location: include/linux/memblock.h:416
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
```
```
In kernel/dma/swiotlb.c (ffffffff828d0054)
Location: include/linux/memblock.h:416
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
```
```
In drivers/firmware/efi/apple-properties.c (ffffffff829190d7)
Location: include/linux/memblock.h:416
Inline: True
Inline callers:
  - drivers/firmware/efi/apple-properties.c:map_properties
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff82ce9883)
Location: include/linux/memblock.h:422
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
```
```
In kernel/dma/swiotlb.c (ffffffff82cf138b)
Location: include/linux/memblock.h:422
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
```
```
In drivers/firmware/efi/memmap.c (ffffffff82d2a4d7)
Location: include/linux/memblock.h:422
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:__efi_memmap_free
```
```
In drivers/firmware/efi/apple-properties.c (ffffffff82d2b547)
Location: include/linux/memblock.h:422
Inline: True
Inline callers:
  - drivers/firmware/efi/apple-properties.c:map_properties
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff82fd72ee)
Location: include/linux/memblock.h:455
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
```
```
In kernel/dma/swiotlb.c (ffffffff82fddd8a)
Location: include/linux/memblock.h:455
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
```
```
In drivers/firmware/efi/memmap.c (ffffffff83018bee)
Location: include/linux/memblock.h:455
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:__efi_memmap_free
```
```
In drivers/firmware/efi/apple-properties.c (ffffffff83019c8f)
Location: include/linux/memblock.h:455
Inline: True
Inline callers:
  - drivers/firmware/efi/apple-properties.c:map_properties
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff831e1d52)
Location: include/linux/memblock.h:455
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
```
```
In kernel/dma/swiotlb.c (ffffffff831e893b)
Location: include/linux/memblock.h:455
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_exit
```
```
In drivers/firmware/efi/memmap.c (ffffffff83223be6)
Location: include/linux/memblock.h:455
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:__efi_memmap_free
```
```
In drivers/firmware/efi/apple-properties.c (ffffffff83224cd7)
Location: include/linux/memblock.h:455
Inline: True
Inline callers:
  - drivers/firmware/efi/apple-properties.c:map_properties
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff832c5660)
Location: include/linux/memblock.h:456
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
```
```
In kernel/dma/swiotlb.c (ffffffff832cce69)
Location: include/linux/memblock.h:456
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
```
```
In mm/kfence/core.c (ffffffff832dcf22)
Location: include/linux/memblock.h:456
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_init_pool
```
```
In drivers/firmware/efi/memmap.c (ffffffff8330d9ec)
Location: include/linux/memblock.h:456
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:__efi_memmap_free
```
```
In drivers/firmware/efi/apple-properties.c (ffffffff8330eb0c)
Location: include/linux/memblock.h:456
Inline: True
Inline callers:
  - drivers/firmware/efi/apple-properties.c:map_properties
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void memblock_free_late(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff8348f26d)
Location: mm/memblock.c:1613
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - mm/memblock.c:memblock_discard
  - mm/memblock.c:memblock_discard
  - mm/kfence/core.c:kfence_init
  - drivers/firmware/efi/memmap.c:__efi_memmap_free
  - drivers/firmware/efi/apple-properties.c:map_properties
```
**Symbols:**

```
ffffffff8348f26d-ffffffff8348f337: memblock_free_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void memblock_free_late(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff83ec1760)
Location: mm/memblock.c:1631
Inline: False
Direct callers:
  - arch/x86/platform/efi/memmap.c:__efi_memmap_free
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - mm/memblock.c:memblock_discard
  - mm/memblock.c:memblock_discard
  - mm/kfence/core.c:kfence_init
  - drivers/firmware/efi/apple-properties.c:map_properties
```
**Symbols:**

```
ffffffff83ec1760-ffffffff83ec1837: memblock_free_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void memblock_free_late(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff836e6f70)
Location: mm/memblock.c:1653
Inline: False
Direct callers:
  - arch/x86/platform/efi/memmap.c:__efi_memmap_free
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - mm/memblock.c:memblock_discard
  - mm/memblock.c:memblock_discard
  - mm/kfence/core.c:kfence_init
  - drivers/firmware/efi/apple-properties.c:map_properties
```
**Symbols:**

```
ffffffff836e6f70-ffffffff836e7047: memblock_free_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void memblock_free_late(phys_addr_t base, phys_addr_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff83919520)
Location: mm/memblock.c:1711
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:ima_free_kexec_buffer
  - arch/x86/platform/efi/memmap.c:__efi_memmap_free
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - mm/memblock.c:memblock_discard
  - mm/memblock.c:memblock_discard
  - mm/kfence/core.c:kfence_init
  - mm/kfence/core.c:kfence_init
  - drivers/firmware/efi/apple-properties.c:map_properties
```
**Symbols:**

```
ffffffff83919520-ffffffff839195f7: memblock_free_late (STB_GLOBAL)
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
In kernel/dma/swiotlb.c (ffff800011447c7c)
Location: include/linux/memblock.h:416
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (c00000000136cd34)
Location: include/linux/memblock.h:416
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
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
In kernel/dma/swiotlb.c (ffffffe000009532)
Location: include/linux/memblock.h:416
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff828b15bd)
Location: include/linux/memblock.h:416
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
```
```
In kernel/dma/swiotlb.c (ffffffff828b8f05)
Location: include/linux/memblock.h:416
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
```
```
In drivers/firmware/efi/apple-properties.c (ffffffff828fe4dd)
Location: include/linux/memblock.h:416
Inline: True
Inline callers:
  - drivers/firmware/efi/apple-properties.c:map_properties
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff828a9742)
Location: include/linux/memblock.h:416
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
```
```
In kernel/dma/swiotlb.c (ffffffff828b1456)
Location: include/linux/memblock.h:416
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
```
```
In drivers/firmware/efi/apple-properties.c (ffffffff828f5d79)
Location: include/linux/memblock.h:416
Inline: True
Inline callers:
  - drivers/firmware/efi/apple-properties.c:map_properties
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff828c44bc)
Location: include/linux/memblock.h:416
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
```
```
In kernel/dma/swiotlb.c (ffffffff828cbc88)
Location: include/linux/memblock.h:416
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
```
```
In drivers/firmware/efi/apple-properties.c (ffffffff8291370c)
Location: include/linux/memblock.h:416
Inline: True
Inline callers:
  - drivers/firmware/efi/apple-properties.c:map_properties
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff828c7662)
Location: include/linux/memblock.h:416
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
```
```
In kernel/dma/swiotlb.c (ffffffff828d1082)
Location: include/linux/memblock.h:416
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
```
```
In drivers/firmware/efi/apple-properties.c (ffffffff8291a139)
Location: include/linux/memblock.h:416
Inline: True
Inline callers:
  - drivers/firmware/efi/apple-properties.c:map_properties
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
