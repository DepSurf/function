# Function: <code>vfio_pci_disable</code>

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
void vfio_pci_disable(struct vfio_pci_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (0)
Location: drivers/vfio/pci/vfio_pci.c:368
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_release
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
```
**Symbols:**

```
ffffffff817d7850-ffffffff817d7cd2: vfio_pci_disable (STB_LOCAL)
ffffffff817d82d7-ffffffff817d830d: vfio_pci_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void vfio_pci_disable(struct vfio_pci_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (0)
Location: drivers/vfio/pci/vfio_pci.c:377
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_release
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
```
**Symbols:**

```
ffffffff818a53a0-ffffffff818a5646: vfio_pci_disable (STB_LOCAL)
ffffffff818a5dfd-ffffffff818a5e33: vfio_pci_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void vfio_pci_disable(struct vfio_pci_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (0)
Location: drivers/vfio/pci/vfio_pci.c:419
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_release
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
```
**Symbols:**

```
ffffffff818b44e0-ffffffff818b4786: vfio_pci_disable (STB_LOCAL)
ffffffff81c1a1eb-ffffffff81c1a221: vfio_pci_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void vfio_pci_disable(struct vfio_pci_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (0)
Location: drivers/vfio/pci/vfio_pci.c:400
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_release
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
```
**Symbols:**

```
ffffffff81897840-ffffffff81897ae7: vfio_pci_disable (STB_LOCAL)
ffffffff81c0c07f-ffffffff81c0c0b5: vfio_pci_disable.cold (STB_LOCAL)
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
void vfio_pci_disable(struct vfio_pci_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (c000000000ab6e30)
Location: drivers/vfio/pci/vfio_pci.c:368
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_release
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
```
**Symbols:**

```
c000000000ab6e30-c000000000ab7470: vfio_pci_disable (STB_LOCAL)
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
void vfio_pci_disable(struct vfio_pci_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (0)
Location: drivers/vfio/pci/vfio_pci.c:368
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_release
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
```
**Symbols:**

```
ffffffff81781900-ffffffff81781d82: vfio_pci_disable (STB_LOCAL)
ffffffff81782387-ffffffff817823bd: vfio_pci_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void vfio_pci_disable(struct vfio_pci_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (0)
Location: drivers/vfio/pci/vfio_pci.c:368
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_release
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
```
**Symbols:**

```
ffffffff817cc6d0-ffffffff817ccb52: vfio_pci_disable (STB_LOCAL)
ffffffff817cd157-ffffffff817cd18d: vfio_pci_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void vfio_pci_disable(struct vfio_pci_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (0)
Location: drivers/vfio/pci/vfio_pci.c:368
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_release
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
```
**Symbols:**

```
ffffffff817e6970-ffffffff817e6df2: vfio_pci_disable (STB_LOCAL)
ffffffff817e73f7-ffffffff817e742d: vfio_pci_disable.cold (STB_LOCAL)
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
