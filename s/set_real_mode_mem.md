# Function: <code>set_real_mode_mem</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void set_real_mode_mem(phys_addr_t mem, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/realmode/init.c (ffffffff81f8d4bf)
Location: arch/x86/realmode/init.c:16
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
```
**Symbols:**

```
ffffffff81f8d4bf-ffffffff81f8d4e8: set_real_mode_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void set_real_mode_mem(phys_addr_t mem, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/realmode/init.c (ffffffff81fc88d3)
Location: arch/x86/realmode/init.c:16
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
```
**Symbols:**

```
ffffffff81fc88d3-ffffffff81fc88fc: set_real_mode_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void set_real_mode_mem(phys_addr_t mem, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/realmode/init.c (ffffffff820a8fc3)
Location: arch/x86/realmode/init.c:16
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
```
**Symbols:**

```
ffffffff820a8fc3-ffffffff820a8ff1: set_real_mode_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void set_real_mode_mem(phys_addr_t mem, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/realmode/init.c (ffffffff826af692)
Location: arch/x86/realmode/init.c:18
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
```
**Symbols:**

```
ffffffff826af692-ffffffff826af6c0: set_real_mode_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void set_real_mode_mem(phys_addr_t mem, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/realmode/init.c (ffffffff826d8d8c)
Location: arch/x86/realmode/init.c:18
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
```
**Symbols:**

```
ffffffff826d8d8c-ffffffff826d8dba: set_real_mode_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void set_real_mode_mem(phys_addr_t mem, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/realmode/init.c (ffffffff8288f170)
Location: arch/x86/realmode/init.c:18
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:reserve_real_mode
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
```
**Symbols:**

```
ffffffff8288f170-ffffffff8288f19e: set_real_mode_mem (STB_GLOBAL)
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
In arch/x86/realmode/init.c (ffffffff828a6737)
Location: arch/x86/include/asm/realmode.h:80
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:reserve_real_mode
```
```
In arch/x86/platform/efi/quirks.c (ffffffff828c016c)
Location: arch/x86/include/asm/realmode.h:80
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
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
In arch/x86/realmode/init.c (ffffffff828a9766)
Location: arch/x86/include/asm/realmode.h:79
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:reserve_real_mode
```
```
In arch/x86/platform/efi/quirks.c (ffffffff828c660e)
Location: arch/x86/include/asm/realmode.h:79
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
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
In arch/x86/realmode/init.c (ffffffff82ccee54)
Location: arch/x86/include/asm/realmode.h:79
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:reserve_real_mode
```
```
In arch/x86/platform/efi/quirks.c (ffffffff82ce986c)
Location: arch/x86/include/asm/realmode.h:79
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
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
In arch/x86/realmode/init.c (ffffffff82fbad15)
Location: arch/x86/include/asm/realmode.h:86
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:reserve_real_mode
```
```
In arch/x86/platform/efi/quirks.c (ffffffff82fd72d7)
Location: arch/x86/include/asm/realmode.h:86
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
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
In arch/x86/realmode/init.c (ffffffff831c55a9)
Location: arch/x86/include/asm/realmode.h:86
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:reserve_real_mode
```
```
In arch/x86/platform/efi/quirks.c (ffffffff831e1d1c)
Location: arch/x86/include/asm/realmode.h:86
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
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
In arch/x86/realmode/init.c (ffffffff832a62c5)
Location: arch/x86/include/asm/realmode.h:86
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:reserve_real_mode
```
```
In arch/x86/platform/efi/quirks.c (ffffffff832c562a)
Location: arch/x86/include/asm/realmode.h:86
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
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
In arch/x86/realmode/init.c (ffffffff83455440)
Location: arch/x86/include/asm/realmode.h:87
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:reserve_real_mode
```
```
In arch/x86/platform/efi/quirks.c (ffffffff834781e6)
Location: arch/x86/include/asm/realmode.h:87
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
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
In arch/x86/realmode/init.c (ffffffff83e73146)
Location: arch/x86/include/asm/realmode.h:87
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:reserve_real_mode
```
```
In arch/x86/platform/efi/quirks.c (ffffffff83ea20e9)
Location: arch/x86/include/asm/realmode.h:87
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
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
In arch/x86/realmode/init.c (ffffffff83694106)
Location: arch/x86/include/asm/realmode.h:89
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:reserve_real_mode
```
```
In arch/x86/platform/efi/quirks.c (ffffffff836c6349)
Location: arch/x86/include/asm/realmode.h:89
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
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
In arch/x86/realmode/init.c (ffffffff838c3ff6)
Location: arch/x86/include/asm/realmode.h:89
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:reserve_real_mode
```
```
In arch/x86/platform/efi/quirks.c (ffffffff838f6f49)
Location: arch/x86/include/asm/realmode.h:89
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/realmode/init.c (ffffffff82897776)
Location: arch/x86/include/asm/realmode.h:79
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:reserve_real_mode
```
```
In arch/x86/platform/efi/quirks.c (ffffffff828b15a6)
Location: arch/x86/include/asm/realmode.h:79
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
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
In arch/x86/realmode/init.c (ffffffff8288faae)
Location: arch/x86/include/asm/realmode.h:79
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:reserve_real_mode
```
```
In arch/x86/platform/efi/quirks.c (ffffffff828a972b)
Location: arch/x86/include/asm/realmode.h:79
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
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
In arch/x86/realmode/init.c (ffffffff828aa766)
Location: arch/x86/include/asm/realmode.h:79
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:reserve_real_mode
```
```
In arch/x86/platform/efi/quirks.c (ffffffff828c44a5)
Location: arch/x86/include/asm/realmode.h:79
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
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
In arch/x86/realmode/init.c (ffffffff828aa776)
Location: arch/x86/include/asm/realmode.h:79
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:reserve_real_mode
```
```
In arch/x86/platform/efi/quirks.c (ffffffff828c764b)
Location: arch/x86/include/asm/realmode.h:79
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
