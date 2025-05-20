# Function: <code>iommu_group_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *iommu_group_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8152a180)
Location: drivers/iommu/iommu.c:551
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:get_pci_alias_or_group
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_bus_notifier
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
```
**Symbols:**

```
ffffffff8152a180-ffffffff8152a1a5: iommu_group_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *iommu_group_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8157d5bc)
Location: drivers/iommu/iommu.c:542
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_bus_notifier
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_or_group
```
**Symbols:**

```
ffffffff8157d540-ffffffff8157d565: iommu_group_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *iommu_group_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff815a9b2c)
Location: drivers/iommu/iommu.c:680
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_bus_notifier
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_or_group
```
**Symbols:**

```
ffffffff815a9ab0-ffffffff815a9ad5: iommu_group_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *iommu_group_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff815bf86c)
Location: drivers/iommu/iommu.c:724
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_or_group
```
**Symbols:**

```
ffffffff815bf7f0-ffffffff815bf815: iommu_group_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *iommu_group_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81625ccc)
Location: drivers/iommu/iommu.c:726
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_or_group
```
**Symbols:**

```
ffffffff81625c50-ffffffff81625c75: iommu_group_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *iommu_group_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81660be5)
Location: drivers/iommu/iommu.c:727
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_bus_notifier
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_or_group
```
**Symbols:**

```
ffffffff81660b70-ffffffff81660b95: iommu_group_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *iommu_group_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167f295)
Location: drivers/iommu/iommu.c:793
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
  - drivers/iommu/iommu.c:fsl_mc_device_group
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_or_group
```
**Symbols:**

```
ffffffff8167f220-ffffffff8167f245: iommu_group_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *iommu_group_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816b626d)
Location: drivers/iommu/iommu.c:811
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
  - drivers/iommu/iommu.c:fsl_mc_device_group
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_or_group
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff816b60b0-ffffffff816b60d8: iommu_group_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *iommu_group_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816d8f6d)
Location: drivers/iommu/iommu.c:867
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
  - drivers/iommu/iommu.c:fsl_mc_device_group
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_or_group
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_group_get_from_dev
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs
```
**Symbols:**

```
ffffffff816d8db0-ffffffff816d8dd8: iommu_group_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *iommu_group_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8178d56d)
Location: drivers/iommu/iommu.c:969
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_bus_notifier
  - drivers/iommu/iommu.c:fsl_mc_device_group
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_or_group
  - drivers/iommu/iommu.c:get_pci_alias_group
  - drivers/iommu/iommu.c:iommu_page_response
  - drivers/iommu/iommu.c:iommu_probe_device
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
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs
```
**Symbols:**

```
ffffffff8178d3a0-ffffffff8178d3ca: iommu_group_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *iommu_group_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff817b907d)
Location: drivers/iommu/iommu.c:990
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_bus_notifier
  - drivers/iommu/iommu.c:fsl_mc_device_group
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_or_group
  - drivers/iommu/iommu.c:get_pci_alias_group
  - drivers/iommu/iommu.c:iommu_page_response
  - drivers/iommu/iommu.c:iommu_probe_device
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
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs
```
**Symbols:**

```
ffffffff817b8eb0-ffffffff817b8eda: iommu_group_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *iommu_group_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8179c28d)
Location: drivers/iommu/iommu.c:1019
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_bus_notifier
  - drivers/iommu/iommu.c:fsl_mc_device_group
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_or_group
  - drivers/iommu/iommu.c:get_pci_alias_group
  - drivers/iommu/iommu.c:iommu_page_response
  - drivers/iommu/iommu.c:iommu_probe_device
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
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs
```
**Symbols:**

```
ffffffff8179c0c0-ffffffff8179c0ea: iommu_group_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *iommu_group_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81824f7d)
Location: drivers/iommu/iommu.c:1034
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_bus_notifier
  - drivers/iommu/iommu.c:fsl_mc_device_group
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_or_group
  - drivers/iommu/iommu.c:get_pci_alias_group
  - drivers/iommu/iommu.c:iommu_page_response
  - drivers/iommu/iommu.c:iommu_probe_device
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
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_fill_devs
```
**Symbols:**

```
ffffffff81824db0-ffffffff81824dda: iommu_group_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *iommu_group_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81968a55)
Location: drivers/iommu/iommu.c:1038
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_device_unuse_default_domain
  - drivers/iommu/iommu.c:iommu_device_use_default_domain
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:probe_iommu_group
  - drivers/iommu/iommu.c:fsl_mc_device_group
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_or_group
  - drivers/iommu/iommu.c:get_pci_alias_group
  - drivers/iommu/iommu.c:iommu_probe_device
  - drivers/iommu/iommu.c:__iommu_probe_device
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/vfio/vfio.c:vfio_register_group_dev
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_fill_devs
```
**Symbols:**

```
ffffffff81964dc0-ffffffff81964dee: iommu_group_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *iommu_group_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81acf035)
Location: drivers/iommu/iommu.c:1159
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev_pasid
  - drivers/iommu/iommu.c:iommu_detach_device_pasid
  - drivers/iommu/iommu.c:iommu_attach_device_pasid
  - drivers/iommu/iommu.c:iommu_device_release_dma_owner
  - drivers/iommu/iommu.c:iommu_device_claim_dma_owner
  - drivers/iommu/iommu.c:iommu_device_unuse_default_domain
  - drivers/iommu/iommu.c:iommu_device_use_default_domain
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:probe_iommu_group
  - drivers/iommu/iommu.c:fsl_mc_device_group
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_or_group
  - drivers/iommu/iommu.c:get_pci_alias_group
  - drivers/iommu/iommu.c:__iommu_probe_device
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81ace140-ffffffff81ace16e: iommu_group_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *iommu_group_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b1dba5)
Location: drivers/iommu/iommu.c:1150
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev_pasid
  - drivers/iommu/iommu.c:iommu_detach_device_pasid
  - drivers/iommu/iommu.c:iommu_attach_device_pasid
  - drivers/iommu/iommu.c:iommu_device_release_dma_owner
  - drivers/iommu/iommu.c:iommu_device_claim_dma_owner
  - drivers/iommu/iommu.c:iommu_device_unuse_default_domain
  - drivers/iommu/iommu.c:iommu_device_use_default_domain
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:probe_iommu_group
  - drivers/iommu/iommu.c:fsl_mc_device_group
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_or_group
  - drivers/iommu/iommu.c:get_pci_alias_group
  - drivers/iommu/iommu.c:__iommu_probe_device
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81b1cd10-ffffffff81b1cd3e: iommu_group_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *iommu_group_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b732e7)
Location: drivers/iommu/iommu.c:1294
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:fsl_mc_device_group
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_or_group
  - drivers/iommu/iommu.c:get_pci_alias_group
```
**Symbols:**

```
ffffffff81b73230-ffffffff81b7325e: iommu_group_get (STB_GLOBAL)
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
struct iommu_group *iommu_group_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffff8000108c4740)
Location: drivers/iommu/iommu.c:867
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
  - drivers/iommu/iommu.c:fsl_mc_device_group
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_or_group
```
**Symbols:**

```
ffff8000108c4548-ffff8000108c4580: iommu_group_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *iommu_group_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c09bbbd8)
Location: drivers/iommu/iommu.c:867
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
  - drivers/iommu/iommu.c:fsl_mc_device_group
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_or_group
Direct callers:
  - drivers/iommu/exynos-iommu.c:exynos_iommu_remove_device
```
**Symbols:**

```
c09bba28-c09bba58: iommu_group_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *iommu_group_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c00000000096a57c)
Location: drivers/iommu/iommu.c:867
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
  - drivers/iommu/iommu.c:fsl_mc_device_group
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_or_group
Direct callers:
  - arch/powerpc/platforms/powernv/npu-dma.c:pnv_npu_compound_attach
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_group_get_from_dev
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs
```
**Symbols:**

```
c00000000096a280-c00000000096a2d0: iommu_group_get (STB_GLOBAL)
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
struct iommu_group *iommu_group_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8169e9bd)
Location: drivers/iommu/iommu.c:867
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
  - drivers/iommu/iommu.c:fsl_mc_device_group
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_or_group
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff8169e800-ffffffff8169e828: iommu_group_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *iommu_group_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167c3ad)
Location: drivers/iommu/iommu.c:867
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
  - drivers/iommu/iommu.c:fsl_mc_device_group
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_or_group
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_group_get_from_dev
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs
```
**Symbols:**

```
ffffffff8167c1f0-ffffffff8167c218: iommu_group_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *iommu_group_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816ccc2d)
Location: drivers/iommu/iommu.c:867
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
  - drivers/iommu/iommu.c:fsl_mc_device_group
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_or_group
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_group_get_from_dev
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs
```
**Symbols:**

```
ffffffff816cca70-ffffffff816cca98: iommu_group_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *iommu_group_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816e710d)
Location: drivers/iommu/iommu.c:867
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_sva_unbind_device
  - drivers/iommu/iommu.c:iommu_sva_bind_device
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_get_domain_for_dev
  - drivers/iommu/iommu.c:iommu_detach_device
  - drivers/iommu/iommu.c:iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_get_for_dev
  - drivers/iommu/iommu.c:fsl_mc_device_group
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_or_group
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_group_get_from_dev
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs
```
**Symbols:**

```
ffffffff816e6f50-ffffffff816e6f78: iommu_group_get (STB_GLOBAL)
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
