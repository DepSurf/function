# Function: <code>wbinvd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void wbinvd();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8104c05f)
Location: arch/x86/include/asm/paravirt.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105282c)
Location: arch/x86/include/asm/paravirt.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff81f755cd)
Location: arch/x86/include/asm/paravirt.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
```
In arch/x86/kernel/tce_64.c (ffffffff810681cb)
Location: arch/x86/include/asm/paravirt.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_build
  - arch/x86/kernel/tce_64.c:tce_free
```
```
In arch/x86/mm/pageattr.c (ffffffff8106c56e)
Location: arch/x86/include/asm/paravirt.h:125
Inline: True
```
```
In arch/x86/lib/cache-smp.c (ffffffff8141b9a9)
Location: arch/x86/include/asm/paravirt.h:125
Inline: True
Inline callers:
  - arch/x86/lib/cache-smp.c:__wbinvd
```
```
In drivers/acpi/sleep.c (ffffffff8147b683)
Location: arch/x86/include/asm/paravirt.h:125
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_hibernation_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/acpi/acpica/hwesleep.c (ffffffff8149a3e5)
Location: arch/x86/include/asm/paravirt.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
```
```
In drivers/acpi/acpica/hwsleep.c (ffffffff8149b07c)
Location: arch/x86/include/asm/paravirt.h:125
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
```
```
In drivers/acpi/acpica/hwxfsleep.c (ffffffff8149ba59)
Location: arch/x86/include/asm/paravirt.h:125
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff814ac54c)
Location: arch/x86/include/asm/paravirt.h:125
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
  - drivers/acpi/processor_idle.c:acpi_idle_enter_freeze
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
```
In drivers/char/agp/generic.c (ffffffff8151cb09)
Location: arch/x86/include/asm/paravirt.h:125
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:ipi_handler
```
**Symbols:**

```
ffffffff8147b683-ffffffff8147b690: wbinvd (STB_LOCAL)
ffffffff814ac54c-ffffffff814ac559: wbinvd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void wbinvd();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8104c13c)
Location: arch/x86/include/asm/paravirt.h:115
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/smpboot.c (ffffffff81052980)
Location: arch/x86/include/asm/paravirt.h:115
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff81f9dd8d)
Location: arch/x86/include/asm/paravirt.h:115
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
```
In arch/x86/kernel/tce_64.c (ffffffff81067f73)
Location: arch/x86/include/asm/paravirt.h:115
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_free
  - arch/x86/kernel/tce_64.c:tce_build
```
```
In arch/x86/mm/pageattr.c (ffffffff8106c697)
Location: arch/x86/include/asm/paravirt.h:115
Inline: True
```
```
In arch/x86/lib/cache-smp.c (ffffffff81463b69)
Location: arch/x86/include/asm/paravirt.h:115
Inline: True
Inline callers:
  - arch/x86/lib/cache-smp.c:__wbinvd
```
```
In drivers/acpi/sleep.c (ffffffff814c9c8b)
Location: arch/x86/include/asm/paravirt.h:115
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_hibernation_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/acpi/acpica/hwesleep.c (ffffffff814e92ed)
Location: arch/x86/include/asm/paravirt.h:115
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
```
```
In drivers/acpi/acpica/hwsleep.c (ffffffff814ea0ee)
Location: arch/x86/include/asm/paravirt.h:115
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
```
```
In drivers/acpi/acpica/hwxfsleep.c (ffffffff814eaac6)
Location: arch/x86/include/asm/paravirt.h:115
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff814fb8a6)
Location: arch/x86/include/asm/paravirt.h:115
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_freeze
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
```
```
In drivers/char/agp/generic.c (ffffffff8156f859)
Location: arch/x86/include/asm/paravirt.h:115
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:ipi_handler
```
**Symbols:**

```
ffffffff814c9c8b-ffffffff814c9c98: wbinvd (STB_LOCAL)
ffffffff814fb8a6-ffffffff814fb8b3: wbinvd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void wbinvd();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8104e58c)
Location: arch/x86/include/asm/paravirt.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/smpboot.c (ffffffff81055289)
Location: arch/x86/include/asm/paravirt.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff81fd9319)
Location: arch/x86/include/asm/paravirt.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
```
In arch/x86/kernel/tce_64.c (ffffffff8106bbc3)
Location: arch/x86/include/asm/paravirt.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_free
  - arch/x86/kernel/tce_64.c:tce_build
```
```
In arch/x86/mm/pageattr.c (ffffffff8107003e)
Location: arch/x86/include/asm/paravirt.h:106
Inline: True
```
```
In arch/x86/lib/cache-smp.c (ffffffff81482e09)
Location: arch/x86/include/asm/paravirt.h:106
Inline: True
Inline callers:
  - arch/x86/lib/cache-smp.c:__wbinvd
```
```
In drivers/acpi/sleep.c (ffffffff814ebbcf)
Location: arch/x86/include/asm/paravirt.h:106
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_hibernation_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/acpi/acpica/hwesleep.c (ffffffff8150bb3c)
Location: arch/x86/include/asm/paravirt.h:106
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
```
```
In drivers/acpi/acpica/hwsleep.c (ffffffff8150c976)
Location: arch/x86/include/asm/paravirt.h:106
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
```
```
In drivers/acpi/acpica/hwxfsleep.c (ffffffff8150d34e)
Location: arch/x86/include/asm/paravirt.h:106
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff8151e57a)
Location: arch/x86/include/asm/paravirt.h:106
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_freeze
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
```
```
In drivers/char/agp/generic.c (ffffffff8159bf19)
Location: arch/x86/include/asm/paravirt.h:106
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:ipi_handler
```
**Symbols:**

```
ffffffff814ebbcf-ffffffff814ebbdc: wbinvd (STB_LOCAL)
ffffffff8151e57a-ffffffff8151e587: wbinvd (STB_LOCAL)
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8104e4fc)
Location: arch/x86/include/asm/paravirt.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/smpboot.c (ffffffff81054b8f)
Location: arch/x86/include/asm/paravirt.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff820ba176)
Location: arch/x86/include/asm/paravirt.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
```
In arch/x86/kernel/tce_64.c (ffffffff8106af83)
Location: arch/x86/include/asm/paravirt.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_free
  - arch/x86/kernel/tce_64.c:tce_build
```
```
In arch/x86/mm/pageattr.c (ffffffff8106f75e)
Location: arch/x86/include/asm/paravirt.h:106
Inline: True
```
```
In arch/x86/lib/cache-smp.c (ffffffff8148c569)
Location: arch/x86/include/asm/paravirt.h:106
Inline: True
Inline callers:
  - arch/x86/lib/cache-smp.c:__wbinvd
```
```
In drivers/acpi/sleep.c (ffffffff814f820a)
Location: arch/x86/include/asm/paravirt.h:106
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_hibernation_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/acpi/acpica/hwesleep.c (ffffffff8151c183)
Location: arch/x86/include/asm/paravirt.h:106
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
```
```
In drivers/acpi/acpica/hwsleep.c (ffffffff8151d04c)
Location: arch/x86/include/asm/paravirt.h:106
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
```
```
In drivers/acpi/acpica/hwxfsleep.c (ffffffff8151da24)
Location: arch/x86/include/asm/paravirt.h:106
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff8153097d)
Location: arch/x86/include/asm/paravirt.h:106
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_freeze
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
```
```
In drivers/char/agp/generic.c (ffffffff815aff59)
Location: arch/x86/include/asm/paravirt.h:106
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:ipi_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void wbinvd();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81051e6c)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105895b)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
Direct callers:
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff826c0b25)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
```
In arch/x86/kernel/tce_64.c (ffffffff8106f883)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_free
  - arch/x86/kernel/tce_64.c:tce_build
```
```
In arch/x86/mm/pageattr.c (ffffffff81074901)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__cpa_flush_all
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826c5bdf)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
```
```
In arch/x86/lib/cache-smp.c (ffffffff814c8659)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - arch/x86/lib/cache-smp.c:__wbinvd
```
```
In drivers/acpi/sleep.c (ffffffff8153a0ea)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_hibernation_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/acpi/acpica/hwesleep.c (ffffffff8156c48e)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
```
```
In drivers/acpi/acpica/hwsleep.c (ffffffff8156da42)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
```
```
In drivers/acpi/acpica/hwxfsleep.c (ffffffff8156e96c)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff815919bd)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
```
```
In drivers/char/agp/generic.c (ffffffff81616af9)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:ipi_handler
```
**Symbols:**

```
ffffffff81056f10-ffffffff81056f1d: wbinvd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void wbinvd();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81054b1c)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105b5c7)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
Direct callers:
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff826ead40)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
```
In arch/x86/kernel/tce_64.c (ffffffff81072753)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_free
  - arch/x86/kernel/tce_64.c:tce_build
```
```
In arch/x86/mm/pageattr.c (ffffffff81077381)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__cpa_flush_all
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826efac2)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
```
In arch/x86/lib/cache-smp.c (ffffffff814f95f5)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - arch/x86/lib/cache-smp.c:__wbinvd
```
```
In drivers/acpi/sleep.c (ffffffff8156fe75)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_hibernation_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/acpi/acpica/hwesleep.c (ffffffff815a30e1)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
```
```
In drivers/acpi/acpica/hwsleep.c (ffffffff815a4690)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
```
```
In drivers/acpi/acpica/hwxfsleep.c (ffffffff815a564c)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff815c8d1d)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
```
```
In drivers/char/agp/generic.c (ffffffff81650815)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:ipi_handler
```
**Symbols:**

```
ffffffff81059d80-ffffffff81059d8d: wbinvd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void wbinvd();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff810521dc)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/smpboot.c (ffffffff81061251)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
Direct callers:
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff828a19db)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
```
In arch/x86/kernel/tce_64.c (ffffffff810787a3)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_free
  - arch/x86/kernel/tce_64.c:tce_build
```
```
In arch/x86/mm/pageattr.c (ffffffff8107db31)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__cpa_flush_all
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a677f)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
```
In arch/x86/lib/cache-smp.c (ffffffff8150de95)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/lib/cache-smp.c:__wbinvd
```
```
In drivers/acpi/sleep.c (ffffffff81587a35)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_hibernation_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/acpi/acpica/hwesleep.c (ffffffff815bbda7)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
```
```
In drivers/acpi/acpica/hwsleep.c (ffffffff815bd04c)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
```
```
In drivers/acpi/acpica/hwxfsleep.c (ffffffff815be008)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff815e22ed)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
```
```
In drivers/char/agp/generic.c (ffffffff8166e9d5)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:ipi_handler
```
**Symbols:**

```
ffffffff8105fa00-ffffffff8105fa0d: wbinvd (STB_LOCAL)
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81055331)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064909)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff828b9c49)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
```
In arch/x86/kernel/tce_64.c (ffffffff8107c313)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_free
  - arch/x86/kernel/tce_64.c:tce_build
```
```
In arch/x86/mm/pageattr.c (ffffffff8108143a)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__cpa_flush_all
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828bee1a)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
```
In arch/x86/lib/cache-smp.c (ffffffff8153c505)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - arch/x86/lib/cache-smp.c:__wbinvd
```
```
In drivers/acpi/sleep.c (ffffffff815b8475)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_hibernation_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/acpi/acpica/hwesleep.c (ffffffff815ed985)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
```
```
In drivers/acpi/acpica/hwsleep.c (ffffffff815eec52)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
```
```
In drivers/acpi/acpica/hwxfsleep.c (ffffffff815efbf3)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff81614140)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
```
```
In drivers/char/agp/generic.c (ffffffff816a45e5)
Location: arch/x86/include/asm/paravirt.h:164
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:ipi_handler
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81055c31)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064f89)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff828c0137)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
```
In arch/x86/kernel/tce_64.c (ffffffff8107d403)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_free
  - arch/x86/kernel/tce_64.c:tce_build
```
```
In arch/x86/mm/pageattr.c (ffffffff810824fa)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__cpa_flush_all
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c5293)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
```
In arch/x86/lib/cache-smp.c (ffffffff8155d315)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
Inline callers:
  - arch/x86/lib/cache-smp.c:__wbinvd
```
```
In drivers/acpi/sleep.c (ffffffff815d96e5)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_hibernation_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/acpi/acpica/hwesleep.c (ffffffff8160ed1a)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
```
```
In drivers/acpi/acpica/hwsleep.c (ffffffff816100e0)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
```
```
In drivers/acpi/acpica/hwxfsleep.c (ffffffff81611081)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff81635630)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
```
```
In drivers/char/agp/generic.c (ffffffff816c7315)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:ipi_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void wbinvd();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8105ad7a)
Location: arch/x86/include/asm/paravirt.h:158
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106b6b7)
Location: arch/x86/include/asm/paravirt.h:158
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
Direct callers:
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff82ce448a)
Location: arch/x86/include/asm/paravirt.h:158
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108bc46)
Location: arch/x86/include/asm/paravirt.h:158
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__cpa_flush_all
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff82ce8467)
Location: arch/x86/include/asm/paravirt.h:158
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
```
In arch/x86/lib/cache-smp.c (ffffffff815e6d85)
Location: arch/x86/include/asm/paravirt.h:158
Inline: True
Inline callers:
  - arch/x86/lib/cache-smp.c:__wbinvd
```
```
In drivers/acpi/sleep.c (ffffffff81683a25)
Location: arch/x86/include/asm/paravirt.h:158
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_power_off_prepare
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/acpi/acpica/hwesleep.c (ffffffff816bb078)
Location: arch/x86/include/asm/paravirt.h:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
```
```
In drivers/acpi/acpica/hwsleep.c (ffffffff816bc4ce)
Location: arch/x86/include/asm/paravirt.h:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
```
```
In drivers/acpi/acpica/hwxfsleep.c (ffffffff816bd44e)
Location: arch/x86/include/asm/paravirt.h:158
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff816e2050)
Location: arch/x86/include/asm/paravirt.h:158
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
```
```
In drivers/char/agp/generic.c (ffffffff8177bdd5)
Location: arch/x86/include/asm/paravirt.h:158
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:ipi_handler
```
**Symbols:**

```
ffffffff810696c0-ffffffff810696cd: wbinvd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void wbinvd();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff810598da)
Location: arch/x86/include/asm/paravirt.h:158
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106d357)
Location: arch/x86/include/asm/paravirt.h:158
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
Direct callers:
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff82fd1ceb)
Location: arch/x86/include/asm/paravirt.h:158
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108bc66)
Location: arch/x86/include/asm/paravirt.h:158
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__cpa_flush_all
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff82fd5e86)
Location: arch/x86/include/asm/paravirt.h:158
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
```
In arch/x86/lib/cache-smp.c (ffffffff8160bed5)
Location: arch/x86/include/asm/paravirt.h:158
Inline: True
Inline callers:
  - arch/x86/lib/cache-smp.c:__wbinvd
```
```
In drivers/acpi/sleep.c (ffffffff816a1915)
Location: arch/x86/include/asm/paravirt.h:158
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_power_off_prepare
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/acpi/acpica/hwesleep.c (ffffffff816d8a70)
Location: arch/x86/include/asm/paravirt.h:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
```
```
In drivers/acpi/acpica/hwsleep.c (ffffffff816d9fdc)
Location: arch/x86/include/asm/paravirt.h:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
```
```
In drivers/acpi/acpica/hwxfsleep.c (ffffffff816daff0)
Location: arch/x86/include/asm/paravirt.h:158
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff816fffc7)
Location: arch/x86/include/asm/paravirt.h:158
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
```
```
In drivers/char/agp/generic.c (ffffffff81794f25)
Location: arch/x86/include/asm/paravirt.h:158
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:ipi_handler
```
**Symbols:**

```
ffffffff8106b2a0-ffffffff8106b2ad: wbinvd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void wbinvd();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8105a256)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106ddc7)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
Direct callers:
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff831dc9a0)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108c866)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__cpa_flush_all
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff831e0902)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
```
In arch/x86/lib/cache-smp.c (ffffffff815ef1b5)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/lib/cache-smp.c:__wbinvd
```
```
In drivers/acpi/sleep.c (ffffffff816848d5)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_power_off_prepare
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/acpi/acpica/hwesleep.c (ffffffff816baa08)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
```
```
In drivers/acpi/acpica/hwsleep.c (ffffffff816bbf72)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
```
```
In drivers/acpi/acpica/hwxfsleep.c (ffffffff816bcf87)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff816e1ad7)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
```
```
In drivers/char/agp/generic.c (ffffffff81777bd5)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:ipi_handler
```
**Symbols:**

```
ffffffff8106bd20-ffffffff8106bd2d: wbinvd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void wbinvd();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff810636a6)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/smpboot.c (ffffffff810795d7)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
Direct callers:
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff832bfa56)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109c0c6)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__cpa_flush_all
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff832c3fe0)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
```
In arch/x86/lib/cache-smp.c (ffffffff8165c2c5)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/lib/cache-smp.c:__wbinvd
```
```
In drivers/acpi/sleep.c (ffffffff816f9b85)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_power_off_prepare
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/acpi/acpica/hwesleep.c (ffffffff81731a60)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
```
```
In drivers/acpi/acpica/hwsleep.c (ffffffff8173311d)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
```
```
In drivers/acpi/processor_idle.c (ffffffff8175a056)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
```
```
In drivers/char/agp/generic.c (ffffffff817fd865)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:ipi_handler
```
**Symbols:**

```
ffffffff81076800-ffffffff8107680d: wbinvd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void wbinvd();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81070331)
Location: arch/x86/include/asm/paravirt.h:181
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/smpboot.c (ffffffff81088468)
Location: arch/x86/include/asm/paravirt.h:181
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
Direct callers:
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff83471f58)
Location: arch/x86/include/asm/paravirt.h:181
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810af750)
Location: arch/x86/include/asm/paravirt.h:181
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__cpa_flush_all
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff8347699d)
Location: arch/x86/include/asm/paravirt.h:181
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec
```
```
In arch/x86/lib/cache-smp.c (ffffffff817752f5)
Location: arch/x86/include/asm/paravirt.h:181
Inline: True
Inline callers:
  - arch/x86/lib/cache-smp.c:__wbinvd
```
```
In drivers/acpi/acpica/hwesleep.c (ffffffff81862771)
Location: arch/x86/include/asm/paravirt.h:181
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
```
```
In drivers/acpi/acpica/hwsleep.c (ffffffff81863fda)
Location: arch/x86/include/asm/paravirt.h:181
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
```
```
In drivers/acpi/processor_idle.c (ffffffff81f29946)
Location: arch/x86/include/asm/paravirt.h:181
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
```
```
In drivers/char/agp/generic.c (ffffffff8193c855)
Location: arch/x86/include/asm/paravirt.h:181
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:ipi_handler
```
**Symbols:**

```
ffffffff81085610-ffffffff81085636: wbinvd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void wbinvd();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106ac1a)
Location: arch/x86/include/asm/paravirt.h:181
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable
```
```
In arch/x86/kernel/smpboot.c (ffffffff8109bf28)
Location: arch/x86/include/asm/paravirt.h:181
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
Direct callers:
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff83e9926b)
Location: arch/x86/include/asm/paravirt.h:181
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810c9cb0)
Location: arch/x86/include/asm/paravirt.h:181
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__cpa_flush_all
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff83e9fb40)
Location: arch/x86/include/asm/paravirt.h:181
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec
```
```
In arch/x86/lib/cache-smp.c (ffffffff818a5eb5)
Location: arch/x86/include/asm/paravirt.h:181
Inline: True
Inline callers:
  - arch/x86/lib/cache-smp.c:__wbinvd
```
```
In drivers/acpi/acpica/hwesleep.c (ffffffff8199fd9a)
Location: arch/x86/include/asm/paravirt.h:181
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
```
```
In drivers/acpi/acpica/hwsleep.c (ffffffff819a1dc9)
Location: arch/x86/include/asm/paravirt.h:181
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
```
```
In drivers/acpi/processor_idle.c (ffffffff820d5796)
Location: arch/x86/include/asm/paravirt.h:181
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
```
```
In drivers/char/agp/generic.c (ffffffff81a9d335)
Location: arch/x86/include/asm/paravirt.h:181
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:ipi_handler
```
**Symbols:**

```
ffffffff81098940-ffffffff81098966: wbinvd (STB_LOCAL)
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106c58a)
Location: arch/x86/include/asm/paravirt.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable
```
```
In arch/x86/kernel/smpboot.c (ffffffff8109ee94)
Location: arch/x86/include/asm/paravirt.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:hlt_play_dead
  - arch/x86/kernel/smpboot.c:mwait_play_dead
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff836bcc8b)
Location: arch/x86/include/asm/paravirt.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cd3c0)
Location: arch/x86/include/asm/paravirt.h:183
Inline: True
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff836c3cab)
Location: arch/x86/include/asm/paravirt.h:183
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec
```
```
In arch/x86/lib/cache-smp.c (ffffffff818e8cc5)
Location: arch/x86/include/asm/paravirt.h:183
Inline: True
Inline callers:
  - arch/x86/lib/cache-smp.c:__wbinvd
```
```
In drivers/acpi/acpica/hwesleep.c (ffffffff819e6a6e)
Location: arch/x86/include/asm/paravirt.h:183
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
```
```
In drivers/acpi/acpica/hwsleep.c (ffffffff819e8aa9)
Location: arch/x86/include/asm/paravirt.h:183
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
```
```
In drivers/acpi/processor_idle.c (ffffffff82143d01)
Location: arch/x86/include/asm/paravirt.h:183
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
```
```
In drivers/char/agp/generic.c (ffffffff81ae8c95)
Location: arch/x86/include/asm/paravirt.h:183
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:ipi_handler
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810737da)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable
```
```
In arch/x86/kernel/smpboot.c (ffffffff810a62c4)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:hlt_play_dead
  - arch/x86/kernel/smpboot.c:mwait_play_dead
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff838ed74b)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d5aa0)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff838f492b)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec
```
```
In arch/x86/lib/cache-smp.c (ffffffff81930165)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - arch/x86/lib/cache-smp.c:__wbinvd
```
```
In drivers/acpi/acpica/hwesleep.c (ffffffff81a317be)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
```
```
In drivers/acpi/acpica/hwsleep.c (ffffffff81a337f9)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
```
```
In drivers/acpi/processor_idle.c (ffffffff82226421)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
```
```
In drivers/char/agp/generic.c (ffffffff81b3c125)
Location: arch/x86/include/asm/paravirt.h:185
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:ipi_handler
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff810557b1)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064a79)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff828ab10d)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
```
In arch/x86/kernel/tce_64.c (ffffffff8107c403)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_free
  - arch/x86/kernel/tce_64.c:tce_build
```
```
In arch/x86/mm/pageattr.c (ffffffff810814fa)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__cpa_flush_all
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828b022b)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
```
In arch/x86/lib/cache-smp.c (ffffffff81555905)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
Inline callers:
  - arch/x86/lib/cache-smp.c:__wbinvd
```
```
In drivers/acpi/sleep.c (ffffffff815cc265)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_hibernation_enter
```
```
In drivers/acpi/acpica/hwesleep.c (ffffffff815f0511)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
```
```
In drivers/acpi/acpica/hwsleep.c (ffffffff815f132a)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
```
```
In drivers/acpi/acpica/hwxfsleep.c (ffffffff815f1b8c)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff81604e20)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
```
```
In drivers/char/agp/generic.c (ffffffff8168cd65)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:ipi_handler
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff810458e1)
Location: arch/x86/include/asm/special_insns.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/smpboot.c (ffffffff81054d53)
Location: arch/x86/include/asm/special_insns.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff828a33d9)
Location: arch/x86/include/asm/special_insns.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
```
In arch/x86/kernel/tce_64.c (ffffffff8106bb21)
Location: arch/x86/include/asm/special_insns.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_free
  - arch/x86/kernel/tce_64.c:tce_build
```
```
In arch/x86/mm/pageattr.c (ffffffff8107072e)
Location: arch/x86/include/asm/special_insns.h:182
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__cpa_flush_all
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a8416)
Location: arch/x86/include/asm/special_insns.h:182
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
```
In arch/x86/lib/cache-smp.c (ffffffff81545bd5)
Location: arch/x86/include/asm/special_insns.h:182
Inline: True
Inline callers:
  - arch/x86/lib/cache-smp.c:__wbinvd
```
```
In drivers/acpi/sleep.c (ffffffff815b5155)
Location: arch/x86/include/asm/special_insns.h:182
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_hibernation_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/acpi/acpica/hwesleep.c (ffffffff815dbae8)
Location: arch/x86/include/asm/special_insns.h:182
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
```
```
In drivers/acpi/acpica/hwsleep.c (ffffffff815dc8fc)
Location: arch/x86/include/asm/special_insns.h:182
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
```
```
In drivers/acpi/acpica/hwxfsleep.c (ffffffff815dd12e)
Location: arch/x86/include/asm/special_insns.h:182
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff815efc1d)
Location: arch/x86/include/asm/special_insns.h:182
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
```
```
In drivers/char/agp/generic.c (ffffffff8166a765)
Location: arch/x86/include/asm/special_insns.h:182
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:ipi_handler
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81055be1)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064f29)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff828be00c)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
```
In arch/x86/kernel/tce_64.c (ffffffff8107c3b3)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_free
  - arch/x86/kernel/tce_64.c:tce_build
```
```
In arch/x86/mm/pageattr.c (ffffffff810814aa)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__cpa_flush_all
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c312a)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
```
In arch/x86/lib/cache-smp.c (ffffffff81551645)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
Inline callers:
  - arch/x86/lib/cache-smp.c:__wbinvd
```
```
In drivers/acpi/sleep.c (ffffffff815cd9c5)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_hibernation_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/acpi/acpica/hwesleep.c (ffffffff81602ffa)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
```
```
In drivers/acpi/acpica/hwsleep.c (ffffffff816043c0)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
```
```
In drivers/acpi/acpica/hwxfsleep.c (ffffffff81605361)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff81629910)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
```
```
In drivers/char/agp/generic.c (ffffffff816bafd5)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:ipi_handler
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81057081)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/smpboot.c (ffffffff81066509)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff828c1159)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
```
In arch/x86/kernel/tce_64.c (ffffffff8107e4b3)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_free
  - arch/x86/kernel/tce_64.c:tce_build
```
```
In arch/x86/mm/pageattr.c (ffffffff810835ca)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__cpa_flush_all
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c62d0)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
```
In arch/x86/lib/cache-smp.c (ffffffff8156b4a5)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
Inline callers:
  - arch/x86/lib/cache-smp.c:__wbinvd
```
```
In drivers/acpi/sleep.c (ffffffff815e7865)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_hibernation_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/acpi/acpica/hwesleep.c (ffffffff8161ceaa)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
```
```
In drivers/acpi/acpica/hwsleep.c (ffffffff8161e270)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
```
```
In drivers/acpi/acpica/hwxfsleep.c (ffffffff8161f211)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff816437b0)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
```
```
In drivers/char/agp/generic.c (ffffffff816d55a5)
Location: arch/x86/include/asm/paravirt.h:152
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:ipi_handler
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
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
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
</ul>
