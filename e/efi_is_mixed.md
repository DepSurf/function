# Function: <code>efi_is_mixed</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff82ce97e7)
Location: arch/x86/include/asm/efi.h:201
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
```
```
In arch/x86/platform/efi/efi.c (ffffffff82cea491)
Location: arch/x86/include/asm/efi.h:201
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:kexec_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_map_regions
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff82ceb0cb)
Location: arch/x86/include/asm/efi.h:201
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_map_region
```
```
In arch/x86/platform/uv/bios_uv.c (ffffffff82cec099)
Location: arch/x86/include/asm/efi.h:201
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:arch_parse_efi_cmdline
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
In arch/x86/platform/efi/quirks.c (ffffffff82fd7252)
Location: arch/x86/include/asm/efi.h:175
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
```
```
In arch/x86/platform/efi/efi.c (ffffffff82fd7e79)
Location: arch/x86/include/asm/efi.h:175
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:kexec_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_map_regions
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff82fd894e)
Location: arch/x86/include/asm/efi.h:175
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_map_region
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
In arch/x86/platform/efi/quirks.c (ffffffff831e1c99)
Location: arch/x86/include/asm/efi.h:183
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
```
```
In arch/x86/platform/efi/efi.c (ffffffff831e2a11)
Location: arch/x86/include/asm/efi.h:183
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_map_regions
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff831e333e)
Location: arch/x86/include/asm/efi.h:183
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_map_region
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
In arch/x86/platform/efi/quirks.c (ffffffff832c55a7)
Location: arch/x86/include/asm/efi.h:183
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
```
```
In arch/x86/platform/efi/efi.c (ffffffff832c6396)
Location: arch/x86/include/asm/efi.h:183
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_map_regions
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff832c6ce1)
Location: arch/x86/include/asm/efi.h:183
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_map_region
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff83478158)
Location: arch/x86/include/asm/efi.h:190
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
```
```
In arch/x86/platform/efi/efi.c (ffffffff83478cfc)
Location: arch/x86/include/asm/efi.h:190
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:kexec_enter_virtual_mode
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff83479ab4)
Location: arch/x86/include/asm/efi.h:190
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_map_region
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff83ea1f41)
Location: arch/x86/include/asm/efi.h:189
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
```
```
In arch/x86/platform/efi/efi.c (ffffffff83ea2ec1)
Location: arch/x86/include/asm/efi.h:189
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:kexec_enter_virtual_mode
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff83ea3e20)
Location: arch/x86/include/asm/efi.h:189
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_map_region
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff836c61a1)
Location: arch/x86/include/asm/efi.h:193
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
```
```
In arch/x86/platform/efi/efi.c (ffffffff836c7111)
Location: arch/x86/include/asm/efi.h:193
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:kexec_enter_virtual_mode
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff836c80d0)
Location: arch/x86/include/asm/efi.h:193
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_map_region
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff838f6da1)
Location: arch/x86/include/asm/efi.h:166
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
```
```
In arch/x86/platform/efi/efi.c (ffffffff838f7d11)
Location: arch/x86/include/asm/efi.h:166
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:kexec_enter_virtual_mode
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff838f8cd0)
Location: arch/x86/include/asm/efi.h:166
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_map_region
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
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
