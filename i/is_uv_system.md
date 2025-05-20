# Function: <code>is_uv_system</code>

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
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/include/asm/uv/uv.h:25
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/uv/uv.h:25
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: arch/x86/include/asm/uv/uv.h:25
Inline: True
```
```
In arch/x86/platform/efi/quirks.c (0)
Location: arch/x86/include/asm/uv/uv.h:25
Inline: True
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
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/include/asm/uv/uv.h:25
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/uv/uv.h:25
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/uv/uv.h:25
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: arch/x86/include/asm/uv/uv.h:25
Inline: True
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
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/include/asm/uv/uv.h:25
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/uv/uv.h:25
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/uv/uv.h:25
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: arch/x86/include/asm/uv/uv.h:25
Inline: True
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
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/include/asm/uv/uv.h:25
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/uv/uv.h:25
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: arch/x86/include/asm/uv/uv.h:25
Inline: True
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
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/include/asm/uv/uv.h:26
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/uv/uv.h:26
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: arch/x86/include/asm/uv/uv.h:26
Inline: True
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
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/include/asm/uv/uv.h:26
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: arch/x86/include/asm/uv/uv.h:26
Inline: True
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
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/include/asm/uv/uv.h:32
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: arch/x86/include/asm/uv/uv.h:32
Inline: True
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
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/include/asm/uv/uv.h:32
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: arch/x86/include/asm/uv/uv.h:32
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int is_uv_system();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828bd8d1)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:333
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_ptc_init
  - arch/x86/platform/uv/uv_sysfs.c:sgi_uv_sysfs_init
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
```
**Symbols:**

```
ffffffff8106d010-ffffffff8106d028: is_uv_system (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int is_uv_system();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82ce1c76)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:359
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_ptc_init
  - arch/x86/platform/uv/uv_sysfs.c:sgi_uv_sysfs_init
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
```
**Symbols:**

```
ffffffff81074370-ffffffff81074388: is_uv_system (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int is_uv_system();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82fcee97)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:517
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
```
**Symbols:**

```
ffffffff81074f00-ffffffff81074f18: is_uv_system (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int is_uv_system();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff831d9934)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:513
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
```
**Symbols:**

```
ffffffff810759a0-ffffffff810759b8: is_uv_system (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int is_uv_system();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff832bc9d9)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:513
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
```
**Symbols:**

```
ffffffff81082e70-ffffffff81082e88: is_uv_system (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int is_uv_system();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8346e311)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:519
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
```
**Symbols:**

```
ffffffff81092c00-ffffffff81092c1e: is_uv_system (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int is_uv_system();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff83e94325)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:519
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
```
**Symbols:**

```
ffffffff810a7df0-ffffffff810a7e0e: is_uv_system (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int is_uv_system();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff836b7e85)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:519
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
```
**Symbols:**

```
ffffffff810ab060-ffffffff810ab07e: is_uv_system (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int is_uv_system();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff838e87c5)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:520
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
```
**Symbols:**

```
ffffffff810b2000-ffffffff810b201e: is_uv_system (STB_GLOBAL)
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
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/include/asm/uv/uv.h:34
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: arch/x86/include/asm/uv/uv.h:34
Inline: True
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
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/include/asm/uv/uv.h:34
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: arch/x86/include/asm/uv/uv.h:34
Inline: True
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
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/include/asm/uv/uv.h:34
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: arch/x86/include/asm/uv/uv.h:34
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int is_uv_system();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828be8fe)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:333
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_ptc_init
  - arch/x86/platform/uv/uv_sysfs.c:sgi_uv_sysfs_init
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
```
**Symbols:**

```
ffffffff8106e6d0-ffffffff8106e6e8: is_uv_system (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
