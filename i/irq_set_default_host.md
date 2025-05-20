# Function: <code>irq_set_default_host</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void irq_set_default_host(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e0210)
Location: kernel/irq/irqdomain.c:295
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_remove
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
**Symbols:**

```
ffffffff810e0210-ffffffff810e0250: irq_set_default_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void irq_set_default_host(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e5c00)
Location: kernel/irq/irqdomain.c:291
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - kernel/irq/irqdomain.c:irq_domain_remove
```
**Symbols:**

```
ffffffff810e5c00-ffffffff810e5c3c: irq_set_default_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void irq_set_default_host(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ec5f0)
Location: kernel/irq/irqdomain.c:314
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - kernel/irq/irqdomain.c:irq_domain_remove
```
**Symbols:**

```
ffffffff810ec5f0-ffffffff810ec62c: irq_set_default_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void irq_set_default_host(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ebf30)
Location: kernel/irq/irqdomain.c:450
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - kernel/irq/irqdomain.c:irq_domain_remove
```
**Symbols:**

```
ffffffff810ebf30-ffffffff810ebf6c: irq_set_default_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void irq_set_default_host(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810f4410)
Location: kernel/irq/irqdomain.c:451
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - kernel/irq/irqdomain.c:irq_domain_remove
```
**Symbols:**

```
ffffffff810f4410-ffffffff810f444c: irq_set_default_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void irq_set_default_host(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810fc800)
Location: kernel/irq/irqdomain.c:453
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - kernel/irq/irqdomain.c:irq_domain_remove
```
**Symbols:**

```
ffffffff810fc800-ffffffff810fc83c: irq_set_default_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void irq_set_default_host(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811080b0)
Location: kernel/irq/irqdomain.c:453
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - kernel/irq/irqdomain.c:irq_domain_remove
```
**Symbols:**

```
ffffffff811080b0-ffffffff811080ec: irq_set_default_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void irq_set_default_host(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811116f0)
Location: kernel/irq/irqdomain.c:453
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - kernel/irq/irqdomain.c:irq_domain_remove
```
**Symbols:**

```
ffffffff811116f0-ffffffff8111172c: irq_set_default_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void irq_set_default_host(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8111d950)
Location: kernel/irq/irqdomain.c:455
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - kernel/irq/irqdomain.c:irq_domain_remove
```
**Symbols:**

```
ffffffff8111d950-ffffffff8111d98c: irq_set_default_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void irq_set_default_host(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8112ad99)
Location: kernel/irq/irqdomain.c:440
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_remove
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
**Symbols:**

```
ffffffff81129b30-ffffffff81129b72: irq_set_default_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void irq_set_default_host(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81126949)
Location: kernel/irq/irqdomain.c:461
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_remove
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
**Symbols:**

```
ffffffff811253e0-ffffffff81125422: irq_set_default_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void irq_set_default_host(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81126980)
Location: kernel/irq/irqdomain.c:463
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_remove
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
**Symbols:**

```
ffffffff81125740-ffffffff81125782: irq_set_default_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void irq_set_default_host(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81146f7d)
Location: kernel/irq/irqdomain.c:473
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_remove
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
**Symbols:**

```
ffffffff81145e70-ffffffff81145eaf: irq_set_default_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void irq_set_default_host(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8116b37d)
Location: kernel/irq/irqdomain.c:473
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_remove
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
**Symbols:**

```
ffffffff8116a080-ffffffff8116a0d3: irq_set_default_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void irq_set_default_host(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811a0150)
Location: kernel/irq/irqdomain.c:497
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_remove
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
**Symbols:**

```
ffffffff8119eaf0-ffffffff8119eb43: irq_set_default_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void irq_set_default_host(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811b2010)
Location: kernel/irq/irqdomain.c:479
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_remove
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
**Symbols:**

```
ffffffff811b09e0-ffffffff811b0a33: irq_set_default_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void irq_set_default_host(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811c1dc0)
Location: kernel/irq/irqdomain.c:479
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_remove
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
**Symbols:**

```
ffffffff811c0760-ffffffff811c07b3: irq_set_default_host (STB_GLOBAL)
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
void irq_set_default_host(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffff800010182e20)
Location: kernel/irq/irqdomain.c:455
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_remove
  - drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irqchip_init
```
**Symbols:**

```
ffff800010182e20-ffff800010182e7c: irq_set_default_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void irq_set_default_host(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c03d22d4)
Location: kernel/irq/irqdomain.c:455
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_remove
Direct callers:
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_of_init
  - drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irqchip_init
```
**Symbols:**

```
c03d218c-c03d21e0: irq_set_default_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void irq_set_default_host(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c0000000001dd880)
Location: kernel/irq/irqdomain.c:455
Inline: False
Direct callers:
  - arch/powerpc/sysdev/mpic.c:mpic_alloc
  - arch/powerpc/sysdev/xics/xics-common.c:xics_init
  - arch/powerpc/sysdev/xive/common.c:xive_core_init
  - kernel/irq/irqdomain.c:irq_domain_remove
```
**Symbols:**

```
c0000000001dd880-c0000000001dd900: irq_set_default_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void irq_set_default_host(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffe00011a3aa)
Location: kernel/irq/irqdomain.c:455
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_remove
```
**Symbols:**

```
ffffffe00011a28c-ffffffe00011a2ea: irq_set_default_host (STB_GLOBAL)
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
void irq_set_default_host(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81115f30)
Location: kernel/irq/irqdomain.c:455
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - kernel/irq/irqdomain.c:irq_domain_remove
```
**Symbols:**

```
ffffffff81115f30-ffffffff81115f6c: irq_set_default_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void irq_set_default_host(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81106c20)
Location: kernel/irq/irqdomain.c:455
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - kernel/irq/irqdomain.c:irq_domain_remove
```
**Symbols:**

```
ffffffff81106c20-ffffffff81106c5c: irq_set_default_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void irq_set_default_host(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81113e20)
Location: kernel/irq/irqdomain.c:455
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - kernel/irq/irqdomain.c:irq_domain_remove
```
**Symbols:**

```
ffffffff81113e20-ffffffff81113e5c: irq_set_default_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void irq_set_default_host(struct irq_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8111f440)
Location: kernel/irq/irqdomain.c:455
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - kernel/irq/irqdomain.c:irq_domain_remove
```
**Symbols:**

```
ffffffff8111f440-ffffffff8111f47c: irq_set_default_host (STB_GLOBAL)
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
