# Function: <code>msi_domain_populate_irqs</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int msi_domain_populate_irqs(struct irq_domain *domain, struct device *dev, int virq, int nvec, msi_alloc_info_t *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff810e8a60)
Location: kernel/irq/msi.c:271
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_alloc
```
**Symbols:**

```
ffffffff810e8a60-ffffffff810e8ba1: msi_domain_populate_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int msi_domain_populate_irqs(struct irq_domain *domain, struct device *dev, int virq, int nvec, msi_alloc_info_t *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff810ef4f0)
Location: kernel/irq/msi.c:291
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_alloc
```
**Symbols:**

```
ffffffff810ef4f0-ffffffff810ef631: msi_domain_populate_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int msi_domain_populate_irqs(struct irq_domain *domain, struct device *dev, int virq, int nvec, msi_alloc_info_t *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff810ef340)
Location: kernel/irq/msi.c:298
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_alloc
```
**Symbols:**

```
ffffffff810ef340-ffffffff810ef467: msi_domain_populate_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int msi_domain_populate_irqs(struct irq_domain *domain, struct device *dev, int virq, int nvec, msi_alloc_info_t *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff810f7e40)
Location: kernel/irq/msi.c:301
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_alloc
```
**Symbols:**

```
ffffffff810f7e40-ffffffff810f7f72: msi_domain_populate_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int msi_domain_populate_irqs(struct irq_domain *domain, struct device *dev, int virq, int nvec, msi_alloc_info_t *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff81100230)
Location: kernel/irq/msi.c:315
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_alloc
```
**Symbols:**

```
ffffffff81100230-ffffffff8110035c: msi_domain_populate_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int msi_domain_populate_irqs(struct irq_domain *domain, struct device *dev, int virq, int nvec, msi_alloc_info_t *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff8110ba00)
Location: kernel/irq/msi.c:315
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_alloc
```
**Symbols:**

```
ffffffff8110ba00-ffffffff8110bb2c: msi_domain_populate_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int msi_domain_populate_irqs(struct irq_domain *domain, struct device *dev, int virq, int nvec, msi_alloc_info_t *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/msi.c (0)
Location: kernel/irq/msi.c:315
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_alloc
```
**Symbols:**

```
ffffffff81115562-ffffffff8111557a: msi_domain_populate_irqs.cold (STB_LOCAL)
ffffffff811150f0-ffffffff811151fb: msi_domain_populate_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int msi_domain_populate_irqs(struct irq_domain *domain, struct device *dev, int virq, int nvec, msi_alloc_info_t *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811212e0)
Location: kernel/irq/msi.c:315
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_alloc
```
**Symbols:**

```
ffffffff811212e0-ffffffff811213f6: msi_domain_populate_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int msi_domain_populate_irqs(struct irq_domain *domain, struct device *dev, int virq, int nvec, msi_alloc_info_t *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff8112d8c0)
Location: kernel/irq/msi.c:315
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_alloc
```
**Symbols:**

```
ffffffff8112d8c0-ffffffff8112d9d6: msi_domain_populate_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int msi_domain_populate_irqs(struct irq_domain *domain, struct device *dev, int virq, int nvec, msi_alloc_info_t *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff81129800)
Location: kernel/irq/msi.c:318
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_alloc
```
**Symbols:**

```
ffffffff81129800-ffffffff81129916: msi_domain_populate_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int msi_domain_populate_irqs(struct irq_domain *domain, struct device *dev, int virq, int nvec, msi_alloc_info_t *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff81129a90)
Location: kernel/irq/msi.c:318
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_alloc
```
**Symbols:**

```
ffffffff81129a90-ffffffff81129ba6: msi_domain_populate_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int msi_domain_populate_irqs(struct irq_domain *domain, struct device *dev, int virq, int nvec, msi_alloc_info_t *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff8114a3c0)
Location: kernel/irq/msi.c:458
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_alloc
```
**Symbols:**

```
ffffffff8114a3c0-ffffffff8114a4d6: msi_domain_populate_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int msi_domain_populate_irqs(struct irq_domain *domain, struct device *dev, int virq_base, int nvec, msi_alloc_info_t *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff8116f790)
Location: kernel/irq/msi.c:712
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_device_domain_alloc
```
**Symbols:**

```
ffffffff8116f790-ffffffff8116f8df: msi_domain_populate_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int msi_domain_populate_irqs(struct irq_domain *domain, struct device *dev, int virq_base, int nvec, msi_alloc_info_t *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811a5640)
Location: kernel/irq/msi.c:1073
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_device_domain_alloc
```
**Symbols:**

```
ffffffff811a5640-ffffffff811a5821: msi_domain_populate_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int msi_domain_populate_irqs(struct irq_domain *domain, struct device *dev, int virq_base, int nvec, msi_alloc_info_t *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811b78a0)
Location: kernel/irq/msi.c:1070
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_device_domain_alloc
```
**Symbols:**

```
ffffffff811b78a0-ffffffff811b7a81: msi_domain_populate_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int msi_domain_populate_irqs(struct irq_domain *domain, struct device *dev, int virq_base, int nvec, msi_alloc_info_t *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811c7760)
Location: kernel/irq/msi.c:1070
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_device_domain_alloc
```
**Symbols:**

```
ffffffff811c7760-ffffffff811c7941: msi_domain_populate_irqs (STB_GLOBAL)
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
int msi_domain_populate_irqs(struct irq_domain *domain, struct device *dev, int virq, int nvec, msi_alloc_info_t *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffff800010187510)
Location: kernel/irq/msi.c:315
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_alloc
```
**Symbols:**

```
ffff800010187510-ffff80001018765c: msi_domain_populate_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int msi_domain_populate_irqs(struct irq_domain *domain, struct device *dev, int virq, int nvec, msi_alloc_info_t *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (c03d60ec)
Location: kernel/irq/msi.c:315
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_alloc
```
**Symbols:**

```
c03d60ec-c03d622c: msi_domain_populate_irqs (STB_GLOBAL)
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
int msi_domain_populate_irqs(struct irq_domain *domain, struct device *dev, int virq, int nvec, msi_alloc_info_t *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffe00011d102)
Location: kernel/irq/msi.c:315
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_alloc
```
**Symbols:**

```
ffffffe00011d102-ffffffe00011d1f2: msi_domain_populate_irqs (STB_GLOBAL)
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
int msi_domain_populate_irqs(struct irq_domain *domain, struct device *dev, int virq, int nvec, msi_alloc_info_t *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811198c0)
Location: kernel/irq/msi.c:315
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_alloc
```
**Symbols:**

```
ffffffff811198c0-ffffffff811199d6: msi_domain_populate_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int msi_domain_populate_irqs(struct irq_domain *domain, struct device *dev, int virq, int nvec, msi_alloc_info_t *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff8110a930)
Location: kernel/irq/msi.c:315
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_alloc
```
**Symbols:**

```
ffffffff8110a930-ffffffff8110aa46: msi_domain_populate_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int msi_domain_populate_irqs(struct irq_domain *domain, struct device *dev, int virq, int nvec, msi_alloc_info_t *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811177b0)
Location: kernel/irq/msi.c:315
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_alloc
```
**Symbols:**

```
ffffffff811177b0-ffffffff811178c6: msi_domain_populate_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int msi_domain_populate_irqs(struct irq_domain *domain, struct device *dev, int virq, int nvec, msi_alloc_info_t *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff81122e40)
Location: kernel/irq/msi.c:315
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_alloc
```
**Symbols:**

```
ffffffff81122e40-ffffffff81122f56: msi_domain_populate_irqs (STB_GLOBAL)
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int virq_base</code>
</li>
<li>
<b>Param removed. </b>
<code>int virq</code>
</li>
</ul>
</details>
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
