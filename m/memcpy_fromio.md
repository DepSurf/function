# Function: <code>memcpy_fromio</code>

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
In arch/x86/kernel/tboot.c (ffffffff8103df5e)
Location: arch/x86/include/asm/io.h:217
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/tboot.c:tboot_log_read
```
```
In arch/x86/platform/efi/efi-bgrt.c (ffffffff81f7b128)
Location: arch/x86/include/asm/io.h:217
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi-bgrt.c:efi_bgrt_init
  - arch/x86/platform/efi/efi-bgrt.c:efi_bgrt_init
```
```
In mm/memory.c (ffffffff811c1e3d)
Location: arch/x86/include/asm/io.h:217
Inline: True
Inline callers:
  - mm/memory.c:generic_access_phys
```
```
In drivers/pci/pci-sysfs.c (ffffffff8143bc9e)
Location: arch/x86/include/asm/io.h:217
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8146d760)
Location: arch/x86/include/asm/io.h:217
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_read
```
```
In drivers/acpi/apei/ghes.c (ffffffff814b54d7)
Location: arch/x86/include/asm/io.h:217
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
```
```
In drivers/char/tpm/tpm_acpi.c (ffffffff81528207)
Location: arch/x86/include/asm/io.h:217
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_acpi.c:read_log
```
```
In drivers/misc/sram.c (ffffffff8157987a)
Location: arch/x86/include/asm/io.h:217
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_read
```
```
In drivers/firmware/dmi_scan.c (ffffffff81fb5a64)
Location: arch/x86/include/asm/io.h:217
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
```
```
In drivers/firmware/efi/esrt.c (ffffffff81fb6cb4)
Location: arch/x86/include/asm/io.h:217
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
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
In arch/x86/kernel/tboot.c (ffffffff8103dd7f)
Location: arch/x86/include/asm/io.h:217
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/tboot.c:tboot_log_read
```
```
In mm/memory.c (ffffffff811dd973)
Location: arch/x86/include/asm/io.h:217
Inline: True
Inline callers:
  - mm/memory.c:generic_access_phys
```
```
In drivers/pci/pci-sysfs.c (ffffffff81487b3e)
Location: arch/x86/include/asm/io.h:217
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff814bba8b)
Location: arch/x86/include/asm/io.h:217
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_read
```
```
In drivers/acpi/apei/ghes.c (ffffffff81504e57)
Location: arch/x86/include/asm/io.h:217
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
```
```
In drivers/char/tpm/tpm_acpi.c (ffffffff8157b257)
Location: arch/x86/include/asm/io.h:217
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_acpi.c:read_log
```
```
In drivers/misc/sram.c (ffffffff815ce93e)
Location: arch/x86/include/asm/io.h:217
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_read
```
```
In drivers/firmware/dmi_scan.c (ffffffff81fe2f67)
Location: arch/x86/include/asm/io.h:217
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
```
```
In drivers/firmware/efi/esrt.c (ffffffff81fe479c)
Location: arch/x86/include/asm/io.h:217
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
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
In arch/x86/kernel/tboot.c (ffffffff8103d63e)
Location: arch/x86/include/asm/io.h:217
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/tboot.c:tboot_log_read
```
```
In mm/memory.c (ffffffff811ed4a3)
Location: arch/x86/include/asm/io.h:217
Inline: True
Inline callers:
  - mm/memory.c:generic_access_phys
```
```
In drivers/pci/pci-sysfs.c (ffffffff814a931e)
Location: arch/x86/include/asm/io.h:217
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff814dda8b)
Location: arch/x86/include/asm/io.h:217
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_read
```
```
In drivers/acpi/apei/ghes.c (ffffffff81529047)
Location: arch/x86/include/asm/io.h:217
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
```
```
In drivers/char/tpm/tpm_acpi.c (ffffffff815a76ce)
Location: arch/x86/include/asm/io.h:217
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_acpi.c:tpm_read_log_acpi
```
```
In drivers/misc/sram.c (ffffffff815fb59e)
Location: arch/x86/include/asm/io.h:217
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_read
```
```
In drivers/firmware/dmi_scan.c (ffffffff82020d36)
Location: arch/x86/include/asm/io.h:217
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void memcpy_fromio(void *dst, const volatile void *src, size_t count);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff8103b748)
Location: arch/x86/include/asm/io.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/tboot.c:tboot_log_read
```
```
In mm/memory.c (ffffffff811f84b2)
Location: arch/x86/include/asm/io.h:233
Inline: True
Inline callers:
  - mm/memory.c:generic_access_phys
  - mm/memory.c:generic_access_phys
```
```
In drivers/pci/pci-sysfs.c (ffffffff814b2b06)
Location: arch/x86/include/asm/io.h:233
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff814ea0e2)
Location: arch/x86/include/asm/io.h:233
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_write
  - drivers/video/fbdev/core/fbmem.c:fb_read
```
```
In drivers/acpi/apei/ghes.c (ffffffff8153c611)
Location: arch/x86/include/asm/io.h:233
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
```
```
In drivers/char/tpm/tpm_acpi.c (ffffffff815bd35b)
Location: arch/x86/include/asm/io.h:233
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_acpi.c:tpm_read_log_acpi
```
```
In drivers/misc/sram.c (ffffffff8160f2fe)
Location: arch/x86/include/asm/io.h:233
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_write
  - drivers/misc/sram.c:sram_read
```
```
In drivers/firmware/dmi_scan.c (ffffffff81783f8b)
Location: arch/x86/include/asm/io.h:233
Inline: False
Direct callers:
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
```
**Symbols:**

```
ffffffff81783f8b-ffffffff81783f95: memcpy_fromio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void memcpy_fromio(void *buffer, const volatile void *addr, size_t size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff8103e168)
Location: include/asm-generic/io.h:987
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/tboot.c:tboot_log_read
```
```
In mm/memory.c (ffffffff81210672)
Location: include/asm-generic/io.h:987
Inline: True
Inline callers:
  - mm/memory.c:generic_access_phys
  - mm/memory.c:generic_access_phys
```
```
In drivers/pci/pci-sysfs.c (ffffffff814f21f6)
Location: include/asm-generic/io.h:987
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8151ec58)
Location: include/asm-generic/io.h:987
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_write
  - drivers/video/fbdev/core/fbmem.c:fb_read
```
```
In drivers/acpi/apei/ghes.c (ffffffff8159f136)
Location: include/asm-generic/io.h:987
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
```
```
In drivers/char/tpm/tpm_acpi.c (ffffffff816237eb)
Location: include/asm-generic/io.h:987
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_acpi.c:tpm_read_log_acpi
```
```
In drivers/misc/sram.c (ffffffff81677b7e)
Location: include/asm-generic/io.h:987
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_write
  - drivers/misc/sram.c:sram_read
```
```
In drivers/firmware/dmi_scan.c (ffffffff817fa35b)
Location: include/asm-generic/io.h:987
Inline: False
Direct callers:
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
```
**Symbols:**

```
ffffffff817fa35b-ffffffff817fa365: memcpy_fromio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void memcpy_fromio(void *buffer, const volatile void *addr, size_t size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff8103f6ff)
Location: include/asm-generic/io.h:1112
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/tboot.c:tboot_log_read
```
```
In mm/memory.c (ffffffff81231076)
Location: include/asm-generic/io.h:1112
Inline: True
Inline callers:
  - mm/memory.c:generic_access_phys
  - mm/memory.c:generic_access_phys
```
```
In drivers/pci/pci-sysfs.c (ffffffff8152249e)
Location: include/asm-generic/io.h:1112
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8155482e)
Location: include/asm-generic/io.h:1112
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_write
  - drivers/video/fbdev/core/fbmem.c:fb_read
```
```
In drivers/acpi/apei/ghes.c (ffffffff815d6e3c)
Location: include/asm-generic/io.h:1112
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
```
```
In drivers/char/tpm/eventlog/acpi.c (ffffffff8165d5bb)
Location: include/asm-generic/io.h:1112
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff81660567)
Location: include/asm-generic/io.h:1112
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/char/tpm/tpm_crb.c:crb_recv
```
```
In drivers/misc/sram.c (ffffffff816b35ea)
Location: include/asm-generic/io.h:1112
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_write
  - drivers/misc/sram.c:sram_read
```
```
In drivers/firmware/dmi_scan.c (ffffffff81843a4b)
Location: include/asm-generic/io.h:1112
Inline: False
Direct callers:
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
```
**Symbols:**

```
ffffffff81843a4b-ffffffff81843a50: memcpy_fromio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void memcpy_fromio(void *to, const volatile void *from, size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/iomem.c (ffffffff8150e5a0)
Location: arch/x86/lib/iomem.c:25
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/tboot.c:tboot_log_read
  - mm/memory.c:generic_access_phys
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/video/fbdev/core/fbmem.c:fb_read
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/misc/sram.c:sram_read
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
```
**Symbols:**

```
ffffffff8150e5a0-ffffffff8150e5e8: memcpy_fromio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void memcpy_fromio(void *to, const volatile void *from, size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/iomem.c (ffffffff8153cc10)
Location: arch/x86/lib/iomem.c:25
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/tboot.c:tboot_log_read
  - mm/memory.c:generic_access_phys
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/video/fbdev/core/fbmem.c:fb_read
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/misc/sram.c:sram_read
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_setup
```
**Symbols:**

```
ffffffff8153cc10-ffffffff8153cc57: memcpy_fromio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void memcpy_fromio(void *to, const volatile void *from, size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/iomem.c (ffffffff8155da20)
Location: arch/x86/lib/iomem.c:25
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/tboot.c:tboot_log_read
  - mm/memory.c:generic_access_phys
  - fs/libfs.c:memory_read_from_io_buffer
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/video/fbdev/core/fbmem.c:fb_read
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/misc/sram.c:sram_read
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_setup
```
**Symbols:**

```
ffffffff8155da20-ffffffff8155da67: memcpy_fromio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void memcpy_fromio(void *to, const volatile void *from, size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/iomem.c (ffffffff815e7490)
Location: arch/x86/lib/iomem.c:25
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/tboot.c:tboot_log_read
  - mm/memory.c:generic_access_phys
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/video/fbdev/core/fbmem.c:fb_read
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/misc/sram.c:sram_read
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
```
**Symbols:**

```
ffffffff815e7490-ffffffff815e74d7: memcpy_fromio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void memcpy_fromio(void *to, const volatile void *from, size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/iomem.c (ffffffff8160c690)
Location: arch/x86/lib/iomem.c:25
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/tboot.c:tboot_log_read
  - mm/memory.c:generic_access_phys
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/video/fbdev/core/fbmem.c:fb_read
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/misc/sram.c:sram_read
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
```
**Symbols:**

```
ffffffff8160c690-ffffffff8160c6d7: memcpy_fromio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void memcpy_fromio(void *to, const volatile void *from, size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/iomem.c (ffffffff815ef930)
Location: arch/x86/lib/iomem.c:25
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/tboot.c:tboot_log_read
  - mm/memory.c:generic_access_phys
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/video/fbdev/core/fbmem.c:fb_read
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/misc/sram.c:sram_read
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments
```
**Symbols:**

```
ffffffff815ef930-ffffffff815ef977: memcpy_fromio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void memcpy_fromio(void *to, const volatile void *from, size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/iomem.c (ffffffff8165ca40)
Location: arch/x86/lib/iomem.c:25
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/tboot.c:tboot_log_read
  - mm/memory.c:generic_access_phys
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/video/fbdev/core/fbmem.c:fb_read
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/misc/sram.c:sram_read
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/remoteproc/remoteproc_coredump.c:rproc_copy_segment
```
**Symbols:**

```
ffffffff8165ca40-ffffffff8165ca87: memcpy_fromio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void memcpy_fromio(void *to, const volatile void *from, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/iomem.c (ffffffff81775cd0)
Location: arch/x86/lib/iomem.c:88
Inline: True
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/tboot.c:tboot_log_read
  - mm/memory.c:generic_access_phys
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/video/fbdev/core/fbmem.c:fb_read
  - drivers/acpi/sysfs.c:acpi_data_show
  - drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_handler
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/misc/sram.c:sram_read
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/remoteproc/remoteproc_coredump.c:rproc_copy_segment
```
**Symbols:**

```
ffffffff81775cd0-ffffffff81775d98: memcpy_fromio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void memcpy_fromio(void *to, const volatile void *from, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/iomem.c (ffffffff818a6a10)
Location: arch/x86/lib/iomem.c:93
Inline: True
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/tboot.c:tboot_log_read
  - mm/memory.c:generic_access_phys
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/video/fbdev/core/fbmem.c:fb_read
  - drivers/acpi/sysfs.c:acpi_data_show
  - drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_handler
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/misc/sram.c:sram_read
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/remoteproc/remoteproc_coredump.c:rproc_copy_segment
```
**Symbols:**

```
ffffffff818a6a10-ffffffff818a6ad8: memcpy_fromio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void memcpy_fromio(void *to, const volatile void *from, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/iomem.c (ffffffff818e9880)
Location: arch/x86/lib/iomem.c:93
Inline: True
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/tboot.c:tboot_log_read
  - mm/memory.c:generic_access_phys
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/video/fbdev/core/fb_io_fops.c:fb_io_read
  - drivers/acpi/sysfs.c:acpi_data_show
  - drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_handler
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/misc/sram.c:sram_read
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/remoteproc/remoteproc_coredump.c:rproc_copy_segment
```
**Symbols:**

```
ffffffff818e9880-ffffffff818e9948: memcpy_fromio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void memcpy_fromio(void *to, const volatile void *from, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/iomem.c (ffffffff81930d20)
Location: arch/x86/lib/iomem.c:93
Inline: True
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/tboot.c:tboot_log_read
  - mm/memory.c:generic_access_phys
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/video/fbdev/core/fb_io_fops.c:fb_io_read
  - drivers/acpi/sysfs.c:acpi_data_show
  - drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_handler
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/misc/sram.c:sram_read
  - drivers/gpu/drm/drm_cache.c:memcpy_fallback
  - drivers/gpu/drm/drm_cache.c:memcpy_fallback
  - drivers/gpu/drm/drm_cache.c:memcpy_fallback
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/remoteproc/remoteproc_coredump.c:rproc_copy_segment
```
**Symbols:**

```
ffffffff81930d20-ffffffff81930de8: memcpy_fromio (STB_GLOBAL)
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
In fs/libfs.c (c059d808)
Location: arch/arm/include/asm/io.h:326
Inline: True
Inline callers:
  - fs/libfs.c:memory_read_from_io_buffer
```
```
In fs/pstore/ram_core.c (c06d75f4)
Location: arch/arm/include/asm/io.h:326
Inline: True
Inline callers:
  - fs/pstore/ram_core.c:persistent_ram_save_old
  - fs/pstore/ram_core.c:persistent_ram_save_old
```
```
In drivers/pci/pci-sysfs.c (c0888890)
Location: arch/arm/include/asm/io.h:326
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
```
```
In drivers/video/fbdev/core/fbmem.c (c08c8754)
Location: arch/arm/include/asm/io.h:326
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_read
```
```
In drivers/dma/ti/edma.c (c092d5c0)
Location: arch/arm/include/asm/io.h:326
Inline: True
Inline callers:
  - drivers/dma/ti/edma.c:dma_ccerr_handler
```
```
In drivers/misc/sram.c (c0a097b4)
Location: arch/arm/include/asm/io.h:326
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_read
```
```
In drivers/mtd/maps/map_funcs.c (c0a99690)
Location: arch/arm/include/asm/io.h:326
Inline: True
Inline callers:
  - drivers/mtd/maps/map_funcs.c:simple_map_copy_from
```
```
In drivers/firmware/dmi_scan.c (c15a66a4)
Location: arch/arm/include/asm/io.h:326
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
```
```
In drivers/firmware/arm_scmi/driver.c (c0c375b0)
Location: arch/arm/include/asm/io.h:326
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/driver.c:scmi_fetch_response
```
```
In sound/core/memory.c (c0c84b20)
Location: arch/arm/include/asm/io.h:326
Inline: True
Inline callers:
  - sound/core/memory.c:copy_to_user_fromio
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
In mm/memory.c (c0000000003c6b80)
Location: arch/powerpc/include/asm/io-defs.h:58
Inline: True
Inline callers:
  - mm/memory.c:generic_access_phys
```
```
In fs/libfs.c (c0000000004bf99c)
Location: arch/powerpc/include/asm/io-defs.h:58
Inline: True
Inline callers:
  - fs/libfs.c:memory_read_from_io_buffer
```
```
In drivers/pci/pci-sysfs.c (c000000000869b64)
Location: arch/powerpc/include/asm/io-defs.h:58
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
```
```
In drivers/video/fbdev/core/fbmem.c (c0000000008a49b8)
Location: arch/powerpc/include/asm/io-defs.h:58
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_read
```
```
In drivers/misc/sram.c (c0000000009ca1c0)
Location: arch/powerpc/include/asm/io-defs.h:58
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_read
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/libfs.c (0)
Location: include/asm-generic/io.h:1097
Inline: True
```
```
In drivers/pci/pci-sysfs.c (ffffffe0004c2250)
Location: include/asm-generic/io.h:1097
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_rom
```
```
In drivers/misc/sram.c (ffffffe0005a2a44)
Location: include/asm-generic/io.h:1097
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_read
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
void memcpy_fromio(void *to, const volatile void *from, size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/iomem.c (ffffffff81556010)
Location: arch/x86/lib/iomem.c:25
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/tboot.c:tboot_log_read
  - mm/memory.c:generic_access_phys
  - fs/libfs.c:memory_read_from_io_buffer
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/video/fbdev/core/fbmem.c:fb_read
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/misc/sram.c:sram_read
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_setup
```
**Symbols:**

```
ffffffff81556010-ffffffff81556057: memcpy_fromio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void memcpy_fromio(void *to, const volatile void *from, size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/iomem.c (ffffffff815464d0)
Location: arch/x86/lib/iomem.c:25
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/tboot.c:tboot_log_read
  - mm/memory.c:generic_access_phys
  - fs/libfs.c:memory_read_from_io_buffer
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/video/fbdev/core/fbmem.c:fb_read
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/misc/sram.c:sram_read
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_setup
```
**Symbols:**

```
ffffffff815464d0-ffffffff81546517: memcpy_fromio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void memcpy_fromio(void *to, const volatile void *from, size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/iomem.c (ffffffff81551d50)
Location: arch/x86/lib/iomem.c:25
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/tboot.c:tboot_log_read
  - mm/memory.c:generic_access_phys
  - fs/libfs.c:memory_read_from_io_buffer
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/video/fbdev/core/fbmem.c:fb_read
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/misc/sram.c:sram_read
  - drivers/i2c/busses/i2c-amd-mp2-pci.c:amd_mp2_process_event
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_setup
```
**Symbols:**

```
ffffffff81551d50-ffffffff81551d97: memcpy_fromio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void memcpy_fromio(void *to, const volatile void *from, size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/iomem.c (ffffffff8156bbe0)
Location: arch/x86/lib/iomem.c:25
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/tboot.c:tboot_log_read
  - mm/memory.c:generic_access_phys
  - fs/libfs.c:memory_read_from_io_buffer
  - drivers/pci/pci-sysfs.c:pci_read_rom
  - drivers/video/fbdev/core/fbmem.c:fb_read
  - drivers/acpi/apei/ghes.c:ghes_copy_tofrom_phys
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/misc/sram.c:sram_read
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_setup
```
**Symbols:**

```
ffffffff8156bbe0-ffffffff8156bc27: memcpy_fromio (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *buffer</code>
</li>
<li>
<b>Param added. </b>
<code>const volatile void *addr</code>
</li>
<li>
<b>Param added. </b>
<code>size_t size</code>
</li>
<li>
<b>Param removed. </b>
<code>void *dst</code>
</li>
<li>
<b>Param removed. </b>
<code>const volatile void *src</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t count</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *to</code>
</li>
<li>
<b>Param added. </b>
<code>const volatile void *from</code>
</li>
<li>
<b>Param added. </b>
<code>size_t n</code>
</li>
<li>
<b>Param removed. </b>
<code>void *buffer</code>
</li>
<li>
<b>Param removed. </b>
<code>const volatile void *addr</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t size</code>
</li>
</ul>
</details>
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
