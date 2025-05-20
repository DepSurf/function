# Function: <code>irq_domain_free_irqs_top</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void irq_domain_free_irqs_top(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e10d0)
Location: kernel/irq/irqdomain.c:1102
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_domain_free
  - kernel/irq/msi.c:msi_domain_alloc
```
**Symbols:**

```
ffffffff810e10d0-ffffffff810e112c: irq_domain_free_irqs_top (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void irq_domain_free_irqs_top(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e69c0)
Location: kernel/irq/irqdomain.c:1154
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_domain_free
  - kernel/irq/msi.c:msi_domain_alloc
```
**Symbols:**

```
ffffffff810e69c0-ffffffff810e6a1c: irq_domain_free_irqs_top (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void irq_domain_free_irqs_top(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ed3b0)
Location: kernel/irq/irqdomain.c:1180
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_domain_free
  - kernel/irq/msi.c:msi_domain_alloc
```
**Symbols:**

```
ffffffff810ed3b0-ffffffff810ed40c: irq_domain_free_irqs_top (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void irq_domain_free_irqs_top(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ece30)
Location: kernel/irq/irqdomain.c:1349
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_free
  - kernel/irq/msi.c:msi_domain_free
  - kernel/irq/msi.c:msi_domain_alloc
```
**Symbols:**

```
ffffffff810ece30-ffffffff810ece8c: irq_domain_free_irqs_top (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void irq_domain_free_irqs_top(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810f5870)
Location: kernel/irq/irqdomain.c:1349
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_free
  - kernel/irq/msi.c:msi_domain_free
  - kernel/irq/msi.c:msi_domain_alloc
```
**Symbols:**

```
ffffffff810f5870-ffffffff810f58cc: irq_domain_free_irqs_top (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void irq_domain_free_irqs_top(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810fdc20)
Location: kernel/irq/irqdomain.c:1233
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_free
  - kernel/irq/msi.c:msi_domain_free
  - kernel/irq/msi.c:msi_domain_alloc
```
**Symbols:**

```
ffffffff810fdc20-ffffffff810fdc7c: irq_domain_free_irqs_top (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void irq_domain_free_irqs_top(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811093f0)
Location: kernel/irq/irqdomain.c:1233
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_free
  - kernel/irq/msi.c:msi_domain_free
  - kernel/irq/msi.c:msi_domain_alloc
```
**Symbols:**

```
ffffffff811093f0-ffffffff8110944c: irq_domain_free_irqs_top (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void irq_domain_free_irqs_top(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811129f0)
Location: kernel/irq/irqdomain.c:1270
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_free
  - kernel/irq/msi.c:msi_domain_free
  - kernel/irq/msi.c:msi_domain_alloc
```
**Symbols:**

```
ffffffff811129f0-ffffffff81112a4c: irq_domain_free_irqs_top (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void irq_domain_free_irqs_top(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8111ec80)
Location: kernel/irq/irqdomain.c:1272
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_domain_free
  - kernel/irq/msi.c:msi_domain_alloc
```
**Symbols:**

```
ffffffff8111ec80-ffffffff8111ecdc: irq_domain_free_irqs_top (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void irq_domain_free_irqs_top(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8112afa0)
Location: kernel/irq/irqdomain.c:1274
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_free
  - arch/x86/platform/uv/uv_irq.c:uv_domain_free
  - kernel/irq/msi.c:msi_domain_free
  - kernel/irq/msi.c:msi_domain_alloc
```
**Symbols:**

```
ffffffff8112afa0-ffffffff8112affc: irq_domain_free_irqs_top (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void irq_domain_free_irqs_top(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81126a30)
Location: kernel/irq/irqdomain.c:1380
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_free
  - arch/x86/platform/uv/uv_irq.c:uv_domain_free
  - kernel/irq/msi.c:msi_domain_free
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/iommu/amd/init.c:intcapxt_irqdomain_free
```
**Symbols:**

```
ffffffff81126a30-ffffffff81126a8c: irq_domain_free_irqs_top (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void irq_domain_free_irqs_top(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81126a70)
Location: kernel/irq/irqdomain.c:1347
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_free
  - arch/x86/platform/uv/uv_irq.c:uv_domain_free
  - kernel/irq/msi.c:msi_domain_free
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/iommu/amd/init.c:intcapxt_irqdomain_free
```
**Symbols:**

```
ffffffff81126a70-ffffffff81126acc: irq_domain_free_irqs_top (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void irq_domain_free_irqs_top(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81146ff0)
Location: kernel/irq/irqdomain.c:1387
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_free
  - arch/x86/platform/uv/uv_irq.c:uv_domain_free
  - kernel/irq/msi.c:msi_domain_free
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/iommu/amd/init.c:intcapxt_irqdomain_free
```
**Symbols:**

```
ffffffff81146ff0-ffffffff8114704c: irq_domain_free_irqs_top (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void irq_domain_free_irqs_top(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8116b410)
Location: kernel/irq/irqdomain.c:1390
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_free
  - arch/x86/platform/uv/uv_irq.c:uv_domain_free
  - kernel/irq/msi.c:msi_domain_free
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/iommu/amd/init.c:intcapxt_irqdomain_free
```
**Symbols:**

```
ffffffff8116b410-ffffffff8116b47a: irq_domain_free_irqs_top (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void irq_domain_free_irqs_top(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811a0200)
Location: kernel/irq/irqdomain.c:1450
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_free
  - arch/x86/platform/uv/uv_irq.c:uv_domain_free
  - kernel/irq/msi.c:msi_domain_free
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/iommu/amd/init.c:intcapxt_irqdomain_free
```
**Symbols:**

```
ffffffff811a0200-ffffffff811a026a: irq_domain_free_irqs_top (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void irq_domain_free_irqs_top(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811b20c0)
Location: kernel/irq/irqdomain.c:1429
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_free
  - arch/x86/platform/uv/uv_irq.c:uv_domain_free
  - kernel/irq/msi.c:msi_domain_free
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/iommu/amd/init.c:intcapxt_irqdomain_free
```
**Symbols:**

```
ffffffff811b20c0-ffffffff811b212a: irq_domain_free_irqs_top (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void irq_domain_free_irqs_top(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811c1e70)
Location: kernel/irq/irqdomain.c:1429
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_free
  - arch/x86/platform/uv/uv_irq.c:uv_domain_free
  - kernel/irq/msi.c:msi_domain_free
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/iommu/amd/init.c:intcapxt_irqdomain_free
```
**Symbols:**

```
ffffffff811c1e70-ffffffff811c1eda: irq_domain_free_irqs_top (STB_GLOBAL)
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
void irq_domain_free_irqs_top(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffff8000101846e8)
Location: kernel/irq/irqdomain.c:1272
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_domain_free
  - kernel/irq/msi.c:msi_domain_alloc
```
**Symbols:**

```
ffff8000101846e8-ffff800010184770: irq_domain_free_irqs_top (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void irq_domain_free_irqs_top(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c03d37e8)
Location: kernel/irq/irqdomain.c:1272
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_domain_free
  - kernel/irq/msi.c:msi_domain_alloc
```
**Symbols:**

```
c03d37e8-c03d3854: irq_domain_free_irqs_top (STB_GLOBAL)
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
void irq_domain_free_irqs_top(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffe00011b68c)
Location: kernel/irq/irqdomain.c:1272
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_domain_free
  - kernel/irq/msi.c:msi_domain_alloc
```
**Symbols:**

```
ffffffe00011b68c-ffffffe00011b6fa: irq_domain_free_irqs_top (STB_GLOBAL)
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
void irq_domain_free_irqs_top(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81117260)
Location: kernel/irq/irqdomain.c:1272
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_domain_free
  - kernel/irq/msi.c:msi_domain_alloc
```
**Symbols:**

```
ffffffff81117260-ffffffff811172bc: irq_domain_free_irqs_top (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void irq_domain_free_irqs_top(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81107f50)
Location: kernel/irq/irqdomain.c:1272
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_domain_free
  - kernel/irq/msi.c:msi_domain_alloc
```
**Symbols:**

```
ffffffff81107f50-ffffffff81107fac: irq_domain_free_irqs_top (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void irq_domain_free_irqs_top(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81115150)
Location: kernel/irq/irqdomain.c:1272
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_domain_free
  - kernel/irq/msi.c:msi_domain_alloc
```
**Symbols:**

```
ffffffff81115150-ffffffff811151ac: irq_domain_free_irqs_top (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void irq_domain_free_irqs_top(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81120780)
Location: kernel/irq/irqdomain.c:1272
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_domain_free
  - kernel/irq/msi.c:msi_domain_alloc
```
**Symbols:**

```
ffffffff81120780-ffffffff811207dc: irq_domain_free_irqs_top (STB_GLOBAL)
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
