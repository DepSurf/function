# Function: <code>to_pci_epf_group</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:42
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:42
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff81546e85)
Location: drivers/pci/endpoint/pci-ep-cfs.c:35
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_id_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_id_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_vendor_id_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_vendor_id_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_deviceid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_deviceid_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_vendorid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_vendorid_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff8155d6b5)
Location: drivers/pci/endpoint/pci-ep-cfs.c:35
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_id_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_id_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_vendor_id_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_vendor_id_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_deviceid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_deviceid_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_vendorid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_vendorid_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msix_interrupts_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msix_interrupts_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff8158d865)
Location: drivers/pci/endpoint/pci-ep-cfs.c:35
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_id_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_id_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_vendor_id_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_vendor_id_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_deviceid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_deviceid_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_vendorid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_vendorid_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msix_interrupts_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msix_interrupts_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff815af485)
Location: drivers/pci/endpoint/pci-ep-cfs.c:35
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_id_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_id_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_vendor_id_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_vendor_id_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_deviceid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_deviceid_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_vendorid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_vendorid_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msix_interrupts_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msix_interrupts_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff816585f5)
Location: drivers/pci/endpoint/pci-ep-cfs.c:34
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_id_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_id_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_vendor_id_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_vendor_id_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_deviceid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_deviceid_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_vendorid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_vendorid_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msix_interrupts_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msix_interrupts_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff81678a5e)
Location: drivers/pci/endpoint/pci-ep-cfs.c:34
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_id_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_id_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_vendor_id_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_vendor_id_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_deviceid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_deviceid_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_vendorid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_vendorid_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msix_interrupts_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msix_interrupts_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff8165b295)
Location: drivers/pci/endpoint/pci-ep-cfs.c:37
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_type_make
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_id_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_id_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_vendor_id_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_vendor_id_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_deviceid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_deviceid_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_vendorid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_vendorid_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msix_interrupts_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msix_interrupts_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_primary_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_primary_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_secondary_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_secondary_epc_epf_link
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff816cd415)
Location: drivers/pci/endpoint/pci-ep-cfs.c:37
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_type_make
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_vepf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_vepf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_vepf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_vepf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_id_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_id_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_vendor_id_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_vendor_id_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_deviceid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_deviceid_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_vendorid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_vendorid_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msix_interrupts_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msix_interrupts_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_primary_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_primary_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_secondary_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_secondary_epc_epf_link
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:37
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:37
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:38
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:38
Inline: True
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
In drivers/pci/endpoint/pci-ep-cfs.c (ffff80001071aae0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:35
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_id_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_id_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_vendor_id_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_vendor_id_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_deviceid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_deviceid_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_vendorid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_vendorid_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msix_interrupts_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msix_interrupts_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (c08a4954)
Location: drivers/pci/endpoint/pci-ep-cfs.c:35
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_id_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_id_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_vendor_id_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_vendor_id_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_deviceid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_deviceid_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_vendorid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_vendorid_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msix_interrupts_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msix_interrupts_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (c00000000088ac84)
Location: drivers/pci/endpoint/pci-ep-cfs.c:35
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_id_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_id_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_vendor_id_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_vendor_id_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_deviceid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_deviceid_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_vendorid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_vendorid_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msix_interrupts_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msix_interrupts_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffe0004e23b4)
Location: drivers/pci/endpoint/pci-ep-cfs.c:35
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_id_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_id_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_vendor_id_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_vendor_id_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_deviceid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_deviceid_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_vendorid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_vendorid_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msix_interrupts_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msix_interrupts_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff815a2c45)
Location: drivers/pci/endpoint/pci-ep-cfs.c:35
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_id_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_id_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_vendor_id_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_vendor_id_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_deviceid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_deviceid_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_vendorid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_vendorid_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msix_interrupts_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msix_interrupts_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff81591de5)
Location: drivers/pci/endpoint/pci-ep-cfs.c:35
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_id_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_id_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_vendor_id_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_vendor_id_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_deviceid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_deviceid_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_vendorid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_vendorid_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msix_interrupts_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msix_interrupts_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff815a31d5)
Location: drivers/pci/endpoint/pci-ep-cfs.c:35
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_id_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_id_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_vendor_id_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_vendor_id_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_deviceid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_deviceid_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_vendorid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_vendorid_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msix_interrupts_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msix_interrupts_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff815bd5d5)
Location: drivers/pci/endpoint/pci-ep-cfs.c:35
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_id_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_id_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_vendor_id_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subsys_vendor_id_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_deviceid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_deviceid_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_vendorid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_vendorid_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msix_interrupts_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msix_interrupts_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
</details>
</li>
</ul>

## Differences
