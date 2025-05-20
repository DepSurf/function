# Function: <code>irq_domain_free_irqs_common</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void irq_domain_free_irqs_common(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e1030)
Location: kernel/irq/irqdomain.c:1082
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - drivers/iommu/amd_iommu.c:irq_remapping_free
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_free
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff810e1030-ffffffff810e10c5: irq_domain_free_irqs_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void irq_domain_free_irqs_common(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e62e0)
Location: kernel/irq/irqdomain.c:1133
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/msi.c:msi_domain_populate_irqs
  - drivers/iommu/amd_iommu.c:irq_remapping_free
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_free
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
  - drivers/base/platform-msi.c:platform_msi_domain_free
```
**Symbols:**

```
ffffffff810e62e0-ffffffff810e6384: irq_domain_free_irqs_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void irq_domain_free_irqs_common(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810eccd0)
Location: kernel/irq/irqdomain.c:1159
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/msi.c:msi_domain_populate_irqs
  - drivers/iommu/amd_iommu.c:irq_remapping_free
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_free
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
  - drivers/base/platform-msi.c:platform_msi_domain_free
```
**Symbols:**

```
ffffffff810eccd0-ffffffff810ecd74: irq_domain_free_irqs_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void irq_domain_free_irqs_common(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ec0d0)
Location: kernel/irq/irqdomain.c:1328
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/msi.c:msi_domain_populate_irqs
  - drivers/iommu/amd_iommu.c:irq_remapping_free
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_free
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
  - drivers/base/platform-msi.c:platform_msi_domain_free
```
**Symbols:**

```
ffffffff810ec0d0-ffffffff810ec160: irq_domain_free_irqs_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void irq_domain_free_irqs_common(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810f45b0)
Location: kernel/irq/irqdomain.c:1328
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/msi.c:msi_domain_populate_irqs
  - drivers/iommu/amd_iommu.c:irq_remapping_free
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_free
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
  - drivers/base/platform-msi.c:platform_msi_domain_free
```
**Symbols:**

```
ffffffff810f45b0-ffffffff810f464b: irq_domain_free_irqs_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void irq_domain_free_irqs_common(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810fc9c0)
Location: kernel/irq/irqdomain.c:1212
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/msi.c:msi_domain_populate_irqs
  - drivers/iommu/amd_iommu.c:irq_remapping_free
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_free
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
  - drivers/base/platform-msi.c:platform_msi_domain_free
```
**Symbols:**

```
ffffffff810fc9c0-ffffffff810fca5b: irq_domain_free_irqs_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void irq_domain_free_irqs_common(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81108270)
Location: kernel/irq/irqdomain.c:1212
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/msi.c:msi_domain_populate_irqs
  - drivers/iommu/amd_iommu.c:irq_remapping_free
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_free
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
  - drivers/base/platform-msi.c:platform_msi_domain_free
```
**Symbols:**

```
ffffffff81108270-ffffffff8110830b: irq_domain_free_irqs_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void irq_domain_free_irqs_common(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81111890)
Location: kernel/irq/irqdomain.c:1249
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/msi.c:msi_domain_populate_irqs
  - drivers/iommu/amd_iommu.c:irq_remapping_free
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_free
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_free
  - drivers/base/platform-msi.c:platform_msi_domain_free
```
**Symbols:**

```
ffffffff81111890-ffffffff81111920: irq_domain_free_irqs_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void irq_domain_free_irqs_common(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8111db00)
Location: kernel/irq/irqdomain.c:1251
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/msi.c:msi_domain_populate_irqs
  - drivers/iommu/amd_iommu.c:irq_remapping_free
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_free
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_free
  - drivers/base/platform-msi.c:platform_msi_domain_free
```
**Symbols:**

```
ffffffff8111db00-ffffffff8111db90: irq_domain_free_irqs_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void irq_domain_free_irqs_common(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8112a730)
Location: kernel/irq/irqdomain.c:1253
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/msi.c:msi_domain_populate_irqs
  - drivers/iommu/amd/iommu.c:irq_remapping_free
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_free
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_free
  - drivers/base/platform-msi.c:platform_msi_domain_free
```
**Symbols:**

```
ffffffff8112a730-ffffffff8112a7c0: irq_domain_free_irqs_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void irq_domain_free_irqs_common(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811262e0)
Location: kernel/irq/irqdomain.c:1359
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/msi.c:msi_domain_populate_irqs
  - drivers/iommu/amd/iommu.c:irq_remapping_free
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_free
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_free
  - drivers/base/platform-msi.c:platform_msi_domain_free
```
**Symbols:**

```
ffffffff811262e0-ffffffff81126363: irq_domain_free_irqs_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void irq_domain_free_irqs_common(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81126300)
Location: kernel/irq/irqdomain.c:1326
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/msi.c:msi_domain_populate_irqs
  - drivers/iommu/amd/iommu.c:irq_remapping_free
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_free
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_free
  - drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_free
  - drivers/base/platform-msi.c:platform_msi_domain_free
```
**Symbols:**

```
ffffffff81126300-ffffffff81126383: irq_domain_free_irqs_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void irq_domain_free_irqs_common(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811465f0)
Location: kernel/irq/irqdomain.c:1366
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/msi.c:msi_domain_populate_irqs
  - drivers/iommu/amd/iommu.c:irq_remapping_free
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_free
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_free
  - drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_free
  - drivers/base/platform-msi.c:platform_msi_domain_free
```
**Symbols:**

```
ffffffff811465f0-ffffffff81146673: irq_domain_free_irqs_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void irq_domain_free_irqs_common(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8116a910)
Location: kernel/irq/irqdomain.c:1369
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/msi.c:msi_domain_populate_irqs
  - drivers/iommu/amd/iommu.c:irq_remapping_free
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_free
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_free
  - drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_alloc
  - drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_alloc
  - drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_free
  - drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_alloc
  - drivers/base/platform-msi.c:platform_msi_device_domain_free
```
**Symbols:**

```
ffffffff8116a910-ffffffff8116a99f: irq_domain_free_irqs_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void irq_domain_free_irqs_common(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8119f510)
Location: kernel/irq/irqdomain.c:1429
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/msi.c:msi_domain_populate_irqs
  - drivers/iommu/amd/iommu.c:irq_remapping_free
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_free
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_free
  - drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_alloc
  - drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_alloc
  - drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_free
  - drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_alloc
  - drivers/base/platform-msi.c:platform_msi_device_domain_free
```
**Symbols:**

```
ffffffff8119f510-ffffffff8119f59f: irq_domain_free_irqs_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void irq_domain_free_irqs_common(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811b1a20)
Location: kernel/irq/irqdomain.c:1408
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/msi.c:msi_domain_populate_irqs
  - drivers/iommu/amd/iommu.c:irq_remapping_free
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_free
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_free
  - drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_alloc
  - drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_alloc
  - drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_free
  - drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_alloc
  - drivers/base/platform-msi.c:platform_msi_device_domain_free
```
**Symbols:**

```
ffffffff811b1a20-ffffffff811b1ab2: irq_domain_free_irqs_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void irq_domain_free_irqs_common(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811c17d0)
Location: kernel/irq/irqdomain.c:1408
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/msi.c:msi_domain_populate_irqs
  - drivers/iommu/amd/iommu.c:irq_remapping_free
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_free
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_free
  - drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_alloc
  - drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_alloc
  - drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_free
  - drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_alloc
  - drivers/base/platform-msi.c:platform_msi_device_domain_free
```
**Symbols:**

```
ffffffff811c17d0-ffffffff811c1862: irq_domain_free_irqs_common (STB_GLOBAL)
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
void irq_domain_free_irqs_common(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffff800010183088)
Location: kernel/irq/irqdomain.c:1251
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/msi.c:msi_domain_populate_irqs
  - drivers/base/platform-msi.c:platform_msi_domain_free
```
**Symbols:**

```
ffff800010183088-ffff800010183138: irq_domain_free_irqs_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void irq_domain_free_irqs_common(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c03d23e0)
Location: kernel/irq/irqdomain.c:1251
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/msi.c:msi_domain_populate_irqs
  - drivers/base/platform-msi.c:platform_msi_domain_free
```
**Symbols:**

```
c03d23e0-c03d2488: irq_domain_free_irqs_common (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void irq_domain_free_irqs_common(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffe00011a4ba)
Location: kernel/irq/irqdomain.c:1251
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/msi.c:msi_domain_populate_irqs
  - drivers/base/platform-msi.c:platform_msi_domain_free
```
**Symbols:**

```
ffffffe00011a4ba-ffffffe00011a53e: irq_domain_free_irqs_common (STB_GLOBAL)
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
void irq_domain_free_irqs_common(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811160e0)
Location: kernel/irq/irqdomain.c:1251
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/msi.c:msi_domain_populate_irqs
  - drivers/iommu/amd_iommu.c:irq_remapping_free
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_free
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_free
  - drivers/base/platform-msi.c:platform_msi_domain_free
```
**Symbols:**

```
ffffffff811160e0-ffffffff81116170: irq_domain_free_irqs_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void irq_domain_free_irqs_common(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81106dd0)
Location: kernel/irq/irqdomain.c:1251
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/msi.c:msi_domain_populate_irqs
  - drivers/iommu/amd_iommu.c:irq_remapping_free
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_free
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_free
  - drivers/base/platform-msi.c:platform_msi_domain_free
```
**Symbols:**

```
ffffffff81106dd0-ffffffff81106e60: irq_domain_free_irqs_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void irq_domain_free_irqs_common(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81113fd0)
Location: kernel/irq/irqdomain.c:1251
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/msi.c:msi_domain_populate_irqs
  - drivers/iommu/amd_iommu.c:irq_remapping_free
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_free
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_free
  - drivers/base/platform-msi.c:platform_msi_domain_free
```
**Symbols:**

```
ffffffff81113fd0-ffffffff81114060: irq_domain_free_irqs_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void irq_domain_free_irqs_common(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8111f5f0)
Location: kernel/irq/irqdomain.c:1251
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/msi.c:msi_domain_populate_irqs
  - drivers/iommu/amd_iommu.c:irq_remapping_free
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_free
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_free
  - drivers/base/platform-msi.c:platform_msi_domain_free
```
**Symbols:**

```
ffffffff8111f5f0-ffffffff8111f680: irq_domain_free_irqs_common (STB_GLOBAL)
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
