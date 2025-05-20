# Function: <code>vfio_pci_core_sriov_configure</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vfio_pci_core_sriov_configure(struct pci_dev *pdev, int nr_virtfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff81928ed0)
Location: drivers/vfio/pci/vfio_pci_core.c:1927
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_sriov_configure
```
**Symbols:**

```
ffffffff81928ed0-ffffffff81928f46: vfio_pci_core_sriov_configure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vfio_pci_core_sriov_configure(struct vfio_pci_core_device *vdev, int nr_virtfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff81a80f40)
Location: drivers/vfio/pci/vfio_pci_core.c:1973
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_unregister_device
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_sriov_configure
```
**Symbols:**

```
ffffffff81a80f40-ffffffff81a810d8: vfio_pci_core_sriov_configure (STB_GLOBAL)
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
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vfio_pci_core_device *vdev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct pci_dev *pdev</code>
</li>
</ul>
</details>
</li>
</ul>
