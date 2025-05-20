# Function: <code>vfio_msi_cap_len</code>

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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817db2ae)
Location: drivers/vfio/pci/vfio_pci_config.c:1155
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfio_msi_cap_len(struct vfio_pci_device *vdev, u8 pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff818a9190)
Location: drivers/vfio/pci/vfio_pci_config.c:1187
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
```
**Symbols:**

```
ffffffff818a9190-ffffffff818a93a8: vfio_msi_cap_len (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfio_msi_cap_len(struct vfio_pci_device *vdev, u8 pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff818b80c0)
Location: drivers/vfio/pci/vfio_pci_config.c:1192
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
```
**Symbols:**

```
ffffffff818b80c0-ffffffff818b82d8: vfio_msi_cap_len (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfio_msi_cap_len(struct vfio_pci_device *vdev, u8 pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff8189b490)
Location: drivers/vfio/pci/vfio_pci_config.c:1192
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
```
**Symbols:**

```
ffffffff8189b490-ffffffff8189b6b2: vfio_msi_cap_len (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vfio_msi_cap_len(struct vfio_pci_core_device *vdev, u8 pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff8192f590)
Location: drivers/vfio/pci/vfio_pci_config.c:1192
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
```
**Symbols:**

```
ffffffff8192f590-ffffffff8192f7b2: vfio_msi_cap_len (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vfio_msi_cap_len(struct vfio_pci_core_device *vdev, u8 pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff81a85f30)
Location: drivers/vfio/pci/vfio_pci_config.c:1228
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
```
**Symbols:**

```
ffffffff81a85f30-ffffffff81a8616d: vfio_msi_cap_len (STB_LOCAL)
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
In drivers/vfio/pci/vfio_pci_config.c (c000000000abc370)
Location: drivers/vfio/pci/vfio_pci_config.c:1155
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff8178535e)
Location: drivers/vfio/pci/vfio_pci_config.c:1155
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817d012e)
Location: drivers/vfio/pci/vfio_pci_config.c:1155
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817ea3ce)
Location: drivers/vfio/pci/vfio_pci_config.c:1155
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_len
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
