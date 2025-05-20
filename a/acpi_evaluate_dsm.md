# Function: <code>acpi_evaluate_dsm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
union acpi_object *acpi_evaluate_dsm(acpi_handle handle, const u8 *uuid, int rev, int func, union acpi_object *argv4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff8147ae3a)
Location: drivers/acpi/utils.c:631
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffff8147ae3a-ffffffff8147af4d: acpi_evaluate_dsm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
union acpi_object *acpi_evaluate_dsm(acpi_handle handle, const u8 *uuid, u64 rev, u64 func, union acpi_object *argv4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff814c93e7)
Location: drivers/acpi/utils.c:628
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffff814c93e7-ffffffff814c94f3: acpi_evaluate_dsm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
union acpi_object *acpi_evaluate_dsm(acpi_handle handle, const u8 *uuid, u64 rev, u64 func, union acpi_object *argv4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff814eb32b)
Location: drivers/acpi/utils.c:628
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffff814eb32b-ffffffff814eb437: acpi_evaluate_dsm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
union acpi_object *acpi_evaluate_dsm(acpi_handle handle, const guid_t *guid, u64 rev, u64 func, union acpi_object *argv4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff814f7390)
Location: drivers/acpi/utils.c:628
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffff814f7390-ffffffff814f74a9: acpi_evaluate_dsm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
union acpi_object *acpi_evaluate_dsm(acpi_handle handle, const guid_t *guid, u64 rev, u64 func, union acpi_object *argv4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81538630)
Location: drivers/acpi/utils.c:629
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffff81538630-ffffffff81538749: acpi_evaluate_dsm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
union acpi_object *acpi_evaluate_dsm(acpi_handle handle, const guid_t *guid, u64 rev, u64 func, union acpi_object *argv4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff8156e2c0)
Location: drivers/acpi/utils.c:629
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffff8156e2c0-ffffffff8156e3d6: acpi_evaluate_dsm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
union acpi_object *acpi_evaluate_dsm(acpi_handle handle, const guid_t *guid, u64 rev, u64 func, union acpi_object *argv4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81585e80)
Location: drivers/acpi/utils.c:629
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/acpi_adxl.c:adxl_dsm
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffff81585e80-ffffffff81585f96: acpi_evaluate_dsm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
union acpi_object *acpi_evaluate_dsm(acpi_handle handle, const guid_t *guid, u64 rev, u64 func, union acpi_object *argv4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815b6b10)
Location: drivers/acpi/utils.c:616
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/acpi_adxl.c:adxl_dsm
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffff815b6b10-ffffffff815b6c26: acpi_evaluate_dsm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
union acpi_object *acpi_evaluate_dsm(acpi_handle handle, const guid_t *guid, u64 rev, u64 func, union acpi_object *argv4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815d7d40)
Location: drivers/acpi/utils.c:616
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/acpi_adxl.c:adxl_dsm
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
**Symbols:**

```
ffffffff815d7d40-ffffffff815d7e56: acpi_evaluate_dsm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
union acpi_object *acpi_evaluate_dsm(acpi_handle handle, const guid_t *guid, u64 rev, u64 func, union acpi_object *argv4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81682070)
Location: drivers/acpi/utils.c:648
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_optimize_delay
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/acpi_adxl.c:adxl_dsm
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
  - drivers/char/tpm/tpm_crb.c:crb_send
```
**Symbols:**

```
ffffffff81682070-ffffffff81682186: acpi_evaluate_dsm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
union acpi_object *acpi_evaluate_dsm(acpi_handle handle, const guid_t *guid, u64 rev, u64 func, union acpi_object *argv4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff816a0420)
Location: drivers/acpi/utils.c:644
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_optimize_delay
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/acpi_adxl.c:adxl_dsm
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
  - drivers/char/tpm/tpm_crb.c:crb_send
```
**Symbols:**

```
ffffffff816a0420-ffffffff816a0536: acpi_evaluate_dsm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
union acpi_object *acpi_evaluate_dsm(acpi_handle handle, const guid_t *guid, u64 rev, u64 func, union acpi_object *argv4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81682e80)
Location: drivers/acpi/utils.c:638
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/acpi_adxl.c:adxl_dsm
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_get_tgl_lpm_reqs
```
**Symbols:**

```
ffffffff81682e80-ffffffff81682f96: acpi_evaluate_dsm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
union acpi_object *acpi_evaluate_dsm(acpi_handle handle, const guid_t *guid, u64 rev, u64 func, union acpi_object *argv4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff816f7fd0)
Location: drivers/acpi/utils.c:652
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/s2idle.c:validate_dsm
  - drivers/acpi/x86/s2idle.c:acpi_sleep_run_lps0_dsm
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/acpi_adxl.c:adxl_dsm
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_get_tgl_lpm_reqs
```
**Symbols:**

```
ffffffff816f7fd0-ffffffff816f80e6: acpi_evaluate_dsm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
union acpi_object *acpi_evaluate_dsm(acpi_handle handle, const guid_t *guid, u64 rev, u64 func, union acpi_object *argv4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81825000)
Location: drivers/acpi/utils.c:652
Inline: False
Direct callers:
  - drivers/pci/pcie/edr.c:pci_acpi_add_edr_notifier
  - drivers/pci/pcie/edr.c:edr_handle_event
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/acpi/utils.c:acpi_check_dsm
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/s2idle.c:validate_dsm
  - drivers/acpi/x86/s2idle.c:acpi_sleep_run_lps0_dsm
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/acpi_adxl.c:adxl_dsm
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/iommu/intel/dmar.c:dmar_walk_dsm_resource
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_get_tgl_lpm_reqs
```
**Symbols:**

```
ffffffff81825000-ffffffff81825142: acpi_evaluate_dsm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
union acpi_object *acpi_evaluate_dsm(acpi_handle handle, const guid_t *guid, u64 rev, u64 func, union acpi_object *argv4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff819561b0)
Location: drivers/acpi/utils.c:690
Inline: False
Direct callers:
  - drivers/pci/pcie/edr.c:pci_acpi_add_edr_notifier
  - drivers/pci/pcie/edr.c:edr_handle_event
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/acpi/utils.c:acpi_check_dsm
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/s2idle.c:validate_dsm
  - drivers/acpi/x86/s2idle.c:acpi_sleep_run_lps0_dsm
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/acpi_adxl.c:adxl_dsm
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/iommu/intel/dmar.c:dmar_walk_dsm_resource
  - drivers/usb/core/usb-acpi.c:usb_acpi_port_lpm_incapable
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/platform/x86/intel/pmc/tgl.c:pmc_core_get_tgl_lpm_reqs
```
**Symbols:**

```
ffffffff819561b0-ffffffff819562f2: acpi_evaluate_dsm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
union acpi_object *acpi_evaluate_dsm(acpi_handle handle, const guid_t *guid, u64 rev, u64 func, union acpi_object *argv4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff8199c5b0)
Location: drivers/acpi/utils.c:690
Inline: False
Direct callers:
  - drivers/pci/pcie/edr.c:pci_acpi_add_edr_notifier
  - drivers/pci/pcie/edr.c:edr_handle_event
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/acpi/utils.c:acpi_check_dsm
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/s2idle.c:validate_dsm
  - drivers/acpi/x86/s2idle.c:acpi_sleep_run_lps0_dsm
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/acpi_adxl.c:adxl_dsm
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/iommu/intel/dmar.c:dmar_walk_dsm_resource
  - drivers/usb/core/usb-acpi.c:usb_acpi_port_lpm_incapable
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/platform/x86/intel/pmc/tgl.c:pmc_core_get_tgl_lpm_reqs
```
**Symbols:**

```
ffffffff8199c5b0-ffffffff8199c6f2: acpi_evaluate_dsm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
union acpi_object *acpi_evaluate_dsm(acpi_handle handle, const guid_t *guid, u64 rev, u64 func, union acpi_object *argv4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff819e55e0)
Location: drivers/acpi/utils.c:762
Inline: False
Direct callers:
  - drivers/pci/pcie/edr.c:pci_acpi_add_edr_notifier
  - drivers/pci/pcie/edr.c:edr_handle_event
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/acpi/utils.c:acpi_check_dsm
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/s2idle.c:validate_dsm
  - drivers/acpi/x86/s2idle.c:acpi_sleep_run_lps0_dsm
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/acpi_adxl.c:adxl_dsm
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/iommu/intel/dmar.c:dmar_walk_dsm_resource
  - drivers/usb/core/usb-acpi.c:usb_acpi_port_lpm_incapable
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/platform/x86/amd/wbrf.c:amd_wbrf_retrieve_freq_band
  - drivers/platform/x86/amd/wbrf.c:wbrf_record
```
**Symbols:**

```
ffffffff819e55e0-ffffffff819e5722: acpi_evaluate_dsm (STB_GLOBAL)
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
union acpi_object *acpi_evaluate_dsm(acpi_handle handle, const guid_t *guid, u64 rev, u64 func, union acpi_object *argv4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffff8000107652a0)
Location: drivers/acpi/utils.c:616
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
**Symbols:**

```
ffff8000107652a0-ffff8000107653b8: acpi_evaluate_dsm (STB_GLOBAL)
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
union acpi_object *acpi_evaluate_dsm(acpi_handle handle, const guid_t *guid, u64 rev, u64 func, union acpi_object *argv4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815cb070)
Location: drivers/acpi/utils.c:616
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/acpi_adxl.c:adxl_dsm
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
**Symbols:**

```
ffffffff815cb070-ffffffff815cb186: acpi_evaluate_dsm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
union acpi_object *acpi_evaluate_dsm(acpi_handle handle, const guid_t *guid, u64 rev, u64 func, union acpi_object *argv4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815b40c0)
Location: drivers/acpi/utils.c:616
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/acpi_adxl.c:adxl_dsm
  - drivers/acpi/nfit/core.c:nfit_intel_shutdown_status
  - drivers/acpi/nfit/core.c:acpi_nfit_ctl
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
**Symbols:**

```
ffffffff815b40c0-ffffffff815b41d6: acpi_evaluate_dsm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
union acpi_object *acpi_evaluate_dsm(acpi_handle handle, const guid_t *guid, u64 rev, u64 func, union acpi_object *argv4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815cc020)
Location: drivers/acpi/utils.c:616
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/acpi_adxl.c:adxl_dsm
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
**Symbols:**

```
ffffffff815cc020-ffffffff815cc136: acpi_evaluate_dsm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
union acpi_object *acpi_evaluate_dsm(acpi_handle handle, const guid_t *guid, u64 rev, u64 func, union acpi_object *argv4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815e5ec0)
Location: drivers/acpi/utils.c:616
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/pci_root.c:acpi_pci_root_create
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/acpi_adxl.c:adxl_dsm
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/char/tpm/tpm_ppi.c:show_ppi_operations
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action
  - drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request
  - drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
**Symbols:**

```
ffffffff815e5ec0-ffffffff815e5fd6: acpi_evaluate_dsm (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int rev</code> ➡️ <code>u64 rev</code>
</li>
<li>
<b>Param type changed. </b>
<code>int func</code> ➡️ <code>u64 func</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const guid_t *guid</code>
</li>
<li>
<b>Param removed. </b>
<code>const u8 *uuid</code>
</li>
</ul>
</details>
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
