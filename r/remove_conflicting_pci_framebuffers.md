# Function: <code>remove_conflicting_pci_framebuffers</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int remove_conflicting_pci_framebuffers(struct pci_dev *pdev, int res_id, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff8156bf90)
Location: drivers/video/fbdev/core/fbmem.c:1878
Inline: False
```
**Symbols:**

```
ffffffff8156bf90-ffffffff8156c032: remove_conflicting_pci_framebuffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int remove_conflicting_pci_framebuffers(struct pci_dev *pdev, int res_id, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (0)
Location: drivers/video/fbdev/core/fbmem.c:1780
Inline: False
```
**Symbols:**

```
ffffffff8159c9e7-ffffffff8159ca7b: remove_conflicting_pci_framebuffers.cold (STB_LOCAL)
ffffffff8159c410-ffffffff8159c4ed: remove_conflicting_pci_framebuffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int remove_conflicting_pci_framebuffers(struct pci_dev *pdev, int res_id, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (0)
Location: drivers/video/fbdev/core/fbmem.c:1770
Inline: False
```
**Symbols:**

```
ffffffff815bdd8e-ffffffff815bde22: remove_conflicting_pci_framebuffers.cold (STB_LOCAL)
ffffffff815bda10-ffffffff815bdaed: remove_conflicting_pci_framebuffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int remove_conflicting_pci_framebuffers(struct pci_dev *pdev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff81667600)
Location: drivers/video/fbdev/core/fbmem.c:1776
Inline: False
```
**Symbols:**

```
ffffffff81667600-ffffffff81667730: remove_conflicting_pci_framebuffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int remove_conflicting_pci_framebuffers(struct pci_dev *pdev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff816881d0)
Location: drivers/video/fbdev/core/fbmem.c:1769
Inline: False
```
**Symbols:**

```
ffffffff816881d0-ffffffff81688300: remove_conflicting_pci_framebuffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int remove_conflicting_pci_framebuffers(struct pci_dev *pdev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff8166af40)
Location: drivers/video/fbdev/core/fbmem.c:1767
Inline: False
```
**Symbols:**

```
ffffffff8166af40-ffffffff8166b070: remove_conflicting_pci_framebuffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int remove_conflicting_pci_framebuffers(struct pci_dev *pdev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff816decf0)
Location: drivers/video/fbdev/core/fbmem.c:1820
Inline: False
```
**Symbols:**

```
ffffffff816decf0-ffffffff816def8d: remove_conflicting_pci_framebuffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int remove_conflicting_pci_framebuffers(struct pci_dev *pdev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff81808d50)
Location: drivers/video/fbdev/core/fbmem.c:1801
Inline: False
```
**Symbols:**

```
ffffffff81808d50-ffffffff81808fff: remove_conflicting_pci_framebuffers (STB_GLOBAL)
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int remove_conflicting_pci_framebuffers(struct pci_dev *pdev, int res_id, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffff8000107437f8)
Location: drivers/video/fbdev/core/fbmem.c:1770
Inline: False
```
**Symbols:**

```
ffff8000107437f8-ffff800010743960: remove_conflicting_pci_framebuffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int remove_conflicting_pci_framebuffers(struct pci_dev *pdev, int res_id, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (c08c84d0)
Location: drivers/video/fbdev/core/fbmem.c:1770
Inline: False
```
**Symbols:**

```
c08c84d0-c08c8620: remove_conflicting_pci_framebuffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int remove_conflicting_pci_framebuffers(struct pci_dev *pdev, int res_id, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (c0000000008a5c00)
Location: drivers/video/fbdev/core/fbmem.c:1770
Inline: False
```
**Symbols:**

```
c0000000008a5c00-c0000000008a5df0: remove_conflicting_pci_framebuffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int remove_conflicting_pci_framebuffers(struct pci_dev *pdev, int res_id, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffe0004f4bb6)
Location: drivers/video/fbdev/core/fbmem.c:1770
Inline: False
```
**Symbols:**

```
ffffffe0004f4bb6-ffffffe0004f4cf6: remove_conflicting_pci_framebuffers (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int remove_conflicting_pci_framebuffers(struct pci_dev *pdev, int res_id, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (0)
Location: drivers/video/fbdev/core/fbmem.c:1770
Inline: False
```
**Symbols:**

```
ffffffff815b1ede-ffffffff815b1f72: remove_conflicting_pci_framebuffers.cold (STB_LOCAL)
ffffffff815b1b60-ffffffff815b1c3d: remove_conflicting_pci_framebuffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int remove_conflicting_pci_framebuffers(struct pci_dev *pdev, int res_id, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (0)
Location: drivers/video/fbdev/core/fbmem.c:1770
Inline: False
```
**Symbols:**

```
ffffffff815a106e-ffffffff815a1102: remove_conflicting_pci_framebuffers.cold (STB_LOCAL)
ffffffff815a0cf0-ffffffff815a0dcd: remove_conflicting_pci_framebuffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int remove_conflicting_pci_framebuffers(struct pci_dev *pdev, int res_id, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (0)
Location: drivers/video/fbdev/core/fbmem.c:1770
Inline: False
```
**Symbols:**

```
ffffffff815b246e-ffffffff815b2502: remove_conflicting_pci_framebuffers.cold (STB_LOCAL)
ffffffff815b20f0-ffffffff815b21cd: remove_conflicting_pci_framebuffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int remove_conflicting_pci_framebuffers(struct pci_dev *pdev, int res_id, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (0)
Location: drivers/video/fbdev/core/fbmem.c:1770
Inline: False
```
**Symbols:**

```
ffffffff815cbede-ffffffff815cbf72: remove_conflicting_pci_framebuffers.cold (STB_LOCAL)
ffffffff815cbb60-ffffffff815cbc3d: remove_conflicting_pci_framebuffers (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int res_id</code>
</li>
<li>
<b>Param reordered. </b>
<code>pdev, res_id, name</code> ➡️ <code>pdev, name</code>
</li>
</ul>
</details>
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
