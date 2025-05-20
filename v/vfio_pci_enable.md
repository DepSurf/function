# Function: <code>vfio_pci_enable</code>

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
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int vfio_pci_enable(struct vfio_pci_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (0)
Location: drivers/vfio/pci/vfio_pci.c:261
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_open
```
**Symbols:**

```
ffffffff817d7d30-ffffffff817d80c6: vfio_pci_enable (STB_LOCAL)
ffffffff817d830d-ffffffff817d837b: vfio_pci_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int vfio_pci_enable(struct vfio_pci_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (0)
Location: drivers/vfio/pci/vfio_pci.c:270
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_open
```
**Symbols:**

```
ffffffff818a5710-ffffffff818a59a2: vfio_pci_enable (STB_LOCAL)
ffffffff818a5e33-ffffffff818a5e86: vfio_pci_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int vfio_pci_enable(struct vfio_pci_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (0)
Location: drivers/vfio/pci/vfio_pci.c:312
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_open
```
**Symbols:**

```
ffffffff818b4840-ffffffff818b4ad8: vfio_pci_enable (STB_LOCAL)
ffffffff81c1a221-ffffffff81c1a274: vfio_pci_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int vfio_pci_enable(struct vfio_pci_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (0)
Location: drivers/vfio/pci/vfio_pci.c:312
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_open
```
**Symbols:**

```
ffffffff81897ba0-ffffffff81897f61: vfio_pci_enable (STB_LOCAL)
ffffffff81c0c0b5-ffffffff81c0c107: vfio_pci_enable.cold (STB_LOCAL)
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
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vfio_pci_enable(struct vfio_pci_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (c000000000ab7540)
Location: drivers/vfio/pci/vfio_pci.c:261
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_open
```
**Symbols:**

```
c000000000ab7540-c000000000ab7aac: vfio_pci_enable (STB_LOCAL)
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
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int vfio_pci_enable(struct vfio_pci_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (0)
Location: drivers/vfio/pci/vfio_pci.c:261
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_open
```
**Symbols:**

```
ffffffff81781de0-ffffffff81782176: vfio_pci_enable (STB_LOCAL)
ffffffff817823bd-ffffffff8178242b: vfio_pci_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int vfio_pci_enable(struct vfio_pci_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (0)
Location: drivers/vfio/pci/vfio_pci.c:261
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_open
```
**Symbols:**

```
ffffffff817ccbb0-ffffffff817ccf46: vfio_pci_enable (STB_LOCAL)
ffffffff817cd18d-ffffffff817cd1fb: vfio_pci_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int vfio_pci_enable(struct vfio_pci_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (0)
Location: drivers/vfio/pci/vfio_pci.c:261
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_open
```
**Symbols:**

```
ffffffff817e6e50-ffffffff817e71e6: vfio_pci_enable (STB_LOCAL)
ffffffff817e742d-ffffffff817e749b: vfio_pci_enable.cold (STB_LOCAL)
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
