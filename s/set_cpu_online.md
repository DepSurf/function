# Function: <code>set_cpu_online</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void set_cpu_online(unsigned int cpu, bool online);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81081f70)
Location: kernel/cpu.c:798
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - arch/x86/xen/smp.c:stop_self
  - arch/x86/xen/smp.c:cpu_bringup
  - arch/x86/kernel/process.c:stop_this_cpu
  - arch/x86/kernel/smpboot.c:start_secondary
  - arch/x86/kernel/smpboot.c:cpu_disable_common
```
**Symbols:**

```
ffffffff81081f70-ffffffff81081f9f: set_cpu_online (STB_GLOBAL)
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
In arch/x86/xen/smp.c (ffffffff8102a077)
Location: include/linux/cpumask.h:744
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:stop_self
  - arch/x86/xen/smp.c:cpu_bringup
```
```
In arch/x86/kernel/process.c (ffffffff81038620)
Location: include/linux/cpumask.h:744
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105276d)
Location: include/linux/cpumask.h:744
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In kernel/cpu.c (ffffffff81fa45e8)
Location: include/linux/cpumask.h:744
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
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
In arch/x86/xen/smp.c (ffffffff8102a7c7)
Location: include/linux/cpumask.h:749
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:stop_self
  - arch/x86/xen/smp.c:cpu_bringup
```
```
In arch/x86/kernel/process.c (ffffffff81037ff7)
Location: include/linux/cpumask.h:749
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105507c)
Location: include/linux/cpumask.h:749
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In kernel/cpu.c (ffffffff81fdff98)
Location: include/linux/cpumask.h:749
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
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
In arch/x86/xen/smp_pv.c (ffffffff810292e7)
Location: include/linux/cpumask.h:792
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
```
In arch/x86/kernel/process.c (ffffffff81036187)
Location: include/linux/cpumask.h:792
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/smpboot.c (ffffffff81054993)
Location: include/linux/cpumask.h:792
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In kernel/cpu.c (ffffffff820c0d9c)
Location: include/linux/cpumask.h:792
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
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
In arch/x86/xen/smp_pv.c (ffffffff810294d6)
Location: include/linux/cpumask.h:796
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
```
In arch/x86/kernel/process.c (ffffffff81038515)
Location: include/linux/cpumask.h:796
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/smpboot.c (ffffffff81058758)
Location: include/linux/cpumask.h:796
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In kernel/cpu.c (ffffffff826c8f97)
Location: include/linux/cpumask.h:796
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
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
In arch/x86/xen/smp_pv.c (ffffffff81029f46)
Location: include/linux/cpumask.h:798
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
```
In arch/x86/kernel/process.c (ffffffff81039a35)
Location: include/linux/cpumask.h:798
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105b3e9)
Location: include/linux/cpumask.h:798
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In kernel/cpu.c (ffffffff826f315a)
Location: include/linux/cpumask.h:798
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
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
In arch/x86/xen/smp_pv.c (ffffffff8102a526)
Location: include/linux/cpumask.h:810
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
```
In arch/x86/kernel/process.c (ffffffff8103af65)
Location: include/linux/cpumask.h:810
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/smpboot.c (ffffffff81061069)
Location: include/linux/cpumask.h:810
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In kernel/cpu.c (ffffffff828a9f42)
Location: include/linux/cpumask.h:810
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
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
In arch/x86/xen/smp_pv.c (ffffffff8102c37e)
Location: include/linux/cpumask.h:809
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
```
In arch/x86/kernel/process.c (ffffffff8103d577)
Location: include/linux/cpumask.h:809
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064704)
Location: include/linux/cpumask.h:809
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In kernel/cpu.c (ffffffff828c2739)
Location: include/linux/cpumask.h:809
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void set_cpu_online(unsigned int cpu, bool online);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a4560)
Location: kernel/cpu.c:2332
Inline: True
Direct callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/process.c:stop_this_cpu
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:start_secondary
  - kernel/cpu.c:boot_cpu_init
```
**Symbols:**

```
ffffffff810a4560-ffffffff810a4598: set_cpu_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void set_cpu_online(unsigned int cpu, bool online);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810ab830)
Location: kernel/cpu.c:2463
Inline: True
Direct callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/process.c:stop_this_cpu
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:start_secondary
  - kernel/cpu.c:boot_cpu_init
```
**Symbols:**

```
ffffffff810ab830-ffffffff810ab868: set_cpu_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void set_cpu_online(unsigned int cpu, bool online);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a70b0)
Location: kernel/cpu.c:2474
Inline: True
Direct callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/process.c:stop_this_cpu
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:start_secondary
  - kernel/cpu.c:boot_cpu_init
```
**Symbols:**

```
ffffffff810a70b0-ffffffff810a70e8: set_cpu_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void set_cpu_online(unsigned int cpu, bool online);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a8150)
Location: kernel/cpu.c:2594
Inline: True
Direct callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/process.c:stop_this_cpu
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:start_secondary
  - kernel/cpu.c:boot_cpu_init
```
**Symbols:**

```
ffffffff810a8150-ffffffff810a8188: set_cpu_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void set_cpu_online(unsigned int cpu, bool online);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810b9c00)
Location: kernel/cpu.c:2621
Inline: True
Direct callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/process.c:stop_this_cpu
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:start_secondary
  - kernel/cpu.c:boot_cpu_init
```
**Symbols:**

```
ffffffff810b9c00-ffffffff810b9c38: set_cpu_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void set_cpu_online(unsigned int cpu, bool online);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810d0700)
Location: kernel/cpu.c:2643
Inline: True
Direct callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/process.c:stop_this_cpu
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:start_secondary
  - kernel/cpu.c:boot_cpu_init
```
**Symbols:**

```
ffffffff810d0700-ffffffff810d0748: set_cpu_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void set_cpu_online(unsigned int cpu, bool online);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810eefe0)
Location: kernel/cpu.c:2669
Inline: True
Direct callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/process.c:stop_this_cpu
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:start_secondary
  - kernel/cpu.c:boot_cpu_init
```
**Symbols:**

```
ffffffff810eefe0-ffffffff810ef028: set_cpu_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void set_cpu_online(unsigned int cpu, bool online);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810faf90)
Location: kernel/cpu.c:3065
Inline: True
Direct callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
  - arch/x86/kernel/process.c:stop_this_cpu
  - arch/x86/kernel/smpboot.c:native_cpu_disable
  - arch/x86/kernel/smpboot.c:start_secondary
  - kernel/cpu.c:boot_cpu_init
```
**Symbols:**

```
ffffffff810faf90-ffffffff810fafd8: set_cpu_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void set_cpu_online(unsigned int cpu, bool online);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81104430)
Location: kernel/cpu.c:3147
Inline: True
Direct callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
  - arch/x86/kernel/process.c:stop_this_cpu
  - arch/x86/kernel/smpboot.c:native_cpu_disable
  - arch/x86/kernel/smpboot.c:start_secondary
  - kernel/cpu.c:boot_cpu_init
```
**Symbols:**

```
ffffffff81104430-ffffffff81104478: set_cpu_online (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void set_cpu_online(unsigned int cpu, bool online);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffff8000100fa1d0)
Location: kernel/cpu.c:2332
Inline: True
Direct callers:
  - arch/arm64/kernel/smp.c:local_cpu_stop
  - arch/arm64/kernel/smp.c:__cpu_disable
  - arch/arm64/kernel/smp.c:secondary_start_kernel
  - kernel/cpu.c:boot_cpu_init
```
**Symbols:**

```
ffff8000100fa1d0-ffff8000100fa2dc: set_cpu_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void set_cpu_online(unsigned int cpu, bool online);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c035838c)
Location: kernel/cpu.c:2332
Inline: True
Direct callers:
  - arch/arm/kernel/smp.c:panic_smp_self_stop
  - arch/arm/kernel/smp.c:handle_IPI
  - arch/arm/kernel/smp.c:secondary_start_kernel
  - arch/arm/kernel/smp.c:__cpu_disable
  - arch/arm/kernel/machine_kexec.c:machine_crash_nonpanic_core
  - kernel/cpu.c:boot_cpu_init
```
**Symbols:**

```
c035838c-c035840c: set_cpu_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_cpu_online(unsigned int cpu, bool online);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (c000000001365e4c)
Location: kernel/cpu.c:2332
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
Direct callers:
  - arch/powerpc/kernel/smp.c:start_secondary
  - arch/powerpc/kernel/smp.c:generic_cpu_disable
  - arch/powerpc/platforms/powernv/smp.c:pnv_smp_cpu_disable
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_cpu_disable
  - kernel/cpu.c:boot_cpu_init
```
**Symbols:**

```
c00000000013e110-c00000000013e178: set_cpu_online.part.0 (STB_LOCAL)
c0000000001413d0-c000000000141448: set_cpu_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void set_cpu_online(unsigned int cpu, bool online);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffe00000479e)
Location: kernel/cpu.c:2332
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
Direct callers:
  - arch/riscv/kernel/smpboot.c:smp_callin
  - arch/riscv/kernel/smp.c:riscv_software_interrupt
```
**Symbols:**

```
ffffffe0000c4352-ffffffe0000c43e2: set_cpu_online (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void set_cpu_online(unsigned int cpu, bool online);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109de80)
Location: kernel/cpu.c:2332
Inline: True
Direct callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/process.c:stop_this_cpu
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:start_secondary
  - kernel/cpu.c:boot_cpu_init
```
**Symbols:**

```
ffffffff8109de80-ffffffff8109deb8: set_cpu_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void set_cpu_online(unsigned int cpu, bool online);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108c8a0)
Location: kernel/cpu.c:2332
Inline: True
Direct callers:
  - arch/x86/kernel/process.c:stop_this_cpu
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:start_secondary
  - kernel/cpu.c:boot_cpu_init
```
**Symbols:**

```
ffffffff8108c8a0-ffffffff8108c8d8: set_cpu_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void set_cpu_online(unsigned int cpu, bool online);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109de30)
Location: kernel/cpu.c:2332
Inline: True
Direct callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/process.c:stop_this_cpu
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:start_secondary
  - kernel/cpu.c:boot_cpu_init
```
**Symbols:**

```
ffffffff8109de30-ffffffff8109de68: set_cpu_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void set_cpu_online(unsigned int cpu, bool online);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a5d20)
Location: kernel/cpu.c:2332
Inline: True
Direct callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/process.c:stop_this_cpu
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:start_secondary
  - kernel/cpu.c:boot_cpu_init
```
**Symbols:**

```
ffffffff810a5d20-ffffffff810a5d58: set_cpu_online (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
