# Function: <code>pcim_iomap_regions</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pcim_iomap_regions(struct pci_dev *pdev, int mask, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff81403260)
Location: lib/devres.c:335
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/gpio/gpio-intel-mid.c:intel_gpio_probe
  - drivers/ata/libata-sff.c:ata_pci_sff_init_host
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/ata_piix.c:piix_init_one
```
**Symbols:**

```
ffffffff81403260-ffffffff81403347: pcim_iomap_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pcim_iomap_regions(struct pci_dev *pdev, int mask, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff8144aea0)
Location: lib/devres.c:335
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_sff_init_host
  - drivers/ata/ata_piix.c:piix_init_one
```
**Symbols:**

```
ffffffff8144aea0-ffffffff8144af87: pcim_iomap_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pcim_iomap_regions(struct pci_dev *pdev, int mask, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff81469860)
Location: lib/devres.c:335
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_sff_init_host
  - drivers/ata/ata_piix.c:piix_init_one
```
**Symbols:**

```
ffffffff81469860-ffffffff81469947: pcim_iomap_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pcim_iomap_regions(struct pci_dev *pdev, int mask, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff8146ef20)
Location: lib/devres.c:335
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_sff_init_host
  - drivers/ata/ata_piix.c:piix_init_one
```
**Symbols:**

```
ffffffff8146ef20-ffffffff8146f030: pcim_iomap_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pcim_iomap_regions(struct pci_dev *pdev, int mask, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff8149b300)
Location: lib/devres.c:336
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_sff_init_host
  - drivers/ata/ata_piix.c:piix_init_one
```
**Symbols:**

```
ffffffff8149b300-ffffffff8149b410: pcim_iomap_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pcim_iomap_regions(struct pci_dev *pdev, int mask, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff814d05a0)
Location: lib/devres.c:334
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_sff_init_host
  - drivers/ata/ata_piix.c:piix_init_one
```
**Symbols:**

```
ffffffff814d05a0-ffffffff814d06b5: pcim_iomap_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pcim_iomap_regions(struct pci_dev *pdev, int mask, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff814e4ed0)
Location: lib/devres.c:370
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_sff_init_host
  - drivers/ata/ata_piix.c:piix_init_one
```
**Symbols:**

```
ffffffff814e4ed0-ffffffff814e4fe5: pcim_iomap_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pcim_iomap_regions(struct pci_dev *pdev, int mask, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff81511850)
Location: lib/devres.c:389
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_sff_init_host
  - drivers/ata/ata_piix.c:piix_init_one
```
**Symbols:**

```
ffffffff81511850-ffffffff81511965: pcim_iomap_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pcim_iomap_regions(struct pci_dev *pdev, int mask, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff815322d0)
Location: lib/devres.c:388
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_sff_init_host
  - drivers/ata/ata_piix.c:piix_init_one
```
**Symbols:**

```
ffffffff815322d0-ffffffff815323e5: pcim_iomap_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pcim_iomap_regions(struct pci_dev *pdev, int mask, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff81596810)
Location: lib/devres.c:399
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_sff_init_host
  - drivers/ata/ata_piix.c:piix_init_sidpr
```
**Symbols:**

```
ffffffff81596810-ffffffff8159690f: pcim_iomap_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pcim_iomap_regions(struct pci_dev *pdev, int mask, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff815b22a0)
Location: lib/devres.c:411
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_sff_init_host
  - drivers/ata/ata_piix.c:piix_init_sidpr
```
**Symbols:**

```
ffffffff815b22a0-ffffffff815b239f: pcim_iomap_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pcim_iomap_regions(struct pci_dev *pdev, int mask, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff815bd0f0)
Location: lib/devres.c:433
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_sff_init_host
  - drivers/ata/ata_piix.c:piix_init_sidpr
```
**Symbols:**

```
ffffffff815bd0f0-ffffffff815bd1ef: pcim_iomap_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pcim_iomap_regions(struct pci_dev *pdev, int mask, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff816243d0)
Location: lib/devres.c:435
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_sff_init_host
  - drivers/ata/ata_piix.c:piix_init_sidpr
```
**Symbols:**

```
ffffffff816243d0-ffffffff8162458d: pcim_iomap_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pcim_iomap_regions(struct pci_dev *pdev, int mask, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff816f4a30)
Location: lib/devres.c:435
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_sff_init_host
  - drivers/ata/ata_piix.c:piix_init_sidpr
```
**Symbols:**

```
ffffffff816f4a30-ffffffff816f4c13: pcim_iomap_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pcim_iomap_regions(struct pci_dev *pdev, int mask, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff817e6c40)
Location: lib/devres.c:423
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_sff_init_host
  - drivers/ata/ata_piix.c:piix_init_sidpr
```
**Symbols:**

```
ffffffff817e6c40-ffffffff817e6e23: pcim_iomap_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pcim_iomap_regions(struct pci_dev *pdev, int mask, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff81826c70)
Location: lib/devres.c:423
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_sff_init_host
  - drivers/ata/ata_piix.c:piix_init_sidpr
```
**Symbols:**

```
ffffffff81826c70-ffffffff81826e2d: pcim_iomap_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pcim_iomap_regions(struct pci_dev *pdev, int mask, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff81878680)
Location: lib/devres.c:423
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_sff_init_host
  - drivers/ata/ata_piix.c:piix_init_sidpr
```
**Symbols:**

```
ffffffff81878680-ffffffff8187883d: pcim_iomap_regions (STB_GLOBAL)
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
int pcim_iomap_regions(struct pci_dev *pdev, int mask, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffff80001063db20)
Location: lib/devres.c:388
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_sff_init_host
```
**Symbols:**

```
ffff80001063db20-ffff80001063dc54: pcim_iomap_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pcim_iomap_regions(struct pci_dev *pdev, int mask, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (c07e4000)
Location: lib/devres.c:388
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_sff_init_host
```
**Symbols:**

```
c07e4000-c07e4104: pcim_iomap_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pcim_iomap_regions(struct pci_dev *pdev, int mask, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (c0000000007e7d80)
Location: lib/devres.c:388
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_sff_init_host
```
**Symbols:**

```
c0000000007e7d80-c0000000007e7f30: pcim_iomap_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pcim_iomap_regions(struct pci_dev *pdev, int mask, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffe00046b860)
Location: lib/devres.c:388
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_sff_init_host
```
**Symbols:**

```
ffffffe00046b860-ffffffe00046b950: pcim_iomap_regions (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int pcim_iomap_regions(struct pci_dev *pdev, int mask, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff8152a8b0)
Location: lib/devres.c:388
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_sff_init_host
  - drivers/ata/ata_piix.c:piix_init_one
```
**Symbols:**

```
ffffffff8152a8b0-ffffffff8152a9c5: pcim_iomap_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pcim_iomap_regions(struct pci_dev *pdev, int mask, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff8151ab90)
Location: lib/devres.c:388
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_sff_init_host
  - drivers/ata/ata_piix.c:piix_init_one
```
**Symbols:**

```
ffffffff8151ab90-ffffffff8151aca5: pcim_iomap_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pcim_iomap_regions(struct pci_dev *pdev, int mask, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff81526940)
Location: lib/devres.c:388
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_sff_init_host
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/i2c/busses/i2c-amd-mp2-pci.c:amd_mp2_pci_probe
```
**Symbols:**

```
ffffffff81526940-ffffffff81526a55: pcim_iomap_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pcim_iomap_regions(struct pci_dev *pdev, int mask, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff815402c0)
Location: lib/devres.c:388
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_regions_request_all
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_pci_sff_init_host
  - drivers/ata/ata_piix.c:piix_init_one
```
**Symbols:**

```
ffffffff815402c0-ffffffff815403d5: pcim_iomap_regions (STB_GLOBAL)
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
