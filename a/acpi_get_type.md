# Function: <code>acpi_get_type</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_type(acpi_handle handle, acpi_object_type *ret_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfobj.c (ffffffff814a05c7)
Location: drivers/acpi/acpica/nsxfobj.c:66
Inline: True
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_eject_store
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
**Symbols:**

```
ffffffff814a05c7-ffffffff814a0635: acpi_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_type(acpi_handle handle, acpi_object_type *ret_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfobj.c (ffffffff814ef8bb)
Location: drivers/acpi/acpica/nsxfobj.c:66
Inline: True
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_eject_store
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
**Symbols:**

```
ffffffff814ef8bb-ffffffff814ef929: acpi_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_type(acpi_handle handle, acpi_object_type *ret_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfobj.c (ffffffff81512310)
Location: drivers/acpi/acpica/nsxfobj.c:66
Inline: True
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_eject_store
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/processor_core.c:set_processor_node_mapping
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
**Symbols:**

```
ffffffff81512310-ffffffff8151237e: acpi_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_type(acpi_handle handle, acpi_object_type *ret_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfobj.c (ffffffff81522a5b)
Location: drivers/acpi/acpica/nsxfobj.c:66
Inline: True
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_eject_store
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
**Symbols:**

```
ffffffff81522a5b-ffffffff81522aca: acpi_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_type(acpi_handle handle, acpi_object_type *ret_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfobj.c (ffffffff815771df)
Location: drivers/acpi/acpica/nsxfobj.c:66
Inline: True
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_eject_store
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
**Symbols:**

```
ffffffff815771df-ffffffff8157724e: acpi_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_type(acpi_handle handle, acpi_object_type *ret_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfobj.c (ffffffff815ae148)
Location: drivers/acpi/acpica/nsxfobj.c:30
Inline: True
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_eject_store
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
**Symbols:**

```
ffffffff815ae148-ffffffff815ae1b7: acpi_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_type(acpi_handle handle, acpi_object_type *ret_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfobj.c (ffffffff815c7139)
Location: drivers/acpi/acpica/nsxfobj.c:30
Inline: True
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_eject_store
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
**Symbols:**

```
ffffffff815c7139-ffffffff815c71a8: acpi_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_type(acpi_handle handle, acpi_object_type *ret_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfobj.c (ffffffff815f8a61)
Location: drivers/acpi/acpica/nsxfobj.c:30
Inline: True
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_eject_store
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
**Symbols:**

```
ffffffff815f8a61-ffffffff815f8acf: acpi_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_type(acpi_handle handle, acpi_object_type *ret_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfobj.c (ffffffff81619f08)
Location: drivers/acpi/acpica/nsxfobj.c:30
Inline: True
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_eject_store
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
**Symbols:**

```
ffffffff81619f08-ffffffff81619f76: acpi_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_type(acpi_handle handle, acpi_object_type *ret_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfobj.c (ffffffff816c6457)
Location: drivers/acpi/acpica/nsxfobj.c:30
Inline: True
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_eject_store
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/processor_pdc.c:processor_physically_present
  - drivers/acpi/acpica/hwpci.c:acpi_hw_get_pci_device_info
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
**Symbols:**

```
ffffffff816c6457-ffffffff816c64c5: acpi_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_type(acpi_handle handle, acpi_object_type *ret_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfobj.c (ffffffff816e4479)
Location: drivers/acpi/acpica/nsxfobj.c:31
Inline: True
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_eject_store
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/processor_pdc.c:processor_physically_present
  - drivers/acpi/acpica/hwpci.c:acpi_hw_get_pci_device_info
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
**Symbols:**

```
ffffffff816e4479-ffffffff816e44e7: acpi_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_type(acpi_handle handle, acpi_object_type *ret_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfobj.c (ffffffff816c634b)
Location: drivers/acpi/acpica/nsxfobj.c:31
Inline: True
Direct callers:
  - drivers/acpi/device_sysfs.c:eject_store
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/acpica/hwpci.c:acpi_hw_process_pci_list
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
**Symbols:**

```
ffffffff816c634b-ffffffff816c63b9: acpi_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_type(acpi_handle handle, acpi_object_type *ret_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfobj.c (ffffffff8173d6b6)
Location: drivers/acpi/acpica/nsxfobj.c:31
Inline: True
Direct callers:
  - drivers/acpi/device_sysfs.c:eject_store
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/acpica/hwpci.c:acpi_hw_process_pci_list
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
**Symbols:**

```
ffffffff8173d6b6-ffffffff8173d724: acpi_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_get_type(acpi_handle handle, acpi_object_type *ret_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfobj.c (ffffffff8186ee9f)
Location: drivers/acpi/acpica/nsxfobj.c:31
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:eject_store
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/acpica/hwpci.c:acpi_hw_process_pci_list
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
**Symbols:**

```
ffffffff8186ee9f-ffffffff8186ef1b: acpi_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_get_type(acpi_handle handle, acpi_object_type *ret_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfobj.c (ffffffff819af110)
Location: drivers/acpi/acpica/nsxfobj.c:31
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:eject_store
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/acpica/hwpci.c:acpi_hw_process_pci_list
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
**Symbols:**

```
ffffffff819af110-ffffffff819af1a6: acpi_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_get_type(acpi_handle handle, acpi_object_type *ret_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfobj.c (ffffffff819f6000)
Location: drivers/acpi/acpica/nsxfobj.c:31
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:eject_store
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/acpica/hwpci.c:acpi_hw_process_pci_list
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
**Symbols:**

```
ffffffff819f6000-ffffffff819f6096: acpi_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_get_type(acpi_handle handle, acpi_object_type *ret_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfobj.c (ffffffff81a40e50)
Location: drivers/acpi/acpica/nsxfobj.c:31
Inline: False
Direct callers:
  - drivers/acpi/device_sysfs.c:eject_store
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:processor_physically_present
  - drivers/acpi/acpica/hwpci.c:acpi_hw_process_pci_list
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
**Symbols:**

```
ffffffff81a40e50-ffffffff81a40ee6: acpi_get_type (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_type(acpi_handle handle, acpi_object_type *ret_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfobj.c (ffff8000107919f4)
Location: drivers/acpi/acpica/nsxfobj.c:30
Inline: True
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_eject_store
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
**Symbols:**

```
ffff8000107919f4-ffff800010791a6c: acpi_get_type (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_type(acpi_handle handle, acpi_object_type *ret_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfobj.c (ffffffff815f706a)
Location: drivers/acpi/acpica/nsxfobj.c:30
Inline: True
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_eject_store
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
**Symbols:**

```
ffffffff815f706a-ffffffff815f70d8: acpi_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_type(acpi_handle handle, acpi_object_type *ret_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfobj.c (ffffffff815e25a9)
Location: drivers/acpi/acpica/nsxfobj.c:30
Inline: True
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_eject_store
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
**Symbols:**

```
ffffffff815e25a9-ffffffff815e2617: acpi_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_type(acpi_handle handle, acpi_object_type *ret_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfobj.c (ffffffff8160e1e8)
Location: drivers/acpi/acpica/nsxfobj.c:30
Inline: True
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_eject_store
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
**Symbols:**

```
ffffffff8160e1e8-ffffffff8160e256: acpi_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_type(acpi_handle handle, acpi_object_type *ret_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfobj.c (ffffffff81628098)
Location: drivers/acpi/acpica/nsxfobj.c:30
Inline: True
Direct callers:
  - drivers/acpi/device_sysfs.c:acpi_eject_store
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
**Symbols:**

```
ffffffff81628098-ffffffff81628106: acpi_get_type (STB_GLOBAL)
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
