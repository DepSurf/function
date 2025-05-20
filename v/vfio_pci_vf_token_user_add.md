# Function: <code>vfio_pci_vf_token_user_add</code>

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
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff818a3640)
Location: drivers/vfio/pci/vfio_pci.c:498
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_open
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_release
```
**Symbols:**

```
ffffffff818a3640-ffffffff818a36c7: vfio_pci_vf_token_user_add.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b22f0)
Location: drivers/vfio/pci/vfio_pci.c:540
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_open
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_release
```
**Symbols:**

```
ffffffff818b22f0-ffffffff818b2377: vfio_pci_vf_token_user_add.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff818957a0)
Location: drivers/vfio/pci/vfio_pci.c:521
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_open
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_release
```
**Symbols:**

```
ffffffff818957a0-ffffffff818957f7: vfio_pci_vf_token_user_add.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void vfio_pci_vf_token_user_add(struct vfio_pci_core_device *vdev, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff819287a0)
Location: drivers/vfio/pci/vfio_pci_core.c:433
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_finish_enable
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_close_device
```
**Symbols:**

```
ffffffff819287a0-ffffffff819287f7: vfio_pci_vf_token_user_add (STB_LOCAL)
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
</ul>
