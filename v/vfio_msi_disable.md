# Function: <code>vfio_msi_disable</code>

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
void vfio_msi_disable(struct vfio_pci_device *vdev, bool msix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817d8990)
Location: drivers/vfio/pci/vfio_pci_intrs.c:375
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
```
**Symbols:**

```
ffffffff817d8990-ffffffff817d8a59: vfio_msi_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void vfio_msi_disable(struct vfio_pci_device *vdev, bool msix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff818a64e0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:386
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
```
**Symbols:**

```
ffffffff818a64e0-ffffffff818a65bb: vfio_msi_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void vfio_msi_disable(struct vfio_pci_device *vdev, bool msix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff818b53d0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:388
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
```
**Symbols:**

```
ffffffff818b53d0-ffffffff818b54ab: vfio_msi_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void vfio_msi_disable(struct vfio_pci_device *vdev, bool msix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff81898870)
Location: drivers/vfio/pci/vfio_pci_intrs.c:388
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
```
**Symbols:**

```
ffffffff81898870-ffffffff8189894c: vfio_msi_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void vfio_msi_disable(struct vfio_pci_core_device *vdev, bool msix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:388
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
```
**Symbols:**

```
ffffffff8192c270-ffffffff8192c358: vfio_msi_disable (STB_LOCAL)
ffffffff81d12344-ffffffff81d12358: vfio_msi_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void vfio_msi_disable(struct vfio_pci_core_device *vdev, bool msix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:388
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
```
**Symbols:**

```
ffffffff81a82a00-ffffffff81a82afc: vfio_msi_disable (STB_LOCAL)
ffffffff81edd07a-ffffffff81edd08e: vfio_msi_disable.cold (STB_LOCAL)
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
void vfio_msi_disable(struct vfio_pci_device *vdev, bool msix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (c000000000ab8650)
Location: drivers/vfio/pci/vfio_pci_intrs.c:375
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
```
**Symbols:**

```
c000000000ab8650-c000000000ab8794: vfio_msi_disable (STB_LOCAL)
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
void vfio_msi_disable(struct vfio_pci_device *vdev, bool msix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff81782a40)
Location: drivers/vfio/pci/vfio_pci_intrs.c:375
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
```
**Symbols:**

```
ffffffff81782a40-ffffffff81782b09: vfio_msi_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void vfio_msi_disable(struct vfio_pci_device *vdev, bool msix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817cd810)
Location: drivers/vfio/pci/vfio_pci_intrs.c:375
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
```
**Symbols:**

```
ffffffff817cd810-ffffffff817cd8d9: vfio_msi_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void vfio_msi_disable(struct vfio_pci_device *vdev, bool msix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817e7ab0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:375
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger
```
**Symbols:**

```
ffffffff817e7ab0-ffffffff817e7b79: vfio_msi_disable (STB_LOCAL)
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
