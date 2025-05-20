# Function: <code>alloc_msi_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct msi_desc *alloc_msi_entry(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff810e2e20)
Location: kernel/irq/msi.c:21
Inline: False
Direct callers:
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff810e2e20-ffffffff810e2e56: alloc_msi_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct msi_desc *alloc_msi_entry(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff810e88c0)
Location: kernel/irq/msi.c:21
Inline: False
Direct callers:
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq
```
**Symbols:**

```
ffffffff810e88c0-ffffffff810e88f6: alloc_msi_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct msi_desc *alloc_msi_entry(struct device *dev, int nvec, const struct cpumask *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff810ef2f0)
Location: kernel/irq/msi.c:29
Inline: False
Direct callers:
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq
```
**Symbols:**

```
ffffffff810ef2f0-ffffffff810ef370: alloc_msi_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct msi_desc *alloc_msi_entry(struct device *dev, int nvec, const struct cpumask *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff810ef100)
Location: kernel/irq/msi.c:29
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq
```
**Symbols:**

```
ffffffff810ef100-ffffffff810ef180: alloc_msi_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct msi_desc *alloc_msi_entry(struct device *dev, int nvec, const struct cpumask *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff810f7bf0)
Location: kernel/irq/msi.c:31
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq
```
**Symbols:**

```
ffffffff810f7bf0-ffffffff810f7c70: alloc_msi_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct msi_desc *alloc_msi_entry(struct device *dev, int nvec, const struct cpumask *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff810fffe0)
Location: kernel/irq/msi.c:30
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq
```
**Symbols:**

```
ffffffff810fffe0-ffffffff81100060: alloc_msi_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct msi_desc *alloc_msi_entry(struct device *dev, int nvec, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff8110b7a0)
Location: kernel/irq/msi.c:29
Inline: False
Direct callers:
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq
```
**Symbols:**

```
ffffffff8110b7a0-ffffffff8110b82b: alloc_msi_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct msi_desc *alloc_msi_entry(struct device *dev, int nvec, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff81114e90)
Location: kernel/irq/msi.c:29
Inline: False
Direct callers:
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq
```
**Symbols:**

```
ffffffff81114e90-ffffffff81114f1e: alloc_msi_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct msi_desc *alloc_msi_entry(struct device *dev, int nvec, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff81121080)
Location: kernel/irq/msi.c:29
Inline: False
Direct callers:
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq
```
**Symbols:**

```
ffffffff81121080-ffffffff8112110e: alloc_msi_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct msi_desc *alloc_msi_entry(struct device *dev, int nvec, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff8112d660)
Location: kernel/irq/msi.c:29
Inline: False
Direct callers:
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq
```
**Symbols:**

```
ffffffff8112d660-ffffffff8112d6ee: alloc_msi_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct msi_desc *alloc_msi_entry(struct device *dev, int nvec, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff81129170)
Location: kernel/irq/msi.c:29
Inline: False
Direct callers:
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq
```
**Symbols:**

```
ffffffff81129170-ffffffff811291fe: alloc_msi_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct msi_desc *alloc_msi_entry(struct device *dev, int nvec, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff81129450)
Location: kernel/irq/msi.c:29
Inline: False
Direct callers:
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msi_capability_init
  - drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq
```
**Symbols:**

```
ffffffff81129450-ffffffff811294da: alloc_msi_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct msi_desc *alloc_msi_entry(struct device *dev, int nvec, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff81149b10)
Location: kernel/irq/msi.c:32
Inline: False
Direct callers:
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq
```
**Symbols:**

```
ffffffff81149b10-ffffffff81149b9a: alloc_msi_entry (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: ✅</summary>

```c
struct msi_desc *alloc_msi_entry(struct device *dev, int nvec, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffff800010187230)
Location: kernel/irq/msi.c:29
Inline: False
Direct callers:
  - drivers/bus/fsl-mc/fsl-mc-msi.c:fsl_mc_msi_domain_alloc_irqs
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/soc/ti/ti_sci_inta_msi.c:ti_sci_inta_msi_domain_alloc_irqs
  - drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq
```
**Symbols:**

```
ffff800010187230-ffff8000101872c4: alloc_msi_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct msi_desc *alloc_msi_entry(struct device *dev, int nvec, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (c03d5e50)
Location: kernel/irq/msi.c:29
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq
```
**Symbols:**

```
c03d5e50-c03d5edc: alloc_msi_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct msi_desc *alloc_msi_entry(struct device *dev, int nvec, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (c0000000001e1520)
Location: kernel/irq/msi.c:29
Inline: False
Direct callers:
  - drivers/pci/msi.c:msi_setup_entry
```
**Symbols:**

```
c0000000001e1520-c0000000001e15f4: alloc_msi_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct msi_desc *alloc_msi_entry(struct device *dev, int nvec, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffe00011cec6)
Location: kernel/irq/msi.c:29
Inline: False
Direct callers:
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq
```
**Symbols:**

```
ffffffe00011cec6-ffffffe00011cf4e: alloc_msi_entry (STB_GLOBAL)
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
struct msi_desc *alloc_msi_entry(struct device *dev, int nvec, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff81119660)
Location: kernel/irq/msi.c:29
Inline: False
Direct callers:
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq
```
**Symbols:**

```
ffffffff81119660-ffffffff811196ee: alloc_msi_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct msi_desc *alloc_msi_entry(struct device *dev, int nvec, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff8110a6d0)
Location: kernel/irq/msi.c:29
Inline: False
Direct callers:
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq
```
**Symbols:**

```
ffffffff8110a6d0-ffffffff8110a75e: alloc_msi_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct msi_desc *alloc_msi_entry(struct device *dev, int nvec, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff81117550)
Location: kernel/irq/msi.c:29
Inline: False
Direct callers:
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq
```
**Symbols:**

```
ffffffff81117550-ffffffff811175de: alloc_msi_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct msi_desc *alloc_msi_entry(struct device *dev, int nvec, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff81122be0)
Location: kernel/irq/msi.c:29
Inline: False
Direct callers:
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq
```
**Symbols:**

```
ffffffff81122be0-ffffffff81122c6e: alloc_msi_entry (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int nvec</code>
</li>
<li>
<b>Param added. </b>
<code>const struct cpumask *affinity</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct cpumask *affinity</code> ➡️ <code>const struct irq_affinity_desc *affinity</code>
</li>
</ul>
</details>
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
