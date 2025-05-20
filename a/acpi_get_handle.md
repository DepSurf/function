# Function: <code>acpi_get_handle</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
acpi_status acpi_get_handle(acpi_handle parent, acpi_string pathname, acpi_handle *ret_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff8149fe31)
Location: drivers/acpi/acpica/nsxfname.c:80
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/acpi/utils.c:acpi_has_method
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/apei/apei-base.c:apei_osc_setup
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/i2c/i2c-core.c:acpi_i2c_find_address
```
**Symbols:**

```
ffffffff8149fe31-ffffffff8149feef: acpi_get_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
acpi_status acpi_get_handle(acpi_handle parent, acpi_string pathname, acpi_handle *ret_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff814ef176)
Location: drivers/acpi/acpica/nsxfname.c:80
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/acpi/utils.c:acpi_has_method
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/apei/apei-base.c:apei_osc_setup
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/i2c/i2c-core.c:acpi_i2c_fill_info
```
**Symbols:**

```
ffffffff814ef176-ffffffff814ef234: acpi_get_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
acpi_status acpi_get_handle(acpi_handle parent, acpi_string pathname, acpi_handle *ret_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff81511c06)
Location: drivers/acpi/acpica/nsxfname.c:80
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/acpi/utils.c:acpi_has_method
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/ec.c:acpi_ec_ecdt_start
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/apei/apei-base.c:apei_osc_setup
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/i2c/i2c-core.c:i2c_acpi_fill_info
```
**Symbols:**

```
ffffffff81511c06-ffffffff81511cc4: acpi_get_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_get_handle(acpi_handle parent, acpi_string pathname, acpi_handle *ret_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff8152235b)
Location: drivers/acpi/acpica/nsxfname.c:80
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/acpi/utils.c:acpi_has_method
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/apei/apei-base.c:apei_osc_setup
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_fill_info
```
**Symbols:**

```
ffffffff8152235b-ffffffff81522419: acpi_get_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_get_handle(acpi_handle parent, acpi_string pathname, acpi_handle *ret_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff81576ad0)
Location: drivers/acpi/acpica/nsxfname.c:80
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/acpi/utils.c:acpi_has_method
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/apei/apei-base.c:apei_osc_setup
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_fill_info
```
**Symbols:**

```
ffffffff81576ad0-ffffffff81576b9d: acpi_get_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_get_handle(acpi_handle parent, acpi_string pathname, acpi_handle *ret_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff815ada4e)
Location: drivers/acpi/acpica/nsxfname.c:46
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/acpi/utils.c:acpi_has_method
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/apei/apei-base.c:apei_osc_setup
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_fill_info
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff815ada4e-ffffffff815adb1b: acpi_get_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_get_handle(acpi_handle parent, acpi_string pathname, acpi_handle *ret_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff815c6a45)
Location: drivers/acpi/acpica/nsxfname.c:46
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/acpi/utils.c:acpi_has_method
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/apei/apei-base.c:apei_osc_setup
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_fill_info
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff815c6a45-ffffffff815c6b0a: acpi_get_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_get_handle(acpi_handle parent, acpi_string pathname, acpi_handle *ret_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff815f8362)
Location: drivers/acpi/acpica/nsxfname.c:46
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/acpi/utils.c:acpi_has_method
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/apei/apei-base.c:apei_osc_setup
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/spi/spi.c:acpi_spi_add_resource
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_fill_info
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff815f8362-ffffffff815f8425: acpi_get_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_get_handle(acpi_handle parent, acpi_string pathname, acpi_handle *ret_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff81619808)
Location: drivers/acpi/acpica/nsxfname.c:46
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/acpi/utils.c:acpi_has_method
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/apei/apei-base.c:apei_osc_setup
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/spi/spi.c:acpi_spi_add_resource
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_fill_info
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff81619808-ffffffff816198cb: acpi_get_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_get_handle(acpi_handle parent, acpi_string pathname, acpi_handle *ret_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff816c5d4e)
Location: drivers/acpi/acpica/nsxfname.c:46
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/acpi/utils.c:acpi_has_method
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/bus.c:acpi_bus_osc_support
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/pci_irq.c:acpi_pci_irq_check_entry
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
  - drivers/acpi/property.c:acpi_add_nondev_subnodes
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/apei/apei-base.c:apei_osc_setup
  - drivers/spi/spi.c:acpi_spi_add_resource
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_fill_info
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists
```
**Symbols:**

```
ffffffff816c5d4e-ffffffff816c5e11: acpi_get_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_get_handle(acpi_handle parent, acpi_string pathname, acpi_handle *ret_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff816e3d81)
Location: drivers/acpi/acpica/nsxfname.c:46
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/acpi/utils.c:acpi_has_method
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/bus.c:acpi_bus_osc_support
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/pci_irq.c:acpi_pci_irq_check_entry
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
  - drivers/acpi/property.c:acpi_add_nondev_subnodes
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/apei/apei-base.c:apei_osc_setup
  - drivers/spi/spi.c:acpi_spi_add_resource
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_fill_info
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists
```
**Symbols:**

```
ffffffff816e3d81-ffffffff816e3e44: acpi_get_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_get_handle(acpi_handle parent, acpi_string pathname, acpi_handle *ret_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff816c5c53)
Location: drivers/acpi/acpica/nsxfname.c:46
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/acpi/utils.c:acpi_has_method
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/bus.c:acpi_bus_init
  - drivers/acpi/bus.c:acpi_bus_init
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/pci_irq.c:acpi_pci_irq_check_entry
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/apei/apei-base.c:apei_osc_setup
  - drivers/iommu/intel/dmar.c:dmar_dev_scope_init
  - drivers/spi/spi.c:acpi_spi_add_resource
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_fill_info
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists
```
**Symbols:**

```
ffffffff816c5c53-ffffffff816c5d16: acpi_get_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_get_handle(acpi_handle parent, acpi_string pathname, acpi_handle *ret_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff8173cfb8)
Location: drivers/acpi/acpica/nsxfname.c:46
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_get_and_request_gpiod
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/acpi/utils.c:acpi_has_method
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/bus.c:acpi_bus_init
  - drivers/acpi/bus.c:acpi_bus_init
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/pci_irq.c:acpi_pci_irq_check_entry
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/apei/apei-base.c:apei_osc_setup
  - drivers/tty/serdev/core.c:acpi_serdev_parse_resource
  - drivers/iommu/intel/dmar.c:dmar_dev_scope_init
  - drivers/spi/spi.c:acpi_spi_add_resource
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_fill_info
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists
```
**Symbols:**

```
ffffffff8173cfb8-ffffffff8173d07b: acpi_get_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_get_handle(acpi_handle parent, acpi_string pathname, acpi_handle *ret_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff8186e742)
Location: drivers/acpi/acpica/nsxfname.c:46
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_get_gpiod
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/acpi/utils.c:acpi_has_method
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/bus.c:acpi_bus_init
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/bus.c:acpi_bus_osc_negotiate_platform_control
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbnames.c:acpi_db_bus_walk
  - drivers/acpi/apei/apei-base.c:apei_osc_setup
  - drivers/tty/serdev/core.c:acpi_serdev_parse_resource
  - drivers/iommu/intel/dmar.c:dmar_dev_scope_init
  - drivers/spi/spi.c:acpi_spi_add_resource
  - drivers/spi/spi.c:acpi_spi_add_resource
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_fill_info
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists
```
**Symbols:**

```
ffffffff8186e742-ffffffff8186e817: acpi_get_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_get_handle(acpi_handle parent, acpi_string pathname, acpi_handle *ret_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff819ae860)
Location: drivers/acpi/acpica/nsxfname.c:46
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_get_gpiod
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/acpi/utils.c:acpi_has_method
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/bus.c:acpi_bus_init
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/bus.c:acpi_bus_osc_negotiate_platform_control
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbnames.c:acpi_db_bus_walk
  - drivers/acpi/apei/apei-base.c:apei_osc_setup
  - drivers/tty/serdev/core.c:acpi_serdev_parse_resource
  - drivers/iommu/intel/dmar.c:dmar_dev_scope_init
  - drivers/spi/spi.c:acpi_spi_add_resource
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_fill_info
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff819ae860-ffffffff819ae92d: acpi_get_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_get_handle(acpi_handle parent, const char *pathname, acpi_handle *ret_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff819f5720)
Location: drivers/acpi/acpica/nsxfname.c:46
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_get_gpiod
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/acpi/utils.c:acpi_has_method
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/bus.c:acpi_bus_init
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/bus.c:acpi_bus_osc_negotiate_platform_control
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbnames.c:acpi_db_bus_walk
  - drivers/acpi/apei/apei-base.c:apei_osc_setup
  - drivers/tty/serdev/core.c:acpi_serdev_parse_resource
  - drivers/iommu/intel/dmar.c:dmar_dev_scope_init
  - drivers/spi/spi.c:acpi_spi_add_resource
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_fill_info
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff819f5720-ffffffff819f57f1: acpi_get_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_get_handle(acpi_handle parent, const char *pathname, acpi_handle *ret_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff81a40570)
Location: drivers/acpi/acpica/nsxfname.c:46
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/acpi/utils.c:acpi_device_dep
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/bus.c:acpi_bus_osc_negotiate_usb_control
  - drivers/acpi/bus.c:acpi_bus_osc_negotiate_platform_control
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/mipi-disco-img.c:parse_csi2_resource
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/pci_irq.c:acpi_pci_irq_check_entry
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
  - drivers/acpi/property.c:acpi_parse_string_ref
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbnames.c:acpi_db_bus_walk
  - drivers/acpi/apei/apei-base.c:apei_osc_setup
  - drivers/tty/serdev/core.c:acpi_serdev_parse_resource
  - drivers/iommu/intel/dmar.c:dmar_dev_scope_init
  - drivers/spi/spi.c:acpi_spi_add_resource
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_fill_info
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff81a40570-ffffffff81a40641: acpi_get_handle (STB_GLOBAL)
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
acpi_status acpi_get_handle(acpi_handle parent, acpi_string pathname, acpi_handle *ret_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffff80001079125c)
Location: drivers/acpi/acpica/nsxfname.c:46
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/acpi/utils.c:acpi_has_method
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/apei/apei-base.c:apei_osc_setup
  - drivers/spi/spi.c:acpi_spi_add_resource
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_fill_info
```
**Symbols:**

```
ffff80001079125c-ffff800010791340: acpi_get_handle (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
acpi_status acpi_get_handle(acpi_handle parent, acpi_string pathname, acpi_handle *ret_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff815f6972)
Location: drivers/acpi/acpica/nsxfname.c:46
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/acpi/utils.c:acpi_has_method
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/spi/spi.c:acpi_spi_add_resource
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff815f6972-ffffffff815f6a2d: acpi_get_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_get_handle(acpi_handle parent, acpi_string pathname, acpi_handle *ret_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff815e1eba)
Location: drivers/acpi/acpica/nsxfname.c:46
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/acpi/utils.c:acpi_has_method
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/nfit/core.c:acpi_nfit_add_dimm
  - drivers/acpi/nfit/core.c:acpi_nfit_add_dimm
  - drivers/acpi/nfit/core.c:acpi_nfit_add_dimm
  - drivers/acpi/apei/apei-base.c:apei_osc_setup
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/spi/spi.c:acpi_spi_add_resource
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff815e1eba-ffffffff815e1f75: acpi_get_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_get_handle(acpi_handle parent, acpi_string pathname, acpi_handle *ret_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff8160dae8)
Location: drivers/acpi/acpica/nsxfname.c:46
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/acpi/utils.c:acpi_has_method
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/apei/apei-base.c:apei_osc_setup
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/spi/spi.c:acpi_spi_add_resource
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_fill_info
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff8160dae8-ffffffff8160dbab: acpi_get_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_get_handle(acpi_handle parent, acpi_string pathname, acpi_handle *ret_handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff81627998)
Location: drivers/acpi/acpica/nsxfname.c:46
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/acpi/utils.c:acpi_has_method
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/bus.c:acpi_init
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/apei/apei-base.c:apei_osc_setup
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/spi/spi.c:acpi_spi_add_resource
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_fill_info
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff81627998-ffffffff81627a5b: acpi_get_handle (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>acpi_string pathname</code> ➡️ <code>const char *pathname</code>
</li>
</ul>
</details>
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
