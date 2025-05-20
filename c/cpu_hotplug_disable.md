# Function: <code>cpu_hotplug_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cpu_hotplug_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81081120)
Location: kernel/cpu.c:178
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_callback
  - kernel/reboot.c:migrate_to_reboot_cpu
```
**Symbols:**

```
ffffffff81081120-ffffffff8108114a: cpu_hotplug_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cpu_hotplug_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81083630)
Location: kernel/cpu.c:255
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_callback
  - kernel/reboot.c:migrate_to_reboot_cpu
```
**Symbols:**

```
ffffffff81083630-ffffffff8108365a: cpu_hotplug_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cpu_hotplug_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810880f0)
Location: kernel/cpu.c:321
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_callback
  - kernel/reboot.c:migrate_to_reboot_cpu
```
**Symbols:**

```
ffffffff810880f0-ffffffff8108811a: cpu_hotplug_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cpu_hotplug_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81085150)
Location: kernel/cpu.c:250
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_callback
  - kernel/reboot.c:migrate_to_reboot_cpu
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_driver.c:acpi_processor_start
```
**Symbols:**

```
ffffffff81085150-ffffffff8108517a: cpu_hotplug_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cpu_hotplug_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108bcb0)
Location: kernel/cpu.c:325
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_callback
  - kernel/reboot.c:migrate_to_reboot_cpu
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_driver.c:acpi_processor_start
```
**Symbols:**

```
ffffffff8108bcb0-ffffffff8108bcda: cpu_hotplug_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cpu_hotplug_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108f4c0)
Location: kernel/cpu.c:322
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_callback
  - kernel/reboot.c:migrate_to_reboot_cpu
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_driver.c:acpi_processor_start
```
**Symbols:**

```
ffffffff8108f4c0-ffffffff8108f4ea: cpu_hotplug_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cpu_hotplug_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810977c0)
Location: kernel/cpu.c:336
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_callback
  - kernel/reboot.c:migrate_to_reboot_cpu
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/powercap/idle_inject.c:idle_inject_stop
```
**Symbols:**

```
ffffffff810977c0-ffffffff810977ea: cpu_hotplug_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cpu_hotplug_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109bd40)
Location: kernel/cpu.c:346
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_callback
  - kernel/reboot.c:migrate_to_reboot_cpu
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - arch/x86/power/hibernate.c:arch_resume_nosmt
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff8109bd40-ffffffff8109bd6a: cpu_hotplug_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cpu_hotplug_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a22c0)
Location: kernel/cpu.c:349
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_callback
  - kernel/reboot.c:migrate_to_reboot_cpu
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - arch/x86/power/hibernate.c:arch_resume_nosmt
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff810a22c0-ffffffff810a22ea: cpu_hotplug_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void cpu_hotplug_disable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a945b)
Location: kernel/cpu.c:350
Inline: True
Inline callers:
  - kernel/cpu.c:cpu_hotplug_pm_callback
Direct callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
  - drivers/pci/pci-driver.c:pci_call_probe
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - arch/x86/power/hibernate.c:arch_resume_nosmt
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff810a8fc0-ffffffff810a8fea: cpu_hotplug_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void cpu_hotplug_disable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a4eab)
Location: kernel/cpu.c:350
Inline: True
Inline callers:
  - kernel/cpu.c:cpu_hotplug_pm_callback
Direct callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
  - drivers/pci/pci-driver.c:pci_call_probe
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - arch/x86/power/hibernate.c:arch_resume_nosmt
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff810a4a10-ffffffff810a4a3a: cpu_hotplug_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void cpu_hotplug_disable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a5bab)
Location: kernel/cpu.c:362
Inline: True
Inline callers:
  - kernel/cpu.c:cpu_hotplug_pm_callback
Direct callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - arch/x86/power/hibernate.c:arch_resume_nosmt
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff810a56e0-ffffffff810a570a: cpu_hotplug_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void cpu_hotplug_disable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810b753b)
Location: kernel/cpu.c:373
Inline: True
Inline callers:
  - kernel/cpu.c:cpu_hotplug_pm_callback
Direct callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - arch/x86/power/hibernate.c:arch_resume_nosmt
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff810b6f20-ffffffff810b6f4a: cpu_hotplug_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void cpu_hotplug_disable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810cdd2b)
Location: kernel/cpu.c:374
Inline: True
Inline callers:
  - kernel/cpu.c:cpu_hotplug_pm_callback
Direct callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
  - drivers/pci/pci-driver.c:pci_call_probe
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - arch/x86/power/hibernate.c:arch_resume_nosmt
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff810cd680-ffffffff810cd6b0: cpu_hotplug_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void cpu_hotplug_disable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810ebecb)
Location: kernel/cpu.c:374
Inline: True
Inline callers:
  - kernel/cpu.c:cpu_hotplug_pm_callback
Direct callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
  - drivers/pci/pci-driver.c:pci_call_probe
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - arch/x86/power/hibernate.c:arch_resume_nosmt
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff810eb760-ffffffff810eb790: cpu_hotplug_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void cpu_hotplug_disable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810f7bab)
Location: kernel/cpu.c:553
Inline: True
Inline callers:
  - kernel/cpu.c:cpu_hotplug_pm_callback
Direct callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
  - drivers/pci/pci-driver.c:pci_call_probe
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - arch/x86/power/hibernate.c:arch_resume_nosmt
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff810f7440-ffffffff810f7470: cpu_hotplug_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void cpu_hotplug_disable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8110107b)
Location: kernel/cpu.c:553
Inline: True
Inline callers:
  - kernel/cpu.c:cpu_hotplug_pm_callback
Direct callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
  - drivers/pci/pci-driver.c:pci_call_probe
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - arch/x86/power/hibernate.c:arch_resume_nosmt
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff811007f0-ffffffff81100820: cpu_hotplug_disable (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void cpu_hotplug_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffff8000100f7398)
Location: kernel/cpu.c:349
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_callback
  - kernel/reboot.c:migrate_to_reboot_cpu
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/powercap/idle_inject.c:idle_inject_stop
```
**Symbols:**

```
ffff8000100f7398-ffff8000100f73e0: cpu_hotplug_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cpu_hotplug_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c0355814)
Location: kernel/cpu.c:349
Inline: False
Direct callers:
  - arch/arm/mach-mvebu/pmsu.c:mvebu_v7_cpu_pm_init
  - kernel/cpu.c:cpu_hotplug_pm_callback
  - kernel/reboot.c:migrate_to_reboot_cpu
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/powercap/idle_inject.c:idle_inject_stop
```
**Symbols:**

```
c0355814-c0355858: cpu_hotplug_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cpu_hotplug_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c00000000013da20)
Location: kernel/cpu.c:349
Inline: False
Direct callers:
  - arch/powerpc/kernel/rtas.c:rtas_ibm_suspend_me
  - kernel/cpu.c:cpu_hotplug_pm_callback
  - kernel/reboot.c:migrate_to_reboot_cpu
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/powercap/idle_inject.c:idle_inject_stop
```
**Symbols:**

```
c00000000013da20-c00000000013da7c: cpu_hotplug_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (0)
Location: include/linux/cpu.h:130
Inline: True
```
```
In drivers/pci/pci-driver.c (0)
Location: include/linux/cpu.h:130
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void cpu_hotplug_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109bbe0)
Location: kernel/cpu.c:349
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_callback
  - kernel/reboot.c:migrate_to_reboot_cpu
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - arch/x86/power/hibernate.c:arch_resume_nosmt
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff8109bbe0-ffffffff8109bc0a: cpu_hotplug_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cpu_hotplug_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108a610)
Location: kernel/cpu.c:349
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_callback
  - kernel/reboot.c:migrate_to_reboot_cpu
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - arch/x86/power/hibernate.c:arch_resume_nosmt
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff8108a610-ffffffff8108a63a: cpu_hotplug_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cpu_hotplug_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109bb90)
Location: kernel/cpu.c:349
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_callback
  - kernel/reboot.c:migrate_to_reboot_cpu
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - arch/x86/power/hibernate.c:arch_resume_nosmt
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff8109bb90-ffffffff8109bbba: cpu_hotplug_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cpu_hotplug_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a3800)
Location: kernel/cpu.c:349
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_callback
  - kernel/reboot.c:migrate_to_reboot_cpu
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - arch/x86/power/hibernate.c:arch_resume_nosmt
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff810a3800-ffffffff810a382a: cpu_hotplug_disable (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
