# Function: <code>acpi_evaluate_object</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
acpi_status acpi_evaluate_object(acpi_handle handle, acpi_string pathname, struct acpi_object_list *external_params, struct acpi_buffer *return_buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff8149f6b1)
Location: drivers/acpi/acpica/nsxfeval.c:175
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/pci-acpi.c:pci_get_hp_params
  - drivers/pci/pci-acpi.c:pci_get_hp_params
  - drivers/acpi/utils.c:acpi_evaluate_integer
  - drivers/acpi/utils.c:acpi_evaluate_ost
  - drivers/acpi/utils.c:acpi_execute_simple_method
  - drivers/acpi/utils.c:acpi_evaluate_reference
  - drivers/acpi/utils.c:acpi_get_physical_device_location
  - drivers/acpi/utils.c:acpi_evaluate_dsm
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/bus.c:acpi_run_osc
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/processor_core.c:acpi_get_phys_id
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/ec.c:acpi_ec_event_processor
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_resume_power_resources
  - drivers/acpi/power.c:acpi_resume_power_resources
  - drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/fan.c:fan_get_cur_state
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/xen/xen-acpi-pad.c:acpi_pad_notify
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff8149f6b1-ffffffff8149f908: acpi_evaluate_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
acpi_status acpi_evaluate_object(acpi_handle handle, acpi_string pathname, struct acpi_object_list *external_params, struct acpi_buffer *return_buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff814ee9c7)
Location: drivers/acpi/acpica/nsxfeval.c:175
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/pci-acpi.c:pci_get_hp_params
  - drivers/pci/pci-acpi.c:pci_get_hp_params
  - drivers/acpi/utils.c:acpi_evaluate_dsm
  - drivers/acpi/utils.c:acpi_execute_simple_method
  - drivers/acpi/utils.c:acpi_evaluate_ost
  - drivers/acpi/utils.c:acpi_get_physical_device_location
  - drivers/acpi/utils.c:acpi_evaluate_reference
  - drivers/acpi/utils.c:acpi_evaluate_integer
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/bus.c:acpi_run_osc
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/ec.c:acpi_ec_event_processor
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/power.c:acpi_resume_power_resources
  - drivers/acpi/power.c:acpi_resume_power_resources
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:fan_get_cur_state
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/xen/xen-acpi-pad.c:acpi_pad_notify
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc
```
**Symbols:**

```
ffffffff814ee9c7-ffffffff814eec1f: acpi_evaluate_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
acpi_status acpi_evaluate_object(acpi_handle handle, acpi_string pathname, struct acpi_object_list *external_params, struct acpi_buffer *return_buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff81511457)
Location: drivers/acpi/acpica/nsxfeval.c:175
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/pci-acpi.c:pci_get_hp_params
  - drivers/pci/pci-acpi.c:pci_get_hp_params
  - drivers/acpi/utils.c:acpi_evaluate_dsm
  - drivers/acpi/utils.c:acpi_execute_simple_method
  - drivers/acpi/utils.c:acpi_evaluate_ost
  - drivers/acpi/utils.c:acpi_get_physical_device_location
  - drivers/acpi/utils.c:acpi_evaluate_reference
  - drivers/acpi/utils.c:acpi_evaluate_integer
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/bus.c:acpi_run_osc
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
  - drivers/acpi/processor_core.c:set_processor_node_mapping
  - drivers/acpi/processor_core.c:__acpi_get_phys_id
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/ec.c:acpi_ec_event_processor
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/power.c:acpi_resume_power_resources
  - drivers/acpi/power.c:acpi_resume_power_resources
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:fan_get_cur_state
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/xen/xen-acpi-pad.c:acpi_pad_notify
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc
```
**Symbols:**

```
ffffffff81511457-ffffffff815116af: acpi_evaluate_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_evaluate_object(acpi_handle handle, acpi_string pathname, struct acpi_object_list *external_params, struct acpi_buffer *return_buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff81521bbf)
Location: drivers/acpi/acpica/nsxfeval.c:198
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/pci-acpi.c:pci_get_hp_params
  - drivers/pci/pci-acpi.c:pci_get_hp_params
  - drivers/acpi/utils.c:acpi_evaluate_dsm
  - drivers/acpi/utils.c:acpi_execute_simple_method
  - drivers/acpi/utils.c:acpi_evaluate_ost
  - drivers/acpi/utils.c:acpi_get_physical_device_location
  - drivers/acpi/utils.c:acpi_evaluate_reference
  - drivers/acpi/utils.c:acpi_evaluate_integer
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/bus.c:acpi_run_osc
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/ec.c:acpi_ec_event_processor
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/power.c:acpi_turn_off_unused_power_resources
  - drivers/acpi/power.c:acpi_resume_power_resources
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:fan_get_cur_state
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/xen/xen-acpi-pad.c:acpi_pad_notify
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc
```
**Symbols:**

```
ffffffff81521bbf-ffffffff81521e10: acpi_evaluate_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_evaluate_object(acpi_handle handle, acpi_string pathname, struct acpi_object_list *external_params, struct acpi_buffer *return_buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff815760b4)
Location: drivers/acpi/acpica/nsxfeval.c:198
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/pci-acpi.c:pci_get_hp_params
  - drivers/pci/pci-acpi.c:pci_get_hp_params
  - drivers/acpi/utils.c:acpi_evaluate_dsm
  - drivers/acpi/utils.c:acpi_execute_simple_method
  - drivers/acpi/utils.c:acpi_evaluate_ost
  - drivers/acpi/utils.c:acpi_get_physical_device_location
  - drivers/acpi/utils.c:acpi_evaluate_reference
  - drivers/acpi/utils.c:acpi_evaluate_integer
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/bus.c:acpi_run_osc
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/ec.c:acpi_ec_event_processor
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:fan_get_cur_state
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/xen/xen-acpi-pad.c:acpi_pad_notify
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc
```
**Symbols:**

```
ffffffff815760b4-ffffffff81576453: acpi_evaluate_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_evaluate_object(acpi_handle handle, acpi_string pathname, struct acpi_object_list *external_params, struct acpi_buffer *return_buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff815ad029)
Location: drivers/acpi/acpica/nsxfeval.c:163
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_initial_sync
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/pci-acpi.c:pci_get_hp_params
  - drivers/pci/pci-acpi.c:pci_get_hp_params
  - drivers/acpi/utils.c:acpi_evaluate_dsm
  - drivers/acpi/utils.c:acpi_execute_simple_method
  - drivers/acpi/utils.c:acpi_evaluate_ost
  - drivers/acpi/utils.c:acpi_get_physical_device_location
  - drivers/acpi/utils.c:acpi_evaluate_reference
  - drivers/acpi/utils.c:acpi_evaluate_integer
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/bus.c:acpi_run_osc
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/ec.c:acpi_ec_event_processor
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:fan_get_cur_state
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_psd
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/xen/xen-acpi-pad.c:acpi_pad_notify
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff815ad029-ffffffff815ad3d3: acpi_evaluate_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_evaluate_object(acpi_handle handle, acpi_string pathname, struct acpi_object_list *external_params, struct acpi_buffer *return_buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff815c6020)
Location: drivers/acpi/acpica/nsxfeval.c:163
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler
  - drivers/pci/pci-acpi.c:pci_get_hp_params
  - drivers/pci/pci-acpi.c:pci_get_hp_params
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/utils.c:acpi_evaluate_dsm
  - drivers/acpi/utils.c:acpi_execute_simple_method
  - drivers/acpi/utils.c:acpi_evaluate_ost
  - drivers/acpi/utils.c:acpi_get_physical_device_location
  - drivers/acpi/utils.c:acpi_evaluate_reference
  - drivers/acpi/utils.c:acpi_evaluate_integer
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/bus.c:acpi_run_osc
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/ec.c:acpi_ec_event_processor
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:fan_get_cur_state
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_psd
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/xen/xen-acpi-pad.c:acpi_pad_notify
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff815c6020-ffffffff815c63ca: acpi_evaluate_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_evaluate_object(acpi_handle handle, acpi_string pathname, struct acpi_object_list *external_params, struct acpi_buffer *return_buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff815f7910)
Location: drivers/acpi/acpica/nsxfeval.c:163
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/utils.c:acpi_evaluate_dsm
  - drivers/acpi/utils.c:acpi_execute_simple_method
  - drivers/acpi/utils.c:acpi_evaluate_ost
  - drivers/acpi/utils.c:acpi_get_physical_device_location
  - drivers/acpi/utils.c:acpi_evaluate_reference
  - drivers/acpi/utils.c:acpi_evaluate_integer
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/bus.c:acpi_run_osc
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/ec.c:acpi_ec_event_processor
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/power.c:__acpi_power_on
  - drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:fan_get_cur_state
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_psd
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/xen/xen-acpi-pad.c:acpi_pad_notify
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff815f7910-ffffffff815f7cc4: acpi_evaluate_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_evaluate_object(acpi_handle handle, acpi_string pathname, struct acpi_object_list *external_params, struct acpi_buffer *return_buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff81618db6)
Location: drivers/acpi/acpica/nsxfeval.c:163
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/utils.c:acpi_evaluate_dsm
  - drivers/acpi/utils.c:acpi_execute_simple_method
  - drivers/acpi/utils.c:acpi_evaluate_ost
  - drivers/acpi/utils.c:acpi_get_physical_device_location
  - drivers/acpi/utils.c:acpi_evaluate_reference
  - drivers/acpi/utils.c:acpi_evaluate_integer
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/bus.c:acpi_run_osc
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/ec.c:acpi_ec_event_processor
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/power.c:__acpi_power_on
  - drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:fan_get_cur_state
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_psd
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/xen/xen-acpi-pad.c:acpi_pad_notify
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff81618db6-ffffffff8161916a: acpi_evaluate_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_evaluate_object(acpi_handle handle, acpi_string pathname, struct acpi_object_list *external_params, struct acpi_buffer *return_buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff816c5197)
Location: drivers/acpi/acpica/nsxfeval.c:163
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler
  - drivers/pci/pci-acpi.c:acpi_run_hpp
  - drivers/pci/pci-acpi.c:acpi_run_hpx
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_run_oshp
  - drivers/acpi/utils.c:acpi_evaluate_dsm
  - drivers/acpi/utils.c:acpi_evaluate_reg
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/utils.c:acpi_evaluate_ost
  - drivers/acpi/utils.c:acpi_get_physical_device_location
  - drivers/acpi/utils.c:acpi_evaluate_reference
  - drivers/acpi/utils.c:acpi_evaluate_integer
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/bus.c:acpi_run_osc
  - drivers/acpi/scan.c:acpi_bus_init_power_state
  - drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
  - drivers/acpi/processor_core.c:map_mat_entry
  - drivers/acpi/processor_pdc.c:processor_physically_present
  - drivers/acpi/ec.c:acpi_ec_event_processor
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/power.c:__acpi_power_on
  - drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/fan.c:acpi_fan_get_fps
  - drivers/acpi/fan.c:acpi_fan_get_fif
  - drivers/acpi/fan.c:fan_get_state_acpi4
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
  - drivers/acpi/processor_throttling.c:acpi_processor_get_tsd
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_control
  - drivers/acpi/processor_perflib.c:acpi_processor_get_psd
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_control
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/xen/xen-acpi-pad.c:acpi_pad_notify
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/ata/libata-acpi.c:ata_acpi_push_id
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/usb/core/usb-acpi.c:usb_acpi_find_companion_for_port
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_offset
  - drivers/cpufreq/intel_pstate.c:intel_pstate_no_acpi_pss
```
**Symbols:**

```
ffffffff816c5197-ffffffff816c554b: acpi_evaluate_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_evaluate_object(acpi_handle handle, acpi_string pathname, struct acpi_object_list *external_params, struct acpi_buffer *return_buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff816e31ca)
Location: drivers/acpi/acpica/nsxfeval.c:163
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler
  - drivers/pci/pci-acpi.c:acpi_run_hpp
  - drivers/pci/pci-acpi.c:acpi_run_hpx
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_run_oshp
  - drivers/acpi/utils.c:acpi_evaluate_dsm
  - drivers/acpi/utils.c:acpi_evaluate_reg
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/utils.c:acpi_evaluate_ost
  - drivers/acpi/utils.c:acpi_get_physical_device_location
  - drivers/acpi/utils.c:acpi_evaluate_reference
  - drivers/acpi/utils.c:acpi_evaluate_integer
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/bus.c:acpi_run_osc
  - drivers/acpi/scan.c:acpi_bus_init_power_state
  - drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
  - drivers/acpi/processor_core.c:map_mat_entry
  - drivers/acpi/processor_pdc.c:processor_physically_present
  - drivers/acpi/ec.c:acpi_ec_event_processor
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/power.c:__acpi_power_on
  - drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/fan.c:acpi_fan_get_fps
  - drivers/acpi/fan.c:acpi_fan_get_fif
  - drivers/acpi/fan.c:fan_get_state_acpi4
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
  - drivers/acpi/processor_throttling.c:acpi_processor_get_tsd
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_control
  - drivers/acpi/processor_perflib.c:acpi_processor_get_psd
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_control
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/xen/xen-acpi-pad.c:acpi_pad_notify
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/ata/libata-acpi.c:ata_acpi_push_id
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/usb/core/usb-acpi.c:usb_acpi_find_companion_for_port
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_offset
  - drivers/cpufreq/intel_pstate.c:intel_pstate_no_acpi_pss
```
**Symbols:**

```
ffffffff816e31ca-ffffffff816e357e: acpi_evaluate_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_evaluate_object(acpi_handle handle, acpi_string pathname, struct acpi_object_list *external_params, struct acpi_buffer *return_buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff816c509f)
Location: drivers/acpi/acpica/nsxfeval.c:163
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:acpi_run_hpx
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/utils.c:acpi_evaluate_dsm
  - drivers/acpi/utils.c:acpi_evaluate_reg
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/utils.c:acpi_evaluate_ost
  - drivers/acpi/utils.c:acpi_get_physical_device_location
  - drivers/acpi/utils.c:acpi_evaluate_reference
  - drivers/acpi/utils.c:acpi_evaluate_integer
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/bus.c:acpi_run_osc
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/ec.c:acpi_ec_event_processor
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/power.c:__acpi_power_on
  - drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_get_fps
  - drivers/acpi/fan.c:fan_get_cur_state
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_control
  - drivers/acpi/processor_perflib.c:acpi_processor_get_psd
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_control
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/xen/xen-acpi-pad.c:acpi_pad_notify
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_offset
  - drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists
```
**Symbols:**

```
ffffffff816c509f-ffffffff816c5453: acpi_evaluate_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_evaluate_object(acpi_handle handle, acpi_string pathname, struct acpi_object_list *external_params, struct acpi_buffer *return_buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff8173c404)
Location: drivers/acpi/acpica/nsxfeval.c:163
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler
  - drivers/pci/pci-acpi.c:pci_dev_acpi_reset
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:acpi_run_hpx
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/utils.c:acpi_evaluate_dsm
  - drivers/acpi/utils.c:acpi_evaluate_reg
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/utils.c:acpi_evaluate_ost
  - drivers/acpi/utils.c:acpi_get_physical_device_location
  - drivers/acpi/utils.c:acpi_evaluate_reference
  - drivers/acpi/utils.c:acpi_evaluate_integer
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/bus.c:acpi_run_osc
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/ec.c:acpi_ec_event_processor
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/power.c:__acpi_power_off
  - drivers/acpi/power.c:__acpi_power_on
  - drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_get_fps
  - drivers/acpi/fan.c:fan_get_cur_state
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_control
  - drivers/acpi/processor_perflib.c:acpi_processor_get_psd
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_control
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/xen/xen-acpi-pad.c:acpi_pad_notify
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_offset
  - drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists
```
**Symbols:**

```
ffffffff8173c404-ffffffff8173c7b8: acpi_evaluate_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_evaluate_object(acpi_handle handle, acpi_string pathname, struct acpi_object_list *external_params, struct acpi_buffer *return_buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff8186db80)
Location: drivers/acpi/acpica/nsxfeval.c:163
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler
  - drivers/pci/pci-acpi.c:pci_dev_acpi_reset
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:acpi_run_hpx
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/utils.c:acpi_evaluate_dsm
  - drivers/acpi/utils.c:acpi_evaluate_reg
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/utils.c:acpi_evaluate_ost
  - drivers/acpi/utils.c:acpi_get_physical_device_location
  - drivers/acpi/utils.c:acpi_evaluate_reference
  - drivers/acpi/utils.c:acpi_evaluate_integer
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/bus.c:acpi_run_osc
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/ec.c:acpi_ec_event_processor
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/power.c:__acpi_power_off
  - drivers/acpi/power.c:__acpi_power_on
  - drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/hwxfsleep.c:acpi_enter_sleep_state_prep
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbexec.c:acpi_db_execution_walk
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_fields
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/fan_core.c:acpi_fan_get_fst
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
  - drivers/acpi/processor_throttling.c:acpi_processor_get_tsd
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_control
  - drivers/acpi/processor_perflib.c:acpi_processor_get_psd
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_control
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/reset/core.c:__device_reset
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_offset
  - drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists
```
**Symbols:**

```
ffffffff8186db80-ffffffff8186df25: acpi_evaluate_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_evaluate_object(acpi_handle handle, acpi_string pathname, struct acpi_object_list *external_params, struct acpi_buffer *return_buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff819ae0c0)
Location: drivers/acpi/acpica/nsxfeval.c:163
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler
  - drivers/pci/pci-acpi.c:pci_dev_acpi_reset
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:acpi_run_hpx
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/utils.c:acpi_evaluate_dsm
  - drivers/acpi/utils.c:acpi_evaluate_reg
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/utils.c:acpi_evaluate_ost
  - drivers/acpi/utils.c:acpi_get_physical_device_location
  - drivers/acpi/utils.c:acpi_evaluate_reference
  - drivers/acpi/utils.c:acpi_get_subsystem_id
  - drivers/acpi/utils.c:acpi_evaluate_integer
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_pm.c:acpi_device_fix_up_power_extended
  - drivers/acpi/device_pm.c:fix_up_power_if_applicable
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/bus.c:acpi_run_osc
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/ec.c:acpi_ec_event_processor
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/power.c:__acpi_power_off
  - drivers/acpi/power.c:__acpi_power_on
  - drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/hwxfsleep.c:acpi_enter_sleep_state_prep
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbexec.c:acpi_db_execution_walk
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_fields
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/fan_core.c:acpi_fan_get_fst
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
  - drivers/acpi/processor_throttling.c:acpi_processor_get_tsd
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_control
  - drivers/acpi/processor_perflib.c:acpi_processor_get_psd
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_control
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/reset/core.c:__device_reset
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_offset
  - drivers/cpufreq/intel_pstate.c:intel_pstate_no_acpi_pss
```
**Symbols:**

```
ffffffff819ae0c0-ffffffff819ae52f: acpi_evaluate_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_evaluate_object(acpi_handle handle, acpi_string pathname, struct acpi_object_list *external_params, struct acpi_buffer *return_buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff819f4f80)
Location: drivers/acpi/acpica/nsxfeval.c:163
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler
  - drivers/pci/pci-acpi.c:pci_dev_acpi_reset
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:acpi_run_hpx
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/utils.c:acpi_evaluate_dsm
  - drivers/acpi/utils.c:acpi_evaluate_reg
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/utils.c:acpi_evaluate_ost
  - drivers/acpi/utils.c:acpi_get_physical_device_location
  - drivers/acpi/utils.c:acpi_evaluate_reference
  - drivers/acpi/utils.c:acpi_get_subsystem_id
  - drivers/acpi/utils.c:acpi_evaluate_integer
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_pm.c:acpi_device_fix_up_power_extended
  - drivers/acpi/device_pm.c:fix_up_power_if_applicable
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/bus.c:acpi_run_osc
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/ec.c:acpi_ec_event_processor
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/power.c:__acpi_power_off
  - drivers/acpi/power.c:__acpi_power_on
  - drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/hwxfsleep.c:acpi_enter_sleep_state_prep
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbexec.c:acpi_db_execution_walk
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_fields
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/fan_core.c:acpi_fan_get_fst
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
  - drivers/acpi/processor_throttling.c:acpi_processor_get_tsd
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_control
  - drivers/acpi/processor_perflib.c:acpi_processor_get_psd
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_control
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/reset/core.c:__device_reset
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_offset
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff819f4f80-ffffffff819f53e5: acpi_evaluate_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_evaluate_object(acpi_handle handle, acpi_string pathname, struct acpi_object_list *external_params, struct acpi_buffer *return_buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff81a3fe60)
Location: drivers/acpi/acpica/nsxfeval.c:163
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler
  - drivers/pci/pci-acpi.c:pci_dev_acpi_reset
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:acpi_run_hpx
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/utils.c:acpi_evaluate_dsm
  - drivers/acpi/utils.c:acpi_evaluate_reg
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/utils.c:acpi_evaluate_ost
  - drivers/acpi/utils.c:acpi_get_physical_device_location
  - drivers/acpi/utils.c:acpi_evaluate_reference
  - drivers/acpi/utils.c:acpi_get_subsystem_id
  - drivers/acpi/utils.c:acpi_evaluate_integer
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_pm.c:acpi_device_fix_up_power_extended
  - drivers/acpi/device_pm.c:fix_up_power_if_applicable
  - drivers/acpi/device_pm.c:acpi_bus_init_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/bus.c:acpi_run_osc
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:processor_physically_present
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
  - drivers/acpi/processor_core.c:map_mat_entry
  - drivers/acpi/ec.c:acpi_ec_event_processor
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/power.c:__acpi_power_off
  - drivers/acpi/power.c:__acpi_power_on
  - drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/hwxfsleep.c:acpi_enter_sleep_state_prep
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_interrupt
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbexec.c:acpi_db_execution_walk
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_fields
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/fan_core.c:acpi_fan_get_fst
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
  - drivers/acpi/processor_throttling.c:acpi_processor_get_tsd
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_control
  - drivers/acpi/processor_perflib.c:acpi_processor_get_psd
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_control
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/reset/core.c:__device_reset
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_offset
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff81a3fe60-ffffffff81a402f4: acpi_evaluate_object (STB_GLOBAL)
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
acpi_status acpi_evaluate_object(acpi_handle handle, acpi_string pathname, struct acpi_object_list *external_params, struct acpi_buffer *return_buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffff8000107909f8)
Location: drivers/acpi/acpica/nsxfeval.c:163
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/utils.c:acpi_evaluate_dsm
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/utils.c:acpi_evaluate_ost
  - drivers/acpi/utils.c:acpi_get_physical_device_location
  - drivers/acpi/utils.c:acpi_evaluate_reference
  - drivers/acpi/utils.c:acpi_evaluate_integer
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/bus.c:acpi_run_osc
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/ec.c:acpi_ec_event_processor
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/power.c:__acpi_power_on
  - drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:fan_get_cur_state
  - drivers/acpi/processor_perflib.c:acpi_processor_get_psd
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
```
**Symbols:**

```
ffff8000107909f8-ffff800010790c50: acpi_evaluate_object (STB_GLOBAL)
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
acpi_status acpi_evaluate_object(acpi_handle handle, acpi_string pathname, struct acpi_object_list *external_params, struct acpi_buffer *return_buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff815f61ac)
Location: drivers/acpi/acpica/nsxfeval.c:163
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/utils.c:acpi_evaluate_dsm
  - drivers/acpi/utils.c:acpi_execute_simple_method
  - drivers/acpi/utils.c:acpi_evaluate_ost
  - drivers/acpi/utils.c:acpi_get_physical_device_location
  - drivers/acpi/utils.c:acpi_evaluate_reference
  - drivers/acpi/utils.c:acpi_evaluate_integer
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/bus.c:acpi_run_osc
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/ec.c:acpi_ec_event_processor
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/power.c:acpi_turn_off_unused_power_resources
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/power.c:__acpi_power_on
  - drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_psd
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/xen/xen-acpi-pad.c:acpi_pad_notify
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff815f61ac-ffffffff815f6400: acpi_evaluate_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_evaluate_object(acpi_handle handle, acpi_string pathname, struct acpi_object_list *external_params, struct acpi_buffer *return_buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff815e1701)
Location: drivers/acpi/acpica/nsxfeval.c:163
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/utils.c:acpi_evaluate_dsm
  - drivers/acpi/utils.c:acpi_execute_simple_method
  - drivers/acpi/utils.c:acpi_evaluate_ost
  - drivers/acpi/utils.c:acpi_get_physical_device_location
  - drivers/acpi/utils.c:acpi_evaluate_reference
  - drivers/acpi/utils.c:acpi_evaluate_integer
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/bus.c:acpi_run_osc
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/ec.c:acpi_ec_event_processor
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/power.c:acpi_turn_off_unused_power_resources
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/power.c:__acpi_power_on
  - drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_psd
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/nfit/core.c:__acpi_nfit_notify
  - drivers/acpi/nfit/core.c:acpi_nfit_add
  - drivers/acpi/nfit/core.c:acpi_nfit_ctl
  - drivers/acpi/nfit/core.c:acpi_label_read
  - drivers/acpi/nfit/core.c:acpi_label_write
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff815e1701-ffffffff815e1955: acpi_evaluate_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_evaluate_object(acpi_handle handle, acpi_string pathname, struct acpi_object_list *external_params, struct acpi_buffer *return_buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff8160d096)
Location: drivers/acpi/acpica/nsxfeval.c:163
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/utils.c:acpi_evaluate_dsm
  - drivers/acpi/utils.c:acpi_execute_simple_method
  - drivers/acpi/utils.c:acpi_evaluate_ost
  - drivers/acpi/utils.c:acpi_get_physical_device_location
  - drivers/acpi/utils.c:acpi_evaluate_reference
  - drivers/acpi/utils.c:acpi_evaluate_integer
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/bus.c:acpi_run_osc
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/ec.c:acpi_ec_event_processor
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/power.c:__acpi_power_on
  - drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:fan_get_cur_state
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_psd
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/xen/xen-acpi-pad.c:acpi_pad_notify
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff8160d096-ffffffff8160d44a: acpi_evaluate_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_evaluate_object(acpi_handle handle, acpi_string pathname, struct acpi_object_list *external_params, struct acpi_buffer *return_buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff81626f46)
Location: drivers/acpi/acpica/nsxfeval.c:163
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_irq_handler
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/utils.c:acpi_evaluate_dsm
  - drivers/acpi/utils.c:acpi_execute_simple_method
  - drivers/acpi/utils.c:acpi_evaluate_ost
  - drivers/acpi/utils.c:acpi_get_physical_device_location
  - drivers/acpi/utils.c:acpi_evaluate_reference
  - drivers/acpi/utils.c:acpi_evaluate_integer
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/bus.c:acpi_run_osc
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_bus_get_ejd
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_core.c:acpi_get_ioapic_id
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/ec.c:acpi_ec_event_processor
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/power.c:__acpi_power_on
  - drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_execute_sleep_method
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object_typed
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:fan_get_cur_state
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_psd
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/xen/xen-acpi-pad.c:acpi_pad_notify
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/ata/libata-acpi.c:ata_acpi_on_devcfg
  - drivers/ata/libata-acpi.c:ata_dev_get_GTF
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_do_osc
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff81626f46-ffffffff816272fa: acpi_evaluate_object (STB_GLOBAL)
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
