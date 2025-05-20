# Function: <code>pci_disable_rom</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pci_disable_rom(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffff8143cef0)
Location: drivers/pci/rom.c:50
Inline: False
Direct callers:
  - drivers/pci/rom.c:pci_map_rom
```
**Symbols:**

```
ffffffff8143cef0-ffffffff8143cf58: pci_disable_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_disable_rom(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/rom.c (ffffffff81488ed5)
Location: drivers/pci/rom.c:54
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
Direct callers:
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff81488e30-ffffffff81488e98: pci_disable_rom.part.2 (STB_LOCAL)
ffffffff81488ea0-ffffffff81488eba: pci_disable_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_disable_rom(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/rom.c (ffffffff814aa6a5)
Location: drivers/pci/rom.c:59
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
Direct callers:
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff814aa600-ffffffff814aa668: pci_disable_rom.part.2 (STB_LOCAL)
ffffffff814aa670-ffffffff814aa68a: pci_disable_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_disable_rom(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/rom.c (ffffffff814b49f5)
Location: drivers/pci/rom.c:59
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
Direct callers:
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff814b4960-ffffffff814b49bd: pci_disable_rom.part.0 (STB_LOCAL)
ffffffff814b49c0-ffffffff814b49db: pci_disable_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_disable_rom(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/rom.c (ffffffff814f4215)
Location: drivers/pci/rom.c:59
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
Direct callers:
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff814f4180-ffffffff814f41dd: pci_disable_rom.part.0 (STB_LOCAL)
ffffffff814f41e0-ffffffff814f41fb: pci_disable_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_disable_rom(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/rom.c (ffffffff815242d5)
Location: drivers/pci/rom.c:58
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
Direct callers:
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff81524240-ffffffff8152429d: pci_disable_rom.part.0 (STB_LOCAL)
ffffffff815242a0-ffffffff815242ba: pci_disable_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_disable_rom(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/rom.c (ffffffff8153a115)
Location: drivers/pci/rom.c:58
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
Direct callers:
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff8153a080-ffffffff8153a0dd: pci_disable_rom.part.0 (STB_LOCAL)
ffffffff8153a0e0-ffffffff8153a0fa: pci_disable_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_disable_rom(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/rom.c (ffffffff81569b86)
Location: drivers/pci/rom.c:58
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
Direct callers:
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff81569ae0-ffffffff81569b41: pci_disable_rom.part.0 (STB_LOCAL)
ffffffff81569b50-ffffffff81569b6a: pci_disable_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_disable_rom(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/rom.c (ffffffff8158ab56)
Location: drivers/pci/rom.c:58
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
Direct callers:
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff8158aab0-ffffffff8158ab11: pci_disable_rom.part.0 (STB_LOCAL)
ffffffff8158ab20-ffffffff8158ab3a: pci_disable_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_rom(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffff81631b09)
Location: drivers/pci/rom.c:58
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
Direct callers:
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff81631a70-ffffffff81631ad8: pci_disable_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_rom(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffff81657119)
Location: drivers/pci/rom.c:58
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
Direct callers:
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff81657080-ffffffff816570e8: pci_disable_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_rom(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffff816399d9)
Location: drivers/pci/rom.c:58
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
Direct callers:
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff81639940-ffffffff816399a8: pci_disable_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_rom(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffff816aa1a9)
Location: drivers/pci/rom.c:58
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
Direct callers:
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff816aa110-ffffffff816aa178: pci_disable_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pci_disable_rom(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffff817cd010)
Location: drivers/pci/rom.c:58
Inline: False
Direct callers:
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff817cd010-ffffffff817cd088: pci_disable_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_disable_rom(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffff818ec450)
Location: drivers/pci/rom.c:58
Inline: False
Direct callers:
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff818ec450-ffffffff818ec4c8: pci_disable_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_disable_rom(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffff8192f930)
Location: drivers/pci/rom.c:58
Inline: False
Direct callers:
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff8192f930-ffffffff8192f9a8: pci_disable_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_disable_rom(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffff819782b0)
Location: drivers/pci/rom.c:58
Inline: False
Direct callers:
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff819782b0-ffffffff81978328: pci_disable_rom (STB_GLOBAL)
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
void pci_disable_rom(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/rom.c (ffff8000106ef6b4)
Location: drivers/pci/rom.c:58
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
Direct callers:
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
```
**Symbols:**

```
ffff8000106ef5e8-ffff8000106ef658: pci_disable_rom.part.0 (STB_LOCAL)
ffff8000106ef658-ffff8000106ef68c: pci_disable_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_disable_rom(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/rom.c (c088a398)
Location: drivers/pci/rom.c:58
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
Direct callers:
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
```
**Symbols:**

```
c088a2d8-c088a350: pci_disable_rom.part.0 (STB_LOCAL)
c088a350-c088a378: pci_disable_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_disable_rom(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/rom.c (c00000000086c6b0)
Location: drivers/pci/rom.c:58
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
Direct callers:
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
```
**Symbols:**

```
c00000000086c5d0-c00000000086c660: pci_disable_rom.part.0 (STB_LOCAL)
c00000000086c660-c00000000086c680: pci_disable_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_disable_rom(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/rom.c (ffffffe0004c360a)
Location: drivers/pci/rom.c:58
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
Direct callers:
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
```
**Symbols:**

```
ffffffe0004c356a-ffffffe0004c35b4: pci_disable_rom.part.0 (STB_LOCAL)
ffffffe0004c35b4-ffffffe0004c35e6: pci_disable_rom (STB_GLOBAL)
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
void pci_disable_rom(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/rom.c (ffffffff8157e9d6)
Location: drivers/pci/rom.c:58
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
Direct callers:
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff8157e930-ffffffff8157e991: pci_disable_rom.part.0 (STB_LOCAL)
ffffffff8157e9a0-ffffffff8157e9ba: pci_disable_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_disable_rom(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/rom.c (ffffffff8156d7b6)
Location: drivers/pci/rom.c:58
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
Direct callers:
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff8156d710-ffffffff8156d771: pci_disable_rom.part.0 (STB_LOCAL)
ffffffff8156d780-ffffffff8156d79a: pci_disable_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_disable_rom(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/rom.c (ffffffff8157e8a6)
Location: drivers/pci/rom.c:58
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
Direct callers:
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff8157e800-ffffffff8157e861: pci_disable_rom.part.0 (STB_LOCAL)
ffffffff8157e870-ffffffff8157e88a: pci_disable_rom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_disable_rom(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/rom.c (ffffffff81598d56)
Location: drivers/pci/rom.c:58
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
Direct callers:
  - drivers/pci/rom.c:pci_unmap_rom
  - drivers/pci/rom.c:pci_map_rom
  - arch/x86/pci/fixup.c:pci_fixup_video
```
**Symbols:**

```
ffffffff81598cb0-ffffffff81598d11: pci_disable_rom.part.0 (STB_LOCAL)
ffffffff81598d20-ffffffff81598d3a: pci_disable_rom (STB_GLOBAL)
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
