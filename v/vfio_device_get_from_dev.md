# Function: <code>vfio_device_get_from_dev</code>

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
struct vfio_device *vfio_device_get_from_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817d15a0)
Location: drivers/vfio/vfio.c:859
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_get_unused_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_aer_err_detected
```
**Symbols:**

```
ffffffff817d15a0-ffffffff817d15e8: vfio_device_get_from_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct vfio_device *vfio_device_get_from_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8189c4e0)
Location: drivers/vfio/vfio.c:862
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_try_zap_and_vma_lock_cb
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_get_unused_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_sriov_configure
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_aer_err_detected
```
**Symbols:**

```
ffffffff8189c4e0-ffffffff8189c559: vfio_device_get_from_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct vfio_device *vfio_device_get_from_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff818ab0f0)
Location: drivers/vfio/vfio.c:863
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_try_zap_and_vma_lock_cb
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_get_unused_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_sriov_configure
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_aer_err_detected
```
**Symbols:**

```
ffffffff818ab0f0-ffffffff818ab169: vfio_device_get_from_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct vfio_device *vfio_device_get_from_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8188e390)
Location: drivers/vfio/vfio.c:808
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_try_zap_and_vma_lock_cb
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_get_unused_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_sriov_configure
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_aer_err_detected
```
**Symbols:**

```
ffffffff8188e390-ffffffff8188e409: vfio_device_get_from_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct vfio_device *vfio_device_get_from_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff819219d0)
Location: drivers/vfio/vfio.c:894
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_sriov_configure
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_aer_err_detected
  - drivers/vfio/pci/vfio_pci_core.c:get_pf_vdev
```
**Symbols:**

```
ffffffff819219d0-ffffffff81921a49: vfio_device_get_from_dev (STB_GLOBAL)
```
</details>
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
struct vfio_device *vfio_device_get_from_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (c000000000aae5a0)
Location: drivers/vfio/vfio.c:859
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_get_unused_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_aer_err_detected
```
**Symbols:**

```
c000000000aae5a0-c000000000aae630: vfio_device_get_from_dev (STB_GLOBAL)
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
struct vfio_device *vfio_device_get_from_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8177b650)
Location: drivers/vfio/vfio.c:859
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_get_unused_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_aer_err_detected
```
**Symbols:**

```
ffffffff8177b650-ffffffff8177b698: vfio_device_get_from_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct vfio_device *vfio_device_get_from_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817c6420)
Location: drivers/vfio/vfio.c:859
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_get_unused_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_aer_err_detected
```
**Symbols:**

```
ffffffff817c6420-ffffffff817c6468: vfio_device_get_from_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct vfio_device *vfio_device_get_from_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817e06c0)
Location: drivers/vfio/vfio.c:859
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_get_unused_devs
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_aer_err_detected
```
**Symbols:**

```
ffffffff817e06c0-ffffffff817e0708: vfio_device_get_from_dev (STB_GLOBAL)
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
