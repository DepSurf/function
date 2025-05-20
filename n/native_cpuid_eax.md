# Function: <code>native_cpuid_eax</code>

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
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff81041a2a)
Location: arch/x86/include/asm/processor.h:236
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81050321)
Location: arch/x86/include/asm/processor.h:236
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
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
In arch/x86/kernel/cpu/intel.c (ffffffff8103fb0f)
Location: arch/x86/include/asm/processor.h:229
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104f2bf)
Location: arch/x86/include/asm/processor.h:229
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104fb88)
Location: arch/x86/include/asm/processor.h:229
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
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
In arch/x86/kernel/cpu/intel.c (ffffffff81042ddb)
Location: arch/x86/include/asm/processor.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81052d0f)
Location: arch/x86/include/asm/processor.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81053f62)
Location: arch/x86/include/asm/processor.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
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
In arch/x86/kernel/cpu/intel.c (ffffffff81044e31)
Location: arch/x86/include/asm/processor.h:231
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810559de)
Location: arch/x86/include/asm/processor.h:231
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81056ba8)
Location: arch/x86/include/asm/processor.h:231
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
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
In arch/x86/kernel/cpu/intel.c (ffffffff81046841)
Location: arch/x86/include/asm/processor.h:220
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105307e)
Location: arch/x86/include/asm/processor.h:220
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81054238)
Location: arch/x86/include/asm/processor.h:220
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
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
In arch/x86/kernel/cpu/intel.c (ffffffff810490ff)
Location: arch/x86/include/asm/processor.h:223
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105622e)
Location: arch/x86/include/asm/processor.h:223
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105745c)
Location: arch/x86/include/asm/processor.h:223
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
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
In arch/x86/kernel/cpu/intel.c (ffffffff810499cf)
Location: arch/x86/include/asm/processor.h:223
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81056ade)
Location: arch/x86/include/asm/processor.h:223
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81057d2c)
Location: arch/x86/include/asm/processor.h:223
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
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
In arch/x86/kernel/cpu/intel.c (ffffffff8104e0b6)
Location: arch/x86/include/asm/processor.h:237
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105bc8f)
Location: arch/x86/include/asm/processor.h:237
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105cf02)
Location: arch/x86/include/asm/processor.h:237
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
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
In arch/x86/kernel/cpu/intel.c (ffffffff8104d5e6)
Location: arch/x86/include/asm/processor.h:237
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105a6df)
Location: arch/x86/include/asm/processor.h:237
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105b762)
Location: arch/x86/include/asm/processor.h:237
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
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
In arch/x86/kernel/cpu/intel.c (ffffffff8104f076)
Location: arch/x86/include/asm/processor.h:237
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105b07f)
Location: arch/x86/include/asm/processor.h:237
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105c112)
Location: arch/x86/include/asm/processor.h:237
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
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
In arch/x86/kernel/cpu/intel.c (ffffffff81057172)
Location: arch/x86/include/asm/processor.h:239
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81064619)
Location: arch/x86/include/asm/processor.h:239
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810658ac)
Location: arch/x86/include/asm/processor.h:239
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
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
In arch/x86/kernel/cpu/intel.c (ffffffff8106360f)
Location: arch/x86/include/asm/processor.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:intel_cpu_collect_info
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81070ef7)
Location: arch/x86/include/asm/processor.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8107232c)
Location: arch/x86/include/asm/processor.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
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
In arch/x86/kernel/cpu/intel.c (ffffffff81072778)
Location: arch/x86/include/asm/cpuid.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:intel_cpu_collect_info
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81080fa7)
Location: arch/x86/include/asm/cpuid.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8108212f)
Location: arch/x86/include/asm/cpuid.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
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
In arch/x86/kernel/cpu/intel.c (ffffffff8107435d)
Location: arch/x86/include/asm/cpuid.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/intel.c:intel_cpu_collect_info
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81083427)
Location: arch/x86/include/asm/cpuid.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810845cc)
Location: arch/x86/include/asm/cpuid.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
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
In arch/x86/kernel/cpu/intel.c (ffffffff8107b84c)
Location: arch/x86/include/asm/cpuid.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8108aeb7)
Location: arch/x86/include/asm/cpuid.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8108bd2b)
Location: arch/x86/include/asm/cpuid.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_ap
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_ap
  - arch/x86/kernel/cpu/microcode/intel.c:intel_collect_cpu_info
```
```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/include/asm/cpuid.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd
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
In arch/x86/kernel/cpu/intel.c (ffffffff81049b3f)
Location: arch/x86/include/asm/processor.h:223
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105665e)
Location: arch/x86/include/asm/processor.h:223
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810578ac)
Location: arch/x86/include/asm/processor.h:223
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
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
In arch/x86/kernel/cpu/intel.c (ffffffff81038e79)
Location: arch/x86/include/asm/processor.h:223
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104686e)
Location: arch/x86/include/asm/processor.h:223
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81047a92)
Location: arch/x86/include/asm/processor.h:223
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
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
In arch/x86/kernel/cpu/intel.c (ffffffff8104997f)
Location: arch/x86/include/asm/processor.h:223
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81056a8e)
Location: arch/x86/include/asm/processor.h:223
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81057cdc)
Location: arch/x86/include/asm/processor.h:223
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
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
In arch/x86/kernel/cpu/intel.c (ffffffff8104ad8f)
Location: arch/x86/include/asm/processor.h:223
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81057f2e)
Location: arch/x86/include/asm/processor.h:223
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105917c)
Location: arch/x86/include/asm/processor.h:223
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
```
</details>
</li>
</ul>

## Differences
