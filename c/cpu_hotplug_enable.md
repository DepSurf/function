# Function: <code>cpu_hotplug_enable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cpu_hotplug_enable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810811a0)
Location: kernel/cpu.c:186
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_callback
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff810811a0-ffffffff810811eb: cpu_hotplug_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cpu_hotplug_enable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81083720)
Location: kernel/cpu.c:263
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_callback
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff81083720-ffffffff8108376b: cpu_hotplug_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cpu_hotplug_enable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810881c0)
Location: kernel/cpu.c:336
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_callback
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff810881c0-ffffffff810881e8: cpu_hotplug_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cpu_hotplug_enable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810851f0)
Location: kernel/cpu.c:265
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_callback
  - kernel/kexec_core.c:kernel_kexec
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_driver.c:acpi_processor_start
```
**Symbols:**

```
ffffffff810851f0-ffffffff81085218: cpu_hotplug_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cpu_hotplug_enable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108bd50)
Location: kernel/cpu.c:340
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_callback
  - kernel/kexec_core.c:kernel_kexec
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_driver.c:acpi_processor_start
```
**Symbols:**

```
ffffffff8108bd50-ffffffff8108bd78: cpu_hotplug_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cpu_hotplug_enable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108f560)
Location: kernel/cpu.c:337
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_callback
  - kernel/kexec_core.c:kernel_kexec
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_driver.c:acpi_processor_start
```
**Symbols:**

```
ffffffff8108f560-ffffffff8108f588: cpu_hotplug_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cpu_hotplug_enable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81097860)
Location: kernel/cpu.c:351
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_callback
  - kernel/kexec_core.c:kernel_kexec
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/powercap/idle_inject.c:idle_inject_stop
```
**Symbols:**

```
ffffffff81097860-ffffffff81097888: cpu_hotplug_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cpu_hotplug_enable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109be20)
Location: kernel/cpu.c:361
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_callback
  - kernel/kexec_core.c:kernel_kexec
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff8109be20-ffffffff8109be48: cpu_hotplug_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cpu_hotplug_enable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a23a0)
Location: kernel/cpu.c:364
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_callback
  - kernel/kexec_core.c:kernel_kexec
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff810a23a0-ffffffff810a23c8: cpu_hotplug_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void cpu_hotplug_enable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a942d)
Location: kernel/cpu.c:365
Inline: True
Inline callers:
  - kernel/cpu.c:cpu_hotplug_pm_callback
Direct callers:
  - kernel/kexec_core.c:kernel_kexec
  - drivers/pci/pci-driver.c:pci_call_probe
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff810a9030-ffffffff810a9058: cpu_hotplug_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void cpu_hotplug_enable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a4e7d)
Location: kernel/cpu.c:365
Inline: True
Inline callers:
  - kernel/cpu.c:cpu_hotplug_pm_callback
Direct callers:
  - kernel/kexec_core.c:kernel_kexec
  - drivers/pci/pci-driver.c:pci_call_probe
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff810a4a80-ffffffff810a4aa8: cpu_hotplug_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void cpu_hotplug_enable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a5b7d)
Location: kernel/cpu.c:377
Inline: True
Inline callers:
  - kernel/cpu.c:cpu_hotplug_pm_callback
Direct callers:
  - kernel/kexec_core.c:kernel_kexec
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff810a5750-ffffffff810a5778: cpu_hotplug_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void cpu_hotplug_enable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810b750d)
Location: kernel/cpu.c:388
Inline: True
Inline callers:
  - kernel/cpu.c:cpu_hotplug_pm_callback
Direct callers:
  - kernel/kexec_core.c:kernel_kexec
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff810b7440-ffffffff810b7468: cpu_hotplug_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void cpu_hotplug_enable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810cdced)
Location: kernel/cpu.c:389
Inline: True
Inline callers:
  - kernel/cpu.c:cpu_hotplug_pm_callback
Direct callers:
  - kernel/kexec_core.c:kernel_kexec
  - drivers/pci/pci-driver.c:pci_call_probe
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff810cdc30-ffffffff810cdc5e: cpu_hotplug_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void cpu_hotplug_enable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810ebe8d)
Location: kernel/cpu.c:389
Inline: True
Inline callers:
  - kernel/cpu.c:cpu_hotplug_pm_callback
Direct callers:
  - kernel/kexec_core.c:kernel_kexec
  - drivers/pci/pci-driver.c:pci_call_probe
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff810ebd20-ffffffff810ebd4e: cpu_hotplug_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void cpu_hotplug_enable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810f7b6d)
Location: kernel/cpu.c:568
Inline: True
Inline callers:
  - kernel/cpu.c:cpu_hotplug_pm_callback
Direct callers:
  - kernel/kexec_core.c:kernel_kexec
  - drivers/pci/pci-driver.c:pci_call_probe
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff810f7a00-ffffffff810f7a2e: cpu_hotplug_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void cpu_hotplug_enable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8110103d)
Location: kernel/cpu.c:568
Inline: True
Inline callers:
  - kernel/cpu.c:cpu_hotplug_pm_callback
Direct callers:
  - kernel/kexec_core.c:kernel_kexec
  - drivers/pci/pci-driver.c:pci_call_probe
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff81100df0-ffffffff81100e1e: cpu_hotplug_enable (STB_GLOBAL)
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
void cpu_hotplug_enable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffff8000100f7438)
Location: kernel/cpu.c:364
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_callback
  - kernel/kexec_core.c:kernel_kexec
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/powercap/idle_inject.c:idle_inject_stop
```
**Symbols:**

```
ffff8000100f7438-ffff8000100f7474: cpu_hotplug_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cpu_hotplug_enable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c0355858)
Location: kernel/cpu.c:364
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_callback
  - kernel/kexec_core.c:kernel_kexec
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/powercap/idle_inject.c:idle_inject_stop
```
**Symbols:**

```
c0355858-c035588c: cpu_hotplug_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cpu_hotplug_enable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c00000000013db00)
Location: kernel/cpu.c:364
Inline: False
Direct callers:
  - arch/powerpc/kernel/rtas.c:rtas_ibm_suspend_me
  - kernel/cpu.c:cpu_hotplug_pm_callback
  - kernel/kexec_core.c:kernel_kexec
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/powercap/idle_inject.c:idle_inject_stop
```
**Symbols:**

```
c00000000013db00-c00000000013db50: cpu_hotplug_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (0)
Location: include/linux/cpu.h:131
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
void cpu_hotplug_enable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109bcc0)
Location: kernel/cpu.c:364
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_callback
  - kernel/kexec_core.c:kernel_kexec
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff8109bcc0-ffffffff8109bce8: cpu_hotplug_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cpu_hotplug_enable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108a6f0)
Location: kernel/cpu.c:364
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_callback
  - kernel/kexec_core.c:kernel_kexec
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff8108a6f0-ffffffff8108a718: cpu_hotplug_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cpu_hotplug_enable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109bc70)
Location: kernel/cpu.c:364
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_callback
  - kernel/kexec_core.c:kernel_kexec
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff8109bc70-ffffffff8109bc98: cpu_hotplug_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cpu_hotplug_enable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a3870)
Location: kernel/cpu.c:364
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_hotplug_pm_callback
  - kernel/kexec_core.c:kernel_kexec
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_driver.c:acpi_processor_start
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - arch/x86/power/hibernate.c:arch_resume_nosmt
```
**Symbols:**

```
ffffffff810a3870-ffffffff810a3898: cpu_hotplug_enable (STB_GLOBAL)
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
