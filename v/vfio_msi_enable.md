# Function: <code>vfio_msi_enable</code>

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
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817d8e91)
Location: drivers/vfio/pci/vfio_pci_intrs.c:247
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfio_msi_enable(struct vfio_pci_device *vdev, int nvec, bool msix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff818a6730)
Location: drivers/vfio/pci/vfio_pci_intrs.c:247
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
```
**Symbols:**

```
ffffffff818a6730-ffffffff818a6888: vfio_msi_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfio_msi_enable(struct vfio_pci_device *vdev, int nvec, bool msix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff818b5620)
Location: drivers/vfio/pci/vfio_pci_intrs.c:247
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
```
**Symbols:**

```
ffffffff818b5620-ffffffff818b5778: vfio_msi_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfio_msi_enable(struct vfio_pci_device *vdev, int nvec, bool msix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff81898ac0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:247
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
```
**Symbols:**

```
ffffffff81898ac0-ffffffff81898c19: vfio_msi_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vfio_msi_enable(struct vfio_pci_core_device *vdev, int nvec, bool msix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff8192c4d0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:247
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
```
**Symbols:**

```
ffffffff8192c4d0-ffffffff8192c629: vfio_msi_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vfio_msi_enable(struct vfio_pci_core_device *vdev, int nvec, bool msix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff81a82b00)
Location: drivers/vfio/pci/vfio_pci_intrs.c:247
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
```
**Symbols:**

```
ffffffff81a82b00-ffffffff81a82c70: vfio_msi_enable (STB_LOCAL)
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
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (c000000000ab8e64)
Location: drivers/vfio/pci/vfio_pci_intrs.c:247
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
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
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff81782f41)
Location: drivers/vfio/pci/vfio_pci_intrs.c:247
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817cdd11)
Location: drivers/vfio/pci/vfio_pci_intrs.c:247
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817e7fb1)
Location: drivers/vfio/pci/vfio_pci_intrs.c:247
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct vfio_pci_device *vdev</code> ➡️ <code>struct vfio_pci_core_device *vdev</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
