# Function: <code>pcim_iomap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void *pcim_iomap(struct pci_dev *pdev, int bar, long unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff81403210)
Location: lib/devres.c:286
Inline: True
Direct callers:
  - lib/devres.c:pcim_iomap_regions
```
**Symbols:**

```
ffffffff81403210-ffffffff81403260: pcim_iomap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void *pcim_iomap(struct pci_dev *pdev, int bar, long unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff8144ae50)
Location: lib/devres.c:286
Inline: True
Direct callers:
  - lib/devres.c:pcim_iomap_regions
```
**Symbols:**

```
ffffffff8144ae50-ffffffff8144aea0: pcim_iomap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void *pcim_iomap(struct pci_dev *pdev, int bar, long unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff81469810)
Location: lib/devres.c:286
Inline: True
Direct callers:
  - lib/devres.c:pcim_iomap_regions
```
**Symbols:**

```
ffffffff81469810-ffffffff81469860: pcim_iomap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void *pcim_iomap(struct pci_dev *pdev, int bar, long unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff8146eed0)
Location: lib/devres.c:286
Inline: True
Direct callers:
  - lib/devres.c:pcim_iomap_regions
```
**Symbols:**

```
ffffffff8146eed0-ffffffff8146ef20: pcim_iomap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void *pcim_iomap(struct pci_dev *pdev, int bar, long unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff8149b2b0)
Location: lib/devres.c:287
Inline: True
Direct callers:
  - lib/devres.c:pcim_iomap_regions
```
**Symbols:**

```
ffffffff8149b2b0-ffffffff8149b300: pcim_iomap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void *pcim_iomap(struct pci_dev *pdev, int bar, long unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff814d0550)
Location: lib/devres.c:285
Inline: True
Direct callers:
  - lib/devres.c:pcim_iomap_regions
```
**Symbols:**

```
ffffffff814d0550-ffffffff814d05a0: pcim_iomap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void *pcim_iomap(struct pci_dev *pdev, int bar, long unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff814e4e80)
Location: lib/devres.c:321
Inline: True
Direct callers:
  - lib/devres.c:pcim_iomap_regions
```
**Symbols:**

```
ffffffff814e4e80-ffffffff814e4ecc: pcim_iomap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void *pcim_iomap(struct pci_dev *pdev, int bar, long unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff81511800)
Location: lib/devres.c:340
Inline: True
Direct callers:
  - lib/devres.c:pcim_iomap_regions
```
**Symbols:**

```
ffffffff81511800-ffffffff8151184e: pcim_iomap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void *pcim_iomap(struct pci_dev *pdev, int bar, long unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff81532280)
Location: lib/devres.c:339
Inline: True
Direct callers:
  - lib/devres.c:pcim_iomap_regions
```
**Symbols:**

```
ffffffff81532280-ffffffff815322ce: pcim_iomap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void *pcim_iomap(struct pci_dev *pdev, int bar, long unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff815967c0)
Location: lib/devres.c:350
Inline: True
Direct callers:
  - lib/devres.c:pcim_iomap_regions
  - drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_setup
```
**Symbols:**

```
ffffffff815967c0-ffffffff8159680e: pcim_iomap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void *pcim_iomap(struct pci_dev *pdev, int bar, long unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff815b2250)
Location: lib/devres.c:362
Inline: True
Direct callers:
  - lib/devres.c:pcim_iomap_regions
  - drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_setup
```
**Symbols:**

```
ffffffff815b2250-ffffffff815b229e: pcim_iomap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void *pcim_iomap(struct pci_dev *pdev, int bar, long unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff815bd0a0)
Location: lib/devres.c:384
Inline: True
Direct callers:
  - lib/devres.c:pcim_iomap_regions
  - drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_setup
```
**Symbols:**

```
ffffffff815bd0a0-ffffffff815bd0ee: pcim_iomap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void *pcim_iomap(struct pci_dev *pdev, int bar, long unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff81624457)
Location: lib/devres.c:386
Inline: True
Inline callers:
  - lib/devres.c:pcim_iomap_regions
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_setup
```
**Symbols:**

```
ffffffff81624310-ffffffff8162435e: pcim_iomap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void *pcim_iomap(struct pci_dev *pdev, int bar, long unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff816f4ac0)
Location: lib/devres.c:386
Inline: True
Inline callers:
  - lib/devres.c:pcim_iomap_regions
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_setup
```
**Symbols:**

```
ffffffff816f47b0-ffffffff816f4806: pcim_iomap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void *pcim_iomap(struct pci_dev *pdev, int bar, long unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff817e6cd0)
Location: lib/devres.c:374
Inline: True
Inline callers:
  - lib/devres.c:pcim_iomap_regions
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_setup
  - drivers/tty/serial/8250/8250_mid.c:mid8250_probe
```
**Symbols:**

```
ffffffff817e6950-ffffffff817e69a6: pcim_iomap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void *pcim_iomap(struct pci_dev *pdev, int bar, long unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff81826d00)
Location: lib/devres.c:374
Inline: True
Inline callers:
  - lib/devres.c:pcim_iomap_regions
Direct callers:
  - drivers/tty/serial/8250/8250_pcilib.c:serial8250_pci_setup_port
  - drivers/tty/serial/8250/8250_mid.c:mid8250_probe
```
**Symbols:**

```
ffffffff81826980-ffffffff818269d6: pcim_iomap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void *pcim_iomap(struct pci_dev *pdev, int bar, long unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff81878710)
Location: lib/devres.c:374
Inline: True
Inline callers:
  - lib/devres.c:pcim_iomap_regions
Direct callers:
  - drivers/tty/serial/8250/8250_pcilib.c:serial8250_pci_setup_port
  - drivers/tty/serial/8250/8250_mid.c:mid8250_probe
```
**Symbols:**

```
ffffffff81878390-ffffffff818783e6: pcim_iomap (STB_GLOBAL)
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
void *pcim_iomap(struct pci_dev *pdev, int bar, long unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffff80001063dab8)
Location: lib/devres.c:339
Inline: True
Direct callers:
  - lib/devres.c:pcim_iomap_regions
```
**Symbols:**

```
ffff80001063dab8-ffff80001063db1c: pcim_iomap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void *pcim_iomap(struct pci_dev *pdev, int bar, long unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (c07e3fa0)
Location: lib/devres.c:339
Inline: True
Direct callers:
  - lib/devres.c:pcim_iomap_regions
  - drivers/tty/serial/8250/8250_pci.c:setup_port
```
**Symbols:**

```
c07e3fa0-c07e4000: pcim_iomap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *pcim_iomap(struct pci_dev *pdev, int bar, long unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (c0000000007e7cc0)
Location: lib/devres.c:339
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_regions
```
**Symbols:**

```
c0000000007e7cc0-c0000000007e7d80: pcim_iomap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void *pcim_iomap(struct pci_dev *pdev, int bar, long unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffe00046b808)
Location: lib/devres.c:339
Inline: True
Direct callers:
  - lib/devres.c:pcim_iomap_regions
```
**Symbols:**

```
ffffffe00046b808-ffffffe00046b860: pcim_iomap (STB_GLOBAL)
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
void *pcim_iomap(struct pci_dev *pdev, int bar, long unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff8152a860)
Location: lib/devres.c:339
Inline: True
Direct callers:
  - lib/devres.c:pcim_iomap_regions
```
**Symbols:**

```
ffffffff8152a860-ffffffff8152a8ae: pcim_iomap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void *pcim_iomap(struct pci_dev *pdev, int bar, long unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff8151ab40)
Location: lib/devres.c:339
Inline: True
Direct callers:
  - lib/devres.c:pcim_iomap_regions
```
**Symbols:**

```
ffffffff8151ab40-ffffffff8151ab8e: pcim_iomap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void *pcim_iomap(struct pci_dev *pdev, int bar, long unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff815268f0)
Location: lib/devres.c:339
Inline: True
Direct callers:
  - lib/devres.c:pcim_iomap_regions
```
**Symbols:**

```
ffffffff815268f0-ffffffff8152693e: pcim_iomap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void *pcim_iomap(struct pci_dev *pdev, int bar, long unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff81540270)
Location: lib/devres.c:339
Inline: True
Direct callers:
  - lib/devres.c:pcim_iomap_regions
```
**Symbols:**

```
ffffffff81540270-ffffffff815402be: pcim_iomap (STB_GLOBAL)
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
