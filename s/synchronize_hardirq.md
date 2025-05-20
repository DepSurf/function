# Function: <code>synchronize_hardirq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool synchronize_hardirq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810dab00)
Location: kernel/irq/manage.c:81
Inline: False
Direct callers:
  - kernel/irq/manage.c:disable_hardirq
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
```
**Symbols:**

```
ffffffff810dab00-ffffffff810dab32: synchronize_hardirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool synchronize_hardirq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e0110)
Location: kernel/irq/manage.c:81
Inline: False
Direct callers:
  - kernel/irq/manage.c:disable_hardirq
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
```
**Symbols:**

```
ffffffff810e0110-ffffffff810e0142: synchronize_hardirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool synchronize_hardirq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e6a60)
Location: kernel/irq/manage.c:81
Inline: False
Direct callers:
  - kernel/irq/manage.c:disable_hardirq
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
```
**Symbols:**

```
ffffffff810e6a60-ffffffff810e6a92: synchronize_hardirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool synchronize_hardirq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e60b0)
Location: kernel/irq/manage.c:83
Inline: False
Direct callers:
  - kernel/irq/manage.c:disable_hardirq
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
```
**Symbols:**

```
ffffffff810e60b0-ffffffff810e60e2: synchronize_hardirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool synchronize_hardirq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810ee330)
Location: kernel/irq/manage.c:83
Inline: False
Direct callers:
  - kernel/irq/manage.c:disable_hardirq
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
```
**Symbols:**

```
ffffffff810ee330-ffffffff810ee362: synchronize_hardirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool synchronize_hardirq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810f6720)
Location: kernel/irq/manage.c:83
Inline: False
Direct callers:
  - kernel/irq/manage.c:disable_hardirq
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
```
**Symbols:**

```
ffffffff810f6720-ffffffff810f6752: synchronize_hardirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool synchronize_hardirq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81101e90)
Location: kernel/irq/manage.c:83
Inline: False
Direct callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:disable_hardirq
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
```
**Symbols:**

```
ffffffff81101e90-ffffffff81101ec2: synchronize_hardirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool synchronize_hardirq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110a760)
Location: kernel/irq/manage.c:104
Inline: False
Direct callers:
  - kernel/irq/manage.c:disable_hardirq
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
```
**Symbols:**

```
ffffffff8110a760-ffffffff8110a794: synchronize_hardirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool synchronize_hardirq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81116b30)
Location: kernel/irq/manage.c:104
Inline: False
Direct callers:
  - kernel/irq/manage.c:disable_hardirq
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
```
**Symbols:**

```
ffffffff81116b30-ffffffff81116b64: synchronize_hardirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool synchronize_hardirq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81125933)
Location: kernel/irq/manage.c:105
Inline: True
Inline callers:
  - kernel/irq/manage.c:disable_hardirq
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/acpi/osl.c:acpi_hotplug_work_fn
```
**Symbols:**

```
ffffffff81125470-ffffffff811254a7: synchronize_hardirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool synchronize_hardirq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81121793)
Location: kernel/irq/manage.c:105
Inline: True
Inline callers:
  - kernel/irq/manage.c:disable_hardirq
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/acpi/osl.c:acpi_hotplug_work_fn
```
**Symbols:**

```
ffffffff811212d0-ffffffff81121307: synchronize_hardirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool synchronize_hardirq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81121a73)
Location: kernel/irq/manage.c:105
Inline: True
Inline callers:
  - kernel/irq/manage.c:disable_hardirq
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/acpi/osl.c:acpi_hotplug_work_fn
```
**Symbols:**

```
ffffffff811215b0-ffffffff811215e7: synchronize_hardirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool synchronize_hardirq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81142013)
Location: kernel/irq/manage.c:98
Inline: True
Inline callers:
  - kernel/irq/manage.c:disable_hardirq
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/acpi/osl.c:acpi_hotplug_work_fn
```
**Symbols:**

```
ffffffff81141b50-ffffffff81141b87: synchronize_hardirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool synchronize_hardirq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81165b39)
Location: kernel/irq/manage.c:98
Inline: True
Inline callers:
  - kernel/irq/manage.c:disable_hardirq
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
```
**Symbols:**

```
ffffffff81165620-ffffffff8116565f: synchronize_hardirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool synchronize_hardirq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81199aa9)
Location: kernel/irq/manage.c:98
Inline: True
Inline callers:
  - kernel/irq/manage.c:disable_hardirq
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
```
**Symbols:**

```
ffffffff81199540-ffffffff8119957f: synchronize_hardirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool synchronize_hardirq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811ab789)
Location: kernel/irq/manage.c:98
Inline: True
Inline callers:
  - kernel/irq/manage.c:disable_hardirq
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
```
**Symbols:**

```
ffffffff811ab220-ffffffff811ab25f: synchronize_hardirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool synchronize_hardirq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811bb389)
Location: kernel/irq/manage.c:98
Inline: True
Inline callers:
  - kernel/irq/manage.c:disable_hardirq
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
```
**Symbols:**

```
ffffffff811bae60-ffffffff811bae9f: synchronize_hardirq (STB_GLOBAL)
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
bool synchronize_hardirq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffff800010179600)
Location: kernel/irq/manage.c:104
Inline: False
Direct callers:
  - kernel/irq/manage.c:disable_hardirq
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
```
**Symbols:**

```
ffff800010179600-ffff800010179658: synchronize_hardirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool synchronize_hardirq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c03ca34c)
Location: kernel/irq/manage.c:104
Inline: False
Direct callers:
  - kernel/irq/manage.c:disable_hardirq
  - drivers/mmc/host/sdhci.c:sdhci_runtime_suspend_host
```
**Symbols:**

```
c03ca34c-c03ca38c: synchronize_hardirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool synchronize_hardirq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c0000000001d2ba0)
Location: kernel/irq/manage.c:104
Inline: False
Direct callers:
  - kernel/irq/manage.c:disable_hardirq
```
**Symbols:**

```
c0000000001d2ba0-c0000000001d2c18: synchronize_hardirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool synchronize_hardirq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffe0001134f4)
Location: kernel/irq/manage.c:104
Inline: False
Direct callers:
  - kernel/irq/manage.c:disable_hardirq
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffe0001134f4-ffffffe000113542: synchronize_hardirq (STB_GLOBAL)
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
bool synchronize_hardirq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110f110)
Location: kernel/irq/manage.c:104
Inline: False
Direct callers:
  - kernel/irq/manage.c:disable_hardirq
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
```
**Symbols:**

```
ffffffff8110f110-ffffffff8110f144: synchronize_hardirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool synchronize_hardirq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810ffe50)
Location: kernel/irq/manage.c:104
Inline: False
Direct callers:
  - kernel/irq/manage.c:disable_hardirq
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
```
**Symbols:**

```
ffffffff810ffe50-ffffffff810ffe84: synchronize_hardirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool synchronize_hardirq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110d000)
Location: kernel/irq/manage.c:104
Inline: False
Direct callers:
  - kernel/irq/manage.c:disable_hardirq
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
```
**Symbols:**

```
ffffffff8110d000-ffffffff8110d034: synchronize_hardirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool synchronize_hardirq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81118560)
Location: kernel/irq/manage.c:104
Inline: False
Direct callers:
  - kernel/irq/manage.c:disable_hardirq
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
```
**Symbols:**

```
ffffffff81118560-ffffffff81118594: synchronize_hardirq (STB_GLOBAL)
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
