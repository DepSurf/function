# Function: <code>vfio_pci_reflck_attach</code>

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
In drivers/vfio/pci/vfio_pci.c (ffffffff817d7636)
Location: drivers/vfio/pci/vfio_pci.c:1488
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfio_pci_reflck_attach(struct vfio_pci_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff818a3c10)
Location: drivers/vfio/pci/vfio_pci.c:2116
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
**Symbols:**

```
ffffffff818a3c10-ffffffff818a3d24: vfio_pci_reflck_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfio_pci_reflck_attach(struct vfio_pci_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b2be0)
Location: drivers/vfio/pci/vfio_pci.c:2194
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
**Symbols:**

```
ffffffff818b2be0-ffffffff818b2cf4: vfio_pci_reflck_attach (STB_LOCAL)
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
In drivers/vfio/pci/vfio_pci.c (ffffffff8189725e)
Location: drivers/vfio/pci/vfio_pci.c:2213
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
</details>
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
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (c000000000ab6b28)
Location: drivers/vfio/pci/vfio_pci.c:1488
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
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
In drivers/vfio/pci/vfio_pci.c (ffffffff817816e6)
Location: drivers/vfio/pci/vfio_pci.c:1488
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
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
In drivers/vfio/pci/vfio_pci.c (ffffffff817cc4b6)
Location: drivers/vfio/pci/vfio_pci.c:1488
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
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
In drivers/vfio/pci/vfio_pci.c (ffffffff817e6756)
Location: drivers/vfio/pci/vfio_pci.c:1488
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
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
