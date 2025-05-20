# Function: <code>memcpy_toio</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811c1e79)
Location: arch/x86/include/asm/io.h:223
Inline: True
Inline callers:
  - mm/memory.c:generic_access_phys
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8146d4ed)
Location: arch/x86/include/asm/io.h:223
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_write
```
```
In drivers/acpi/apei/ghes.c (ffffffff814b55fb)
Location: arch/x86/include/asm/io.h:223
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff8153290b)
Location: arch/x86/include/asm/io.h:223
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
```
In drivers/misc/sram.c (ffffffff8157981a)
Location: arch/x86/include/asm/io.h:223
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_write
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811dd9af)
Location: arch/x86/include/asm/io.h:223
Inline: True
Inline callers:
  - mm/memory.c:generic_access_phys
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff814bb80a)
Location: arch/x86/include/asm/io.h:223
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_write
```
```
In drivers/acpi/apei/ghes.c (ffffffff81504f7e)
Location: arch/x86/include/asm/io.h:223
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
```
```
In drivers/iommu/amd_iommu_init.c (0)
Location: arch/x86/include/asm/io.h:223
Inline: True
```
```
In drivers/misc/sram.c (ffffffff815ce8de)
Location: arch/x86/include/asm/io.h:223
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_write
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811ed4df)
Location: arch/x86/include/asm/io.h:223
Inline: True
Inline callers:
  - mm/memory.c:generic_access_phys
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff814dd80a)
Location: arch/x86/include/asm/io.h:223
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_write
```
```
In drivers/acpi/apei/ghes.c (ffffffff8152916e)
Location: arch/x86/include/asm/io.h:223
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
```
```
In drivers/iommu/amd_iommu_init.c (0)
Location: arch/x86/include/asm/io.h:223
Inline: True
```
```
In drivers/misc/sram.c (ffffffff815fb53e)
Location: arch/x86/include/asm/io.h:223
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_write
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: arch/x86/include/asm/io.h:247
Inline: False
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: arch/x86/include/asm/io.h:247
Inline: False
```
```
In drivers/acpi/apei/ghes.c (0)
Location: arch/x86/include/asm/io.h:247
Inline: False
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff815cacc6)
Location: arch/x86/include/asm/io.h:247
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
```
```
In drivers/misc/sram.c (0)
Location: arch/x86/include/asm/io.h:247
Inline: False
```
**Symbols:**

```
ffffffff815cacc6-ffffffff815cacd2: memcpy_toio.constprop.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: include/asm-generic/io.h:1005
Inline: False
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/asm-generic/io.h:1005
Inline: False
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/asm-generic/io.h:1005
Inline: False
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff81631a86)
Location: include/asm-generic/io.h:1005
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
```
```
In drivers/misc/sram.c (0)
Location: include/asm-generic/io.h:1005
Inline: False
```
**Symbols:**

```
ffffffff81631a86-ffffffff81631a92: memcpy_toio.constprop.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: include/asm-generic/io.h:1130
Inline: False
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/asm-generic/io.h:1130
Inline: False
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/asm-generic/io.h:1130
Inline: False
```
```
In drivers/char/tpm/tpm_crb.c (0)
Location: include/asm-generic/io.h:1130
Inline: False
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff8166bfd7)
Location: include/asm-generic/io.h:1130
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
Direct callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
```
```
In drivers/misc/sram.c (0)
Location: include/asm-generic/io.h:1130
Inline: False
```
**Symbols:**

```
ffffffff8166c5f6-ffffffff8166c5fd: memcpy_toio.constprop.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void memcpy_toio(volatile void *to, const void *from, size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/iomem.c (ffffffff8150e5f0)
Location: arch/x86/lib/iomem.c:43
Inline: False
Direct callers:
  - mm/memory.c:generic_access_phys
  - drivers/video/fbdev/core/fbmem.c:fb_write
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/misc/sram.c:sram_write
```
**Symbols:**

```
ffffffff8150e5f0-ffffffff8150e638: memcpy_toio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void memcpy_toio(volatile void *to, const void *from, size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/iomem.c (ffffffff8153cc60)
Location: arch/x86/lib/iomem.c:43
Inline: False
Direct callers:
  - mm/memory.c:generic_access_phys
  - drivers/video/fbdev/core/fbmem.c:fb_write
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/misc/sram.c:sram_write
```
**Symbols:**

```
ffffffff8153cc60-ffffffff8153cca7: memcpy_toio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void memcpy_toio(volatile void *to, const void *from, size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/iomem.c (ffffffff8155da70)
Location: arch/x86/lib/iomem.c:43
Inline: False
Direct callers:
  - mm/memory.c:generic_access_phys
  - drivers/video/fbdev/core/fbmem.c:fb_write
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/misc/sram.c:sram_write
```
**Symbols:**

```
ffffffff8155da70-ffffffff8155dab7: memcpy_toio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void memcpy_toio(volatile void *to, const void *from, size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/iomem.c (ffffffff815e74e0)
Location: arch/x86/lib/iomem.c:43
Inline: False
Direct callers:
  - mm/memory.c:generic_access_phys
  - drivers/video/fbdev/core/fbmem.c:fb_write
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/iommu/amd/init.c:enable_iommus_v2
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:iommu_init_ga_log
  - drivers/iommu/amd/init.c:iommu_init_ga_log
  - drivers/iommu/amd/init.c:iommu_enable_event_buffer
  - drivers/iommu/amd/init.c:iommu_enable_command_buffer
  - drivers/iommu/amd/init.c:iommu_set_device_table
  - drivers/misc/sram.c:sram_write
```
**Symbols:**

```
ffffffff815e74e0-ffffffff815e7527: memcpy_toio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void memcpy_toio(volatile void *to, const void *from, size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/iomem.c (ffffffff8160c6e0)
Location: arch/x86/lib/iomem.c:43
Inline: False
Direct callers:
  - mm/memory.c:generic_access_phys
  - drivers/video/fbdev/core/fbmem.c:fb_write
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/iommu/amd/init.c:enable_iommus_v2
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_ga_log
  - drivers/iommu/amd/init.c:iommu_init_ga_log
  - drivers/iommu/amd/init.c:iommu_enable_event_buffer
  - drivers/iommu/amd/init.c:iommu_enable_command_buffer
  - drivers/misc/sram.c:sram_write
```
**Symbols:**

```
ffffffff8160c6e0-ffffffff8160c727: memcpy_toio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void memcpy_toio(volatile void *to, const void *from, size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/iomem.c (ffffffff815ef980)
Location: arch/x86/lib/iomem.c:43
Inline: False
Direct callers:
  - mm/memory.c:generic_access_phys
  - drivers/video/fbdev/core/fbmem.c:fb_write
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/iommu/amd/init.c:enable_iommus_v2
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_enable_event_buffer
  - drivers/iommu/amd/init.c:iommu_enable_command_buffer
  - drivers/misc/sram.c:sram_write
```
**Symbols:**

```
ffffffff815ef980-ffffffff815ef9c7: memcpy_toio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void memcpy_toio(volatile void *to, const void *from, size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/iomem.c (ffffffff8165ca90)
Location: arch/x86/lib/iomem.c:43
Inline: False
Direct callers:
  - mm/memory.c:generic_access_phys
  - drivers/video/fbdev/core/fbmem.c:fb_write
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/iommu/amd/init.c:enable_iommus_v2
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_enable_event_buffer
  - drivers/iommu/amd/init.c:iommu_enable_command_buffer
  - drivers/misc/sram.c:sram_write
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments
```
**Symbols:**

```
ffffffff8165ca90-ffffffff8165cad7: memcpy_toio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void memcpy_toio(volatile void *to, const void *from, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/iomem.c (ffffffff81775da0)
Location: arch/x86/lib/iomem.c:97
Inline: True
Direct callers:
  - mm/memory.c:generic_access_phys
  - drivers/video/fbdev/core/fbmem.c:fb_write
  - drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_handler
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/iommu/amd/init.c:enable_iommus_v2
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_enable_event_buffer
  - drivers/iommu/amd/init.c:iommu_enable_command_buffer
  - drivers/misc/sram.c:sram_write
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments
```
**Symbols:**

```
ffffffff81775da0-ffffffff81775e69: memcpy_toio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void memcpy_toio(volatile void *to, const void *from, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/iomem.c (ffffffff818a6af0)
Location: arch/x86/lib/iomem.c:102
Inline: True
Direct callers:
  - mm/memory.c:generic_access_phys
  - drivers/video/fbdev/core/fbmem.c:fb_write
  - drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_handler
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:enable_iommus_v2
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_enable_event_buffer
  - drivers/iommu/amd/init.c:iommu_enable_command_buffer
  - drivers/iommu/amd/init.c:iommu_set_device_table
  - drivers/misc/sram.c:sram_write
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments
```
**Symbols:**

```
ffffffff818a6af0-ffffffff818a6bb9: memcpy_toio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void memcpy_toio(volatile void *to, const void *from, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/iomem.c (ffffffff818e9960)
Location: arch/x86/lib/iomem.c:102
Inline: True
Direct callers:
  - mm/memory.c:generic_access_phys
  - drivers/video/fbdev/core/fb_io_fops.c:fb_io_write
  - drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_handler
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:enable_iommus_v2
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_enable_event_buffer
  - drivers/iommu/amd/init.c:iommu_enable_command_buffer
  - drivers/iommu/amd/init.c:iommu_set_device_table
  - drivers/misc/sram.c:sram_write
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments
```
**Symbols:**

```
ffffffff818e9960-ffffffff818e9a29: memcpy_toio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void memcpy_toio(volatile void *to, const void *from, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/iomem.c (ffffffff81930e00)
Location: arch/x86/lib/iomem.c:102
Inline: True
Direct callers:
  - mm/memory.c:generic_access_phys
  - drivers/video/fbdev/core/fb_io_fops.c:fb_io_write
  - drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_handler
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_enable_event_buffer
  - drivers/iommu/amd/init.c:iommu_enable_command_buffer
  - drivers/iommu/amd/init.c:iommu_set_device_table
  - drivers/misc/sram.c:sram_write
  - drivers/gpu/drm/drm_cache.c:memcpy_fallback
  - drivers/gpu/drm/drm_cache.c:memcpy_fallback
  - drivers/gpu/drm/drm_format_helper.c:drm_fb_memcpy
  - drivers/gpu/drm/drm_fbdev_generic.c:drm_fbdev_generic_damage_blit_real
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments
```
**Symbols:**

```
ffffffff81930e00-ffffffff81930ec9: memcpy_toio (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/mach-omap2/control.c (c03354ec)
Location: arch/arm/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents
  - arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents
  - arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents
  - arch/arm/mach-omap2/control.c:omap3_save_scratchpad_contents
```
```
In arch/arm/mach-shmobile/pm-rcar-gen2.c (c151a420)
Location: arch/arm/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/arm/mach-shmobile/pm-rcar-gen2.c:rcar_gen2_pm_init
  - arch/arm/mach-shmobile/pm-rcar-gen2.c:rcar_gen2_pm_init
```
```
In fs/pstore/ram_core.c (c06d7734)
Location: arch/arm/include/asm/io.h:334
Inline: True
Inline callers:
  - fs/pstore/ram_core.c:persistent_ram_write
  - fs/pstore/ram_core.c:persistent_ram_write
```
```
In drivers/video/fbdev/core/fbmem.c (c08c89a8)
Location: arch/arm/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_write
```
```
In drivers/dma/ti/edma.c (c092ca64)
Location: arch/arm/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/dma/ti/edma.c:edma_pm_resume
  - drivers/dma/ti/edma.c:edma_probe
  - drivers/dma/ti/edma.c:edma_execute
  - drivers/dma/ti/edma.c:edma_free_slot
  - drivers/dma/ti/edma.c:edma_alloc_slot
```
```
In drivers/misc/sram.c (c0a09760)
Location: arch/arm/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_write
```
```
In drivers/mtd/maps/map_funcs.c (c0a99634)
Location: arch/arm/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/mtd/maps/map_funcs.c:simple_map_copy_to
```
```
In drivers/firmware/arm_scmi/driver.c (c0c379d0)
Location: arch/arm/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/driver.c:scmi_tx_prepare
```
```
In sound/core/memory.c (c0c84c44)
Location: arch/arm/include/asm/io.h:334
Inline: True
Inline callers:
  - sound/core/memory.c:copy_from_user_toio
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003c6b18)
Location: arch/powerpc/include/asm/io-defs.h:60
Inline: True
Inline callers:
  - mm/memory.c:generic_access_phys
```
```
In drivers/video/fbdev/core/fbmem.c (c0000000008a5994)
Location: arch/powerpc/include/asm/io-defs.h:60
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_write
```
```
In drivers/misc/sram.c (c0000000009ca10c)
Location: arch/powerpc/include/asm/io-defs.h:60
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_write
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
In drivers/misc/sram.c (ffffffe0005a29e2)
Location: include/asm-generic/io.h:1115
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_write
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
void memcpy_toio(volatile void *to, const void *from, size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/iomem.c (ffffffff81556060)
Location: arch/x86/lib/iomem.c:43
Inline: False
Direct callers:
  - mm/memory.c:generic_access_phys
  - drivers/video/fbdev/core/fbmem.c:fb_write
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/misc/sram.c:sram_write
```
**Symbols:**

```
ffffffff81556060-ffffffff815560a7: memcpy_toio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void memcpy_toio(volatile void *to, const void *from, size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/iomem.c (ffffffff81546520)
Location: arch/x86/lib/iomem.c:43
Inline: False
Direct callers:
  - mm/memory.c:generic_access_phys
  - drivers/video/fbdev/core/fbmem.c:fb_write
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/misc/sram.c:sram_write
```
**Symbols:**

```
ffffffff81546520-ffffffff81546567: memcpy_toio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void memcpy_toio(volatile void *to, const void *from, size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/iomem.c (ffffffff81551da0)
Location: arch/x86/lib/iomem.c:43
Inline: False
Direct callers:
  - mm/memory.c:generic_access_phys
  - drivers/video/fbdev/core/fbmem.c:fb_write
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/misc/sram.c:sram_write
  - drivers/i2c/busses/i2c-amd-mp2-pci.c:amd_mp2_rw
```
**Symbols:**

```
ffffffff81551da0-ffffffff81551de7: memcpy_toio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void memcpy_toio(volatile void *to, const void *from, size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/iomem.c (ffffffff8156bc30)
Location: arch/x86/lib/iomem.c:43
Inline: False
Direct callers:
  - mm/memory.c:generic_access_phys
  - drivers/video/fbdev/core/fbmem.c:fb_write
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/misc/sram.c:sram_write
```
**Symbols:**

```
ffffffff8156bc30-ffffffff8156bc77: memcpy_toio (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
