# Function: <code>vfio_pci_intx_mask</code>

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
<summary>In <code>5.4</code>: ✅</summary>

```c
void vfio_pci_intx_mask(struct vfio_pci_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817d90d0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:36
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
```
**Symbols:**

```
ffffffff817d90d0-ffffffff817d9161: vfio_pci_intx_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void vfio_pci_intx_mask(struct vfio_pci_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff818a6da0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:36
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
```
**Symbols:**

```
ffffffff818a6da0-ffffffff818a6e31: vfio_pci_intx_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void vfio_pci_intx_mask(struct vfio_pci_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff818b5c90)
Location: drivers/vfio/pci/vfio_pci_intrs.c:36
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
```
**Symbols:**

```
ffffffff818b5c90-ffffffff818b5d21: vfio_pci_intx_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void vfio_pci_intx_mask(struct vfio_pci_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff81899140)
Location: drivers/vfio/pci/vfio_pci_intrs.c:36
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
```
**Symbols:**

```
ffffffff81899140-ffffffff818991d5: vfio_pci_intx_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void vfio_pci_intx_mask(struct vfio_pci_core_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:36
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
```
**Symbols:**

```
ffffffff81d12430-ffffffff81d1246e: vfio_pci_intx_mask.cold (STB_LOCAL)
ffffffff8192cd00-ffffffff8192cdc3: vfio_pci_intx_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void vfio_pci_intx_mask(struct vfio_pci_core_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:36
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_mask
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
```
**Symbols:**

```
ffffffff81edd168-ffffffff81edd1a6: vfio_pci_intx_mask.cold (STB_LOCAL)
ffffffff81a833b0-ffffffff81a83480: vfio_pci_intx_mask (STB_GLOBAL)
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
void vfio_pci_intx_mask(struct vfio_pci_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (c000000000ab91a0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:36
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
```
**Symbols:**

```
c000000000ab91a0-c000000000ab9290: vfio_pci_intx_mask (STB_GLOBAL)
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
<summary>In <code>azure</code>: ✅</summary>

```c
void vfio_pci_intx_mask(struct vfio_pci_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff81783180)
Location: drivers/vfio/pci/vfio_pci_intrs.c:36
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
```
**Symbols:**

```
ffffffff81783180-ffffffff81783211: vfio_pci_intx_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void vfio_pci_intx_mask(struct vfio_pci_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817cdf50)
Location: drivers/vfio/pci/vfio_pci_intrs.c:36
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
```
**Symbols:**

```
ffffffff817cdf50-ffffffff817cdfe1: vfio_pci_intx_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void vfio_pci_intx_mask(struct vfio_pci_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817e81f0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:36
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
```
**Symbols:**

```
ffffffff817e81f0-ffffffff817e8281: vfio_pci_intx_mask (STB_GLOBAL)
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
