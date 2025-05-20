# Function: <code>work_on_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int work_on_cpu(int cpu, long int (*fn)(void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109b020)
Location: kernel/workqueue.c:4610
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling
  - drivers/cpufreq/powernow-k8.c:powernowk8_target
```
**Symbols:**

```
ffffffff8109b020-ffffffff8109b0af: work_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int work_on_cpu(int cpu, long int (*fn)(void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109e620)
Location: kernel/workqueue.c:4698
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling
  - drivers/cpufreq/powernow-k8.c:powernowk8_target
```
**Symbols:**

```
ffffffff8109e620-ffffffff8109e6af: work_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int work_on_cpu(int cpu, long int (*fn)(void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a3200)
Location: kernel/workqueue.c:4728
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling
  - drivers/cpufreq/powernow-k8.c:powernowk8_target
```
**Symbols:**

```
ffffffff810a3200-ffffffff810a328f: work_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int work_on_cpu(int cpu, long int (*fn)(void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a04e0)
Location: kernel/workqueue.c:4748
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe
  - kernel/workqueue.c:work_on_cpu_safe
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_throttling.c:call_on_cpu
  - drivers/cpufreq/powernow-k8.c:powernowk8_target
```
**Symbols:**

```
ffffffff810a04e0-ffffffff810a0565: work_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int work_on_cpu(int cpu, long int (*fn)(void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a6a80)
Location: kernel/workqueue.c:4774
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe
  - kernel/workqueue.c:work_on_cpu_safe
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_throttling.c:call_on_cpu
  - drivers/cpufreq/powernow-k8.c:powernowk8_target
```
**Symbols:**

```
ffffffff810a6a80-ffffffff810a6b05: work_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int work_on_cpu(int cpu, long int (*fn)(void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ad710)
Location: kernel/workqueue.c:4891
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe
  - kernel/workqueue.c:work_on_cpu_safe
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/cpufreq/powernow-k8.c:powernowk8_target
```
**Symbols:**

```
ffffffff810ad710-ffffffff810ad797: work_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int work_on_cpu(int cpu, long int (*fn)(void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b6a00)
Location: kernel/workqueue.c:4914
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe
  - kernel/workqueue.c:work_on_cpu_safe
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/cpufreq/powernow-k8.c:powernowk8_target
```
**Symbols:**

```
ffffffff810b6a00-ffffffff810b6a87: work_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int work_on_cpu(int cpu, long int (*fn)(void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bce50)
Location: kernel/workqueue.c:5059
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe
  - kernel/workqueue.c:work_on_cpu_safe
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/cpufreq/powernow-k8.c:powernowk8_target
```
**Symbols:**

```
ffffffff810bce50-ffffffff810bced3: work_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int work_on_cpu(int cpu, long int (*fn)(void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c2ad0)
Location: kernel/workqueue.c:5093
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe
  - kernel/workqueue.c:work_on_cpu_safe
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/cpufreq/powernow-k8.c:powernowk8_target
```
**Symbols:**

```
ffffffff810c2ad0-ffffffff810c2b53: work_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long int work_on_cpu(int cpu, long int (*fn)(void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ca26c)
Location: kernel/workqueue.c:5116
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu_safe
Direct callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe
  - drivers/pci/pci-driver.c:pci_call_probe
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
  - drivers/cpufreq/powernow-k8.c:powernowk8_target
```
**Symbols:**

```
ffffffff810c93f0-ffffffff810c9471: work_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long int work_on_cpu(int cpu, long int (*fn)(void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c539c)
Location: kernel/workqueue.c:5137
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu_safe
Direct callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe
  - drivers/pci/pci-driver.c:pci_call_probe
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
  - drivers/cpufreq/powernow-k8.c:powernowk8_target
```
**Symbols:**

```
ffffffff810c4530-ffffffff810c45b1: work_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long int work_on_cpu(int cpu, long int (*fn)(void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c6c8c)
Location: kernel/workqueue.c:5144
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu_safe
Direct callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
  - drivers/cpufreq/powernow-k8.c:powernowk8_target
```
**Symbols:**

```
ffffffff810c5dc0-ffffffff810c5e41: work_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long int work_on_cpu(int cpu, long int (*fn)(void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810d993c)
Location: kernel/workqueue.c:5197
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu_safe
Direct callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
  - drivers/cpufreq/powernow-k8.c:powernowk8_target
```
**Symbols:**

```
ffffffff810d8aa0-ffffffff810d8b21: work_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long int work_on_cpu(int cpu, long int (*fn)(void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810f362a)
Location: kernel/workqueue.c:5182
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu_safe
Direct callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe
  - drivers/pci/pci-driver.c:pci_call_probe
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
  - drivers/cpufreq/powernow-k8.c:powernowk8_target
```
**Symbols:**

```
ffffffff810f34f0-ffffffff810f357b: work_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long int work_on_cpu(int cpu, long int (*fn)(void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8111506a)
Location: kernel/workqueue.c:5191
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu_safe
Direct callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe
  - drivers/pci/pci-driver.c:pci_call_probe
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
  - drivers/cpufreq/powernow-k8.c:powernowk8_target
```
**Symbols:**

```
ffffffff81113c00-ffffffff81113c8b: work_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long int work_on_cpu(int cpu, long int (*fn)(void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8112103a)
Location: kernel/workqueue.c:5584
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu_safe
Direct callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe
  - kernel/cpu.c:cpu_down_maps_locked
  - drivers/pci/pci-driver.c:pci_call_probe
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
  - drivers/cpufreq/powernow-k8.c:powernowk8_target
```
**Symbols:**

```
ffffffff811203c0-ffffffff8112044b: work_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
long int work_on_cpu(int cpu, long int (*fn)(void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffff80001011f888)
Location: kernel/workqueue.c:5093
Inline: False
Direct callers:
  - kernel/workqueue.c:work_on_cpu_safe
  - drivers/pci/pci-driver.c:pci_device_probe
```
**Symbols:**

```
ffff80001011f888-ffff80001011f924: work_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int work_on_cpu(int cpu, long int (*fn)(void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c0373874)
Location: kernel/workqueue.c:5093
Inline: False
Direct callers:
  - kernel/workqueue.c:work_on_cpu_safe
```
**Symbols:**

```
c0373874-c0373920: work_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int work_on_cpu(int cpu, long int (*fn)(void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c000000000169c00)
Location: kernel/workqueue.c:5093
Inline: False
Direct callers:
  - kernel/workqueue.c:work_on_cpu_safe
  - drivers/pci/pci-driver.c:pci_device_probe
```
**Symbols:**

```
c000000000169c00-c000000000169cb4: work_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int work_on_cpu(int cpu, long int (*fn)(void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffe0000d87b8)
Location: kernel/workqueue.c:5093
Inline: False
Direct callers:
  - kernel/workqueue.c:work_on_cpu_safe
```
**Symbols:**

```
ffffffe0000d87b8-ffffffe0000d8850: work_on_cpu (STB_GLOBAL)
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
long int work_on_cpu(int cpu, long int (*fn)(void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bce40)
Location: kernel/workqueue.c:5093
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe
  - kernel/workqueue.c:work_on_cpu_safe
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/cpufreq/powernow-k8.c:powernowk8_target
```
**Symbols:**

```
ffffffff810bce40-ffffffff810bcec3: work_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int work_on_cpu(int cpu, long int (*fn)(void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ab680)
Location: kernel/workqueue.c:5093
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe
  - kernel/workqueue.c:work_on_cpu_safe
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/cpufreq/powernow-k8.c:powernowk8_target
```
**Symbols:**

```
ffffffff810ab680-ffffffff810ab703: work_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int work_on_cpu(int cpu, long int (*fn)(void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bc3a0)
Location: kernel/workqueue.c:5093
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe
  - kernel/workqueue.c:work_on_cpu_safe
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/cpufreq/powernow-k8.c:powernowk8_target
```
**Symbols:**

```
ffffffff810bc3a0-ffffffff810bc423: work_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int work_on_cpu(int cpu, long int (*fn)(void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c46d0)
Location: kernel/workqueue.c:5093
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe
  - kernel/workqueue.c:work_on_cpu_safe
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/cpufreq/powernow-k8.c:powernowk8_target
```
**Symbols:**

```
ffffffff810c46d0-ffffffff810c4753: work_on_cpu (STB_GLOBAL)
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
