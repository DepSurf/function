# Function: <code>vfio_iommu_group_put</code>

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
void vfio_iommu_group_put(struct iommu_group *group, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817d01e0)
Location: drivers/vfio/vfio.c:161
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
**Symbols:**

```
ffffffff817d01e0-ffffffff817d0224: vfio_iommu_group_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void vfio_iommu_group_put(struct iommu_group *group, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8189ad30)
Location: drivers/vfio/vfio.c:162
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_remove
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
**Symbols:**

```
ffffffff8189ad30-ffffffff8189ad74: vfio_iommu_group_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void vfio_iommu_group_put(struct iommu_group *group, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff818a9940)
Location: drivers/vfio/vfio.c:162
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_remove
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
**Symbols:**

```
ffffffff818a9940-ffffffff818a9984: vfio_iommu_group_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void vfio_iommu_group_put(struct iommu_group *group, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8188cd10)
Location: drivers/vfio/vfio.c:152
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_remove
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
**Symbols:**

```
ffffffff8188cd10-ffffffff8188cd54: vfio_iommu_group_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void vfio_iommu_group_put(struct iommu_group *group, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff81920290)
Location: drivers/vfio/vfio.c:225
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_unregister_device
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_register_device
```
**Symbols:**

```
ffffffff81920290-ffffffff819202d4: vfio_iommu_group_put (STB_GLOBAL)
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
void vfio_iommu_group_put(struct iommu_group *group, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (c000000000aade00)
Location: drivers/vfio/vfio.c:161
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
**Symbols:**

```
c000000000aade00-c000000000aadea0: vfio_iommu_group_put (STB_GLOBAL)
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
void vfio_iommu_group_put(struct iommu_group *group, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8177a290)
Location: drivers/vfio/vfio.c:161
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
**Symbols:**

```
ffffffff8177a290-ffffffff8177a2d4: vfio_iommu_group_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void vfio_iommu_group_put(struct iommu_group *group, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817c5060)
Location: drivers/vfio/vfio.c:161
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
**Symbols:**

```
ffffffff817c5060-ffffffff817c50a4: vfio_iommu_group_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void vfio_iommu_group_put(struct iommu_group *group, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817df300)
Location: drivers/vfio/vfio.c:161
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
**Symbols:**

```
ffffffff817df300-ffffffff817df344: vfio_iommu_group_put (STB_GLOBAL)
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
