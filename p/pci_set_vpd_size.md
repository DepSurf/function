# Function: <code>pci_set_vpd_size</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int pci_set_vpd_size(struct pci_dev *dev, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81479568)
Location: drivers/pci/access.c:283
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_vpd_f0_set_size
```
**Symbols:**

```
ffffffff814792e0-ffffffff81479308: pci_set_vpd_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int pci_set_vpd_size(struct pci_dev *dev, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8149a9f8)
Location: drivers/pci/access.c:295
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_vpd_f0_set_size
Direct callers:
  - drivers/pci/quirks.c:quirk_chelsio_extend_vpd
```
**Symbols:**

```
ffffffff8149a670-ffffffff8149a698: pci_set_vpd_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int pci_set_vpd_size(struct pci_dev *dev, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814a4678)
Location: drivers/pci/access.c:303
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_vpd_f0_set_size
Direct callers:
  - drivers/pci/quirks.c:quirk_chelsio_extend_vpd
```
**Symbols:**

```
ffffffff814a4210-ffffffff814a4238: pci_set_vpd_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int pci_set_vpd_size(struct pci_dev *dev, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814e3428)
Location: drivers/pci/access.c:303
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_vpd_f0_set_size
Direct callers:
  - drivers/pci/quirks.c:quirk_chelsio_extend_vpd
  - drivers/pci/quirks.c:quirk_chelsio_extend_vpd
```
**Symbols:**

```
ffffffff814e2f90-ffffffff814e2fbe: pci_set_vpd_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int pci_set_vpd_size(struct pci_dev *dev, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff81525a79)
Location: drivers/pci/vpd.c:68
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_f0_set_size
```
**Symbols:**

```
ffffffff815251b0-ffffffff815251de: pci_set_vpd_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int pci_set_vpd_size(struct pci_dev *dev, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff8153b909)
Location: drivers/pci/vpd.c:68
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_f0_set_size
```
**Symbols:**

```
ffffffff8153b040-ffffffff8153b06e: pci_set_vpd_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int pci_set_vpd_size(struct pci_dev *dev, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff8156b2ca)
Location: drivers/pci/vpd.c:68
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_f0_set_size
```
**Symbols:**

```
ffffffff8156aad0-ffffffff8156aafe: pci_set_vpd_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int pci_set_vpd_size(struct pci_dev *dev, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff8158c29a)
Location: drivers/pci/vpd.c:68
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_f0_set_size
```
**Symbols:**

```
ffffffff8158baa0-ffffffff8158bace: pci_set_vpd_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int pci_set_vpd_size(struct pci_dev *dev, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff81633549)
Location: drivers/pci/vpd.c:68
Inline: True
Inline callers:
  - drivers/pci/vpd.c:quirk_chelsio_extend_vpd
  - drivers/pci/vpd.c:quirk_chelsio_extend_vpd
  - drivers/pci/vpd.c:pci_vpd_f0_set_size
```
**Symbols:**

```
ffffffff81632b40-ffffffff81632b6e: pci_set_vpd_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int pci_set_vpd_size(struct pci_dev *dev, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff81658699)
Location: drivers/pci/vpd.c:68
Inline: True
Inline callers:
  - drivers/pci/vpd.c:quirk_chelsio_extend_vpd
  - drivers/pci/vpd.c:quirk_chelsio_extend_vpd
  - drivers/pci/vpd.c:pci_vpd_f0_set_size
```
**Symbols:**

```
ffffffff81657c90-ffffffff81657cbe: pci_set_vpd_size (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int pci_set_vpd_size(struct pci_dev *dev, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffff8000106f1384)
Location: drivers/pci/vpd.c:68
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_f0_set_size
```
**Symbols:**

```
ffff8000106f0938-ffff8000106f0988: pci_set_vpd_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int pci_set_vpd_size(struct pci_dev *dev, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (c088be5c)
Location: drivers/pci/vpd.c:68
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_f0_set_size
```
**Symbols:**

```
c088b3a8-c088b3e8: pci_set_vpd_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int pci_set_vpd_size(struct pci_dev *dev, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (c00000000086ed18)
Location: drivers/pci/vpd.c:68
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_f0_set_size
```
**Symbols:**

```
c00000000086dfa0-c00000000086e000: pci_set_vpd_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int pci_set_vpd_size(struct pci_dev *dev, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffe0004c4c78)
Location: drivers/pci/vpd.c:68
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_f0_set_size
```
**Symbols:**

```
ffffffe0004c43f2-ffffffe0004c4432: pci_set_vpd_size (STB_GLOBAL)
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
int pci_set_vpd_size(struct pci_dev *dev, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff8158011a)
Location: drivers/pci/vpd.c:68
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_f0_set_size
```
**Symbols:**

```
ffffffff8157f920-ffffffff8157f94e: pci_set_vpd_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int pci_set_vpd_size(struct pci_dev *dev, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff8156eefa)
Location: drivers/pci/vpd.c:68
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_f0_set_size
```
**Symbols:**

```
ffffffff8156e700-ffffffff8156e72e: pci_set_vpd_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int pci_set_vpd_size(struct pci_dev *dev, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff8157ffea)
Location: drivers/pci/vpd.c:68
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_f0_set_size
```
**Symbols:**

```
ffffffff8157f7f0-ffffffff8157f81e: pci_set_vpd_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int pci_set_vpd_size(struct pci_dev *dev, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff8159a49a)
Location: drivers/pci/vpd.c:68
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_f0_set_size
```
**Symbols:**

```
ffffffff81599ca0-ffffffff81599cce: pci_set_vpd_size (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
