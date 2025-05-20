# Function: <code>efi_is_native</code>

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
In arch/x86/platform/efi/quirks.c (ffffffff81f79a6e)
Location: arch/x86/include/asm/efi.h:136
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
```
```
In arch/x86/platform/efi/efi.c (ffffffff81f7a4e0)
Location: arch/x86/include/asm/efi.h:136
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81f7ad99)
Location: arch/x86/include/asm/efi.h:136
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_map_region
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
In arch/x86/platform/efi/quirks.c (ffffffff81fa2172)
Location: arch/x86/include/asm/efi.h:147
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
```
```
In arch/x86/platform/efi/efi.c (ffffffff81fa2f6e)
Location: arch/x86/include/asm/efi.h:147
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_init
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81fa38b9)
Location: arch/x86/include/asm/efi.h:147
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_map_region
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
In arch/x86/platform/efi/quirks.c (ffffffff81fdd7b3)
Location: arch/x86/include/asm/efi.h:146
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
```
```
In arch/x86/platform/efi/efi.c (ffffffff81fde88a)
Location: arch/x86/include/asm/efi.h:146
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_init
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81fdf23b)
Location: arch/x86/include/asm/efi.h:146
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_map_region
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff820be60e)
Location: arch/x86/include/asm/efi.h:146
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
```
```
In arch/x86/platform/efi/efi.c (ffffffff820bf67a)
Location: arch/x86/include/asm/efi.h:146
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_init
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff820c018d)
Location: arch/x86/include/asm/efi.h:146
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_map_region
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff826c6733)
Location: arch/x86/include/asm/efi.h:160
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
```
```
In arch/x86/platform/efi/efi.c (ffffffff826c77a6)
Location: arch/x86/include/asm/efi.h:160
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_init
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff826c8344)
Location: arch/x86/include/asm/efi.h:160
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_map_region
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff826f0847)
Location: arch/x86/include/asm/efi.h:156
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
```
```
In arch/x86/platform/efi/efi.c (ffffffff826f18ad)
Location: arch/x86/include/asm/efi.h:156
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_init
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff826f2281)
Location: arch/x86/include/asm/efi.h:156
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_map_region
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
In arch/x86/platform/efi/quirks.c (ffffffff828a79cc)
Location: arch/x86/include/asm/efi.h:157
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
```
```
In arch/x86/platform/efi/efi.c (ffffffff828a864d)
Location: arch/x86/include/asm/efi.h:157
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_init
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828a928a)
Location: arch/x86/include/asm/efi.h:157
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_map_region
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
In arch/x86/platform/efi/quirks.c (ffffffff828c00dc)
Location: arch/x86/include/asm/efi.h:157
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
```
```
In arch/x86/platform/efi/efi.c (ffffffff828c117b)
Location: arch/x86/include/asm/efi.h:157
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_init
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c1a73)
Location: arch/x86/include/asm/efi.h:157
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_map_region
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
In arch/x86/platform/efi/quirks.c (ffffffff828c658a)
Location: arch/x86/include/asm/efi.h:157
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
```
```
In arch/x86/platform/efi/efi.c (ffffffff828c7602)
Location: arch/x86/include/asm/efi.h:157
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_init
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c7eec)
Location: arch/x86/include/asm/efi.h:157
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_map_region
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff828b1522)
Location: arch/x86/include/asm/efi.h:157
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
```
```
In arch/x86/platform/efi/efi.c (ffffffff828b259a)
Location: arch/x86/include/asm/efi.h:157
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_init
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828b2e84)
Location: arch/x86/include/asm/efi.h:157
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_map_region
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
In arch/x86/platform/efi/quirks.c (ffffffff828a96a7)
Location: arch/x86/include/asm/efi.h:157
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
```
```
In arch/x86/platform/efi/efi.c (ffffffff828aa70c)
Location: arch/x86/include/asm/efi.h:157
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_init
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828ab005)
Location: arch/x86/include/asm/efi.h:157
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_map_region
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
In arch/x86/platform/efi/quirks.c (ffffffff828c4421)
Location: arch/x86/include/asm/efi.h:157
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
```
```
In arch/x86/platform/efi/efi.c (ffffffff828c5499)
Location: arch/x86/include/asm/efi.h:157
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_init
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c5d83)
Location: arch/x86/include/asm/efi.h:157
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_map_region
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
In arch/x86/platform/efi/quirks.c (ffffffff828c75c7)
Location: arch/x86/include/asm/efi.h:157
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
```
```
In arch/x86/platform/efi/efi.c (ffffffff828c863f)
Location: arch/x86/include/asm/efi.h:157
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_init
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c8f29)
Location: arch/x86/include/asm/efi.h:157
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_map_region
```
</details>
</li>
</ul>

## Differences
