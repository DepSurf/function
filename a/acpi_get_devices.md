# Function: <code>acpi_get_devices</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_devices(const char *HID, acpi_walk_callback user_function, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff8149f9d3)
Location: drivers/acpi/acpica/nsxfeval.c:784
Inline: True
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_early_processor_osc
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - arch/x86/pci/mmconfig-shared.c:is_acpi_reserved
  - arch/x86/pci/mmconfig-shared.c:is_acpi_reserved
```
**Symbols:**

```
ffffffff8149f9d3-ffffffff8149fa67: acpi_get_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_devices(const char *HID, acpi_walk_callback user_function, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff814eecea)
Location: drivers/acpi/acpica/nsxfeval.c:783
Inline: True
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_early_processor_osc
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - arch/x86/pci/mmconfig-shared.c:is_acpi_reserved
  - arch/x86/pci/mmconfig-shared.c:is_acpi_reserved
```
**Symbols:**

```
ffffffff814eecea-ffffffff814eed86: acpi_get_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_devices(const char *HID, acpi_walk_callback user_function, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff8151177a)
Location: drivers/acpi/acpica/nsxfeval.c:783
Inline: True
Direct callers:
  - drivers/acpi/resource.c:acpi_resource_consumer
  - drivers/acpi/acpi_processor.c:acpi_early_processor_osc
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - arch/x86/pci/mmconfig-shared.c:is_acpi_reserved
  - arch/x86/pci/mmconfig-shared.c:is_acpi_reserved
```
**Symbols:**

```
ffffffff8151177a-ffffffff81511816: acpi_get_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_get_devices(const char *HID, acpi_walk_callback user_function, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff81521b23)
Location: drivers/acpi/acpica/nsxfeval.c:806
Inline: False
Direct callers:
  - drivers/acpi/resource.c:acpi_resource_consumer
  - drivers/acpi/acpi_processor.c:acpi_processor_check_duplicates
  - drivers/acpi/acpi_processor.c:acpi_early_processor_osc
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - arch/x86/pci/mmconfig-shared.c:is_acpi_reserved
  - arch/x86/pci/mmconfig-shared.c:is_acpi_reserved
```
**Symbols:**

```
ffffffff81521b23-ffffffff81521bbf: acpi_get_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_get_devices(const char *HID, acpi_walk_callback user_function, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff81575f80)
Location: drivers/acpi/acpica/nsxfeval.c:806
Inline: False
Direct callers:
  - drivers/acpi/resource.c:acpi_resource_consumer
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/acpi_processor.c:acpi_early_processor_osc
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - arch/x86/pci/mmconfig-shared.c:is_acpi_reserved
  - arch/x86/pci/mmconfig-shared.c:is_acpi_reserved
```
**Symbols:**

```
ffffffff81575f80-ffffffff815760b4: acpi_get_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_get_devices(const char *HID, acpi_walk_callback user_function, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff815acef5)
Location: drivers/acpi/acpica/nsxfeval.c:771
Inline: False
Direct callers:
  - drivers/acpi/resource.c:acpi_resource_consumer
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/acpi_processor.c:acpi_early_processor_osc
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/pnp/pnpacpi/core.c:pnpacpi_init
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - arch/x86/pci/mmconfig-shared.c:is_acpi_reserved
  - arch/x86/pci/mmconfig-shared.c:is_acpi_reserved
```
**Symbols:**

```
ffffffff815acef5-ffffffff815ad029: acpi_get_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_get_devices(const char *HID, acpi_walk_callback user_function, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff815c5eec)
Location: drivers/acpi/acpica/nsxfeval.c:771
Inline: False
Direct callers:
  - drivers/acpi/resource.c:acpi_resource_consumer
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/acpi_processor.c:acpi_early_processor_osc
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/pnp/pnpacpi/core.c:pnpacpi_init
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - arch/x86/pci/mmconfig-shared.c:is_acpi_reserved
  - arch/x86/pci/mmconfig-shared.c:is_acpi_reserved
```
**Symbols:**

```
ffffffff815c5eec-ffffffff815c6020: acpi_get_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_get_devices(const char *HID, acpi_walk_callback user_function, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff815f77d9)
Location: drivers/acpi/acpica/nsxfeval.c:771
Inline: False
Direct callers:
  - drivers/acpi/resource.c:acpi_resource_consumer
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/acpi_processor.c:acpi_early_processor_osc
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/pnp/pnpacpi/core.c:pnpacpi_init
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - arch/x86/pci/mmconfig-shared.c:is_acpi_reserved
  - arch/x86/pci/mmconfig-shared.c:is_acpi_reserved
```
**Symbols:**

```
ffffffff815f77d9-ffffffff815f7910: acpi_get_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_get_devices(const char *HID, acpi_walk_callback user_function, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff81618c7f)
Location: drivers/acpi/acpica/nsxfeval.c:771
Inline: False
Direct callers:
  - drivers/acpi/resource.c:acpi_resource_consumer
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/acpi_processor.c:acpi_early_processor_osc
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/pnp/pnpacpi/core.c:pnpacpi_init
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - arch/x86/pci/mmconfig-shared.c:is_acpi_reserved
  - arch/x86/pci/mmconfig-shared.c:is_acpi_reserved
```
**Symbols:**

```
ffffffff81618c7f-ffffffff81618db6: acpi_get_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_get_devices(const char *HID, acpi_walk_callback user_function, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff816c5757)
Location: drivers/acpi/acpica/nsxfeval.c:771
Inline: False
Direct callers:
  - drivers/acpi/resource.c:acpi_resource_consumer
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/acpi_processor.c:acpi_early_processor_osc
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/pnp/pnpacpi/core.c:pnpacpi_init
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - arch/x86/pci/mmconfig-shared.c:is_acpi_reserved
  - arch/x86/pci/mmconfig-shared.c:is_acpi_reserved
```
**Symbols:**

```
ffffffff816c5757-ffffffff816c588e: acpi_get_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_get_devices(const char *HID, acpi_walk_callback user_function, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff816e378a)
Location: drivers/acpi/acpica/nsxfeval.c:771
Inline: False
Direct callers:
  - drivers/acpi/resource.c:acpi_resource_consumer
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/acpi_processor.c:acpi_early_processor_osc
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/pnp/pnpacpi/core.c:pnpacpi_init
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - arch/x86/pci/mmconfig-shared.c:is_acpi_reserved
  - arch/x86/pci/mmconfig-shared.c:is_acpi_reserved
```
**Symbols:**

```
ffffffff816e378a-ffffffff816e38c1: acpi_get_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_get_devices(const char *HID, acpi_walk_callback user_function, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff816c565f)
Location: drivers/acpi/acpica/nsxfeval.c:771
Inline: False
Direct callers:
  - drivers/acpi/resource.c:acpi_resource_consumer
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/acpi_processor.c:acpi_early_processor_osc
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/pnp/pnpacpi/core.c:pnpacpi_init
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - arch/x86/pci/mmconfig-shared.c:is_acpi_reserved
  - arch/x86/pci/mmconfig-shared.c:is_acpi_reserved
```
**Symbols:**

```
ffffffff816c565f-ffffffff816c5796: acpi_get_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_get_devices(const char *HID, acpi_walk_callback user_function, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff8173c9c4)
Location: drivers/acpi/acpica/nsxfeval.c:771
Inline: False
Direct callers:
  - drivers/acpi/resource.c:acpi_resource_consumer
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/acpi_processor.c:acpi_early_processor_osc
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/pnp/pnpacpi/core.c:pnpacpi_init
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - arch/x86/pci/mmconfig-shared.c:is_acpi_reserved
  - arch/x86/pci/mmconfig-shared.c:is_acpi_reserved
```
**Symbols:**

```
ffffffff8173c9c4-ffffffff8173cafb: acpi_get_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_get_devices(const char *HID, acpi_walk_callback user_function, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff8186e141)
Location: drivers/acpi/acpica/nsxfeval.c:771
Inline: False
Direct callers:
  - drivers/acpi/resource.c:acpi_resource_consumer
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/acpi_processor.c:acpi_early_processor_osc
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/pnp/pnpacpi/core.c:pnpacpi_init
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - arch/x86/pci/mmconfig-shared.c:is_acpi_reserved
  - arch/x86/pci/mmconfig-shared.c:is_acpi_reserved
```
**Symbols:**

```
ffffffff8186e141-ffffffff8186e296: acpi_get_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_get_devices(const char *HID, acpi_walk_callback user_function, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff819ad980)
Location: drivers/acpi/acpica/nsxfeval.c:771
Inline: False
Direct callers:
  - drivers/acpi/resource.c:acpi_resource_consumer
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/acpi_processor.c:acpi_early_processor_osc
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/pnp/pnpacpi/core.c:pnpacpi_init
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - arch/x86/pci/mmconfig-shared.c:is_acpi_reserved
  - arch/x86/pci/mmconfig-shared.c:is_acpi_reserved
```
**Symbols:**

```
ffffffff819ad980-ffffffff819adae8: acpi_get_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_get_devices(const char *HID, acpi_walk_callback user_function, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff819f4840)
Location: drivers/acpi/acpica/nsxfeval.c:771
Inline: False
Direct callers:
  - drivers/acpi/resource.c:acpi_resource_consumer
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/acpi_processor.c:acpi_early_processor_osc
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/pnp/pnpacpi/core.c:pnpacpi_init
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - arch/x86/pci/mmconfig-shared.c:is_acpi_reserved
  - arch/x86/pci/mmconfig-shared.c:is_acpi_reserved
```
**Symbols:**

```
ffffffff819f4840-ffffffff819f49a8: acpi_get_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_get_devices(const char *HID, acpi_walk_callback user_function, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff81a3f660)
Location: drivers/acpi/acpica/nsxfeval.c:771
Inline: False
Direct callers:
  - drivers/acpi/resource.c:acpi_resource_consumer
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/acpi_processor.c:acpi_early_processor_control_setup
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/pnp/pnpacpi/core.c:pnpacpi_init
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/gpu/drm/drm_privacy_screen_x86.c:detect_thinkpad_privacy_screen
  - arch/x86/pci/mmconfig-shared.c:is_acpi_reserved
  - arch/x86/pci/mmconfig-shared.c:is_acpi_reserved
```
**Symbols:**

```
ffffffff81a3f660-ffffffff81a3f7c8: acpi_get_devices (STB_GLOBAL)
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
acpi_status acpi_get_devices(const char *HID, acpi_walk_callback user_function, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffff800010790938)
Location: drivers/acpi/acpica/nsxfeval.c:771
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_get_rc_resources
  - drivers/acpi/resource.c:acpi_resource_consumer
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/pnp/pnpacpi/core.c:pnpacpi_init
```
**Symbols:**

```
ffff800010790938-ffff8000107909f8: acpi_get_devices (STB_GLOBAL)
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
acpi_status acpi_get_devices(const char *HID, acpi_walk_callback user_function, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff815f610d)
Location: drivers/acpi/acpica/nsxfeval.c:771
Inline: False
Direct callers:
  - drivers/acpi/resource.c:acpi_resource_consumer
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/acpi_processor.c:acpi_early_processor_osc
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/pnp/pnpacpi/core.c:pnpacpi_init
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - arch/x86/pci/mmconfig-shared.c:is_acpi_reserved
  - arch/x86/pci/mmconfig-shared.c:is_acpi_reserved
```
**Symbols:**

```
ffffffff815f610d-ffffffff815f61ac: acpi_get_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_get_devices(const char *HID, acpi_walk_callback user_function, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff815e1662)
Location: drivers/acpi/acpica/nsxfeval.c:771
Inline: False
Direct callers:
  - drivers/acpi/resource.c:acpi_resource_consumer
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/acpi_processor.c:acpi_early_processor_osc
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/pnp/pnpacpi/core.c:pnpacpi_init
  - arch/x86/pci/mmconfig-shared.c:is_acpi_reserved
  - arch/x86/pci/mmconfig-shared.c:is_acpi_reserved
```
**Symbols:**

```
ffffffff815e1662-ffffffff815e1701: acpi_get_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_get_devices(const char *HID, acpi_walk_callback user_function, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff8160cf5f)
Location: drivers/acpi/acpica/nsxfeval.c:771
Inline: False
Direct callers:
  - drivers/acpi/resource.c:acpi_resource_consumer
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/acpi_processor.c:acpi_early_processor_osc
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/pnp/pnpacpi/core.c:pnpacpi_init
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - arch/x86/pci/mmconfig-shared.c:is_acpi_reserved
  - arch/x86/pci/mmconfig-shared.c:is_acpi_reserved
```
**Symbols:**

```
ffffffff8160cf5f-ffffffff8160d096: acpi_get_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_get_devices(const char *HID, acpi_walk_callback user_function, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff81626e0f)
Location: drivers/acpi/acpica/nsxfeval.c:771
Inline: False
Direct callers:
  - drivers/acpi/resource.c:acpi_resource_consumer
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/acpi_processor.c:acpi_early_processor_osc
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/pnp/pnpacpi/core.c:pnpacpi_init
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - arch/x86/pci/mmconfig-shared.c:is_acpi_reserved
  - arch/x86/pci/mmconfig-shared.c:is_acpi_reserved
```
**Symbols:**

```
ffffffff81626e0f-ffffffff81626f46: acpi_get_devices (STB_GLOBAL)
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
