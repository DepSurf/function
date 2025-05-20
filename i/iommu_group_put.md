# Function: <code>iommu_group_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void iommu_group_put(struct iommu_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8152a0c0)
Location: drivers/iommu/iommu.c:569
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_bus_notifier
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
```
**Symbols:**

```
ffffffff8152a0c0-ffffffff8152a0da: iommu_group_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void iommu_group_put(struct iommu_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8157ef4b)
Location: drivers/iommu/iommu.c:560
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_bus_notifier
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
```
**Symbols:**

```
ffffffff8157d330-ffffffff8157d34a: iommu_group_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void iommu_group_put(struct iommu_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff815ab9db)
Location: drivers/iommu/iommu.c:711
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_bus_notifier
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
```
**Symbols:**

```
ffffffff815a9870-ffffffff815a988a: iommu_group_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void iommu_group_put(struct iommu_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff815c16ab)
Location: drivers/iommu/iommu.c:755
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
```
**Symbols:**

```
ffffffff815bf4b0-ffffffff815bf4cb: iommu_group_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void iommu_group_put(struct iommu_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81627e6b)
Location: drivers/iommu/iommu.c:757
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
```
**Symbols:**

```
ffffffff81625ab0-ffffffff81625acb: iommu_group_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void iommu_group_put(struct iommu_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81662abe)
Location: drivers/iommu/iommu.c:758
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_bus_notifier
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
```
**Symbols:**

```
ffffffff81660a90-ffffffff81660aaa: iommu_group_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void iommu_group_put(struct iommu_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8168109e)
Location: drivers/iommu/iommu.c:824
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
```
**Symbols:**

```
ffffffff8167ef70-ffffffff8167ef8a: iommu_group_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void iommu_group_put(struct iommu_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816b62a8)
Location: drivers/iommu/iommu.c:842
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff816b5df0-ffffffff816b5e0a: iommu_group_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void iommu_group_put(struct iommu_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816d8fa8)
Location: drivers/iommu/iommu.c:898
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_group_get_from_dev
  - drivers/vfio/vfio.c:vfio_group_put
  - drivers/vfio/vfio.c:vfio_iommu_group_put
  - drivers/vfio/vfio.c:vfio_iommu_group_put
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs
```
**Symbols:**

```
ffffffff816d8af0-ffffffff816d8b0a: iommu_group_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void iommu_group_put(struct iommu_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8178d5a8)
Location: drivers/iommu/iommu.c:1001
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_bus_notifier
  - drivers/iommu/iommu.c:iommu_page_response
  - drivers/iommu/iommu.c:iommu_probe_device
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/iommu/iommu.c:__iommu_probe_device
Direct callers:
  - drivers/iommu/intel/iommu.c:probe_acpi_namespace_devices
  - drivers/vfio/vfio.c:vfio_unregister_notifier
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio.c:vfio_unpin_pages
  - drivers/vfio/vfio.c:vfio_pin_pages
  - drivers/vfio/vfio.c:vfio_group_get_external_user_from_dev
  - drivers/vfio/vfio.c:vfio_device_get_from_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_group_release
  - drivers/vfio/vfio.c:vfio_iommu_group_put
  - drivers/vfio/vfio.c:vfio_iommu_group_put
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs
```
**Symbols:**

```
ffffffff8178d1d0-ffffffff8178d1ea: iommu_group_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void iommu_group_put(struct iommu_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff817b90b8)
Location: drivers/iommu/iommu.c:1022
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_bus_notifier
  - drivers/iommu/iommu.c:iommu_page_response
  - drivers/iommu/iommu.c:iommu_probe_device
  - drivers/iommu/iommu.c:iommu_probe_device
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/iommu/iommu.c:__iommu_probe_device
Direct callers:
  - drivers/iommu/intel/iommu.c:probe_acpi_namespace_devices
  - drivers/vfio/vfio.c:vfio_unregister_notifier
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio.c:vfio_unpin_pages
  - drivers/vfio/vfio.c:vfio_pin_pages
  - drivers/vfio/vfio.c:vfio_group_get_external_user_from_dev
  - drivers/vfio/vfio.c:vfio_device_get_from_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_group_release
  - drivers/vfio/vfio.c:vfio_iommu_group_put
  - drivers/vfio/vfio.c:vfio_iommu_group_put
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs
```
**Symbols:**

```
ffffffff817b8b90-ffffffff817b8baa: iommu_group_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void iommu_group_put(struct iommu_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8179c2c8)
Location: drivers/iommu/iommu.c:1051
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_bus_notifier
  - drivers/iommu/iommu.c:iommu_page_response
  - drivers/iommu/iommu.c:iommu_probe_device
  - drivers/iommu/iommu.c:iommu_probe_device
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/iommu/iommu.c:__iommu_probe_device
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/vfio/vfio.c:vfio_unregister_notifier
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio.c:vfio_unpin_pages
  - drivers/vfio/vfio.c:vfio_pin_pages
  - drivers/vfio/vfio.c:vfio_group_get_external_user_from_dev
  - drivers/vfio/vfio.c:vfio_device_get_from_dev
  - drivers/vfio/vfio.c:vfio_register_group_dev
  - drivers/vfio/vfio.c:vfio_register_group_dev
  - drivers/vfio/vfio.c:vfio_group_release
  - drivers/vfio/vfio.c:vfio_iommu_group_put
  - drivers/vfio/vfio.c:vfio_iommu_group_put
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs
```
**Symbols:**

```
ffffffff8179bda0-ffffffff8179bdba: iommu_group_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void iommu_group_put(struct iommu_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81824fb8)
Location: drivers/iommu/iommu.c:1066
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_bus_notifier
  - drivers/iommu/iommu.c:iommu_page_response
  - drivers/iommu/iommu.c:iommu_probe_device
  - drivers/iommu/iommu.c:iommu_probe_device
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/iommu/iommu.c:__iommu_probe_device
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/vfio/vfio.c:vfio_unregister_notifier
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio.c:vfio_unpin_pages
  - drivers/vfio/vfio.c:vfio_pin_pages
  - drivers/vfio/vfio.c:vfio_group_get_external_user_from_dev
  - drivers/vfio/vfio.c:vfio_device_get_from_dev
  - drivers/vfio/vfio.c:vfio_register_group_dev
  - drivers/vfio/vfio.c:vfio_register_group_dev
  - drivers/vfio/vfio.c:vfio_group_release
  - drivers/vfio/vfio.c:vfio_iommu_group_put
  - drivers/vfio/vfio.c:vfio_iommu_group_put
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_fill_devs
```
**Symbols:**

```
ffffffff81824b30-ffffffff81824b4a: iommu_group_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void iommu_group_put(struct iommu_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81968a98)
Location: drivers/iommu/iommu.c:1070
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_device_unuse_default_domain
  - drivers/iommu/iommu.c:iommu_device_unuse_default_domain
  - drivers/iommu/iommu.c:iommu_device_use_default_domain
  - drivers/iommu/iommu.c:iommu_device_use_default_domain
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:probe_iommu_group
  - drivers/iommu/iommu.c:probe_iommu_group
  - drivers/iommu/iommu.c:iommu_probe_device
  - drivers/iommu/iommu.c:iommu_probe_device
  - drivers/iommu/iommu.c:iommu_probe_device
  - drivers/iommu/iommu.c:iommu_probe_device
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/iommu/iommu.c:__iommu_probe_device
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/vfio/vfio.c:vfio_register_group_dev
  - drivers/vfio/vfio.c:vfio_register_group_dev
  - drivers/vfio/vfio.c:vfio_noiommu_group_alloc
  - drivers/vfio/vfio.c:vfio_noiommu_group_alloc
  - drivers/vfio/vfio.c:vfio_group_release
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_fill_devs
```
**Symbols:**

```
ffffffff81965a80-ffffffff81965aa6: iommu_group_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void iommu_group_put(struct iommu_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81acf095)
Location: drivers/iommu/iommu.c:1191
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev_pasid
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev_pasid
  - drivers/iommu/iommu.c:iommu_detach_device_pasid
  - drivers/iommu/iommu.c:iommu_detach_device_pasid
  - drivers/iommu/iommu.c:iommu_attach_device_pasid
  - drivers/iommu/iommu.c:iommu_attach_device_pasid
  - drivers/iommu/iommu.c:iommu_device_release_dma_owner
  - drivers/iommu/iommu.c:iommu_device_release_dma_owner
  - drivers/iommu/iommu.c:iommu_device_claim_dma_owner
  - drivers/iommu/iommu.c:iommu_device_claim_dma_owner
  - drivers/iommu/iommu.c:iommu_device_unuse_default_domain
  - drivers/iommu/iommu.c:iommu_device_unuse_default_domain
  - drivers/iommu/iommu.c:iommu_device_use_default_domain
  - drivers/iommu/iommu.c:iommu_device_use_default_domain
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:probe_iommu_group
  - drivers/iommu/iommu.c:probe_iommu_group
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/iommu/iommu.c:__iommu_probe_device
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81acef90-ffffffff81acefb6: iommu_group_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void iommu_group_put(struct iommu_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b1dc05)
Location: drivers/iommu/iommu.c:1182
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev_pasid
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev_pasid
  - drivers/iommu/iommu.c:iommu_detach_device_pasid
  - drivers/iommu/iommu.c:iommu_detach_device_pasid
  - drivers/iommu/iommu.c:iommu_attach_device_pasid
  - drivers/iommu/iommu.c:iommu_attach_device_pasid
  - drivers/iommu/iommu.c:iommu_device_release_dma_owner
  - drivers/iommu/iommu.c:iommu_device_release_dma_owner
  - drivers/iommu/iommu.c:iommu_device_claim_dma_owner
  - drivers/iommu/iommu.c:iommu_device_claim_dma_owner
  - drivers/iommu/iommu.c:iommu_device_unuse_default_domain
  - drivers/iommu/iommu.c:iommu_device_unuse_default_domain
  - drivers/iommu/iommu.c:iommu_device_use_default_domain
  - drivers/iommu/iommu.c:iommu_device_use_default_domain
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:probe_iommu_group
  - drivers/iommu/iommu.c:probe_iommu_group
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/iommu/iommu.c:__iommu_probe_device
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81b1db00-ffffffff81b1db26: iommu_group_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void iommu_group_put(struct iommu_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b75ff0)
Location: drivers/iommu/iommu.c:1326
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:__iommu_group_remove_device
  - drivers/iommu/iommu.c:__iommu_group_remove_device
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/iommu/iommu.c:__iommu_probe_device
  - drivers/iommu/iommu.c:iommu_device_unregister
  - drivers/iommu/iommu.c:iommu_device_unregister
```
**Symbols:**

```
ffffffff81b740d0-ffffffff81b740f6: iommu_group_put (STB_GLOBAL)
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
void iommu_group_put(struct iommu_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffff8000108c4774)
Location: drivers/iommu/iommu.c:898
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
Direct callers:
  - drivers/iommu/arm-smmu.c:arm_smmu_add_device
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_add_device
  - drivers/iommu/rockchip-iommu.c:rk_iommu_probe
  - drivers/iommu/rockchip-iommu.c:rk_iommu_add_device
  - drivers/iommu/qcom_iommu.c:qcom_iommu_add_device
  - drivers/iommu/virtio-iommu.c:viommu_add_device
```
**Symbols:**

```
ffff8000108c4208-ffff8000108c4238: iommu_group_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void iommu_group_put(struct iommu_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c09bbc0c)
Location: drivers/iommu/iommu.c:898
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
Direct callers:
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_add_device
  - drivers/iommu/omap-iommu.c:_omap_iommu_add_device
  - drivers/iommu/omap-iommu.c:omap_iommu_remove
  - drivers/iommu/omap-iommu.c:omap_iommu_probe
  - drivers/iommu/rockchip-iommu.c:rk_iommu_probe
  - drivers/iommu/rockchip-iommu.c:rk_iommu_add_device
  - drivers/iommu/tegra-gart.c:gart_iommu_add_device
  - drivers/iommu/tegra-smmu.c:tegra_smmu_add_device
  - drivers/iommu/exynos-iommu.c:exynos_iommu_remove_device
  - drivers/iommu/exynos-iommu.c:exynos_iommu_add_device
  - drivers/iommu/qcom_iommu.c:qcom_iommu_add_device
```
**Symbols:**

```
c09bb724-c09bb74c: iommu_group_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void iommu_group_put(struct iommu_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c00000000096a5dc)
Location: drivers/iommu/iommu.c:898
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
Direct callers:
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_ioda_release_pe
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_ioda_release_pe
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_sriov_disable
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_group_get_from_dev
  - drivers/vfio/vfio.c:vfio_group_put
  - drivers/vfio/vfio.c:vfio_iommu_group_put
  - drivers/vfio/vfio.c:vfio_iommu_group_put
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs
```
**Symbols:**

```
c000000000969f10-c000000000969f50: iommu_group_put (STB_GLOBAL)
```
</details>
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
void iommu_group_put(struct iommu_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8169e9f8)
Location: drivers/iommu/iommu.c:898
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff8169e540-ffffffff8169e55a: iommu_group_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void iommu_group_put(struct iommu_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167c3e8)
Location: drivers/iommu/iommu.c:898
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_group_get_from_dev
  - drivers/vfio/vfio.c:vfio_group_put
  - drivers/vfio/vfio.c:vfio_iommu_group_put
  - drivers/vfio/vfio.c:vfio_iommu_group_put
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs
```
**Symbols:**

```
ffffffff8167bf30-ffffffff8167bf4a: iommu_group_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void iommu_group_put(struct iommu_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816ccc68)
Location: drivers/iommu/iommu.c:898
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_group_get_from_dev
  - drivers/vfio/vfio.c:vfio_group_put
  - drivers/vfio/vfio.c:vfio_iommu_group_put
  - drivers/vfio/vfio.c:vfio_iommu_group_put
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs
```
**Symbols:**

```
ffffffff816cc7b0-ffffffff816cc7ca: iommu_group_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void iommu_group_put(struct iommu_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816e7148)
Location: drivers/iommu/iommu.c:898
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_group_get_from_dev
  - drivers/vfio/vfio.c:vfio_group_put
  - drivers/vfio/vfio.c:vfio_iommu_group_put
  - drivers/vfio/vfio.c:vfio_iommu_group_put
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs
```
**Symbols:**

```
ffffffff816e6c90-ffffffff816e6caa: iommu_group_put (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
