# Function: <code>cpuid_ecx</code>

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
In arch/x86/xen/enlighten.c (ffffffff8101bc9f)
Location: arch/x86/include/asm/processor.h:542
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_read_msr_safe
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104098e)
Location: arch/x86/include/asm/processor.h:542
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:get_cpu_cap
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104286b)
Location: arch/x86/include/asm/processor.h:542
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
```
```
In arch/x86/kernel/reboot.c (ffffffff81050168)
Location: arch/x86/include/asm/processor.h:542
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/crash.c (ffffffff8105d62d)
Location: arch/x86/include/asm/processor.h:542
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:kdump_nmi_callback
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
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
In arch/x86/xen/enlighten.c (ffffffff8101b12e)
Location: arch/x86/include/asm/processor.h:553
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_read_msr_safe
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff810427db)
Location: arch/x86/include/asm/processor.h:553
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/reboot.c (ffffffff810504cc)
Location: arch/x86/include/asm/processor.h:553
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/crash.c (ffffffff8105d728)
Location: arch/x86/include/asm/processor.h:553
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
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
In arch/x86/xen/enlighten.c (ffffffff8101b85e)
Location: arch/x86/include/asm/processor.h:595
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_read_msr_safe
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff810422cb)
Location: arch/x86/include/asm/processor.h:595
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81fd1063)
Location: arch/x86/include/asm/processor.h:595
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/reboot.c (ffffffff81052d3c)
Location: arch/x86/include/asm/processor.h:595
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/crash.c (ffffffff810607a5)
Location: arch/x86/include/asm/processor.h:595
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
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
In arch/x86/xen/enlighten_pv.c (ffffffff820a5d04)
Location: arch/x86/include/asm/processor.h:606
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_read_msr_safe
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff810403e9)
Location: arch/x86/include/asm/processor.h:606
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff820b1b9c)
Location: arch/x86/include/asm/processor.h:606
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/reboot.c (ffffffff8105284c)
Location: arch/x86/include/asm/processor.h:606
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81053125)
Location: arch/x86/include/asm/processor.h:606
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff8105f825)
Location: arch/x86/include/asm/processor.h:606
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff826ac3f9)
Location: arch/x86/include/asm/processor.h:628
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_read_msr_safe
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81043885)
Location: arch/x86/include/asm/processor.h:628
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff826b841c)
Location: arch/x86/include/asm/processor.h:628
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/reboot.c (ffffffff8105655a)
Location: arch/x86/include/asm/processor.h:628
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/smp.c (ffffffff81056e58)
Location: arch/x86/include/asm/processor.h:628
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff81063858)
Location: arch/x86/include/asm/processor.h:628
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
**Symbols:**

```
ffffffff810563a0-ffffffff810563f5: cpuid_ecx.constprop.6 (STB_LOCAL)
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
In arch/x86/xen/enlighten_pv.c (ffffffff826d5545)
Location: arch/x86/include/asm/processor.h:644
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_read_msr_safe
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81045c5c)
Location: arch/x86/include/asm/processor.h:644
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff826e210c)
Location: arch/x86/include/asm/processor.h:644
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/reboot.c (ffffffff81059785)
Location: arch/x86/include/asm/processor.h:644
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81059ccf)
Location: arch/x86/include/asm/processor.h:644
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff81066509)
Location: arch/x86/include/asm/processor.h:644
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff8288b5c9)
Location: arch/x86/include/asm/processor.h:639
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff810476b6)
Location: arch/x86/include/asm/processor.h:639
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104834a)
Location: arch/x86/include/asm/processor.h:639
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff82898a5a)
Location: arch/x86/include/asm/processor.h:639
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/reboot.c (ffffffff8105f02d)
Location: arch/x86/include/asm/processor.h:639
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/smp.c (ffffffff8105f94f)
Location: arch/x86/include/asm/processor.h:639
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff8106c519)
Location: arch/x86/include/asm/processor.h:639
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
**Symbols:**

```
ffffffff8105ee40-ffffffff8105ee95: cpuid_ecx.constprop.4 (STB_LOCAL)
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
In arch/x86/xen/enlighten_pv.c (ffffffff828a2a09)
Location: arch/x86/include/asm/processor.h:629
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104a47e)
Location: arch/x86/include/asm/processor.h:629
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104b0e4)
Location: arch/x86/include/asm/processor.h:629
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff828b065e)
Location: arch/x86/include/asm/processor.h:629
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/reboot.c (ffffffff8106283a)
Location: arch/x86/include/asm/processor.h:629
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81062dbe)
Location: arch/x86/include/asm/processor.h:629
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff81070519)
Location: arch/x86/include/asm/processor.h:629
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
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
In arch/x86/xen/enlighten_pv.c (ffffffff828a5ac8)
Location: arch/x86/include/asm/processor.h:629
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104ae08)
Location: arch/x86/include/asm/processor.h:629
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104bae4)
Location: arch/x86/include/asm/processor.h:629
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff828b3aa6)
Location: arch/x86/include/asm/processor.h:629
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/reboot.c (ffffffff810630aa)
Location: arch/x86/include/asm/processor.h:629
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff8106347e)
Location: arch/x86/include/asm/processor.h:629
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff81071519)
Location: arch/x86/include/asm/processor.h:629
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
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
In arch/x86/xen/enlighten_pv.c (ffffffff82ccba5c)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104f92e)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff810503b2)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff82cd8b1f)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/reboot.c (ffffffff81068f61)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:emergency_vmx_disable_all
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81069281)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
```
In arch/x86/kernel/crash.c (ffffffff81078623)
Location: arch/x86/include/asm/processor.h:663
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
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
In arch/x86/xen/enlighten_pv.c (ffffffff82fb78ca)
Location: arch/x86/include/asm/processor.h:646
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104eb8e)
Location: arch/x86/include/asm/processor.h:646
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104f482)
Location: arch/x86/include/asm/processor.h:646
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff82fc4f3d)
Location: arch/x86/include/asm/processor.h:646
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/reboot.c (ffffffff8106abb2)
Location: arch/x86/include/asm/processor.h:646
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:emergency_vmx_disable_all
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff8106aea1)
Location: arch/x86/include/asm/processor.h:646
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
```
In arch/x86/kernel/crash.c (ffffffff81078628)
Location: arch/x86/include/asm/processor.h:646
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
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
In arch/x86/xen/enlighten_pv.c (ffffffff831c233e)
Location: arch/x86/include/asm/processor.h:628
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff810504e6)
Location: arch/x86/include/asm/processor.h:628
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff81050f42)
Location: arch/x86/include/asm/processor.h:628
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff831cf800)
Location: arch/x86/include/asm/processor.h:628
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/reboot.c (ffffffff8106b822)
Location: arch/x86/include/asm/processor.h:628
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff8106bc91)
Location: arch/x86/include/asm/processor.h:628
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
```
In arch/x86/kernel/crash.c (ffffffff810794e8)
Location: arch/x86/include/asm/processor.h:628
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
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
In arch/x86/xen/enlighten_pv.c (ffffffff832a2da3)
Location: arch/x86/include/asm/processor.h:640
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff810587f2)
Location: arch/x86/include/asm/processor.h:640
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff81059377)
Location: arch/x86/include/asm/processor.h:640
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff832b1c72)
Location: arch/x86/include/asm/processor.h:640
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/reboot.c (ffffffff8107631f)
Location: arch/x86/include/asm/processor.h:640
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81076771)
Location: arch/x86/include/asm/processor.h:640
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
```
In arch/x86/kernel/crash.c (ffffffff81087548)
Location: arch/x86/include/asm/processor.h:640
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
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
In arch/x86/xen/enlighten_pv.c (ffffffff83451c25)
Location: arch/x86/include/asm/processor.h:640
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8106504d)
Location: arch/x86/include/asm/processor.h:640
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff81065a5c)
Location: arch/x86/include/asm/processor.h:640
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff83462edd)
Location: arch/x86/include/asm/processor.h:640
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/reboot.c (ffffffff81085064)
Location: arch/x86/include/asm/processor.h:640
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81085350)
Location: arch/x86/include/asm/processor.h:640
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
```
In arch/x86/kernel/crash.c (ffffffff8109768c)
Location: arch/x86/include/asm/processor.h:640
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
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
In arch/x86/xen/enlighten_pv.c (ffffffff83e6e837)
Location: arch/x86/include/asm/cpuid.h:112
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81074320)
Location: arch/x86/include/asm/cpuid.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff81074d8c)
Location: arch/x86/include/asm/cpuid.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff83e859ef)
Location: arch/x86/include/asm/cpuid.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/reboot.c (ffffffff81097e61)
Location: arch/x86/include/asm/cpuid.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
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
In arch/x86/xen/enlighten_pv.c (ffffffff8368f569)
Location: arch/x86/include/asm/cpuid.h:112
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff810761cd)
Location: arch/x86/include/asm/cpuid.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff81076efc)
Location: arch/x86/include/asm/cpuid.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff836a8eef)
Location: arch/x86/include/asm/cpuid.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/reboot.c (ffffffff8109af01)
Location: arch/x86/include/asm/cpuid.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
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
In arch/x86/xen/enlighten_pv.c (ffffffff838bf259)
Location: arch/x86/include/asm/cpuid.h:112
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_init_capabilities
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8107d2b1)
Location: arch/x86/include/asm/cpuid.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8107e47c)
Location: arch/x86/include/asm/cpuid.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff838d9586)
Location: arch/x86/include/asm/cpuid.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
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
In arch/x86/xen/enlighten_pv.c (ffffffff82893ad1)
Location: arch/x86/include/asm/processor.h:629
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104af78)
Location: arch/x86/include/asm/processor.h:629
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104bc54)
Location: arch/x86/include/asm/processor.h:629
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff828a1ac5)
Location: arch/x86/include/asm/processor.h:629
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/reboot.c (ffffffff81062b9a)
Location: arch/x86/include/asm/processor.h:629
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81062f6e)
Location: arch/x86/include/asm/processor.h:629
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff81070519)
Location: arch/x86/include/asm/processor.h:629
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
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
In arch/x86/kernel/cpu/amd.c (ffffffff8103a1d8)
Location: arch/x86/include/asm/processor.h:629
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8103ade8)
Location: arch/x86/include/asm/processor.h:629
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff82899bcb)
Location: arch/x86/include/asm/processor.h:629
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/reboot.c (ffffffff81052f64)
Location: arch/x86/include/asm/processor.h:629
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81053297)
Location: arch/x86/include/asm/processor.h:629
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff81060523)
Location: arch/x86/include/asm/processor.h:629
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
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
In arch/x86/xen/enlighten_pv.c (ffffffff828a6ac8)
Location: arch/x86/include/asm/processor.h:629
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104adb8)
Location: arch/x86/include/asm/processor.h:629
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104ba94)
Location: arch/x86/include/asm/processor.h:629
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff828b4a88)
Location: arch/x86/include/asm/processor.h:629
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/reboot.c (ffffffff8106304a)
Location: arch/x86/include/asm/processor.h:629
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff8106341e)
Location: arch/x86/include/asm/processor.h:629
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff81070519)
Location: arch/x86/include/asm/processor.h:629
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
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
In arch/x86/xen/enlighten_pv.c (ffffffff828a6a9c)
Location: arch/x86/include/asm/processor.h:629
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104c1c8)
Location: arch/x86/include/asm/processor.h:629
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104cea4)
Location: arch/x86/include/asm/processor.h:629
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff828b4aa9)
Location: arch/x86/include/asm/processor.h:629
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/reboot.c (ffffffff8106460a)
Location: arch/x86/include/asm/processor.h:629
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff810649de)
Location: arch/x86/include/asm/processor.h:629
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff81072533)
Location: arch/x86/include/asm/processor.h:629
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
</details>
</li>
</ul>

## Differences
