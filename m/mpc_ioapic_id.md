# Function: <code>mpc_ioapic_id</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int mpc_ioapic_id(int ioapic_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81f727c7)
Location: arch/x86/kernel/apic/io_apic.c:123
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:find_isa_irq_apic
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
Direct callers:
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
```
**Symbols:**

```
ffffffff81056d50-ffffffff81056d6a: mpc_ioapic_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int mpc_ioapic_id(int ioapic_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81057f66)
Location: arch/x86/kernel/apic/io_apic.c:123
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:find_isa_irq_apic
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
```
**Symbols:**

```
ffffffff81056fc0-ffffffff81056fda: mpc_ioapic_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int mpc_ioapic_id(int ioapic_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105acf6)
Location: arch/x86/kernel/apic/io_apic.c:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:find_isa_irq_apic
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
```
**Symbols:**

```
ffffffff81059d70-ffffffff81059d8a: mpc_ioapic_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int mpc_ioapic_id(int ioapic_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105a2c9)
Location: arch/x86/kernel/apic/io_apic.c:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:find_isa_irq_apic
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
```
**Symbols:**

```
ffffffff810593e0-ffffffff810593fa: mpc_ioapic_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int mpc_ioapic_id(int ioapic_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105e7be)
Location: arch/x86/kernel/apic/io_apic.c:123
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:find_isa_irq_apic
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
```
**Symbols:**

```
ffffffff8105d8d0-ffffffff8105d8ea: mpc_ioapic_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int mpc_ioapic_id(int ioapic_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810621a5)
Location: arch/x86/kernel/apic/io_apic.c:124
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:find_isa_irq_apic
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping
```
**Symbols:**

```
ffffffff81060a30-ffffffff81060a4a: mpc_ioapic_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int mpc_ioapic_id(int ioapic_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81067e9a)
Location: arch/x86/kernel/apic/io_apic.c:124
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:find_isa_irq_apic
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping
```
**Symbols:**

```
ffffffff81066710-ffffffff8106672a: mpc_ioapic_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int mpc_ioapic_id(int ioapic_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106b64b)
Location: arch/x86/kernel/apic/io_apic.c:125
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:find_isa_irq_apic
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping
```
**Symbols:**

```
ffffffff81069d80-ffffffff81069d9a: mpc_ioapic_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int mpc_ioapic_id(int ioapic_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106bfaf)
Location: arch/x86/kernel/apic/io_apic.c:125
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:find_isa_irq_apic
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping
```
**Symbols:**

```
ffffffff8106a720-ffffffff8106a73a: mpc_ioapic_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int mpc_ioapic_id(int ioapic_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810732dd)
Location: arch/x86/kernel/apic/io_apic.c:125
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC_irqs
  - arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:find_isa_irq_apic
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
Direct callers:
  - arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - drivers/iommu/amd/init.c:check_ioapic_information
  - drivers/iommu/intel/irq_remapping.c:parse_ioapics_under_ir
```
**Symbols:**

```
ffffffff81071ad0-ffffffff81071aea: mpc_ioapic_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int mpc_ioapic_id(int ioapic_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81bd7425)
Location: arch/x86/kernel/apic/io_apic.c:125
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC_irqs
  - arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:find_isa_irq_apic
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
Direct callers:
  - arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - drivers/iommu/amd/init.c:check_ioapic_information
  - drivers/iommu/intel/irq_remapping.c:parse_ioapics_under_ir
```
**Symbols:**

```
ffffffff81072f80-ffffffff81072f9a: mpc_ioapic_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int mpc_ioapic_id(int ioapic_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81bc95cd)
Location: arch/x86/kernel/apic/io_apic.c:125
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:find_isa_irq_apic
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
Direct callers:
  - arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping
```
**Symbols:**

```
ffffffff81073a50-ffffffff81073a6a: mpc_ioapic_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int mpc_ioapic_id(int ioapic_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81080e50)
Location: arch/x86/kernel/apic/io_apic.c:125
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:find_isa_irq_apic
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
Direct callers:
  - arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping
```
**Symbols:**

```
ffffffff81080eb0-ffffffff81080ee6: mpc_ioapic_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int mpc_ioapic_id(int ioapic_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810900cf)
Location: arch/x86/kernel/apic/io_apic.c:126
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:find_isa_irq_apic
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
Direct callers:
  - arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping
```
**Symbols:**

```
ffffffff81090840-ffffffff8109087e: mpc_ioapic_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int mpc_ioapic_id(int ioapic_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a4f88)
Location: arch/x86/kernel/apic/io_apic.c:126
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:find_isa_irq_apic
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
Direct callers:
  - arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping
```
**Symbols:**

```
ffffffff810a5340-ffffffff810a537e: mpc_ioapic_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int mpc_ioapic_id(int ioapic_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a806e)
Location: arch/x86/kernel/apic/io_apic.c:127
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:find_isa_irq_apic
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
Direct callers:
  - arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping
```
**Symbols:**

```
ffffffff810a8430-ffffffff810a8471: mpc_ioapic_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int mpc_ioapic_id(int ioapic_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810af0fd)
Location: arch/x86/kernel/apic/io_apic.c:127
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:find_isa_irq_apic
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
Direct callers:
  - arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping
```
**Symbols:**

```
ffffffff810af4c0-ffffffff810af501: mpc_ioapic_id (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int mpc_ioapic_id(int ioapic_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106ba9f)
Location: arch/x86/kernel/apic/io_apic.c:125
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:find_isa_irq_apic
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping
```
**Symbols:**

```
ffffffff8106a210-ffffffff8106a22a: mpc_ioapic_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int mpc_ioapic_id(int ioapic_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105bdd2)
Location: arch/x86/kernel/apic/io_apic.c:125
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:find_isa_irq_apic
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping
```
**Symbols:**

```
ffffffff8105a570-ffffffff8105a58a: mpc_ioapic_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int mpc_ioapic_id(int ioapic_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106bf4f)
Location: arch/x86/kernel/apic/io_apic.c:125
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:find_isa_irq_apic
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping
```
**Symbols:**

```
ffffffff8106a6c0-ffffffff8106a6da: mpc_ioapic_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int mpc_ioapic_id(int ioapic_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106d64f)
Location: arch/x86/kernel/apic/io_apic.c:125
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
  - arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:setup_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
  - arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:find_isa_irq_apic
  - arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_init
  - arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic
  - arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq
  - arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping
```
**Symbols:**

```
ffffffff8106bdc0-ffffffff8106bdda: mpc_ioapic_id (STB_GLOBAL)
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
