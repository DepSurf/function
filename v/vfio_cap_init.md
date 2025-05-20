# Function: <code>vfio_cap_init</code>

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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817db878)
Location: drivers/vfio/pci/vfio_pci_config.c:1425
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int vfio_cap_init(struct vfio_pci_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:1457
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
```
**Symbols:**

```
ffffffff818a95c0-ffffffff818a97cb: vfio_cap_init (STB_LOCAL)
ffffffff818aa3d0-ffffffff818aa42f: vfio_cap_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int vfio_cap_init(struct vfio_pci_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:1462
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
```
**Symbols:**

```
ffffffff818b84f0-ffffffff818b86f8: vfio_cap_init (STB_LOCAL)
ffffffff81c1a445-ffffffff81c1a4a4: vfio_cap_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int vfio_cap_init(struct vfio_pci_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:1462
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
```
**Symbols:**

```
ffffffff8189b8d0-ffffffff8189bae9: vfio_cap_init (STB_LOCAL)
ffffffff81c0c334-ffffffff81c0c390: vfio_cap_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int vfio_cap_init(struct vfio_pci_core_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:1462
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
```
**Symbols:**

```
ffffffff8192f9d0-ffffffff8192fc29: vfio_cap_init (STB_LOCAL)
ffffffff81d127d6-ffffffff81d12832: vfio_cap_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int vfio_cap_init(struct vfio_pci_core_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:1509
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
```
**Symbols:**

```
ffffffff81a86390-ffffffff81a86637: vfio_cap_init (STB_LOCAL)
ffffffff81edd509-ffffffff81edd573: vfio_cap_init.cold (STB_LOCAL)
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
In drivers/vfio/pci/vfio_pci_config.c (c000000000abca38)
Location: drivers/vfio/pci/vfio_pci_config.c:1425
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff81785928)
Location: drivers/vfio/pci/vfio_pci_config.c:1425
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817d06f8)
Location: drivers/vfio/pci/vfio_pci_config.c:1425
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817ea998)
Location: drivers/vfio/pci/vfio_pci_config.c:1425
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
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
