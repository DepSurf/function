# Function: <code>quirk_disable_msi</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void quirk_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81443df0)
Location: drivers/pci/quirks.c:2267
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
```
**Symbols:**

```
ffffffff81443df0-ffffffff81443e27: quirk_disable_msi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void quirk_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff814905b2)
Location: drivers/pci/quirks.c:2308
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
```
**Symbols:**

```
ffffffff8148fcc0-ffffffff8148fcf7: quirk_disable_msi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void quirk_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff814b1e02)
Location: drivers/pci/quirks.c:2320
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
```
**Symbols:**

```
ffffffff814b1510-ffffffff814b1547: quirk_disable_msi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void quirk_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff814bd8d2)
Location: drivers/pci/quirks.c:2380
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
Direct callers:
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
```
**Symbols:**

```
ffffffff814bd850-ffffffff814bd87f: quirk_disable_msi.part.30 (STB_LOCAL)
ffffffff814bd880-ffffffff814bd899: quirk_disable_msi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void quirk_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff814fdc62)
Location: drivers/pci/quirks.c:2381
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
Direct callers:
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
```
**Symbols:**

```
ffffffff814fdbe0-ffffffff814fdc0f: quirk_disable_msi.part.28 (STB_LOCAL)
ffffffff814fdc10-ffffffff814fdc29: quirk_disable_msi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void quirk_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff8152e522)
Location: drivers/pci/quirks.c:2415
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
Direct callers:
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
```
**Symbols:**

```
ffffffff8152e4a0-ffffffff8152e4cf: quirk_disable_msi.part.29 (STB_LOCAL)
ffffffff8152e4d0-ffffffff8152e4e8: quirk_disable_msi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void quirk_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81545372)
Location: drivers/pci/quirks.c:2456
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
Direct callers:
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
```
**Symbols:**

```
ffffffff81545320-ffffffff81545338: quirk_disable_msi (STB_LOCAL)
ffffffff815452f0-ffffffff8154531f: quirk_disable_msi.part.29 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void quirk_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81574762)
Location: drivers/pci/quirks.c:2471
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
```
**Symbols:**

```
ffffffff81576230-ffffffff81576248: quirk_disable_msi (STB_LOCAL)
ffffffff815775c5-ffffffff815775ec: quirk_disable_msi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void quirk_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81595e12)
Location: drivers/pci/quirks.c:2465
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
```
**Symbols:**

```
ffffffff81597920-ffffffff81597938: quirk_disable_msi (STB_LOCAL)
ffffffff81598d49-ffffffff81598d70: quirk_disable_msi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void quirk_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81644582)
Location: drivers/pci/quirks.c:2542
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
Direct callers:
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
```
**Symbols:**

```
ffffffff81644530-ffffffff81644546: quirk_disable_msi (STB_LOCAL)
ffffffff81647223-ffffffff81647252: quirk_disable_msi.part.0 (STB_LOCAL)
ffffffff81647252-ffffffff8164725c: quirk_disable_msi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void quirk_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff8166a992)
Location: drivers/pci/quirks.c:2543
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
Direct callers:
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
```
**Symbols:**

```
ffffffff8166a940-ffffffff8166a956: quirk_disable_msi (STB_LOCAL)
ffffffff81bfadd3-ffffffff81bfae02: quirk_disable_msi.part.0 (STB_LOCAL)
ffffffff81bfae02-ffffffff81bfae0c: quirk_disable_msi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void quirk_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff8164e7c9)
Location: drivers/pci/quirks.c:2540
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
Direct callers:
  - drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
```
**Symbols:**

```
ffffffff8164cca0-ffffffff8164ccb1: quirk_disable_msi (STB_LOCAL)
ffffffff81becc3f-ffffffff81becc6e: quirk_disable_msi.part.0 (STB_LOCAL)
ffffffff81becc6e-ffffffff81becc79: quirk_disable_msi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void quirk_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff816c0449)
Location: drivers/pci/quirks.c:2579
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
Direct callers:
  - drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
```
**Symbols:**

```
ffffffff816bead0-ffffffff816beae1: quirk_disable_msi (STB_LOCAL)
ffffffff81ce7927-ffffffff81ce7956: quirk_disable_msi.part.0 (STB_LOCAL)
ffffffff81ce7956-ffffffff81ce7961: quirk_disable_msi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void quirk_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff817e5c61)
Location: drivers/pci/quirks.c:2592
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
Direct callers:
  - drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
```
**Symbols:**

```
ffffffff817e4ad0-ffffffff817e4ae7: quirk_disable_msi (STB_LOCAL)
ffffffff81eaeac1-ffffffff81eaeafa: quirk_disable_msi.part.0 (STB_LOCAL)
ffffffff81eaeafa-ffffffff81eaeb0b: quirk_disable_msi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void quirk_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff8190ace1)
Location: drivers/pci/quirks.c:2594
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap
  - drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
```
**Symbols:**

```
ffffffff8190a9c0-ffffffff8190aa0e: quirk_disable_msi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void quirk_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff8194e221)
Location: drivers/pci/quirks.c:2700
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap
  - drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
```
**Symbols:**

```
ffffffff8194df00-ffffffff8194df4e: quirk_disable_msi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void quirk_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81997651)
Location: drivers/pci/quirks.c:2714
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap
  - drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
```
**Symbols:**

```
ffffffff81997330-ffffffff8199737e: quirk_disable_msi (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void quirk_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffff8000106fd830)
Location: drivers/pci/quirks.c:2465
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
Direct callers:
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
```
**Symbols:**

```
ffff8000106fd7a8-ffff8000106fd7e0: quirk_disable_msi (STB_LOCAL)
ffff8000107002f0-ffff800010700334: quirk_disable_msi.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void quirk_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (c0895da0)
Location: drivers/pci/quirks.c:2465
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
Direct callers:
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
```
**Symbols:**

```
c0898074-c08980b0: quirk_disable_msi.part.0 (STB_LOCAL)
c0895d34-c0895d5c: quirk_disable_msi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void quirk_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (c00000000087c160)
Location: drivers/pci/quirks.c:2465
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
```
**Symbols:**

```
c00000000087e2a0-c00000000087e308: quirk_disable_msi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void quirk_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffe0004cd32c)
Location: drivers/pci/quirks.c:2465
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
Direct callers:
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
```
**Symbols:**

```
ffffffe0004cf31e-ffffffe0004cf360: quirk_disable_msi.part.0 (STB_LOCAL)
ffffffe0004cd2b4-ffffffe0004cd2e4: quirk_disable_msi (STB_LOCAL)
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
void quirk_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81589ca2)
Location: drivers/pci/quirks.c:2465
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
```
**Symbols:**

```
ffffffff8158b7b0-ffffffff8158b7c8: quirk_disable_msi (STB_LOCAL)
ffffffff8158cbd9-ffffffff8158cc00: quirk_disable_msi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void quirk_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff815787e2)
Location: drivers/pci/quirks.c:2465
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
```
**Symbols:**

```
ffffffff8157a2f0-ffffffff8157a308: quirk_disable_msi (STB_LOCAL)
ffffffff8157b719-ffffffff8157b740: quirk_disable_msi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void quirk_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81589b62)
Location: drivers/pci/quirks.c:2465
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
```
**Symbols:**

```
ffffffff8158b670-ffffffff8158b688: quirk_disable_msi (STB_LOCAL)
ffffffff8158ca99-ffffffff8158cac0: quirk_disable_msi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void quirk_disable_msi(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff815a4012)
Location: drivers/pci/quirks.c:2465
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
  - drivers/pci/quirks.c:quirk_amd_780_apc_msi
```
**Symbols:**

```
ffffffff815a5b20-ffffffff815a5b38: quirk_disable_msi (STB_LOCAL)
ffffffff815a6f49-ffffffff815a6f70: quirk_disable_msi.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
