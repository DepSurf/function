# Function: <code>vga_remove_vgacon</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int vga_remove_vgacon(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff8178b32d)
Location: drivers/gpu/vga/vgaarb.c:194
Inline: True
```
**Symbols:**

```
ffffffff8178b32d-ffffffff8178b394: vga_remove_vgacon.cold (STB_LOCAL)
ffffffff8178a420-ffffffff8178a43e: vga_remove_vgacon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int vga_remove_vgacon(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff817aef48)
Location: drivers/gpu/vga/vgaarb.c:194
Inline: True
```
**Symbols:**

```
ffffffff817aef48-ffffffff817aefaf: vga_remove_vgacon.cold (STB_LOCAL)
ffffffff817ae040-ffffffff817ae05e: vga_remove_vgacon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int vga_remove_vgacon(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff81874fbb)
Location: drivers/gpu/vga/vgaarb.c:194
Inline: True
```
**Symbols:**

```
ffffffff81874fbb-ffffffff81875022: vga_remove_vgacon.cold (STB_LOCAL)
ffffffff81874020-ffffffff8187403e: vga_remove_vgacon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int vga_remove_vgacon(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff81c186cb)
Location: drivers/gpu/vga/vgaarb.c:194
Inline: True
```
**Symbols:**

```
ffffffff81c186cb-ffffffff81c18732: vga_remove_vgacon.cold (STB_LOCAL)
ffffffff81882bc0-ffffffff81882bde: vga_remove_vgacon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int vga_remove_vgacon(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff81c0a4bd)
Location: drivers/gpu/vga/vgaarb.c:195
Inline: True
```
**Symbols:**

```
ffffffff81c0a4bd-ffffffff81c0a526: vga_remove_vgacon.cold (STB_LOCAL)
ffffffff81865410-ffffffff81865425: vga_remove_vgacon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int vga_remove_vgacon(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff81d0f17c)
Location: drivers/gpu/vga/vgaarb.c:192
Inline: True
```
**Symbols:**

```
ffffffff81d0f17c-ffffffff81d0f1e5: vga_remove_vgacon.cold (STB_LOCAL)
ffffffff818f4790-ffffffff818f47a5: vga_remove_vgacon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int vga_remove_vgacon(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/vgaarb.c (ffffffff81eb21fd)
Location: drivers/pci/vgaarb.c:170
Inline: True
```
**Symbols:**

```
ffffffff81eb21fd-ffffffff81eb2272: vga_remove_vgacon.cold (STB_LOCAL)
ffffffff817f3b30-ffffffff817f3b51: vga_remove_vgacon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int vga_remove_vgacon(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vgaarb.c (ffffffff8191e110)
Location: drivers/pci/vgaarb.c:170
Inline: True
Direct callers:
  - drivers/video/aperture.c:aperture_remove_conflicting_pci_devices
```
**Symbols:**

```
ffffffff8191e110-ffffffff8191e1b0: vga_remove_vgacon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int vga_remove_vgacon(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vgaarb.c (ffffffff81961620)
Location: drivers/pci/vgaarb.c:170
Inline: True
Direct callers:
  - drivers/video/aperture.c:aperture_remove_conflicting_pci_devices
```
**Symbols:**

```
ffffffff81961620-ffffffff819616c0: vga_remove_vgacon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int vga_remove_vgacon(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vgaarb.c (ffffffff819aada0)
Location: drivers/pci/vgaarb.c:167
Inline: True
Direct callers:
  - drivers/video/aperture.c:aperture_remove_conflicting_pci_devices
```
**Symbols:**

```
ffffffff819aada0-ffffffff819aae40: vga_remove_vgacon (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int vga_remove_vgacon(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffff8000109bf4a0)
Location: drivers/gpu/vga/vgaarb.c:184
Inline: False
```
**Symbols:**

```
ffff8000109bf4a0-ffff8000109bf4bc: vga_remove_vgacon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vga_remove_vgacon(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (c0a8c8d8)
Location: drivers/gpu/vga/vgaarb.c:184
Inline: False
```
**Symbols:**

```
c0a8c8d8-c0a8c8f4: vga_remove_vgacon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int vga_remove_vgacon(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (c000000000a81020)
Location: drivers/gpu/vga/vgaarb.c:194
Inline: True
```
**Symbols:**

```
c000000000a81020-c000000000a810f0: vga_remove_vgacon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int vga_remove_vgacon(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffe000612dfe)
Location: drivers/gpu/vga/vgaarb.c:194
Inline: True
```
**Symbols:**

```
ffffffe000612dfe-ffffffe000612e9e: vga_remove_vgacon (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int vga_remove_vgacon(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff81773a68)
Location: drivers/gpu/vga/vgaarb.c:194
Inline: True
```
**Symbols:**

```
ffffffff81773a68-ffffffff81773acf: vga_remove_vgacon.cold (STB_LOCAL)
ffffffff81772b60-ffffffff81772b7e: vga_remove_vgacon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int vga_remove_vgacon(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff81753818)
Location: drivers/gpu/vga/vgaarb.c:194
Inline: True
```
**Symbols:**

```
ffffffff81753818-ffffffff8175387f: vga_remove_vgacon.cold (STB_LOCAL)
ffffffff81752910-ffffffff8175292e: vga_remove_vgacon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int vga_remove_vgacon(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff817a3dc8)
Location: drivers/gpu/vga/vgaarb.c:194
Inline: True
```
**Symbols:**

```
ffffffff817a3dc8-ffffffff817a3e2f: vga_remove_vgacon.cold (STB_LOCAL)
ffffffff817a2ec0-ffffffff817a2ede: vga_remove_vgacon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int vga_remove_vgacon(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpu/vga/vgaarb.c (ffffffff817bdc48)
Location: drivers/gpu/vga/vgaarb.c:194
Inline: True
```
**Symbols:**

```
ffffffff817bdc48-ffffffff817bdcaf: vga_remove_vgacon.cold (STB_LOCAL)
ffffffff817bcd40-ffffffff817bcd5e: vga_remove_vgacon (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
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
