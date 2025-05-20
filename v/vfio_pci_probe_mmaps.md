# Function: <code>vfio_pci_probe_mmaps</code>

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
In drivers/vfio/pci/vfio_pci.c (ffffffff817d7e9b)
Location: drivers/vfio/pci/vfio_pci.c:110
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void vfio_pci_probe_mmaps(struct vfio_pci_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff818a36d0)
Location: drivers/vfio/pci/vfio_pci.c:116
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
```
**Symbols:**

```
ffffffff818a36d0-ffffffff818a3841: vfio_pci_probe_mmaps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void vfio_pci_probe_mmaps(struct vfio_pci_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b2380)
Location: drivers/vfio/pci/vfio_pci.c:158
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
```
**Symbols:**

```
ffffffff818b2380-ffffffff818b24d2: vfio_pci_probe_mmaps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (0)
Location: drivers/vfio/pci/vfio_pci.c:158
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff819294ee)
Location: drivers/vfio/pci/vfio_pci_core.c:86
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_finish_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff81a7f520)
Location: drivers/vfio/pci/vfio_pci_core.c:90
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_finish_enable
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
In drivers/vfio/pci/vfio_pci.c (c000000000ab7710)
Location: drivers/vfio/pci/vfio_pci.c:110
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
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
In drivers/vfio/pci/vfio_pci.c (ffffffff81781f4b)
Location: drivers/vfio/pci/vfio_pci.c:110
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
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
In drivers/vfio/pci/vfio_pci.c (ffffffff817ccd1b)
Location: drivers/vfio/pci/vfio_pci.c:110
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
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
In drivers/vfio/pci/vfio_pci.c (ffffffff817e6fbb)
Location: drivers/vfio/pci/vfio_pci.c:110
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
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
</ul>
