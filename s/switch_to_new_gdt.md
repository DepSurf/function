# Function: <code>switch_to_new_gdt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void switch_to_new_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81040430)
Location: arch/x86/kernel/cpu/common.c:386
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_setup_gdt
  - arch/x86/xen/enlighten.c:xen_setup_gdt
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
```
**Symbols:**

```
ffffffff81040430-ffffffff81040473: switch_to_new_gdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void switch_to_new_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81040280)
Location: arch/x86/kernel/cpu/common.c:450
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_setup_gdt
  - arch/x86/xen/enlighten.c:xen_setup_gdt
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
```
**Symbols:**

```
ffffffff81040280-ffffffff810402c3: switch_to_new_gdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void switch_to_new_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8103fcc0)
Location: arch/x86/kernel/cpu/common.c:453
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_setup_gdt
  - arch/x86/xen/enlighten.c:xen_setup_gdt
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
```
**Symbols:**

```
ffffffff8103fcc0-ffffffff8103fd03: switch_to_new_gdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void switch_to_new_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8103dc30)
Location: arch/x86/kernel/cpu/common.c:500
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
```
**Symbols:**

```
ffffffff8103dc30-ffffffff8103dc73: switch_to_new_gdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void switch_to_new_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104171f)
Location: arch/x86/kernel/cpu/common.c:539
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
```
**Symbols:**

```
ffffffff810407c0-ffffffff810407d6: switch_to_new_gdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void switch_to_new_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81042fef)
Location: arch/x86/kernel/cpu/common.c:549
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
```
**Symbols:**

```
ffffffff81042010-ffffffff81042026: switch_to_new_gdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void switch_to_new_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81044657)
Location: arch/x86/kernel/cpu/common.c:549
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
```
**Symbols:**

```
ffffffff81043630-ffffffff81043646: switch_to_new_gdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void switch_to_new_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81046c05)
Location: arch/x86/kernel/cpu/common.c:613
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
```
**Symbols:**

```
ffffffff81045b90-ffffffff81045baa: switch_to_new_gdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void switch_to_new_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81047385)
Location: arch/x86/kernel/cpu/common.c:613
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
```
**Symbols:**

```
ffffffff810462f0-ffffffff8104630a: switch_to_new_gdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void switch_to_new_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104b156)
Location: arch/x86/kernel/cpu/common.c:618
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
```
**Symbols:**

```
ffffffff8104a2a0-ffffffff8104a2bc: switch_to_new_gdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void switch_to_new_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104a827)
Location: arch/x86/kernel/cpu/common.c:636
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
```
**Symbols:**

```
ffffffff81049740-ffffffff8104975c: switch_to_new_gdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void switch_to_new_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104c0f0)
Location: arch/x86/kernel/cpu/common.c:634
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
```
**Symbols:**

```
ffffffff8104aec0-ffffffff8104aedc: switch_to_new_gdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void switch_to_new_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8105344a)
Location: arch/x86/kernel/cpu/common.c:637
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
```
**Symbols:**

```
ffffffff81051f90-ffffffff81051fac: switch_to_new_gdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void switch_to_new_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8105eece)
Location: arch/x86/kernel/cpu/common.c:745
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
```
**Symbols:**

```
ffffffff8105d910-ffffffff8105d92f: switch_to_new_gdt (STB_GLOBAL)
```
</details>
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void switch_to_new_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81047505)
Location: arch/x86/kernel/cpu/common.c:613
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
```
**Symbols:**

```
ffffffff81046470-ffffffff8104648a: switch_to_new_gdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void switch_to_new_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81036674)
Location: arch/x86/kernel/cpu/common.c:613
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
Direct callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
```
**Symbols:**

```
ffffffff81035770-ffffffff810357a1: switch_to_new_gdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void switch_to_new_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81047345)
Location: arch/x86/kernel/cpu/common.c:613
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
```
**Symbols:**

```
ffffffff810462b0-ffffffff810462ca: switch_to_new_gdt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void switch_to_new_gdt(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81048745)
Location: arch/x86/kernel/cpu/common.c:613
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
```
**Symbols:**

```
ffffffff810476b0-ffffffff810476ca: switch_to_new_gdt (STB_GLOBAL)
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
