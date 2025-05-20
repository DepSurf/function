# Function: <code>efi_fpu_end</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff8109714f)
Location: arch/x86/include/asm/efi.h:83
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_crash_gracefully_on_page_fault
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff831e33b4)
Location: arch/x86/include/asm/efi.h:83
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
```
```
In arch/x86/platform/uv/bios_uv.c (ffffffff8109981f)
Location: arch/x86/include/asm/efi.h:83
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:__uv_bios_call
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff819a6ac0)
Location: arch/x86/include/asm/efi.h:83
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
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
In arch/x86/platform/efi/quirks.c (ffffffff810a70bb)
Location: arch/x86/include/asm/efi.h:83
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_crash_gracefully_on_page_fault
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff832c6d57)
Location: arch/x86/include/asm/efi.h:83
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
```
```
In arch/x86/platform/uv/bios_uv.c (ffffffff810a983f)
Location: arch/x86/include/asm/efi.h:83
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:__uv_bios_call
```
```
In drivers/acpi/prmt.c (ffffffff8171375a)
Location: arch/x86/include/asm/efi.h:83
Inline: True
Inline callers:
  - drivers/acpi/prmt.c:acpi_platformrt_space_handler
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81a53e60)
Location: arch/x86/include/asm/efi.h:83
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
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
In arch/x86/platform/efi/quirks.c (ffffffff810bc41d)
Location: arch/x86/include/asm/efi.h:85
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_crash_gracefully_on_page_fault
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff83479b2a)
Location: arch/x86/include/asm/efi.h:85
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
```
```
In arch/x86/platform/uv/bios_uv.c (ffffffff810bf119)
Location: arch/x86/include/asm/efi.h:85
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:__uv_bios_call
```
```
In drivers/acpi/prmt.c (ffffffff81842e8d)
Location: arch/x86/include/asm/efi.h:85
Inline: True
Inline callers:
  - drivers/acpi/prmt.c:acpi_platformrt_space_handler
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81bc32c8)
Location: arch/x86/include/asm/efi.h:85
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
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
In arch/x86/platform/efi/quirks.c (ffffffff810d7861)
Location: arch/x86/include/asm/efi.h:85
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_crash_gracefully_on_page_fault
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff83ea3eb7)
Location: arch/x86/include/asm/efi.h:85
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
```
```
In arch/x86/platform/uv/bios_uv.c (ffffffff810dae49)
Location: arch/x86/include/asm/efi.h:85
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:__uv_bios_call
```
```
In drivers/acpi/prmt.c (ffffffff81979f91)
Location: arch/x86/include/asm/efi.h:85
Inline: True
Inline callers:
  - drivers/acpi/prmt.c:acpi_platformrt_space_handler
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81d67624)
Location: arch/x86/include/asm/efi.h:85
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
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
In arch/x86/platform/efi/quirks.c (ffffffff810e2df1)
Location: arch/x86/include/asm/efi.h:87
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_crash_gracefully_on_page_fault
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff836c8176)
Location: arch/x86/include/asm/efi.h:87
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
```
```
In arch/x86/platform/uv/bios_uv.c (ffffffff810e63e6)
Location: arch/x86/include/asm/efi.h:87
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:__uv_bios_call
```
```
In drivers/acpi/prmt.c (ffffffff819c09fe)
Location: arch/x86/include/asm/efi.h:87
Inline: True
Inline callers:
  - drivers/acpi/prmt.c:acpi_platformrt_space_handler
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81dd27dc)
Location: arch/x86/include/asm/efi.h:87
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff838f8d76)
Location: arch/x86/include/asm/efi.h:87
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:arch_efi_call_virt_teardown
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
