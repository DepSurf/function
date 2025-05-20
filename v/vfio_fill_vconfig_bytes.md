# Function: <code>vfio_fill_vconfig_bytes</code>

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
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817dab00)
Location: drivers/vfio/pci/vfio_pci_config.c:1378
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
```
**Symbols:**

```
ffffffff817dab00-ffffffff817dac02: vfio_fill_vconfig_bytes.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfio_fill_vconfig_bytes(struct vfio_pci_device *vdev, int offset, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff818a8960)
Location: drivers/vfio/pci/vfio_pci_config.c:1410
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init
```
**Symbols:**

```
ffffffff818a8960-ffffffff818a8a62: vfio_fill_vconfig_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfio_fill_vconfig_bytes(struct vfio_pci_device *vdev, int offset, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff818b77c0)
Location: drivers/vfio/pci/vfio_pci_config.c:1415
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init
```
**Symbols:**

```
ffffffff818b77c0-ffffffff818b78c2: vfio_fill_vconfig_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfio_fill_vconfig_bytes(struct vfio_pci_device *vdev, int offset, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff8189ac50)
Location: drivers/vfio/pci/vfio_pci_config.c:1415
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init
```
**Symbols:**

```
ffffffff8189ac50-ffffffff8189ad48: vfio_fill_vconfig_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vfio_fill_vconfig_bytes(struct vfio_pci_core_device *vdev, int offset, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff8192e810)
Location: drivers/vfio/pci/vfio_pci_config.c:1415
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init
```
**Symbols:**

```
ffffffff8192e810-ffffffff8192e908: vfio_fill_vconfig_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vfio_fill_vconfig_bytes(struct vfio_pci_core_device *vdev, int offset, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff81a850b0)
Location: drivers/vfio/pci/vfio_pci_config.c:1462
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init
```
**Symbols:**

```
ffffffff81a850b0-ffffffff81a851b4: vfio_fill_vconfig_bytes (STB_LOCAL)
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
int vfio_fill_vconfig_bytes(struct vfio_pci_device *vdev, int offset, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (c000000000abb420)
Location: drivers/vfio/pci/vfio_pci_config.c:1378
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
```
**Symbols:**

```
c000000000abb420-c000000000abb604: vfio_fill_vconfig_bytes (STB_LOCAL)
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
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff81784bb0)
Location: drivers/vfio/pci/vfio_pci_config.c:1378
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
```
**Symbols:**

```
ffffffff81784bb0-ffffffff81784cb2: vfio_fill_vconfig_bytes.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817cf980)
Location: drivers/vfio/pci/vfio_pci_config.c:1378
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
```
**Symbols:**

```
ffffffff817cf980-ffffffff817cfa82: vfio_fill_vconfig_bytes.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817e9c20)
Location: drivers/vfio/pci/vfio_pci_config.c:1378
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
```
**Symbols:**

```
ffffffff817e9c20-ffffffff817e9d22: vfio_fill_vconfig_bytes.isra.0 (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
