# Function: <code>irq_calc_affinity_vectors</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int irq_calc_affinity_vectors(int maxvec, const struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff810efdd0)
Location: kernel/irq/affinity.c:144
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff810efdd0-ffffffff810efe1c: irq_calc_affinity_vectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int irq_calc_affinity_vectors(int minvec, int maxvec, const struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff810efd80)
Location: kernel/irq/affinity.c:206
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff810efd80-ffffffff810efdd6: irq_calc_affinity_vectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int irq_calc_affinity_vectors(int minvec, int maxvec, const struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff810f8930)
Location: kernel/irq/affinity.c:207
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff810f8930-ffffffff810f8986: irq_calc_affinity_vectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int irq_calc_affinity_vectors(int minvec, int maxvec, const struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff81100eb0)
Location: kernel/irq/affinity.c:257
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff81100eb0-ffffffff81100efd: irq_calc_affinity_vectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int irq_calc_affinity_vectors(int minvec, int maxvec, const struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff8110c780)
Location: kernel/irq/affinity.c:307
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff8110c780-ffffffff8110c812: irq_calc_affinity_vectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int irq_calc_affinity_vectors(unsigned int minvec, unsigned int maxvec, const struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff81115eb0)
Location: kernel/irq/affinity.c:325
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff81115eb0-ffffffff81115f08: irq_calc_affinity_vectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int irq_calc_affinity_vectors(unsigned int minvec, unsigned int maxvec, const struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff81122290)
Location: kernel/irq/affinity.c:496
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff81122290-ffffffff811222e8: irq_calc_affinity_vectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int irq_calc_affinity_vectors(unsigned int minvec, unsigned int maxvec, const struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff8112e8b0)
Location: kernel/irq/affinity.c:496
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff8112e8b0-ffffffff8112e908: irq_calc_affinity_vectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int irq_calc_affinity_vectors(unsigned int minvec, unsigned int maxvec, const struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff8112a4a0)
Location: kernel/irq/affinity.c:496
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
```
**Symbols:**

```
ffffffff8112a4a0-ffffffff8112a4f8: irq_calc_affinity_vectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int irq_calc_affinity_vectors(unsigned int minvec, unsigned int maxvec, const struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff8112a720)
Location: kernel/irq/affinity.c:496
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
```
**Symbols:**

```
ffffffff8112a720-ffffffff8112a778: irq_calc_affinity_vectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int irq_calc_affinity_vectors(unsigned int minvec, unsigned int maxvec, const struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff8114b0d0)
Location: kernel/irq/affinity.c:496
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
```
**Symbols:**

```
ffffffff8114b0d0-ffffffff8114b128: irq_calc_affinity_vectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int irq_calc_affinity_vectors(unsigned int minvec, unsigned int maxvec, const struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff81170750)
Location: kernel/irq/affinity.c:497
Inline: False
Direct callers:
  - drivers/pci/msi/msi.c:__pci_enable_msi_range
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
```
**Symbols:**

```
ffffffff81170750-ffffffff811707b3: irq_calc_affinity_vectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int irq_calc_affinity_vectors(unsigned int minvec, unsigned int maxvec, const struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff811a6be0)
Location: kernel/irq/affinity.c:497
Inline: False
Direct callers:
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:__pci_enable_msi_range
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
```
**Symbols:**

```
ffffffff811a6be0-ffffffff811a6c43: irq_calc_affinity_vectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int irq_calc_affinity_vectors(unsigned int minvec, unsigned int maxvec, const struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff811b8750)
Location: kernel/irq/affinity.c:110
Inline: False
Direct callers:
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:__pci_enable_msi_range
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
```
**Symbols:**

```
ffffffff811b8750-ffffffff811b87ac: irq_calc_affinity_vectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int irq_calc_affinity_vectors(unsigned int minvec, unsigned int maxvec, const struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff811c8610)
Location: kernel/irq/affinity.c:110
Inline: False
Direct callers:
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:__pci_enable_msi_range
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
```
**Symbols:**

```
ffffffff811c8610-ffffffff811c866c: irq_calc_affinity_vectors (STB_GLOBAL)
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
unsigned int irq_calc_affinity_vectors(unsigned int minvec, unsigned int maxvec, const struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffff800010188498)
Location: kernel/irq/affinity.c:496
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffff800010188498-ffff80001018851c: irq_calc_affinity_vectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int irq_calc_affinity_vectors(unsigned int minvec, unsigned int maxvec, const struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (c03d6e08)
Location: kernel/irq/affinity.c:496
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
c03d6e08-c03d6e80: irq_calc_affinity_vectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int irq_calc_affinity_vectors(unsigned int minvec, unsigned int maxvec, const struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (c0000000001e24e0)
Location: kernel/irq/affinity.c:496
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
c0000000001e24e0-c0000000001e25b0: irq_calc_affinity_vectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int irq_calc_affinity_vectors(unsigned int minvec, unsigned int maxvec, const struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffe00011db3a)
Location: kernel/irq/affinity.c:496
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffe00011db3a-ffffffe00011dbae: irq_calc_affinity_vectors (STB_GLOBAL)
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
unsigned int irq_calc_affinity_vectors(unsigned int minvec, unsigned int maxvec, const struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff8111a870)
Location: kernel/irq/affinity.c:496
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff8111a870-ffffffff8111a8c8: irq_calc_affinity_vectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int irq_calc_affinity_vectors(unsigned int minvec, unsigned int maxvec, const struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff8110b8e0)
Location: kernel/irq/affinity.c:496
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff8110b8e0-ffffffff8110b938: irq_calc_affinity_vectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int irq_calc_affinity_vectors(unsigned int minvec, unsigned int maxvec, const struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff81118760)
Location: kernel/irq/affinity.c:496
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff81118760-ffffffff811187b8: irq_calc_affinity_vectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int irq_calc_affinity_vectors(unsigned int minvec, unsigned int maxvec, const struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff81123df0)
Location: kernel/irq/affinity.c:496
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff81123df0-ffffffff81123e48: irq_calc_affinity_vectors (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int minvec</code>
</li>
<li>
<b>Param reordered. </b>
<code>maxvec, affd</code> ➡️ <code>minvec, maxvec, affd</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int minvec</code> ➡️ <code>unsigned int minvec</code>
</li>
<li>
<b>Param type changed. </b>
<code>int maxvec</code> ➡️ <code>unsigned int maxvec</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>unsigned int</code>
</li>
</ul>
</details>
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
