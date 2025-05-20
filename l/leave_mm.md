# Function: <code>leave_mm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void leave_mm(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810724e0)
Location: arch/x86/mm/tlb.c:41
Inline: True
Direct callers:
  - arch/x86/xen/mmu.c:xen_exit_mmap
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
  - arch/x86/mm/tlb.c:flush_tlb_page
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff810724e0-ffffffff810725ae: leave_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void leave_mm(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810721d0)
Location: arch/x86/mm/tlb.c:43
Inline: True
Direct callers:
  - arch/x86/xen/mmu.c:xen_exit_mmap
  - arch/x86/mm/tlb.c:flush_tlb_page
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff810721d0-ffffffff81072291: leave_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void leave_mm(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81075d40)
Location: arch/x86/mm/tlb.c:43
Inline: True
Direct callers:
  - arch/x86/xen/mmu.c:xen_exit_mmap
  - arch/x86/mm/tlb.c:flush_tlb_page
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff81075d40-ffffffff81075e00: leave_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void leave_mm(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81074890)
Location: arch/x86/mm/tlb.c:31
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff81074890-ffffffff810748ca: leave_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void leave_mm(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8107a7f0)
Location: arch/x86/mm/tlb.c:123
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff8107a7f0-ffffffff8107a82a: leave_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void leave_mm(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8107d5a0)
Location: arch/x86/mm/tlb.c:123
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff8107d5a0-ffffffff8107d5da: leave_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void leave_mm(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810840d0)
Location: arch/x86/mm/tlb.c:131
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff810840d0-ffffffff8108410a: leave_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void leave_mm(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/tlb.c (0)
Location: arch/x86/mm/tlb.c:132
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff81088500-ffffffff81088513: leave_mm.cold (STB_LOCAL)
ffffffff81087d60-ffffffff81087d9b: leave_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void leave_mm(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81088a20)
Location: arch/x86/mm/tlb.c:132
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff81088a20-ffffffff81088a5b: leave_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void leave_mm(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108b2c0)
Location: arch/x86/mm/tlb.c:288
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff8108b2c0-ffffffff8108b31b: leave_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void leave_mm(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108b380)
Location: arch/x86/mm/tlb.c:287
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - arch/x86/kernel/alternative.c:__text_poke
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
**Symbols:**

```
ffffffff8108b380-ffffffff8108b3db: leave_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void leave_mm(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108bf00)
Location: arch/x86/mm/tlb.c:288
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - arch/x86/kernel/alternative.c:__text_poke
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
**Symbols:**

```
ffffffff8108bf00-ffffffff8108bf63: leave_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void leave_mm(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8109b6c0)
Location: arch/x86/mm/tlb.c:295
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - arch/x86/kernel/alternative.c:__text_poke
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
**Symbols:**

```
ffffffff8109b6c0-ffffffff8109b723: leave_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void leave_mm(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810ae920)
Location: arch/x86/mm/tlb.c:296
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - arch/x86/kernel/alternative.c:__text_poke
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
**Symbols:**

```
ffffffff810ae920-ffffffff810ae973: leave_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void leave_mm(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810c8c50)
Location: arch/x86/mm/tlb.c:296
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - arch/x86/kernel/alternative.c:__text_poke
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
**Symbols:**

```
ffffffff810c8c50-ffffffff810c8ca3: leave_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void leave_mm(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810cc290)
Location: arch/x86/mm/tlb.c:301
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - arch/x86/kernel/alternative.c:__text_poke
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
**Symbols:**

```
ffffffff810cc290-ffffffff810cc2e3: leave_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void leave_mm(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810d4920)
Location: arch/x86/mm/tlb.c:302
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - arch/x86/kernel/alternative.c:__text_poke
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
**Symbols:**

```
ffffffff810d4920-ffffffff810d4973: leave_mm (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void leave_mm(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81087a20)
Location: arch/x86/mm/tlb.c:132
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff81087a20-ffffffff81087a5b: leave_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void leave_mm(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81076680)
Location: arch/x86/mm/tlb.c:132
Inline: False
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff81076680-ffffffff810766c2: leave_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void leave_mm(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810879d0)
Location: arch/x86/mm/tlb.c:132
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff810879d0-ffffffff81087a0b: leave_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void leave_mm(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81089b80)
Location: arch/x86/mm/tlb.c:132
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff81089b80-ffffffff81089bbb: leave_mm (STB_GLOBAL)
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
