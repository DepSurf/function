# Function: <code>acpi_pci_get_bridge_handle</code>

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
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff8144e93b)
Location: include/linux/pci-acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
```
```
In drivers/pci/pci-acpi.c (ffffffff81457927)
Location: include/linux/pci-acpi.h:38
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_get_hp_params
```
```
In drivers/xen/pci.c (ffffffff814d1a2f)
Location: include/linux/pci-acpi.h:38
Inline: True
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
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff8149b542)
Location: include/linux/pci-acpi.h:40
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/pci/pci-acpi.c (ffffffff814a4567)
Location: include/linux/pci-acpi.h:40
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_get_hp_params
```
```
In drivers/xen/pci.c (ffffffff81522707)
Location: include/linux/pci-acpi.h:40
Inline: True
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
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff814bd122)
Location: include/linux/pci-acpi.h:42
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/pci/pci-acpi.c (ffffffff814c6377)
Location: include/linux/pci-acpi.h:42
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_get_hp_params
```
```
In drivers/xen/pci.c (ffffffff8154ebe7)
Location: include/linux/pci-acpi.h:42
Inline: True
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
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff814c78f2)
Location: include/linux/pci-acpi.h:42
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/pci/pci-acpi.c (ffffffff814d0220)
Location: include/linux/pci-acpi.h:42
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_get_hp_params
```
```
In drivers/xen/pci.c (ffffffff81563171)
Location: include/linux/pci-acpi.h:42
Inline: True
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
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff81507e92)
Location: include/linux/pci-acpi.h:43
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/pci/pci-acpi.c (ffffffff81510460)
Location: include/linux/pci-acpi.h:43
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_get_hp_params
```
```
In drivers/xen/pci.c (ffffffff815c7625)
Location: include/linux/pci-acpi.h:43
Inline: True
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
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff81538d72)
Location: include/linux/pci-acpi.h:43
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/pci/pci-acpi.c (ffffffff815455e4)
Location: include/linux/pci-acpi.h:43
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_get_hp_params
```
```
In drivers/xen/pci.c (ffffffff815ffee7)
Location: include/linux/pci-acpi.h:43
Inline: True
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
In drivers/pci/pci-acpi.c (ffffffff8154161f)
Location: include/linux/pci-acpi.h:43
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_get_hp_params
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff81550102)
Location: include/linux/pci-acpi.h:43
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/xen/pci.c (ffffffff8161afb7)
Location: include/linux/pci-acpi.h:43
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
acpi_handle acpi_pci_get_bridge_handle(struct pci_bus *pbus);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff8157151b)
Location: include/linux/pci-acpi.h:43
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff8157ff52)
Location: include/linux/pci-acpi.h:43
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/xen/pci.c (ffffffff8164ecca)
Location: include/linux/pci-acpi.h:43
Inline: True
```
**Symbols:**

```
ffffffff8157fb70-ffffffff8157fbbd: acpi_pci_get_bridge_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
acpi_handle acpi_pci_get_bridge_handle(struct pci_bus *pbus);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff815928c7)
Location: include/linux/pci-acpi.h:43
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff815a1992)
Location: include/linux/pci-acpi.h:43
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/xen/pci.c (ffffffff816711a8)
Location: include/linux/pci-acpi.h:43
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
```
**Symbols:**

```
ffffffff815a15b0-ffffffff815a15fd: acpi_pci_get_bridge_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
acpi_handle acpi_pci_get_bridge_handle(struct pci_bus *pbus);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81641313)
Location: include/linux/pci-acpi.h:43
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff8164a322)
Location: include/linux/pci-acpi.h:43
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/xen/pci.c (ffffffff8172180e)
Location: include/linux/pci-acpi.h:43
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
```
**Symbols:**

```
ffffffff81649f50-ffffffff81649fa3: acpi_pci_get_bridge_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
acpi_handle acpi_pci_get_bridge_handle(struct pci_bus *pbus);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81667803)
Location: include/linux/pci-acpi.h:43
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff8166ec12)
Location: include/linux/pci-acpi.h:43
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/xen/pci.c (ffffffff8173e4e4)
Location: include/linux/pci-acpi.h:43
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
```
**Symbols:**

```
ffffffff8166e840-ffffffff8166e893: acpi_pci_get_bridge_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
acpi_handle acpi_pci_get_bridge_handle(struct pci_bus *pbus);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81649c70)
Location: include/linux/pci-acpi.h:43
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff81651152)
Location: include/linux/pci-acpi.h:43
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/xen/pci.c (ffffffff81722000)
Location: include/linux/pci-acpi.h:43
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
```
**Symbols:**

```
ffffffff81650d90-ffffffff81650de3: acpi_pci_get_bridge_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
acpi_handle acpi_pci_get_bridge_handle(struct pci_bus *pbus);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff816bb740)
Location: include/linux/pci-acpi.h:43
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff816c2e92)
Location: include/linux/pci-acpi.h:43
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/xen/pci.c (ffffffff817a0e3e)
Location: include/linux/pci-acpi.h:43
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
```
**Symbols:**

```
ffffffff816c2ad0-ffffffff816c2b23: acpi_pci_get_bridge_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
acpi_handle acpi_pci_get_bridge_handle(struct pci_bus *pbus);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff817dfa24)
Location: include/linux/pci-acpi.h:43
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff817e88bf)
Location: include/linux/pci-acpi.h:43
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/xen/pci.c (ffffffff818dac91)
Location: include/linux/pci-acpi.h:43
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
```
**Symbols:**

```
ffffffff817e84e0-ffffffff817e854b: acpi_pci_get_bridge_handle (STB_LOCAL)
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
In drivers/pci/pci-acpi.c (ffffffff81902894)
Location: include/linux/pci-acpi.h:43
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff8190e25f)
Location: include/linux/pci-acpi.h:43
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/xen/pci.c (ffffffff81a2dc61)
Location: include/linux/pci-acpi.h:43
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
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
In drivers/pci/pci-acpi.c (ffffffff81945f24)
Location: include/linux/pci-acpi.h:43
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff819518df)
Location: include/linux/pci-acpi.h:43
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/xen/pci.c (ffffffff81a77401)
Location: include/linux/pci-acpi.h:43
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
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
In drivers/pci/pci-acpi.c (ffffffff8198f254)
Location: include/linux/pci-acpi.h:43
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff8199ad3f)
Location: include/linux/pci-acpi.h:43
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/xen/pci.c (ffffffff81ac9611)
Location: include/linux/pci-acpi.h:43
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
acpi_handle acpi_pci_get_bridge_handle(struct pci_bus *pbus);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffff8000106f8868)
Location: include/linux/pci-acpi.h:43
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffff80001070a154)
Location: include/linux/pci-acpi.h:43
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/xen/pci.c (ffff80001083c718)
Location: include/linux/pci-acpi.h:43
Inline: True
```
**Symbols:**

```
ffff800010709cc0-ffff800010709d2c: acpi_pci_get_bridge_handle (STB_LOCAL)
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
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
acpi_handle acpi_pci_get_bridge_handle(struct pci_bus *pbus);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81586757)
Location: include/linux/pci-acpi.h:43
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff815951a2)
Location: include/linux/pci-acpi.h:43
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/xen/pci.c (ffffffff81637268)
Location: include/linux/pci-acpi.h:43
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
```
**Symbols:**

```
ffffffff81594dc0-ffffffff81594e0d: acpi_pci_get_bridge_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
acpi_handle acpi_pci_get_bridge_handle(struct pci_bus *pbus);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81575527)
Location: include/linux/pci-acpi.h:43
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff81584332)
Location: include/linux/pci-acpi.h:43
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
**Symbols:**

```
ffffffff81583f50-ffffffff81583f9d: acpi_pci_get_bridge_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
acpi_handle acpi_pci_get_bridge_handle(struct pci_bus *pbus);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81586617)
Location: include/linux/pci-acpi.h:43
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff815956e2)
Location: include/linux/pci-acpi.h:43
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/xen/pci.c (ffffffff81664fe8)
Location: include/linux/pci-acpi.h:43
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
```
**Symbols:**

```
ffffffff81595300-ffffffff8159534d: acpi_pci_get_bridge_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
acpi_handle acpi_pci_get_bridge_handle(struct pci_bus *pbus);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff815a0ac7)
Location: include/linux/pci-acpi.h:43
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff815afb62)
Location: include/linux/pci-acpi.h:43
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/xen/pci.c (ffffffff8167f598)
Location: include/linux/pci-acpi.h:43
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
```
**Symbols:**

```
ffffffff815af780-ffffffff815af7cd: acpi_pci_get_bridge_handle (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
