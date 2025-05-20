# Function: <code>pci_msi_supported</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int pci_msi_supported(struct pci_dev *dev, int nvec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81453b50)
Location: drivers/pci/msi.c:818
Inline: True
Direct callers:
  - drivers/pci/msi.c:pci_enable_msi_range
```
**Symbols:**

```
ffffffff81453b50-ffffffff81453baf: pci_msi_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int pci_msi_supported(struct pci_dev *dev, int nvec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814a0460)
Location: drivers/pci/msi.c:832
Inline: True
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff814a0460-ffffffff814a04c2: pci_msi_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int pci_msi_supported(struct pci_dev *dev, int nvec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814c2010)
Location: drivers/pci/msi.c:846
Inline: True
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff814c2010-ffffffff814c2072: pci_msi_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int pci_msi_supported(struct pci_dev *dev, int nvec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814cc550)
Location: drivers/pci/msi.c:822
Inline: True
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msix
```
**Symbols:**

```
ffffffff814cc550-ffffffff814cc5b2: pci_msi_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int pci_msi_supported(struct pci_dev *dev, int nvec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8150ca80)
Location: drivers/pci/msi.c:822
Inline: True
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msix
```
**Symbols:**

```
ffffffff8150ca80-ffffffff8150cae2: pci_msi_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int pci_msi_supported(struct pci_dev *dev, int nvec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff815418d0)
Location: drivers/pci/msi.c:822
Inline: True
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msix
```
**Symbols:**

```
ffffffff815418d0-ffffffff81541932: pci_msi_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int pci_msi_supported(struct pci_dev *dev, int nvec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81558c20)
Location: drivers/pci/msi.c:821
Inline: True
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff81558c20-ffffffff81558c82: pci_msi_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int pci_msi_supported(struct pci_dev *dev, int nvec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81588cd0)
Location: drivers/pci/msi.c:856
Inline: True
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff81588cd0-ffffffff81588d29: pci_msi_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int pci_msi_supported(struct pci_dev *dev, int nvec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff815aa5f0)
Location: drivers/pci/msi.c:857
Inline: True
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff815aa5f0-ffffffff815aa649: pci_msi_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8165402a)
Location: drivers/pci/msi.c:857
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8165e47a)
Location: drivers/pci/msi.c:881
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8164089a)
Location: drivers/pci/msi.c:883
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff816b159e)
Location: drivers/pci/msi.c:793
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:pci_enable_msix_range
  - drivers/pci/msi.c:pci_enable_msix_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff817d402f)
Location: drivers/pci/msi/msi.c:670
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:__pci_enable_msi_range
  - drivers/pci/msi/msi.c:__pci_enable_msi_range
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff818f5c4c)
Location: drivers/pci/msi/msi.c:28
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:__pci_enable_msi_range
  - drivers/pci/msi/msi.c:__pci_enable_msi_range
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff8193907c)
Location: drivers/pci/msi/msi.c:28
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:__pci_enable_msi_range
  - drivers/pci/msi/msi.c:__pci_enable_msi_range
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff81981edc)
Location: drivers/pci/msi/msi.c:29
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:__pci_enable_msi_range
  - drivers/pci/msi/msi.c:__pci_enable_msi_range
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
int pci_msi_supported(struct pci_dev *dev, int nvec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffff800010713bb0)
Location: drivers/pci/msi.c:857
Inline: True
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffff800010713bb0-ffff800010713c3c: pci_msi_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int pci_msi_supported(struct pci_dev *dev, int nvec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (c089e79c)
Location: drivers/pci/msi.c:857
Inline: True
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
c089e79c-c089e83c: pci_msi_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int pci_msi_supported(struct pci_dev *dev, int nvec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (c000000000883530)
Location: drivers/pci/msi.c:857
Inline: True
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
c000000000883530-c0000000008835c8: pci_msi_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int pci_msi_supported(struct pci_dev *dev, int nvec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffe0004dd716)
Location: drivers/pci/msi.c:857
Inline: True
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffe0004dd716-ffffffe0004dd782: pci_msi_supported (STB_LOCAL)
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
int pci_msi_supported(struct pci_dev *dev, int nvec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8159ddc0)
Location: drivers/pci/msi.c:857
Inline: True
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff8159ddc0-ffffffff8159de19: pci_msi_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int pci_msi_supported(struct pci_dev *dev, int nvec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8158cf50)
Location: drivers/pci/msi.c:857
Inline: True
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff8158cf50-ffffffff8158cfa9: pci_msi_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int pci_msi_supported(struct pci_dev *dev, int nvec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8159e340)
Location: drivers/pci/msi.c:857
Inline: True
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff8159e340-ffffffff8159e399: pci_msi_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int pci_msi_supported(struct pci_dev *dev, int nvec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff815b8770)
Location: drivers/pci/msi.c:857
Inline: True
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff815b8770-ffffffff815b87c9: pci_msi_supported (STB_LOCAL)
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
