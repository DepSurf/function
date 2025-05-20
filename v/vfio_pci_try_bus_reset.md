# Function: <code>vfio_pci_try_bus_reset</code>

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
In drivers/vfio/pci/vfio_pci.c (ffffffff817d7a80)
Location: drivers/vfio/pci/vfio_pci.c:1571
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void vfio_pci_try_bus_reset(struct vfio_pci_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff818a51a0)
Location: drivers/vfio/pci/vfio_pci.c:2226
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff818a51a0-ffffffff818a539a: vfio_pci_try_bus_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void vfio_pci_try_bus_reset(struct vfio_pci_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b42e0)
Location: drivers/vfio/pci/vfio_pci.c:2304
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff818b42e0-ffffffff818b44da: vfio_pci_try_bus_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void vfio_pci_try_bus_reset(struct vfio_pci_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff81897620)
Location: drivers/vfio/pci/vfio_pci.c:2323
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff81897620-ffffffff81897833: vfio_pci_try_bus_reset (STB_LOCAL)
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
In drivers/vfio/pci/vfio_pci.c (c000000000ab70ec)
Location: drivers/vfio/pci/vfio_pci.c:1571
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
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
In drivers/vfio/pci/vfio_pci.c (ffffffff81781b30)
Location: drivers/vfio/pci/vfio_pci.c:1571
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
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
In drivers/vfio/pci/vfio_pci.c (ffffffff817cc900)
Location: drivers/vfio/pci/vfio_pci.c:1571
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
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
In drivers/vfio/pci/vfio_pci.c (ffffffff817e6ba0)
Location: drivers/vfio/pci/vfio_pci.c:1571
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
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
</ul>
