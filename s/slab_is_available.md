# Function: <code>slab_is_available</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool slab_is_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811b4a80)
Location: mm/slab_common.c:757
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/xen/p2m.c:free_p2m_page
  - mm/nobootmem.c:__alloc_bootmem_node_nopanic
  - mm/nobootmem.c:__alloc_bootmem_low_node
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_virt_alloc_internal
  - mm/sparse.c:sparse_index_alloc
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
  - drivers/base/platform.c:early_platform_driver_probe
```
**Symbols:**

```
ffffffff811b4a80-ffffffff811b4a95: slab_is_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool slab_is_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811cdb40)
Location: mm/slab_common.c:765
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/realmode/init.c:reserve_real_mode
  - mm/nobootmem.c:__alloc_bootmem_low_node
  - mm/nobootmem.c:__alloc_bootmem_node
  - mm/nobootmem.c:__alloc_bootmem_node_nopanic
  - mm/memblock.c:memblock_virt_alloc_internal
  - mm/memblock.c:memblock_double_array
  - mm/sparse.c:sparse_index_alloc
  - drivers/base/platform.c:early_platform_driver_probe
```
**Symbols:**

```
ffffffff811cdb40-ffffffff811cdb55: slab_is_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool slab_is_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811ddc90)
Location: mm/slab_common.c:794
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/realmode/init.c:reserve_real_mode
  - mm/nobootmem.c:__alloc_bootmem_low_node
  - mm/nobootmem.c:__alloc_bootmem_node
  - mm/nobootmem.c:__alloc_bootmem_node_nopanic
  - mm/memblock.c:memblock_virt_alloc_internal
  - mm/memblock.c:memblock_double_array
  - mm/sparse.c:sparse_index_alloc
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
**Symbols:**

```
ffffffff811ddc90-ffffffff811ddca5: slab_is_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool slab_is_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811e79a0)
Location: mm/slab_common.c:865
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/realmode/init.c:reserve_real_mode
  - kernel/params.c:param_set_charp
  - mm/nobootmem.c:__alloc_bootmem_low_node
  - mm/nobootmem.c:__alloc_bootmem_node
  - mm/nobootmem.c:__alloc_bootmem_node_nopanic
  - mm/memblock.c:memblock_virt_alloc_internal
  - mm/memblock.c:memblock_double_array
  - mm/sparse.c:sparse_index_alloc
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
**Symbols:**

```
ffffffff811e79a0-ffffffff811e79b5: slab_is_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool slab_is_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811fdbe0)
Location: mm/slab_common.c:874
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/realmode/init.c:reserve_real_mode
  - kernel/params.c:param_set_charp
  - mm/nobootmem.c:__alloc_bootmem_low_node
  - mm/nobootmem.c:__alloc_bootmem_node
  - mm/nobootmem.c:__alloc_bootmem_node_nopanic
  - mm/memblock.c:memblock_virt_alloc_internal
  - mm/memblock.c:memblock_double_array
  - mm/sparse.c:sparse_index_alloc
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
**Symbols:**

```
ffffffff811fdbe0-ffffffff811fdbf5: slab_is_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool slab_is_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8121ef10)
Location: mm/slab_common.c:930
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/realmode/init.c:reserve_real_mode
  - kernel/params.c:param_set_charp
  - mm/nobootmem.c:__alloc_bootmem_low_node
  - mm/nobootmem.c:__alloc_bootmem_node
  - mm/nobootmem.c:__alloc_bootmem_node_nopanic
  - mm/nobootmem.c:___alloc_bootmem_nopanic
  - mm/memblock.c:memblock_virt_alloc_internal
  - mm/memblock.c:memblock_double_array
  - mm/sparse.c:sparse_index_alloc
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
**Symbols:**

```
ffffffff8121ef10-ffffffff8121ef25: slab_is_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool slab_is_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81231ef0)
Location: mm/slab_common.c:957
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/realmode/init.c:reserve_real_mode
  - kernel/params.c:param_set_charp
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_double_array
  - mm/sparse.c:sparse_index_alloc
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
**Symbols:**

```
ffffffff81231ef0-ffffffff81231f05: slab_is_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool slab_is_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff812423c0)
Location: mm/slab_common.c:984
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/realmode/init.c:reserve_real_mode
  - kernel/params.c:param_set_charp
  - mm/percpu.c:pcpu_mem_zalloc
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_double_array
  - mm/sparse.c:sparse_index_alloc
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
**Symbols:**

```
ffffffff812423c0-ffffffff812423d5: slab_is_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool slab_is_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff812508e0)
Location: mm/slab_common.c:1035
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/realmode/init.c:reserve_real_mode
  - kernel/params.c:param_set_charp
  - mm/percpu.c:pcpu_mem_zalloc
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_double_array
  - mm/sparse.c:sparse_index_alloc
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
  - security/security.c:security_add_hooks
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
**Symbols:**

```
ffffffff812508e0-ffffffff812508f5: slab_is_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool slab_is_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8127ef50)
Location: mm/slab_common.c:1035
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/realmode/init.c:reserve_real_mode
  - kernel/params.c:param_set_charp
  - mm/percpu.c:pcpu_mem_zalloc
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_double_array
  - mm/sparse.c:sparse_index_alloc
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
  - security/security.c:security_add_hooks
  - drivers/firmware/efi/memmap.c:__efi_memmap_free
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
**Symbols:**

```
ffffffff8127ef50-ffffffff8127ef65: slab_is_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool slab_is_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81288bc0)
Location: mm/slab_common.c:535
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/realmode/init.c:reserve_real_mode
  - kernel/params.c:param_set_charp
  - mm/percpu.c:pcpu_mem_zalloc
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_double_array
  - mm/sparse.c:sparse_index_alloc
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
  - security/security.c:security_add_hooks
  - drivers/firmware/efi/memmap.c:__efi_memmap_free
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
**Symbols:**

```
ffffffff81288bc0-ffffffff81288bd5: slab_is_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool slab_is_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8128e270)
Location: mm/slab_common.c:541
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/realmode/init.c:reserve_real_mode
  - kernel/params.c:param_set_charp
  - mm/percpu.c:pcpu_mem_zalloc
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_double_array
  - mm/sparse.c:sparse_index_alloc
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
  - security/security.c:security_add_hooks
  - drivers/firmware/efi/memmap.c:__efi_memmap_free
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
**Symbols:**

```
ffffffff8128e270-ffffffff8128e285: slab_is_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool slab_is_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff812ce120)
Location: mm/slab_common.c:545
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/realmode/init.c:reserve_real_mode
  - kernel/params.c:param_set_charp
  - mm/percpu.c:pcpu_mem_zalloc
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_double_array
  - mm/sparse.c:sparse_index_alloc
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
  - security/security.c:security_add_hooks
  - drivers/firmware/efi/memmap.c:__efi_memmap_free
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
**Symbols:**

```
ffffffff812ce120-ffffffff812ce135: slab_is_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool slab_is_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8132c1d0)
Location: mm/slab_common.c:536
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/realmode/init.c:reserve_real_mode
  - kernel/params.c:param_set_charp
  - mm/percpu.c:pcpu_mem_zalloc
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_double_array
  - mm/sparse.c:sparse_index_alloc
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
  - security/security.c:security_add_hooks
  - drivers/firmware/efi/memmap.c:__efi_memmap_free
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
**Symbols:**

```
ffffffff8132c1d0-ffffffff8132c1e9: slab_is_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool slab_is_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813a1ce0)
Location: mm/slab_common.c:525
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/platform/efi/memmap.c:__efi_memmap_free
  - arch/x86/platform/efi/memmap.c:efi_memmap_alloc
  - kernel/params.c:param_set_charp
  - mm/percpu.c:pcpu_mem_zalloc
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_double_array
  - mm/sparse.c:sparse_index_alloc
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
  - security/security.c:security_add_hooks
```
**Symbols:**

```
ffffffff813a1ce0-ffffffff813a1cf9: slab_is_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool slab_is_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813d50d0)
Location: mm/slab_common.c:525
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/platform/efi/memmap.c:__efi_memmap_free
  - arch/x86/platform/efi/memmap.c:efi_memmap_alloc
  - kernel/params.c:param_set_charp
  - mm/percpu.c:pcpu_mem_zalloc
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_double_array
  - mm/sparse.c:sparse_index_alloc
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
  - security/security.c:security_add_hooks
```
**Symbols:**

```
ffffffff813d50d0-ffffffff813d50e9: slab_is_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool slab_is_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813ff500)
Location: mm/slab_common.c:520
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/platform/efi/memmap.c:__efi_memmap_free
  - arch/x86/platform/efi/memmap.c:efi_memmap_alloc
  - kernel/params.c:param_set_charp
  - mm/percpu.c:pcpu_mem_zalloc
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_double_array
  - mm/sparse.c:sparse_index_alloc
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
  - security/security.c:security_add_hooks
```
**Symbols:**

```
ffffffff813ff500-ffffffff813ff519: slab_is_available (STB_GLOBAL)
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
bool slab_is_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffff8000102e79c8)
Location: mm/slab_common.c:1035
Inline: False
Direct callers:
  - kernel/params.c:param_set_charp
  - mm/percpu.c:pcpu_mem_zalloc
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_double_array
  - mm/sparse.c:sparse_index_alloc
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
  - security/security.c:security_add_hooks
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
**Symbols:**

```
ffff8000102e79c8-ffff8000102e79f0: slab_is_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool slab_is_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (c050bac4)
Location: mm/slab_common.c:1035
Inline: False
Direct callers:
  - kernel/params.c:param_set_charp
  - mm/percpu.c:pcpu_mem_zalloc
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_double_array
  - security/security.c:security_add_hooks
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
**Symbols:**

```
c050bac4-c050baf4: slab_is_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool slab_is_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (c0000000003a9840)
Location: mm/slab_common.c:1035
Inline: False
Direct callers:
  - arch/powerpc/kernel/rtas.c:rtas_call
  - arch/powerpc/kernel/rtas.c:__fetch_rtas_last_error
  - arch/powerpc/kernel/pci-common.c:pcibios_alloc_controller
  - arch/powerpc/mm/ioremap_64.c:__ioremap_caller
  - arch/powerpc/mm/ioremap_64.c:__ioremap_at
  - arch/powerpc/mm/book3s64/hash_pgtable.c:hash__map_kernel_page
  - arch/powerpc/mm/book3s64/radix_pgtable.c:__map_kernel_page
  - arch/powerpc/lib/alloc.c:zalloc_maybe_bootmem
  - arch/powerpc/sysdev/msi_bitmap.c:msi_bitmap_alloc
  - kernel/params.c:param_set_charp
  - mm/percpu.c:pcpu_mem_zalloc
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_double_array
  - mm/sparse.c:sparse_index_alloc
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
  - security/security.c:security_add_hooks
  - drivers/base/platform.c:early_platform_driver_probe
```
**Symbols:**

```
c0000000003a9840-c0000000003a9864: slab_is_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool slab_is_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffe0001fd4fa)
Location: mm/slab_common.c:1035
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_mem_zalloc
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_double_array
  - mm/sparse.c:sparse_index_alloc
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
  - security/security.c:security_add_hooks
  - drivers/base/platform.c:early_platform_driver_probe
```
**Symbols:**

```
ffffffe0001fd4fa-ffffffe0001fd522: slab_is_available (STB_GLOBAL)
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
bool slab_is_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81248f30)
Location: mm/slab_common.c:1035
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/realmode/init.c:reserve_real_mode
  - kernel/params.c:param_set_charp
  - mm/percpu.c:pcpu_mem_zalloc
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_double_array
  - mm/sparse.c:sparse_index_alloc
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
  - security/security.c:security_add_hooks
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
**Symbols:**

```
ffffffff81248f30-ffffffff81248f45: slab_is_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool slab_is_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8123bee0)
Location: mm/slab_common.c:1035
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:reserve_real_mode
  - kernel/params.c:param_set_charp
  - mm/percpu.c:pcpu_mem_zalloc
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_double_array
  - mm/sparse.c:sparse_index_alloc
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
  - security/security.c:security_add_hooks
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
**Symbols:**

```
ffffffff8123bee0-ffffffff8123bef5: slab_is_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool slab_is_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81246cd0)
Location: mm/slab_common.c:1035
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/realmode/init.c:reserve_real_mode
  - kernel/params.c:param_set_charp
  - mm/percpu.c:pcpu_mem_zalloc
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_double_array
  - mm/sparse.c:sparse_index_alloc
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
  - security/security.c:security_add_hooks
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
**Symbols:**

```
ffffffff81246cd0-ffffffff81246ce5: slab_is_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool slab_is_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81256500)
Location: mm/slab_common.c:1035
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/realmode/init.c:reserve_real_mode
  - kernel/params.c:param_set_charp
  - mm/percpu.c:pcpu_mem_zalloc
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_double_array
  - mm/sparse.c:sparse_index_alloc
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
  - security/security.c:security_add_hooks
  - drivers/base/platform.c:early_platform_driver_probe
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
**Symbols:**

```
ffffffff81256500-ffffffff81256515: slab_is_available (STB_GLOBAL)
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
