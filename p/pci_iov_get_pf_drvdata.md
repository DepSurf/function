# Function: <code>pci_iov_get_pf_drvdata</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void *pci_iov_get_pf_drvdata(struct pci_dev *dev, struct pci_driver *pf_driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff817f1400)
Location: drivers/pci/iov.c:66
Inline: True
```
**Symbols:**

```
ffffffff817f1400-ffffffff817f1448: pci_iov_get_pf_drvdata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void *pci_iov_get_pf_drvdata(struct pci_dev *dev, struct pci_driver *pf_driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff81919920)
Location: drivers/pci/iov.c:66
Inline: True
```
**Symbols:**

```
ffffffff81919920-ffffffff81919968: pci_iov_get_pf_drvdata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void *pci_iov_get_pf_drvdata(struct pci_dev *dev, struct pci_driver *pf_driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff8195cf40)
Location: drivers/pci/iov.c:66
Inline: True
```
**Symbols:**

```
ffffffff8195cf40-ffffffff8195cf88: pci_iov_get_pf_drvdata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void *pci_iov_get_pf_drvdata(struct pci_dev *dev, struct pci_driver *pf_driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff819a6560)
Location: drivers/pci/iov.c:65
Inline: True
Direct callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_vf_get_pf_dev
```
**Symbols:**

```
ffffffff819a6560-ffffffff819a65a8: pci_iov_get_pf_drvdata (STB_GLOBAL)
```
</details>
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
