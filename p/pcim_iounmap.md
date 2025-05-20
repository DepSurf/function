# Function: <code>pcim_iounmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void pcim_iounmap(struct pci_dev *pdev, void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff81403150)
Location: lib/devres.c:308
Inline: True
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
```
**Symbols:**

```
ffffffff81403150-ffffffff814031a5: pcim_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void pcim_iounmap(struct pci_dev *pdev, void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff8144ad90)
Location: lib/devres.c:308
Inline: True
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
```
**Symbols:**

```
ffffffff8144ad90-ffffffff8144ade5: pcim_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void pcim_iounmap(struct pci_dev *pdev, void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff81469750)
Location: lib/devres.c:308
Inline: True
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
```
**Symbols:**

```
ffffffff81469750-ffffffff814697a5: pcim_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void pcim_iounmap(struct pci_dev *pdev, void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff8146ee30)
Location: lib/devres.c:308
Inline: True
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
```
**Symbols:**

```
ffffffff8146ee30-ffffffff8146ee76: pcim_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void pcim_iounmap(struct pci_dev *pdev, void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff8149b210)
Location: lib/devres.c:309
Inline: True
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
```
**Symbols:**

```
ffffffff8149b210-ffffffff8149b256: pcim_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void pcim_iounmap(struct pci_dev *pdev, void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff814d04b0)
Location: lib/devres.c:307
Inline: True
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
```
**Symbols:**

```
ffffffff814d04b0-ffffffff814d04f6: pcim_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void pcim_iounmap(struct pci_dev *pdev, void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff814e4de0)
Location: lib/devres.c:343
Inline: True
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
```
**Symbols:**

```
ffffffff814e4de0-ffffffff814e4e26: pcim_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pcim_iounmap(struct pci_dev *pdev, void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/devres.c (ffffffff81511a71)
Location: lib/devres.c:362
Inline: True
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
```
**Symbols:**

```
ffffffff81511a71-ffffffff81511a84: pcim_iounmap.cold (STB_LOCAL)
ffffffff81511760-ffffffff815117a5: pcim_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void pcim_iounmap(struct pci_dev *pdev, void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff815321e0)
Location: lib/devres.c:361
Inline: True
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
```
**Symbols:**

```
ffffffff815321e0-ffffffff81532226: pcim_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pcim_iounmap(struct pci_dev *pdev, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff815966d0)
Location: lib/devres.c:372
Inline: False
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
```
**Symbols:**

```
ffffffff815966d0-ffffffff81596716: pcim_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pcim_iounmap(struct pci_dev *pdev, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff815b2160)
Location: lib/devres.c:384
Inline: False
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
```
**Symbols:**

```
ffffffff815b2160-ffffffff815b21a6: pcim_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pcim_iounmap(struct pci_dev *pdev, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff815bcfa0)
Location: lib/devres.c:406
Inline: False
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
```
**Symbols:**

```
ffffffff815bcfa0-ffffffff815bcfe6: pcim_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pcim_iounmap(struct pci_dev *pdev, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff816242c0)
Location: lib/devres.c:408
Inline: False
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
```
**Symbols:**

```
ffffffff816242c0-ffffffff81624306: pcim_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pcim_iounmap(struct pci_dev *pdev, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff816f4750)
Location: lib/devres.c:408
Inline: False
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
```
**Symbols:**

```
ffffffff816f4750-ffffffff816f47ae: pcim_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pcim_iounmap(struct pci_dev *pdev, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff817e68e0)
Location: lib/devres.c:396
Inline: False
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
```
**Symbols:**

```
ffffffff817e68e0-ffffffff817e693e: pcim_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pcim_iounmap(struct pci_dev *pdev, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff81826910)
Location: lib/devres.c:396
Inline: False
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
```
**Symbols:**

```
ffffffff81826910-ffffffff8182696e: pcim_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pcim_iounmap(struct pci_dev *pdev, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff81878320)
Location: lib/devres.c:396
Inline: False
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
```
**Symbols:**

```
ffffffff81878320-ffffffff8187837e: pcim_iounmap (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void pcim_iounmap(struct pci_dev *pdev, void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffff80001063d9f8)
Location: lib/devres.c:361
Inline: True
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
```
**Symbols:**

```
ffff80001063d9f8-ffff80001063da50: pcim_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void pcim_iounmap(struct pci_dev *pdev, void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (c07e3ed4)
Location: lib/devres.c:361
Inline: True
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
```
**Symbols:**

```
c07e3ed4-c07e3f48: pcim_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pcim_iounmap(struct pci_dev *pdev, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (c0000000007e7c20)
Location: lib/devres.c:361
Inline: False
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
```
**Symbols:**

```
c0000000007e7c20-c0000000007e7cc0: pcim_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void pcim_iounmap(struct pci_dev *pdev, void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffe00046b758)
Location: lib/devres.c:361
Inline: True
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
```
**Symbols:**

```
ffffffe00046b758-ffffffe00046b79a: pcim_iounmap (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void pcim_iounmap(struct pci_dev *pdev, void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff8152a7c0)
Location: lib/devres.c:361
Inline: True
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
```
**Symbols:**

```
ffffffff8152a7c0-ffffffff8152a806: pcim_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void pcim_iounmap(struct pci_dev *pdev, void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff8151aaa0)
Location: lib/devres.c:361
Inline: True
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
```
**Symbols:**

```
ffffffff8151aaa0-ffffffff8151aae6: pcim_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void pcim_iounmap(struct pci_dev *pdev, void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff81526850)
Location: lib/devres.c:361
Inline: True
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
```
**Symbols:**

```
ffffffff81526850-ffffffff81526896: pcim_iounmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void pcim_iounmap(struct pci_dev *pdev, void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff815401d0)
Location: lib/devres.c:361
Inline: True
Direct callers:
  - lib/devres.c:pcim_iounmap_regions
  - lib/devres.c:pcim_iomap_regions
```
**Symbols:**

```
ffffffff815401d0-ffffffff81540216: pcim_iounmap (STB_GLOBAL)
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
