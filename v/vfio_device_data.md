# Function: <code>vfio_device_data</code>

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
void *vfio_device_data(struct vfio_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817cfee0)
Location: drivers/vfio/vfio.c:896
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_get_unused_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_aer_err_detected
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff817cfee0-ffffffff817cfeef: vfio_device_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *vfio_device_data(struct vfio_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8189a940)
Location: drivers/vfio/vfio.c:911
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_try_bus_reset
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_try_bus_reset
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_try_zap_and_vma_lock_cb
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_get_unused_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_sriov_configure
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_aer_err_detected
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
**Symbols:**

```
ffffffff8189a940-ffffffff8189a94f: vfio_device_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *vfio_device_data(struct vfio_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff818a94f0)
Location: drivers/vfio/vfio.c:912
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_try_bus_reset
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_try_bus_reset
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_try_zap_and_vma_lock_cb
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_get_unused_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_sriov_configure
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_aer_err_detected
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
**Symbols:**

```
ffffffff818a94f0-ffffffff818a94ff: vfio_device_data (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
void *vfio_device_data(struct vfio_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (c000000000aad870)
Location: drivers/vfio/vfio.c:896
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_get_unused_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_aer_err_detected
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
c000000000aad870-c000000000aad880: vfio_device_data (STB_GLOBAL)
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
void *vfio_device_data(struct vfio_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff81779f90)
Location: drivers/vfio/vfio.c:896
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_get_unused_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_aer_err_detected
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff81779f90-ffffffff81779f9f: vfio_device_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *vfio_device_data(struct vfio_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817c4d60)
Location: drivers/vfio/vfio.c:896
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_get_unused_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_aer_err_detected
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff817c4d60-ffffffff817c4d6f: vfio_device_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *vfio_device_data(struct vfio_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817df000)
Location: drivers/vfio/vfio.c:896
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_get_unused_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_aer_err_detected
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff817df000-ffffffff817df00f: vfio_device_data (STB_GLOBAL)
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
