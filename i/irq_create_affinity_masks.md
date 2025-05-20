# Function: <code>irq_create_affinity_masks</code>

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
struct cpumask *irq_create_affinity_masks(int nvecs, const struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff810ef890)
Location: kernel/irq/affinity.c:60
Inline: False
Direct callers:
  - drivers/pci/msi.c:msi_setup_entry
```
**Symbols:**

```
ffffffff810ef890-ffffffff810efdc1: irq_create_affinity_masks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct cpumask *irq_create_affinity_masks(int nvecs, const struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff810ef6d0)
Location: kernel/irq/affinity.c:104
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:msi_setup_entry
```
**Symbols:**

```
ffffffff810ef6d0-ffffffff810efd79: irq_create_affinity_masks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct cpumask *irq_create_affinity_masks(int nvecs, const struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff810f82c0)
Location: kernel/irq/affinity.c:105
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:msi_setup_entry
```
**Symbols:**

```
ffffffff810f82c0-ffffffff810f8928: irq_create_affinity_masks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct cpumask *irq_create_affinity_masks(int nvecs, const struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff81100b00)
Location: kernel/irq/affinity.c:177
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:msi_setup_entry
```
**Symbols:**

```
ffffffff81100b00-ffffffff81100eb0: irq_create_affinity_masks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct irq_affinity_desc *irq_create_affinity_masks(int nvecs, const struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff8110c2b0)
Location: kernel/irq/affinity.c:235
Inline: False
Direct callers:
  - drivers/pci/msi.c:msi_setup_entry
```
**Symbols:**

```
ffffffff8110c2b0-ffffffff8110c778: irq_create_affinity_masks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct irq_affinity_desc *irq_create_affinity_masks(unsigned int nvecs, struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/affinity.c (0)
Location: kernel/irq/affinity.c:245
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:msi_setup_entry
```
**Symbols:**

```
ffffffff81115f08-ffffffff81115f1b: irq_create_affinity_masks.cold (STB_LOCAL)
ffffffff81115a40-ffffffff81115eae: irq_create_affinity_masks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct irq_affinity_desc *irq_create_affinity_masks(unsigned int nvecs, struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff81121e50)
Location: kernel/irq/affinity.c:416
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:msi_setup_entry
```
**Symbols:**

```
ffffffff81121e50-ffffffff81122289: irq_create_affinity_masks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct irq_affinity_desc *irq_create_affinity_masks(unsigned int nvecs, struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff8112e660)
Location: kernel/irq/affinity.c:416
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msi_setup_entry
```
**Symbols:**

```
ffffffff8112e660-ffffffff8112e8ad: irq_create_affinity_masks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct irq_affinity_desc *irq_create_affinity_masks(unsigned int nvecs, struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff8112a250)
Location: kernel/irq/affinity.c:416
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
```
**Symbols:**

```
ffffffff8112a250-ffffffff8112a49d: irq_create_affinity_masks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct irq_affinity_desc *irq_create_affinity_masks(unsigned int nvecs, struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff8112a4d0)
Location: kernel/irq/affinity.c:416
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msi_capability_init
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
```
**Symbols:**

```
ffffffff8112a4d0-ffffffff8112a714: irq_create_affinity_masks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct irq_affinity_desc *irq_create_affinity_masks(unsigned int nvecs, struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff8114ae60)
Location: kernel/irq/affinity.c:416
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
```
**Symbols:**

```
ffffffff8114ae60-ffffffff8114b0c5: irq_create_affinity_masks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct irq_affinity_desc *irq_create_affinity_masks(unsigned int nvecs, struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff811704d0)
Location: kernel/irq/affinity.c:417
Inline: False
Direct callers:
  - drivers/pci/msi/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi/msi.c:__pci_enable_msi_range
  - drivers/pci/msi/msi.c:msix_capability_init
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
```
**Symbols:**

```
ffffffff811704d0-ffffffff8117074f: irq_create_affinity_masks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct irq_affinity_desc *irq_create_affinity_masks(unsigned int nvecs, struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff811a6950)
Location: kernel/irq/affinity.c:417
Inline: False
Direct callers:
  - drivers/pci/msi/api.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:msi_capability_init
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
```
**Symbols:**

```
ffffffff811a6950-ffffffff811a6bcf: irq_create_affinity_masks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct irq_affinity_desc *irq_create_affinity_masks(unsigned int nvecs, struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/affinity.c (0)
Location: kernel/irq/affinity.c:26
Inline: False
Direct callers:
  - drivers/pci/msi/api.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:msi_capability_init
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
```
**Symbols:**

```
ffffffff820d8272-ffffffff820d82fb: irq_create_affinity_masks.cold (STB_LOCAL)
ffffffff811b8330-ffffffff811b873f: irq_create_affinity_masks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct irq_affinity_desc *irq_create_affinity_masks(unsigned int nvecs, struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/affinity.c (0)
Location: kernel/irq/affinity.c:26
Inline: False
Direct callers:
  - drivers/pci/msi/api.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:msi_capability_init
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
```
**Symbols:**

```
ffffffff821b34f3-ffffffff821b357c: irq_create_affinity_masks.cold (STB_LOCAL)
ffffffff811c81f0-ffffffff811c85ff: irq_create_affinity_masks (STB_GLOBAL)
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
struct irq_affinity_desc *irq_create_affinity_masks(unsigned int nvecs, struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffff800010188088)
Location: kernel/irq/affinity.c:416
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:msi_setup_entry
```
**Symbols:**

```
ffff800010188088-ffff800010188498: irq_create_affinity_masks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct irq_affinity_desc *irq_create_affinity_masks(unsigned int nvecs, struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (c03d6a60)
Location: kernel/irq/affinity.c:416
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
c03d6a60-c03d6e08: irq_create_affinity_masks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct irq_affinity_desc *irq_create_affinity_masks(unsigned int nvecs, struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (c0000000001e2190)
Location: kernel/irq/affinity.c:416
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:msi_setup_entry
```
**Symbols:**

```
c0000000001e2190-c0000000001e24e0: irq_create_affinity_masks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct irq_affinity_desc *irq_create_affinity_masks(unsigned int nvecs, struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffe00011d882)
Location: kernel/irq/affinity.c:416
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:msi_setup_entry
```
**Symbols:**

```
ffffffe00011d882-ffffffe00011db3a: irq_create_affinity_masks (STB_GLOBAL)
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
struct irq_affinity_desc *irq_create_affinity_masks(unsigned int nvecs, struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff8111a430)
Location: kernel/irq/affinity.c:416
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:msi_setup_entry
```
**Symbols:**

```
ffffffff8111a430-ffffffff8111a869: irq_create_affinity_masks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct irq_affinity_desc *irq_create_affinity_masks(unsigned int nvecs, struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff8110b4a0)
Location: kernel/irq/affinity.c:416
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:msi_setup_entry
```
**Symbols:**

```
ffffffff8110b4a0-ffffffff8110b8d9: irq_create_affinity_masks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct irq_affinity_desc *irq_create_affinity_masks(unsigned int nvecs, struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff81118320)
Location: kernel/irq/affinity.c:416
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:msi_setup_entry
```
**Symbols:**

```
ffffffff81118320-ffffffff81118759: irq_create_affinity_masks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct irq_affinity_desc *irq_create_affinity_masks(unsigned int nvecs, struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff811239b0)
Location: kernel/irq/affinity.c:416
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:msi_setup_entry
```
**Symbols:**

```
ffffffff811239b0-ffffffff81123de9: irq_create_affinity_masks (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>struct cpumask *</code> ➡️ <code>struct irq_affinity_desc *</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int nvecs</code> ➡️ <code>unsigned int nvecs</code>
</li>
<li>
<b>Param type changed. </b>
<code>const struct irq_affinity *affd</code> ➡️ <code>struct irq_affinity *affd</code>
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
