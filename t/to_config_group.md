# Function: <code>to_config_group</code>

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
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff812df2d8)
Location: include/linux/configfs.h:106
Inline: True
Inline callers:
  - fs/configfs/dir.c:link_obj
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: include/linux/configfs.h:106
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
In fs/configfs/dir.c (ffffffff81303c48)
Location: include/linux/configfs.h:106
Inline: True
Inline callers:
  - fs/configfs/dir.c:link_obj
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: include/linux/configfs.h:106
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
In fs/configfs/dir.c (ffffffff81333255)
Location: include/linux/configfs.h:106
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_detach_group
  - fs/configfs/dir.c:link_obj
  - fs/configfs/dir.c:link_obj
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff81546e85)
Location: include/linux/configfs.h:106
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
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store
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
In fs/configfs/dir.c (ffffffff8134a645)
Location: include/linux/configfs.h:106
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_detach_group
  - fs/configfs/dir.c:link_obj
  - fs/configfs/dir.c:link_obj
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff8155d6b5)
Location: include/linux/configfs.h:106
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
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store
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
In fs/configfs/dir.c (ffffffff81372e95)
Location: include/linux/configfs.h:92
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_detach_group
  - fs/configfs/dir.c:link_obj
  - fs/configfs/dir.c:link_obj
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff8158d865)
Location: include/linux/configfs.h:92
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
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store
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
In fs/configfs/dir.c (ffffffff8138b295)
Location: include/linux/configfs.h:92
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_detach_group
  - fs/configfs/dir.c:link_obj
  - fs/configfs/dir.c:link_obj
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff815af485)
Location: include/linux/configfs.h:92
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
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store
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
In fs/configfs/dir.c (ffffffff813d5b2b)
Location: include/linux/configfs.h:92
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:link_group
  - fs/configfs/dir.c:link_group
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff816585f5)
Location: include/linux/configfs.h:92
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
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store
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
In fs/configfs/dir.c (ffffffff813e781b)
Location: include/linux/configfs.h:92
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:link_group
  - fs/configfs/dir.c:link_group
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff81678a5e)
Location: include/linux/configfs.h:92
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
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store
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
In fs/configfs/dir.c (ffffffff813ee1eb)
Location: include/linux/configfs.h:90
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:link_group
  - fs/configfs/dir.c:link_group
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff8165b295)
Location: include/linux/configfs.h:90
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
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_primary_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_primary_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_primary_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_primary_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_secondary_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_secondary_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_secondary_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_secondary_epc_epf_link
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
In fs/configfs/dir.c (ffffffff8143f9fb)
Location: include/linux/configfs.h:90
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:client_drop_item
  - fs/configfs/dir.c:link_group
  - fs/configfs/dir.c:link_group
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff816cd415)
Location: include/linux/configfs.h:90
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
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_primary_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_primary_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_primary_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_primary_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_secondary_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_secondary_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_secondary_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_secondary_epc_epf_link
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
In fs/configfs/dir.c (0)
Location: include/linux/configfs.h:90
Inline: True
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: include/linux/configfs.h:90
Inline: True
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
In fs/configfs/dir.c (0)
Location: include/linux/configfs.h:90
Inline: True
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: include/linux/configfs.h:90
Inline: True
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
In fs/configfs/dir.c (0)
Location: include/linux/configfs.h:90
Inline: True
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: include/linux/configfs.h:90
Inline: True
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
In fs/configfs/dir.c (0)
Location: include/linux/configfs.h:90
Inline: True
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: include/linux/configfs.h:90
Inline: True
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
In fs/configfs/dir.c (ffff80001045c3a4)
Location: include/linux/configfs.h:92
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_detach_group
  - fs/configfs/dir.c:link_obj
  - fs/configfs/dir.c:link_obj
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (ffff80001071aae0)
Location: include/linux/configfs.h:92
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
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store
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
In fs/configfs/dir.c (c061d53c)
Location: include/linux/configfs.h:92
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_detach_group
  - fs/configfs/dir.c:link_obj
  - fs/configfs/dir.c:link_obj
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (c08a4954)
Location: include/linux/configfs.h:92
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
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store
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
In fs/configfs/dir.c (c000000000577c34)
Location: include/linux/configfs.h:92
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:client_drop_item
  - fs/configfs/dir.c:client_disconnect_notify
  - fs/configfs/dir.c:configfs_detach_group
  - fs/configfs/dir.c:link_obj
  - fs/configfs/dir.c:link_obj
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (c00000000088ac84)
Location: include/linux/configfs.h:92
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
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store
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
In fs/configfs/dir.c (ffffffe0002ea8b8)
Location: include/linux/configfs.h:92
Inline: True
Inline callers:
  - fs/configfs/dir.c:link_obj
  - fs/configfs/dir.c:link_obj
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: include/linux/configfs.h:92
Inline: True
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
In fs/configfs/dir.c (ffffffff81383875)
Location: include/linux/configfs.h:92
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_detach_group
  - fs/configfs/dir.c:link_obj
  - fs/configfs/dir.c:link_obj
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff815a2c45)
Location: include/linux/configfs.h:92
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
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store
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
In fs/configfs/dir.c (ffffffff81374305)
Location: include/linux/configfs.h:92
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_detach_group
  - fs/configfs/dir.c:link_obj
  - fs/configfs/dir.c:link_obj
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff81591de5)
Location: include/linux/configfs.h:92
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
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store
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
In fs/configfs/dir.c (ffffffff81381345)
Location: include/linux/configfs.h:92
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_detach_group
  - fs/configfs/dir.c:link_obj
  - fs/configfs/dir.c:link_obj
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff815a31d5)
Location: include/linux/configfs.h:92
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
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store
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
In fs/configfs/dir.c (ffffffff81394e05)
Location: include/linux/configfs.h:92
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_detach_group
  - fs/configfs/dir.c:link_obj
  - fs/configfs/dir.c:link_obj
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff815bd5d5)
Location: include/linux/configfs.h:92
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
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_unlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_show
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store
```
</details>
</li>
</ul>

## Differences
