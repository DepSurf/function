# Function: <code>acpi_get_override_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_get_override_irq(u32 gsi, int *trigger, int *polarity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81057370)
Location: arch/x86/kernel/apic/io_apic.c:2490
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/pci/xen.c:pci_xen_initial_domain
```
**Symbols:**

```
ffffffff81057370-ffffffff81057486: acpi_get_override_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_get_override_irq(u32 gsi, int *trigger, int *polarity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81057610)
Location: arch/x86/kernel/apic/io_apic.c:2491
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
```
**Symbols:**

```
ffffffff81057610-ffffffff81057733: acpi_get_override_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_get_override_irq(u32 gsi, int *trigger, int *polarity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105a3a0)
Location: arch/x86/kernel/apic/io_apic.c:2492
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
```
**Symbols:**

```
ffffffff8105a3a0-ffffffff8105a4c3: acpi_get_override_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int acpi_get_override_irq(u32 gsi, int *trigger, int *polarity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810599e0)
Location: arch/x86/kernel/apic/io_apic.c:2490
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
```
**Symbols:**

```
ffffffff810599e0-ffffffff81059aff: acpi_get_override_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int acpi_get_override_irq(u32 gsi, int *trigger, int *polarity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105ded0)
Location: arch/x86/kernel/apic/io_apic.c:2543
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
```
**Symbols:**

```
ffffffff8105ded0-ffffffff8105dfef: acpi_get_override_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int acpi_get_override_irq(u32 gsi, int *trigger, int *polarity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:2536
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
```
**Symbols:**

```
ffffffff8106211c-ffffffff81062132: acpi_get_override_irq.cold.23 (STB_LOCAL)
ffffffff81060f10-ffffffff8106102c: acpi_get_override_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int acpi_get_override_irq(u32 gsi, int *trigger, int *polarity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:2536
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
```
**Symbols:**

```
ffffffff81067e11-ffffffff81067e27: acpi_get_override_irq.cold.21 (STB_LOCAL)
ffffffff81066bf0-ffffffff81066d0c: acpi_get_override_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int acpi_get_override_irq(u32 gsi, int *trigger, int *polarity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:2594
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
```
**Symbols:**

```
ffffffff8106b5da-ffffffff8106b5f0: acpi_get_override_irq.cold (STB_LOCAL)
ffffffff8106a3b0-ffffffff8106a4c7: acpi_get_override_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int acpi_get_override_irq(u32 gsi, int *trigger, int *polarity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:2597
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
```
**Symbols:**

```
ffffffff8106bf3e-ffffffff8106bf54: acpi_get_override_irq.cold (STB_LOCAL)
ffffffff8106ad50-ffffffff8106ae67: acpi_get_override_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int acpi_get_override_irq(u32 gsi, int *trigger, int *polarity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:2590
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
```
**Symbols:**

```
ffffffff8107325c-ffffffff8107328a: acpi_get_override_irq.cold (STB_LOCAL)
ffffffff81072160-ffffffff81072248: acpi_get_override_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int acpi_get_override_irq(u32 gsi, int *is_level, int *active_low);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81073710)
Location: arch/x86/kernel/apic/io_apic.c:853
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:pci_xen_initial_domain
```
**Symbols:**

```
ffffffff81073710-ffffffff8107372c: acpi_get_override_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int acpi_get_override_irq(u32 gsi, int *is_level, int *active_low);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810741e0)
Location: arch/x86/kernel/apic/io_apic.c:853
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:pci_xen_initial_domain
```
**Symbols:**

```
ffffffff810741e0-ffffffff810741fc: acpi_get_override_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int acpi_get_override_irq(u32 gsi, int *is_level, int *active_low);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810814e0)
Location: arch/x86/kernel/apic/io_apic.c:853
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:pci_xen_initial_domain
```
**Symbols:**

```
ffffffff810814e0-ffffffff810814fc: acpi_get_override_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int acpi_get_override_irq(u32 gsi, int *is_level, int *active_low);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81090fa0)
Location: arch/x86/kernel/apic/io_apic.c:854
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_gsi_to_irq
  - drivers/acpi/resource.c:acpi_dev_get_irqresource
  - arch/x86/pci/xen.c:pci_xen_initial_domain
```
**Symbols:**

```
ffffffff81090fa0-ffffffff81090fc6: acpi_get_override_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_get_override_irq(u32 gsi, int *is_level, int *active_low);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a5b50)
Location: arch/x86/kernel/apic/io_apic.c:854
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_gsi_to_irq
  - drivers/acpi/resource.c:acpi_dev_get_irqresource
  - arch/x86/pci/xen.c:pci_xen_initial_domain
```
**Symbols:**

```
ffffffff810a5b50-ffffffff810a5b76: acpi_get_override_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_get_override_irq(u32 gsi, int *is_level, int *active_low);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a8d50)
Location: arch/x86/kernel/apic/io_apic.c:855
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_gsi_to_irq
  - drivers/acpi/resource.c:acpi_dev_get_irqresource
  - arch/x86/pci/xen.c:pci_xen_initial_domain
```
**Symbols:**

```
ffffffff810a8d50-ffffffff810a8d76: acpi_get_override_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_get_override_irq(u32 gsi, int *is_level, int *active_low);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810afde0)
Location: arch/x86/kernel/apic/io_apic.c:855
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_gsi_to_irq
  - drivers/acpi/resource.c:acpi_dev_get_irqresource
  - arch/x86/pci/xen.c:pci_xen_initial_domain
```
**Symbols:**

```
ffffffff810afde0-ffffffff810afe06: acpi_get_override_irq (STB_GLOBAL)
```
</details>
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
In drivers/acpi/resource.c (0)
Location: include/linux/acpi.h:327
Inline: True
```
</details>
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int acpi_get_override_irq(u32 gsi, int *trigger, int *polarity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:2603
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
```
**Symbols:**

```
ffffffff8106ba2e-ffffffff8106ba44: acpi_get_override_irq.cold (STB_LOCAL)
ffffffff8106a840-ffffffff8106a957: acpi_get_override_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int acpi_get_override_irq(u32 gsi, int *trigger, int *polarity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:2597
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
```
**Symbols:**

```
ffffffff8105bd5e-ffffffff8105bd74: acpi_get_override_irq.cold (STB_LOCAL)
ffffffff8105aba0-ffffffff8105acb7: acpi_get_override_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int acpi_get_override_irq(u32 gsi, int *trigger, int *polarity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:2597
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
```
**Symbols:**

```
ffffffff8106bede-ffffffff8106bef4: acpi_get_override_irq.cold (STB_LOCAL)
ffffffff8106acf0-ffffffff8106ae07: acpi_get_override_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int acpi_get_override_irq(u32 gsi, int *trigger, int *polarity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/kernel/apic/io_apic.c:2597
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/pci/xen.c:pci_xen_initial_domain
```
**Symbols:**

```
ffffffff8106d5de-ffffffff8106d5f4: acpi_get_override_irq.cold (STB_LOCAL)
ffffffff8106c3f0-ffffffff8106c507: acpi_get_override_irq (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int *is_level</code>
</li>
<li>
<b>Param added. </b>
<code>int *active_low</code>
</li>
<li>
<b>Param removed. </b>
<code>int *trigger</code>
</li>
<li>
<b>Param removed. </b>
<code>int *polarity</code>
</li>
</ul>
</details>
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
