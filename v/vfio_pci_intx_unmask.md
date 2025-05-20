# Function: <code>vfio_pci_intx_unmask</code>

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
void vfio_pci_intx_unmask(struct vfio_pci_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817d91d0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:110
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
```
**Symbols:**

```
ffffffff817d91d0-ffffffff817d91f7: vfio_pci_intx_unmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void vfio_pci_intx_unmask(struct vfio_pci_device *vdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff818a6ea0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:110
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
```
**Symbols:**

```
ffffffff818a6ea0-ffffffff818a6eeb: vfio_pci_intx_unmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void vfio_pci_intx_unmask(struct vfio_pci_device *vdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff818b5d90)
Location: drivers/vfio/pci/vfio_pci_intrs.c:110
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
```
**Symbols:**

```
ffffffff818b5d90-ffffffff818b5ddb: vfio_pci_intx_unmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void vfio_pci_intx_unmask(struct vfio_pci_device *vdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff81899240)
Location: drivers/vfio/pci/vfio_pci_intrs.c:110
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
```
**Symbols:**

```
ffffffff81899240-ffffffff8189928b: vfio_pci_intx_unmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void vfio_pci_intx_unmask(struct vfio_pci_core_device *vdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff8192c979)
Location: drivers/vfio/pci/vfio_pci_intrs.c:110
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
```
**Symbols:**

```
ffffffff81d1246e-ffffffff81d12483: vfio_pci_intx_unmask.cold (STB_LOCAL)
ffffffff8192ce30-ffffffff8192ce8a: vfio_pci_intx_unmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void vfio_pci_intx_unmask(struct vfio_pci_core_device *vdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff81a8301c)
Location: drivers/vfio/pci/vfio_pci_intrs.c:110
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_unmask
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_unmask
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_unmask
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_unmask
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
```
**Symbols:**

```
ffffffff81edd1a6-ffffffff81edd1bb: vfio_pci_intx_unmask.cold (STB_LOCAL)
ffffffff81a83500-ffffffff81a8356e: vfio_pci_intx_unmask (STB_GLOBAL)
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
void vfio_pci_intx_unmask(struct vfio_pci_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (c000000000ab9330)
Location: drivers/vfio/pci/vfio_pci_intrs.c:110
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
```
**Symbols:**

```
c000000000ab9330-c000000000ab939c: vfio_pci_intx_unmask (STB_GLOBAL)
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
void vfio_pci_intx_unmask(struct vfio_pci_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff81783280)
Location: drivers/vfio/pci/vfio_pci_intrs.c:110
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
```
**Symbols:**

```
ffffffff81783280-ffffffff817832a7: vfio_pci_intx_unmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void vfio_pci_intx_unmask(struct vfio_pci_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817ce050)
Location: drivers/vfio/pci/vfio_pci_intrs.c:110
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
```
**Symbols:**

```
ffffffff817ce050-ffffffff817ce077: vfio_pci_intx_unmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void vfio_pci_intx_unmask(struct vfio_pci_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817e82f0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:110
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
```
**Symbols:**

```
ffffffff817e82f0-ffffffff817e8317: vfio_pci_intx_unmask (STB_GLOBAL)
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
