# Function: <code>resource_contains</code>

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
In kernel/resource.c (ffffffff81087305)
Location: include/linux/ioport.h:174
Inline: True
Inline callers:
  - kernel/resource.c:__find_resource
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:allocate_resource
```
```
In drivers/pci/host-bridge.c (ffffffff81432ed5)
Location: include/linux/ioport.h:174
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
```
```
In drivers/pci/pci.c (ffffffff81433bcb)
Location: include/linux/ioport.h:174
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_find_parent_resource
```
```
In drivers/pci/setup-bus.c (ffffffff81440496)
Location: include/linux/ioport.h:174
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
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
In kernel/resource.c (ffffffff8108a332)
Location: include/linux/ioport.h:206
Inline: True
Inline callers:
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:__find_resource
```
```
In drivers/pci/host-bridge.c (ffffffff8147e755)
Location: include/linux/ioport.h:206
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
```
```
In drivers/pci/pci.c (ffffffff8147f46b)
Location: include/linux/ioport.h:206
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_find_parent_resource
```
```
In drivers/pci/setup-bus.c (ffffffff8148c366)
Location: include/linux/ioport.h:206
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
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
In kernel/resource.c (ffffffff8108f282)
Location: include/linux/ioport.h:206
Inline: True
Inline callers:
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:__find_resource
```
```
In drivers/pci/host-bridge.c (ffffffff8149fdf5)
Location: include/linux/ioport.h:206
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
```
```
In drivers/pci/pci.c (ffffffff814a1f12)
Location: include/linux/ioport.h:206
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_parent_resource
```
```
In drivers/pci/setup-bus.c (ffffffff814adb56)
Location: include/linux/ioport.h:206
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/acpi/resource.c (ffffffff814f2961)
Location: include/linux/ioport.h:206
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff8200c0f6)
Location: include/linux/ioport.h:206
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
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
In kernel/resource.c (ffffffff8108c222)
Location: include/linux/ioport.h:206
Inline: True
Inline callers:
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:__find_resource
```
```
In drivers/pci/host-bridge.c (ffffffff814a9c29)
Location: include/linux/ioport.h:206
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
```
```
In drivers/pci/pci.c (ffffffff814abb4a)
Location: include/linux/ioport.h:206
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_parent_resource
```
```
In drivers/pci/setup-bus.c (ffffffff814b7ef9)
Location: include/linux/ioport.h:206
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/acpi/resource.c (ffffffff81500579)
Location: include/linux/ioport.h:206
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
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
In kernel/resource.c (ffffffff81092f5a)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:__find_resource
```
```
In drivers/pci/host-bridge.c (ffffffff814e8e85)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
```
```
In drivers/pci/pci.c (ffffffff814eac02)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_parent_resource
```
```
In drivers/pci/setup-bus.c (ffffffff814f8049)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/acpi/resource.c (ffffffff8154276c)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
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
In kernel/resource.c (ffffffff8109698a)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:__find_resource
```
```
In drivers/pci/host-bridge.c (ffffffff81518631)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
```
```
In drivers/pci/pci.c (ffffffff8151c022)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_parent_resource
```
```
In drivers/pci/setup-bus.c (ffffffff81528ba6)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/acpi/resource.c (ffffffff815786e8)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8165fd66)
Location: include/linux/ioport.h:209
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
In kernel/resource.c (ffffffff8109ec9a)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:__find_resource
  - kernel/resource.c:__find_resource
```
```
In drivers/pci/host-bridge.c (ffffffff8152e0b1)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
```
```
In drivers/pci/pci.c (ffffffff8152ff12)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/pci.c:pci_find_parent_resource
```
```
In drivers/pci/setup-bus.c (ffffffff8153ea46)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/acpi/resource.c (ffffffff81590338)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8167e3b6)
Location: include/linux/ioport.h:209
Inline: True
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
In kernel/resource.c (ffffffff810a32e2)
Location: include/linux/ioport.h:218
Inline: True
Inline callers:
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:__find_resource
  - kernel/resource.c:__find_resource
```
```
In drivers/pci/host-bridge.c (ffffffff8155d85f)
Location: include/linux/ioport.h:218
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
```
```
In drivers/pci/pci.c (ffffffff8155f6ed)
Location: include/linux/ioport.h:218
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/pci.c:pci_find_parent_resource
```
```
In drivers/pci/setup-bus.c (ffffffff8156dec7)
Location: include/linux/ioport.h:218
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/acpi/resource.c (ffffffff815c1118)
Location: include/linux/ioport.h:218
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff816b5066)
Location: include/linux/ioport.h:218
Inline: True
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
In kernel/resource.c (ffffffff810a9912)
Location: include/linux/ioport.h:218
Inline: True
Inline callers:
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:__find_resource
  - kernel/resource.c:__find_resource
```
```
In drivers/pci/host-bridge.c (ffffffff8157e8cf)
Location: include/linux/ioport.h:218
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
```
```
In drivers/pci/pci.c (ffffffff8158082d)
Location: include/linux/ioport.h:218
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/pci.c:pci_find_parent_resource
```
```
In drivers/pci/setup-bus.c (ffffffff8158eea7)
Location: include/linux/ioport.h:218
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/acpi/resource.c (ffffffff815e23d8)
Location: include/linux/ioport.h:218
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff816d7d46)
Location: include/linux/ioport.h:218
Inline: True
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
In kernel/resource.c (ffffffff810b14a9)
Location: include/linux/ioport.h:220
Inline: True
Inline callers:
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:__find_resource
  - kernel/resource.c:__find_resource
```
```
In drivers/pci/host-bridge.c (ffffffff81623df5)
Location: include/linux/ioport.h:220
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
```
```
In drivers/pci/pci.c (ffffffff81625ac0)
Location: include/linux/ioport.h:220
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/pci.c:pci_find_parent_resource
```
```
In drivers/pci/setup-bus.c (ffffffff81633e61)
Location: include/linux/ioport.h:220
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:assign_fixed_resource_on_bus
```
```
In drivers/acpi/resource.c (ffffffff8168cdce)
Location: include/linux/ioport.h:220
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_dev_consumes_res
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
In kernel/resource.c (ffffffff810acc09)
Location: include/linux/ioport.h:224
Inline: True
Inline callers:
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:__find_resource
  - kernel/resource.c:__find_resource
```
```
In drivers/pci/host-bridge.c (ffffffff816499b5)
Location: include/linux/ioport.h:224
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
```
```
In drivers/pci/pci.c (ffffffff8164b8e0)
Location: include/linux/ioport.h:224
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/pci.c:pci_find_parent_resource
```
```
In drivers/pci/setup-bus.c (ffffffff81658f11)
Location: include/linux/ioport.h:224
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:assign_fixed_resource_on_bus
```
```
In drivers/acpi/resource.c (ffffffff816aaace)
Location: include/linux/ioport.h:224
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_dev_consumes_res
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
In kernel/resource.c (ffffffff810addf9)
Location: include/linux/ioport.h:225
Inline: True
Inline callers:
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:__find_resource
  - kernel/resource.c:__find_resource
```
```
In drivers/pci/host-bridge.c (ffffffff8162c56a)
Location: include/linux/ioport.h:225
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
```
```
In drivers/pci/pci.c (ffffffff8162e4c8)
Location: include/linux/ioport.h:225
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/pci.c:pci_find_parent_resource
```
```
In drivers/pci/setup-bus.c (ffffffff8163df98)
Location: include/linux/ioport.h:225
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/acpi/resource.c (ffffffff8168d3ee)
Location: include/linux/ioport.h:225
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
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
In kernel/resource.c (ffffffff810bf979)
Location: include/linux/ioport.h:225
Inline: True
Inline callers:
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:__find_resource
  - kernel/resource.c:__find_resource
```
```
In drivers/pci/host-bridge.c (ffffffff8169ba5a)
Location: include/linux/ioport.h:225
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
```
```
In drivers/pci/pci.c (ffffffff8169d95f)
Location: include/linux/ioport.h:225
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/pci.c:pci_find_parent_resource
```
```
In drivers/pci/setup-bus.c (ffffffff816aeae6)
Location: include/linux/ioport.h:225
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/acpi/resource.c (ffffffff81702c1e)
Location: include/linux/ioport.h:225
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
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
In kernel/resource.c (ffffffff810d6df4)
Location: include/linux/ioport.h:225
Inline: True
Inline callers:
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:__find_resource
  - kernel/resource.c:__find_resource
```
```
In drivers/pci/host-bridge.c (ffffffff817bd2aa)
Location: include/linux/ioport.h:225
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
```
```
In drivers/pci/pci.c (ffffffff817bffdf)
Location: include/linux/ioport.h:225
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/pci.c:pci_find_parent_resource
```
```
In drivers/pci/setup-bus.c (ffffffff817d1f61)
Location: include/linux/ioport.h:225
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/acpi/resource.c (ffffffff81830bd0)
Location: include/linux/ioport.h:225
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
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
In kernel/resource.c (ffffffff810f6844)
Location: include/linux/ioport.h:232
Inline: True
Inline callers:
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:__find_resource
  - kernel/resource.c:__find_resource
```
```
In drivers/pci/host-bridge.c (ffffffff818d936a)
Location: include/linux/ioport.h:232
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
```
```
In drivers/pci/pci.c (ffffffff818dc61f)
Location: include/linux/ioport.h:232
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/pci.c:pci_find_parent_resource
```
```
In drivers/pci/setup-bus.c (ffffffff818f23f1)
Location: include/linux/ioport.h:232
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/acpi/resource.c (ffffffff81963d60)
Location: include/linux/ioport.h:232
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
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
In kernel/resource.c (ffffffff81102c64)
Location: include/linux/ioport.h:232
Inline: True
Inline callers:
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:__find_resource
  - kernel/resource.c:__find_resource
```
```
In drivers/pci/host-bridge.c (ffffffff8191c69a)
Location: include/linux/ioport.h:232
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
```
```
In drivers/pci/pci.c (ffffffff8191f94f)
Location: include/linux/ioport.h:232
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/pci.c:pci_find_parent_resource
```
```
In drivers/pci/setup-bus.c (ffffffff81935803)
Location: include/linux/ioport.h:232
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/acpi/resource.c (ffffffff819aa200)
Location: include/linux/ioport.h:232
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
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
In kernel/resource.c (ffffffff8110c594)
Location: include/linux/ioport.h:232
Inline: True
Inline callers:
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:__find_resource
  - kernel/resource.c:__find_resource
```
```
In drivers/pci/host-bridge.c (ffffffff81964aca)
Location: include/linux/ioport.h:232
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
```
```
In drivers/pci/pci.c (ffffffff81967ac1)
Location: include/linux/ioport.h:232
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/pci.c:pci_find_parent_resource
```
```
In drivers/pci/setup-bus.c (ffffffff8197e5b5)
Location: include/linux/ioport.h:232
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/acpi/resource.c (ffffffff819f4490)
Location: include/linux/ioport.h:232
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffff8000101016e8)
Location: include/linux/ioport.h:218
Inline: True
Inline callers:
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:__find_resource
  - kernel/resource.c:__find_resource
```
```
In drivers/pci/host-bridge.c (ffff8000106e11a8)
Location: include/linux/ioport.h:218
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
```
```
In drivers/pci/pci.c (ffff8000106e34c8)
Location: include/linux/ioport.h:218
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/pci.c:pci_find_parent_resource
```
```
In drivers/pci/setup-bus.c (ffff8000106f41b4)
Location: include/linux/ioport.h:218
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/acpi/resource.c (ffff80001076eda4)
Location: include/linux/ioport.h:218
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
```
```
In drivers/acpi/pci_mcfg.c (ffff80001079fcbc)
Location: include/linux/ioport.h:218
Inline: True
Inline callers:
  - drivers/acpi/pci_mcfg.c:pci_mcfg_lookup
```
```
In drivers/char/tpm/tpm_crb.c (ffff8000108c30a4)
Location: include/linux/ioport.h:218
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c035dd0c)
Location: include/linux/ioport.h:218
Inline: True
Inline callers:
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:__find_resource
  - kernel/resource.c:__find_resource
```
```
In drivers/pci/host-bridge.c (c087ce6c)
Location: include/linux/ioport.h:218
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
```
```
In drivers/pci/pci.c (c087f428)
Location: include/linux/ioport.h:218
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/pci.c:pci_find_parent_resource
```
```
In drivers/pci/setup-bus.c (c088ec4c)
Location: include/linux/ioport.h:218
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c000000000148f50)
Location: include/linux/ioport.h:218
Inline: True
Inline callers:
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:__find_resource
  - kernel/resource.c:__find_resource
```
```
In drivers/pci/host-bridge.c (c00000000085a3c0)
Location: include/linux/ioport.h:218
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
```
```
In drivers/pci/pci.c (c00000000085d5b8)
Location: include/linux/ioport.h:218
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/pci.c:pci_find_parent_resource
```
```
In drivers/pci/setup-bus.c (c000000000872838)
Location: include/linux/ioport.h:218
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
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
In kernel/resource.c (ffffffe0000c89aa)
Location: include/linux/ioport.h:218
Inline: True
Inline callers:
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:__find_resource
  - kernel/resource.c:__find_resource
```
```
In drivers/pci/host-bridge.c (ffffffe0004b8dfc)
Location: include/linux/ioport.h:218
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
```
```
In drivers/pci/pci.c (ffffffe0004bab92)
Location: include/linux/ioport.h:218
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/pci.c:pci_find_parent_resource
```
```
In drivers/pci/setup-bus.c (ffffffe0004c7336)
Location: include/linux/ioport.h:218
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
</details>
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
In kernel/resource.c (ffffffff810a3232)
Location: include/linux/ioport.h:218
Inline: True
Inline callers:
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:__find_resource
  - kernel/resource.c:__find_resource
```
```
In drivers/pci/host-bridge.c (ffffffff81572def)
Location: include/linux/ioport.h:218
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
```
```
In drivers/pci/pci.c (ffffffff81574d4d)
Location: include/linux/ioport.h:218
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/pci.c:pci_find_parent_resource
```
```
In drivers/pci/setup-bus.c (ffffffff81582d27)
Location: include/linux/ioport.h:218
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/acpi/resource.c (ffffffff815d4698)
Location: include/linux/ioport.h:218
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8169d796)
Location: include/linux/ioport.h:218
Inline: True
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
In kernel/resource.c (ffffffff81091c12)
Location: include/linux/ioport.h:218
Inline: True
Inline callers:
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:__find_resource
  - kernel/resource.c:__find_resource
```
```
In drivers/pci/host-bridge.c (ffffffff8156154f)
Location: include/linux/ioport.h:218
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
```
```
In drivers/pci/pci.c (ffffffff815634ad)
Location: include/linux/ioport.h:218
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/pci.c:pci_find_parent_resource
```
```
In drivers/pci/setup-bus.c (ffffffff81571b07)
Location: include/linux/ioport.h:218
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/acpi/resource.c (ffffffff815be258)
Location: include/linux/ioport.h:218
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8167b186)
Location: include/linux/ioport.h:218
Inline: True
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
In kernel/resource.c (ffffffff810a31e2)
Location: include/linux/ioport.h:218
Inline: True
Inline callers:
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:__find_resource
  - kernel/resource.c:__find_resource
```
```
In drivers/pci/host-bridge.c (ffffffff8157261f)
Location: include/linux/ioport.h:218
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
```
```
In drivers/pci/pci.c (ffffffff8157457d)
Location: include/linux/ioport.h:218
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/pci.c:pci_find_parent_resource
```
```
In drivers/pci/setup-bus.c (ffffffff81582bf7)
Location: include/linux/ioport.h:218
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/acpi/resource.c (ffffffff815d66b8)
Location: include/linux/ioport.h:218
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff816cba06)
Location: include/linux/ioport.h:218
Inline: True
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
In kernel/resource.c (ffffffff810ab287)
Location: include/linux/ioport.h:218
Inline: True
Inline callers:
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:__find_resource
  - kernel/resource.c:__find_resource
```
```
In drivers/pci/host-bridge.c (ffffffff8158caff)
Location: include/linux/ioport.h:218
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
```
```
In drivers/pci/pci.c (ffffffff8158eb4d)
Location: include/linux/ioport.h:218
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/pci.c:pci_find_parent_resource
```
```
In drivers/pci/setup-bus.c (ffffffff8159d0a7)
Location: include/linux/ioport.h:218
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/acpi/resource.c (ffffffff815f0578)
Location: include/linux/ioport.h:218
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff816e5ed6)
Location: include/linux/ioport.h:218
Inline: True
```
</details>
</li>
</ul>

## Differences
