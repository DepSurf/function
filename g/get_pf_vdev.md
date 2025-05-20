# Function: <code>get_pf_vdev</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff818a35e0)
Location: drivers/vfio/pci/vfio_pci.c:478
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_vf_token
```
**Symbols:**

```
ffffffff818a35e0-ffffffff818a3640: get_pf_vdev.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b2290)
Location: drivers/vfio/pci/vfio_pci.c:520
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_vf_token
```
**Symbols:**

```
ffffffff818b2290-ffffffff818b22f0: get_pf_vdev.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff81895740)
Location: drivers/vfio/pci/vfio_pci.c:501
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_vf_token
```
**Symbols:**

```
ffffffff81895740-ffffffff8189579e: get_pf_vdev.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct vfio_pci_core_device *get_pf_vdev(struct vfio_pci_core_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff81928720)
Location: drivers/vfio/pci/vfio_pci_core.c:413
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_validate_vf_token
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_vf_token_user_add
```
**Symbols:**

```
ffffffff81928720-ffffffff81928791: get_pf_vdev (STB_LOCAL)
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
In <code>ppc64el</code>: Absent ⚠️
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
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
