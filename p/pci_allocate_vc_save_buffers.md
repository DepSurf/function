# Function: <code>pci_allocate_vc_save_buffers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pci_allocate_vc_save_buffers(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vc.c (ffffffff814414f0)
Location: drivers/pci/vc.c:417
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
```
**Symbols:**

```
ffffffff814414f0-ffffffff8144158c: pci_allocate_vc_save_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pci_allocate_vc_save_buffers(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vc.c (ffffffff8148d400)
Location: drivers/pci/vc.c:417
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
```
**Symbols:**

```
ffffffff8148d400-ffffffff8148d499: pci_allocate_vc_save_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pci_allocate_vc_save_buffers(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vc.c (ffffffff814aebf0)
Location: drivers/pci/vc.c:417
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
```
**Symbols:**

```
ffffffff814aebf0-ffffffff814aec89: pci_allocate_vc_save_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pci_allocate_vc_save_buffers(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vc.c (ffffffff814b8f50)
Location: drivers/pci/vc.c:417
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
```
**Symbols:**

```
ffffffff814b8f50-ffffffff814b8feb: pci_allocate_vc_save_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_allocate_vc_save_buffers(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vc.c (ffffffff814f93a0)
Location: drivers/pci/vc.c:417
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
```
**Symbols:**

```
ffffffff814f93a0-ffffffff814f943b: pci_allocate_vc_save_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pci_allocate_vc_save_buffers(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vc.c (ffffffff81529e70)
Location: drivers/pci/vc.c:413
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
```
**Symbols:**

```
ffffffff81529e70-ffffffff81529f0b: pci_allocate_vc_save_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_allocate_vc_save_buffers(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vc.c (ffffffff8153fd20)
Location: drivers/pci/vc.c:413
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
```
**Symbols:**

```
ffffffff8153fd20-ffffffff8153fdbb: pci_allocate_vc_save_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void pci_allocate_vc_save_buffers(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vc.c (0)
Location: drivers/pci/vc.c:413
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
```
**Symbols:**

```
ffffffff8156f682-ffffffff8156f69a: pci_allocate_vc_save_buffers.cold (STB_LOCAL)
ffffffff8156f500-ffffffff8156f565: pci_allocate_vc_save_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void pci_allocate_vc_save_buffers(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vc.c (0)
Location: drivers/pci/vc.c:414
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
```
**Symbols:**

```
ffffffff815906c2-ffffffff815906da: pci_allocate_vc_save_buffers.cold (STB_LOCAL)
ffffffff81590540-ffffffff815905a5: pci_allocate_vc_save_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void pci_allocate_vc_save_buffers(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vc.c (0)
Location: drivers/pci/vc.c:414
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
```
**Symbols:**

```
ffffffff81638203-ffffffff8163821b: pci_allocate_vc_save_buffers.cold (STB_LOCAL)
ffffffff81638080-ffffffff816380f5: pci_allocate_vc_save_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void pci_allocate_vc_save_buffers(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vc.c (0)
Location: drivers/pci/vc.c:413
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
```
**Symbols:**

```
ffffffff81bf8e6e-ffffffff81bf8e86: pci_allocate_vc_save_buffers.cold (STB_LOCAL)
ffffffff8165ca40-ffffffff8165cab6: pci_allocate_vc_save_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void pci_allocate_vc_save_buffers(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vc.c (0)
Location: drivers/pci/vc.c:413
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
```
**Symbols:**

```
ffffffff81beacc5-ffffffff81beacdd: pci_allocate_vc_save_buffers.cold (STB_LOCAL)
ffffffff8163efe0-ffffffff8163f056: pci_allocate_vc_save_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pci_allocate_vc_save_buffers(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vc.c (ffffffff816afc60)
Location: drivers/pci/vc.c:413
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
```
**Symbols:**

```
ffffffff816afc60-ffffffff816afd44: pci_allocate_vc_save_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pci_allocate_vc_save_buffers(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vc.c (ffffffff817d31a0)
Location: drivers/pci/vc.c:413
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
```
**Symbols:**

```
ffffffff817d31a0-ffffffff817d328b: pci_allocate_vc_save_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_allocate_vc_save_buffers(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vc.c (ffffffff818f3b30)
Location: drivers/pci/vc.c:413
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
```
**Symbols:**

```
ffffffff818f3b30-ffffffff818f3c25: pci_allocate_vc_save_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_allocate_vc_save_buffers(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vc.c (ffffffff81936f80)
Location: drivers/pci/vc.c:413
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
```
**Symbols:**

```
ffffffff81936f80-ffffffff81937075: pci_allocate_vc_save_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_allocate_vc_save_buffers(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vc.c (ffffffff8197fde0)
Location: drivers/pci/vc.c:414
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
```
**Symbols:**

```
ffffffff8197fde0-ffffffff8197fed5: pci_allocate_vc_save_buffers (STB_GLOBAL)
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
void pci_allocate_vc_save_buffers(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vc.c (ffff8000106f5740)
Location: drivers/pci/vc.c:414
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
```
**Symbols:**

```
ffff8000106f5740-ffff8000106f5814: pci_allocate_vc_save_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_allocate_vc_save_buffers(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vc.c (c08901ec)
Location: drivers/pci/vc.c:414
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
```
**Symbols:**

```
c08901ec-c0890280: pci_allocate_vc_save_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_allocate_vc_save_buffers(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vc.c (c0000000008743c0)
Location: drivers/pci/vc.c:414
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
```
**Symbols:**

```
c0000000008743c0-c0000000008744a4: pci_allocate_vc_save_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_allocate_vc_save_buffers(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vc.c (ffffffe0004c8644)
Location: drivers/pci/vc.c:414
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
```
**Symbols:**

```
ffffffe0004c8644-ffffffe0004c86e2: pci_allocate_vc_save_buffers (STB_GLOBAL)
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
void pci_allocate_vc_save_buffers(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vc.c (0)
Location: drivers/pci/vc.c:414
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
```
**Symbols:**

```
ffffffff81584542-ffffffff8158455a: pci_allocate_vc_save_buffers.cold (STB_LOCAL)
ffffffff815843c0-ffffffff81584425: pci_allocate_vc_save_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void pci_allocate_vc_save_buffers(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vc.c (0)
Location: drivers/pci/vc.c:414
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
```
**Symbols:**

```
ffffffff81573322-ffffffff8157333a: pci_allocate_vc_save_buffers.cold (STB_LOCAL)
ffffffff815731a0-ffffffff81573205: pci_allocate_vc_save_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void pci_allocate_vc_save_buffers(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vc.c (0)
Location: drivers/pci/vc.c:414
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
```
**Symbols:**

```
ffffffff81584412-ffffffff8158442a: pci_allocate_vc_save_buffers.cold (STB_LOCAL)
ffffffff81584290-ffffffff815842f5: pci_allocate_vc_save_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void pci_allocate_vc_save_buffers(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vc.c (0)
Location: drivers/pci/vc.c:414
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_allocate_cap_save_buffers
```
**Symbols:**

```
ffffffff8159e8c2-ffffffff8159e8da: pci_allocate_vc_save_buffers.cold (STB_LOCAL)
ffffffff8159e740-ffffffff8159e7a5: pci_allocate_vc_save_buffers (STB_GLOBAL)
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
