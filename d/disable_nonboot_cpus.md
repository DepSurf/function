# Function: <code>disable_nonboot_cpus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int disable_nonboot_cpus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81081b40)
Location: kernel/cpu.c:572
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff81081b40-ffffffff81081d0a: disable_nonboot_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int disable_nonboot_cpus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81084c90)
Location: kernel/cpu.c:1027
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
  - arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable
```
**Symbols:**

```
ffffffff81084c90-ffffffff81084e53: disable_nonboot_cpus (STB_GLOBAL)
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
In kernel/power/suspend.c (ffffffff810d9d5d)
Location: include/linux/cpu.h:123
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
```
```
In kernel/power/hibernate.c (ffffffff810db485)
Location: include/linux/cpu.h:123
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable
  - kernel/power/hibernate.c:hibernation_snapshot
```
```
In kernel/kexec_core.c (ffffffff8111cd4a)
Location: include/linux/cpu.h:123
Inline: True
Inline callers:
  - kernel/kexec_core.c:kernel_kexec
```
```
In arch/x86/power/cpu.c (ffffffff8178d556)
Location: include/linux/cpu.h:123
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable
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
In kernel/power/suspend.c (ffffffff810d8dff)
Location: include/linux/cpu.h:131
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
```
```
In kernel/power/hibernate.c (ffffffff810da597)
Location: include/linux/cpu.h:131
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable
  - kernel/power/hibernate.c:hibernation_snapshot
```
```
In kernel/kexec_core.c (ffffffff8111e978)
Location: include/linux/cpu.h:131
Inline: True
Inline callers:
  - kernel/kexec_core.c:kernel_kexec
```
```
In arch/x86/power/cpu.c (ffffffff817ab6e6)
Location: include/linux/cpu.h:131
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable
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
In kernel/power/suspend.c (ffffffff810e0ce9)
Location: include/linux/cpu.h:129
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
```
```
In kernel/power/hibernate.c (ffffffff810e2742)
Location: include/linux/cpu.h:129
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable
  - kernel/power/hibernate.c:hibernation_snapshot
```
```
In kernel/kexec_core.c (ffffffff8112a0d8)
Location: include/linux/cpu.h:129
Inline: True
Inline callers:
  - kernel/kexec_core.c:kernel_kexec
```
```
In arch/x86/power/cpu.c (ffffffff81822c56)
Location: include/linux/cpu.h:129
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable
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
In kernel/power/suspend.c (ffffffff810e92e3)
Location: include/linux/cpu.h:133
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
```
```
In kernel/power/hibernate.c (ffffffff810eaa6c)
Location: include/linux/cpu.h:133
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable
  - kernel/power/hibernate.c:hibernation_snapshot
```
```
In kernel/kexec_core.c (ffffffff81137ffe)
Location: include/linux/cpu.h:133
Inline: True
Inline callers:
  - kernel/kexec_core.c:kernel_kexec
```
```
In arch/x86/power/cpu.c (ffffffff8186ceae)
Location: include/linux/cpu.h:133
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable
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
In kernel/power/suspend.c (ffffffff810f4903)
Location: include/linux/cpu.h:135
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
```
```
In kernel/power/hibernate.c (ffffffff810f609c)
Location: include/linux/cpu.h:135
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable
  - kernel/power/hibernate.c:hibernation_snapshot
```
```
In kernel/kexec_core.c (ffffffff8114381e)
Location: include/linux/cpu.h:135
Inline: True
Inline callers:
  - kernel/kexec_core.c:kernel_kexec
```
```
In arch/x86/power/cpu.c (ffffffff8188cebe)
Location: include/linux/cpu.h:135
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/power/cpu.c (ffffffff818d7865)
Location: include/linux/cpu.h:137
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/power/cpu.c (ffffffff81909ba5)
Location: include/linux/cpu.h:142
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/process.c (ffff800010089008)
Location: include/linux/cpu.h:142
Inline: True
Inline callers:
  - arch/arm64/kernel/process.c:machine_shutdown
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/reboot.c (c030d310)
Location: include/linux/cpu.h:142
Inline: True
Inline callers:
  - arch/arm/kernel/reboot.c:machine_shutdown
```
</details>
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/power/cpu.c (ffffffff818a8f65)
Location: include/linux/cpu.h:142
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/power/cpu.c (ffffffff81863bd5)
Location: include/linux/cpu.h:142
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/power/cpu.c (ffffffff818fa5c5)
Location: include/linux/cpu.h:142
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/power/cpu.c (ffffffff8191b725)
Location: include/linux/cpu.h:142
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable
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
</ul>
