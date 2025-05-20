# Function: <code>vfio_config_init</code>

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
int vfio_config_init(struct vfio_pci_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:1630
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
```
**Symbols:**

```
ffffffff817dc102-ffffffff817dc17e: vfio_config_init.cold (STB_LOCAL)
ffffffff817db750-ffffffff817dbb13: vfio_config_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int vfio_config_init(struct vfio_pci_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:1667
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
```
**Symbols:**

```
ffffffff818aa42f-ffffffff818aa44c: vfio_config_init.cold (STB_LOCAL)
ffffffff818a9f20-ffffffff818aa0ed: vfio_config_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int vfio_config_init(struct vfio_pci_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:1672
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
```
**Symbols:**

```
ffffffff81c1a4a4-ffffffff81c1a4c1: vfio_config_init.cold (STB_LOCAL)
ffffffff818b8e50-ffffffff818b9027: vfio_config_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int vfio_config_init(struct vfio_pci_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:1672
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
```
**Symbols:**

```
ffffffff81c0c390-ffffffff81c0c3ad: vfio_config_init.cold (STB_LOCAL)
ffffffff8189c320-ffffffff8189c504: vfio_config_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int vfio_config_init(struct vfio_pci_core_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:1672
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_enable
```
**Symbols:**

```
ffffffff81d12832-ffffffff81d12864: vfio_config_init.cold (STB_LOCAL)
ffffffff81930570-ffffffff81930765: vfio_config_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int vfio_config_init(struct vfio_pci_core_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:1722
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_enable
```
**Symbols:**

```
ffffffff81edd573-ffffffff81edd5a5: vfio_config_init.cold (STB_LOCAL)
ffffffff81a87060-ffffffff81a87288: vfio_config_init (STB_GLOBAL)
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
int vfio_config_init(struct vfio_pci_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (c000000000abc8f0)
Location: drivers/vfio/pci/vfio_pci_config.c:1630
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
```
**Symbols:**

```
c000000000abc8f0-c000000000abce5c: vfio_config_init (STB_GLOBAL)
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
int vfio_config_init(struct vfio_pci_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:1630
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
```
**Symbols:**

```
ffffffff817861b2-ffffffff8178622e: vfio_config_init.cold (STB_LOCAL)
ffffffff81785800-ffffffff81785bc3: vfio_config_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int vfio_config_init(struct vfio_pci_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:1630
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
```
**Symbols:**

```
ffffffff817d0f82-ffffffff817d0ffe: vfio_config_init.cold (STB_LOCAL)
ffffffff817d05d0-ffffffff817d0993: vfio_config_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int vfio_config_init(struct vfio_pci_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:1630
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
```
**Symbols:**

```
ffffffff817eb222-ffffffff817eb29e: vfio_config_init.cold (STB_LOCAL)
ffffffff817ea870-ffffffff817eac33: vfio_config_init (STB_GLOBAL)
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
