# Function: <code>vfio_config_free</code>

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
void vfio_config_free(struct vfio_pci_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817dbb20)
Location: drivers/vfio/pci/vfio_pci_config.c:1723
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff817dbb20-ffffffff817dbb63: vfio_config_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void vfio_config_free(struct vfio_pci_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff818aa0f0)
Location: drivers/vfio/pci/vfio_pci_config.c:1769
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff818aa0f0-ffffffff818aa164: vfio_config_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void vfio_config_free(struct vfio_pci_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff818b9030)
Location: drivers/vfio/pci/vfio_pci_config.c:1776
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff818b9030-ffffffff818b90a4: vfio_config_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void vfio_config_free(struct vfio_pci_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff8189c510)
Location: drivers/vfio/pci/vfio_pci_config.c:1776
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff8189c510-ffffffff8189c599: vfio_config_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void vfio_config_free(struct vfio_pci_core_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff81930770)
Location: drivers/vfio/pci/vfio_pci_config.c:1776
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable
```
**Symbols:**

```
ffffffff81930770-ffffffff819307f9: vfio_config_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void vfio_config_free(struct vfio_pci_core_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff81a87290)
Location: drivers/vfio/pci/vfio_pci_config.c:1826
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable
```
**Symbols:**

```
ffffffff81a87290-ffffffff81a8731f: vfio_config_free (STB_GLOBAL)
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
void vfio_config_free(struct vfio_pci_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (c000000000abce60)
Location: drivers/vfio/pci/vfio_pci_config.c:1723
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
c000000000abce60-c000000000abced4: vfio_config_free (STB_GLOBAL)
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
void vfio_config_free(struct vfio_pci_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff81785bd0)
Location: drivers/vfio/pci/vfio_pci_config.c:1723
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff81785bd0-ffffffff81785c13: vfio_config_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void vfio_config_free(struct vfio_pci_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817d09a0)
Location: drivers/vfio/pci/vfio_pci_config.c:1723
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff817d09a0-ffffffff817d09e3: vfio_config_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void vfio_config_free(struct vfio_pci_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817eac40)
Location: drivers/vfio/pci/vfio_pci_config.c:1723
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
**Symbols:**

```
ffffffff817eac40-ffffffff817eac83: vfio_config_free (STB_GLOBAL)
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
