# Function: <code>vfio_ecap_init</code>

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
int vfio_ecap_init(struct vfio_pci_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:1510
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
```
**Symbols:**

```
ffffffff817dac10-ffffffff817db121: vfio_ecap_init (STB_LOCAL)
ffffffff817dbffe-ffffffff817dc0d8: vfio_ecap_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int vfio_ecap_init(struct vfio_pci_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:1547
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
```
**Symbols:**

```
ffffffff818a8e10-ffffffff818a9006: vfio_ecap_init (STB_LOCAL)
ffffffff818aa30a-ffffffff818aa3a6: vfio_ecap_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int vfio_ecap_init(struct vfio_pci_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:1552
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
```
**Symbols:**

```
ffffffff818b7d50-ffffffff818b7f3b: vfio_ecap_init (STB_LOCAL)
ffffffff81c1a389-ffffffff81c1a41b: vfio_ecap_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int vfio_ecap_init(struct vfio_pci_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:1552
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
```
**Symbols:**

```
ffffffff8189b1a0-ffffffff8189b393: vfio_ecap_init (STB_LOCAL)
ffffffff81c0c278-ffffffff81c0c30a: vfio_ecap_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int vfio_ecap_init(struct vfio_pci_core_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:1552
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
```
**Symbols:**

```
ffffffff8192f270-ffffffff8192f494: vfio_ecap_init (STB_LOCAL)
ffffffff81d12706-ffffffff81d127ac: vfio_ecap_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int vfio_ecap_init(struct vfio_pci_core_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:1602
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
```
**Symbols:**

```
ffffffff81a85bd0-ffffffff81a85e1b: vfio_ecap_init (STB_LOCAL)
ffffffff81edd40d-ffffffff81edd4e0: vfio_ecap_init.cold (STB_LOCAL)
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
int vfio_ecap_init(struct vfio_pci_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (c000000000abb610)
Location: drivers/vfio/pci/vfio_pci_config.c:1510
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
```
**Symbols:**

```
c000000000abb610-c000000000abbd20: vfio_ecap_init (STB_LOCAL)
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
int vfio_ecap_init(struct vfio_pci_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:1510
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
```
**Symbols:**

```
ffffffff81784cc0-ffffffff817851d1: vfio_ecap_init (STB_LOCAL)
ffffffff817860ae-ffffffff81786188: vfio_ecap_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int vfio_ecap_init(struct vfio_pci_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:1510
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
```
**Symbols:**

```
ffffffff817cfa90-ffffffff817cffa1: vfio_ecap_init (STB_LOCAL)
ffffffff817d0e7e-ffffffff817d0f58: vfio_ecap_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int vfio_ecap_init(struct vfio_pci_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:1510
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
```
**Symbols:**

```
ffffffff817e9d30-ffffffff817ea241: vfio_ecap_init (STB_LOCAL)
ffffffff817eb11e-ffffffff817eb1f8: vfio_ecap_init.cold (STB_LOCAL)
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
