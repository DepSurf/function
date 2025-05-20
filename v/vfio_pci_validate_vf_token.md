# Function: <code>vfio_pci_validate_vf_token</code>

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
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int vfio_pci_validate_vf_token(struct vfio_pci_device *vdev, bool vf_token, uuid_t *uuid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (0)
Location: drivers/vfio/pci/vfio_pci.c:1665
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_match
```
**Symbols:**

```
ffffffff818a3850-ffffffff818a3aa2: vfio_pci_validate_vf_token (STB_LOCAL)
ffffffff818a5d23-ffffffff818a5de3: vfio_pci_validate_vf_token.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int vfio_pci_validate_vf_token(struct vfio_pci_device *vdev, bool vf_token, uuid_t *uuid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (0)
Location: drivers/vfio/pci/vfio_pci.c:1740
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_match
```
**Symbols:**

```
ffffffff818b2830-ffffffff818b2a79: vfio_pci_validate_vf_token (STB_LOCAL)
ffffffff81c1a0d1-ffffffff81c1a191: vfio_pci_validate_vf_token.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int vfio_pci_validate_vf_token(struct vfio_pci_device *vdev, bool vf_token, uuid_t *uuid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (0)
Location: drivers/vfio/pci/vfio_pci.c:1737
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_match
```
**Symbols:**

```
ffffffff81895b40-ffffffff81895d4a: vfio_pci_validate_vf_token (STB_LOCAL)
ffffffff81c0bf5f-ffffffff81c0c025: vfio_pci_validate_vf_token.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int vfio_pci_validate_vf_token(struct vfio_pci_core_device *vdev, bool vf_token, uuid_t *uuid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_core.c (0)
Location: drivers/vfio/pci/vfio_pci_core.c:1541
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_match
```
**Symbols:**

```
ffffffff81929ae0-ffffffff81929cea: vfio_pci_validate_vf_token (STB_LOCAL)
ffffffff81d11fbb-ffffffff81d12081: vfio_pci_validate_vf_token.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int vfio_pci_validate_vf_token(struct vfio_pci_core_device *vdev, bool vf_token, uuid_t *uuid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_core.c (0)
Location: drivers/vfio/pci/vfio_pci_core.c:1571
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_match
```
**Symbols:**

```
ffffffff81a7fec0-ffffffff81a800a2: vfio_pci_validate_vf_token (STB_LOCAL)
ffffffff81edcd4f-ffffffff81edce09: vfio_pci_validate_vf_token.cold (STB_LOCAL)
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
