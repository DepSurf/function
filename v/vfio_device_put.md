# Function: <code>vfio_device_put</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void vfio_device_put(struct vfio_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817d0560)
Location: drivers/vfio/vfio.c:581
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_device_fops_release
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
  - drivers/vfio/vfio.c:vfio_dev_viable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_get_unused_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_aer_err_detected
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_aer_err_detected
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff817d0560-ffffffff817d05f3: vfio_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void vfio_device_put(struct vfio_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8189ba40)
Location: drivers/vfio/vfio.c:584
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_device_fops_release
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_dev_viable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_try_bus_reset
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_try_zap_and_vma_lock_cb
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_get_unused_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_sriov_configure
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_sriov_configure
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_sriov_configure
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_aer_err_detected
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_aer_err_detected
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_vf_token
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_vf_token
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
**Symbols:**

```
ffffffff8189ba40-ffffffff8189ba8a: vfio_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void vfio_device_put(struct vfio_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff818aa650)
Location: drivers/vfio/vfio.c:584
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_device_fops_release
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_dev_viable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_try_bus_reset
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_try_zap_and_vma_lock_cb
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_get_unused_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_sriov_configure
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_sriov_configure
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_sriov_configure
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_aer_err_detected
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_aer_err_detected
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_vf_token
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_vf_token
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
**Symbols:**

```
ffffffff818aa650-ffffffff818aa69a: vfio_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void vfio_device_put(struct vfio_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8188d7d0)
Location: drivers/vfio/vfio.c:526
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_device_fops_release
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
  - drivers/vfio/vfio.c:vfio_unregister_group_dev
  - drivers/vfio/vfio.c:vfio_register_group_dev
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
  - drivers/vfio/vfio.c:vfio_dev_viable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_try_bus_reset
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_try_zap_and_vma_lock_cb
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_get_unused_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_sriov_configure
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_sriov_configure
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_aer_err_detected
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_vf_token
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_vf_token
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
**Symbols:**

```
ffffffff8188d7d0-ffffffff8188d80c: vfio_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void vfio_device_put(struct vfio_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff81920d40)
Location: drivers/vfio/vfio.c:599
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_device_fops_release
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
  - drivers/vfio/vfio.c:vfio_unregister_group_dev
  - drivers/vfio/vfio.c:vfio_register_group_dev
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
  - drivers/vfio/vfio.c:vfio_dev_viable
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_sriov_configure
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_sriov_configure
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_aer_err_detected
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_validate_vf_token
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_validate_vf_token
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_vf_token_user_add
  - drivers/vfio/pci/vfio_pci_core.c:get_pf_vdev
```
**Symbols:**

```
ffffffff81920d40-ffffffff81920d7c: vfio_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void vfio_device_put(struct vfio_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff81a77870)
Location: drivers/vfio/vfio.c:451
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_device_fops_release
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_unregister_group_dev
  - drivers/vfio/vfio.c:__vfio_register_dev
```
**Symbols:**

```
ffffffff81a77870-ffffffff81a778d0: vfio_device_put (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void vfio_device_put(struct vfio_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (c000000000aae630)
Location: drivers/vfio/vfio.c:581
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_device_fops_release
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
  - drivers/vfio/vfio.c:vfio_dev_viable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_get_unused_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_aer_err_detected
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_aer_err_detected
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
c000000000aae630-c000000000aae710: vfio_device_put (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void vfio_device_put(struct vfio_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8177a610)
Location: drivers/vfio/vfio.c:581
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_device_fops_release
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
  - drivers/vfio/vfio.c:vfio_dev_viable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_get_unused_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_aer_err_detected
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_aer_err_detected
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff8177a610-ffffffff8177a6a3: vfio_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void vfio_device_put(struct vfio_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817c53e0)
Location: drivers/vfio/vfio.c:581
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_device_fops_release
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
  - drivers/vfio/vfio.c:vfio_dev_viable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_get_unused_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_aer_err_detected
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_aer_err_detected
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff817c53e0-ffffffff817c5473: vfio_device_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void vfio_device_put(struct vfio_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817df680)
Location: drivers/vfio/vfio.c:581
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_device_fops_release
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
  - drivers/vfio/vfio.c:vfio_dev_viable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_get_unused_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_aer_err_detected
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_aer_err_detected
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff817df680-ffffffff817df713: vfio_device_put (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
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
