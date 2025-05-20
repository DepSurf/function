# Function: <code>platform_msi_domain_free</code>

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
void platform_msi_domain_free(struct irq_domain *domain, unsigned int virq, unsigned int nvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff815c24d0)
Location: drivers/base/platform-msi.c:375
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_alloc
```
**Symbols:**

```
ffffffff815c24d0-ffffffff815c2570: platform_msi_domain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void platform_msi_domain_free(struct irq_domain *domain, unsigned int virq, unsigned int nvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff815f1910)
Location: drivers/base/platform-msi.c:373
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_alloc
```
**Symbols:**

```
ffffffff815f1910-ffffffff815f19b0: platform_msi_domain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void platform_msi_domain_free(struct irq_domain *domain, unsigned int virq, unsigned int nvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff81605a60)
Location: drivers/base/platform-msi.c:373
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_alloc
```
**Symbols:**

```
ffffffff81605a60-ffffffff81605aea: platform_msi_domain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void platform_msi_domain_free(struct irq_domain *domain, unsigned int virq, unsigned int nvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff8166de60)
Location: drivers/base/platform-msi.c:373
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_alloc
```
**Symbols:**

```
ffffffff8166de60-ffffffff8166deea: platform_msi_domain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void platform_msi_domain_free(struct irq_domain *domain, unsigned int virq, unsigned int nvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff816a98d0)
Location: drivers/base/platform-msi.c:365
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_alloc
```
**Symbols:**

```
ffffffff816a98d0-ffffffff816a9958: platform_msi_domain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void platform_msi_domain_free(struct irq_domain *domain, unsigned int virq, unsigned int nvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff816ca4c0)
Location: drivers/base/platform-msi.c:367
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_alloc
```
**Symbols:**

```
ffffffff816ca4c0-ffffffff816ca598: platform_msi_domain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void platform_msi_domain_free(struct irq_domain *domain, unsigned int virq, unsigned int nvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/platform-msi.c (0)
Location: drivers/base/platform-msi.c:367
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_alloc
```
**Symbols:**

```
ffffffff81705be7-ffffffff81705bfa: platform_msi_domain_free.cold (STB_LOCAL)
ffffffff81705a50-ffffffff81705b25: platform_msi_domain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void platform_msi_domain_free(struct irq_domain *domain, unsigned int virq, unsigned int nvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff81729ce0)
Location: drivers/base/platform-msi.c:367
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_alloc
```
**Symbols:**

```
ffffffff81729ce0-ffffffff81729dab: platform_msi_domain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void platform_msi_domain_free(struct irq_domain *domain, unsigned int virq, unsigned int nvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff817e65a0)
Location: drivers/base/platform-msi.c:367
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_alloc
```
**Symbols:**

```
ffffffff817e65a0-ffffffff817e666b: platform_msi_domain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void platform_msi_domain_free(struct irq_domain *domain, unsigned int virq, unsigned int nvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff817fb230)
Location: drivers/base/platform-msi.c:374
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_alloc
```
**Symbols:**

```
ffffffff817fb230-ffffffff817fb2fb: platform_msi_domain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void platform_msi_domain_free(struct irq_domain *domain, unsigned int virq, unsigned int nvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff817dff00)
Location: drivers/base/platform-msi.c:375
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_alloc
```
**Symbols:**

```
ffffffff817dff00-ffffffff817dffcb: platform_msi_domain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void platform_msi_domain_free(struct irq_domain *domain, unsigned int virq, unsigned int nvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff8186ba00)
Location: drivers/base/platform-msi.c:385
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_alloc
```
**Symbols:**

```
ffffffff8186ba00-ffffffff8186bacb: platform_msi_domain_free (STB_GLOBAL)
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
void platform_msi_domain_free(struct irq_domain *domain, unsigned int virq, unsigned int nvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffff80001091fcd0)
Location: drivers/base/platform-msi.c:367
Inline: False
Direct callers:
  - drivers/irqchip/irq-mvebu-icu.c:mvebu_icu_irq_domain_free
  - drivers/irqchip/irq-mvebu-icu.c:mvebu_icu_irq_domain_alloc
  - drivers/base/platform-msi.c:platform_msi_domain_alloc
```
**Symbols:**

```
ffff80001091fcd0-ffff80001091fdc0: platform_msi_domain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void platform_msi_domain_free(struct irq_domain *domain, unsigned int virq, unsigned int nvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (c0a04da0)
Location: drivers/base/platform-msi.c:367
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_alloc
```
**Symbols:**

```
c0a04da0-c0a04e6c: platform_msi_domain_free (STB_GLOBAL)
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
void platform_msi_domain_free(struct irq_domain *domain, unsigned int virq, unsigned int nvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffe00059eac4)
Location: drivers/base/platform-msi.c:367
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_alloc
```
**Symbols:**

```
ffffffe00059eac4-ffffffe00059eb7e: platform_msi_domain_free (STB_GLOBAL)
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
void platform_msi_domain_free(struct irq_domain *domain, unsigned int virq, unsigned int nvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff816efac0)
Location: drivers/base/platform-msi.c:367
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_alloc
```
**Symbols:**

```
ffffffff816efac0-ffffffff816efb8b: platform_msi_domain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void platform_msi_domain_free(struct irq_domain *domain, unsigned int virq, unsigned int nvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff816c9bd0)
Location: drivers/base/platform-msi.c:367
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_alloc
```
**Symbols:**

```
ffffffff816c9bd0-ffffffff816c9c9b: platform_msi_domain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void platform_msi_domain_free(struct irq_domain *domain, unsigned int virq, unsigned int nvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff8171d1a0)
Location: drivers/base/platform-msi.c:367
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_alloc
```
**Symbols:**

```
ffffffff8171d1a0-ffffffff8171d26b: platform_msi_domain_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void platform_msi_domain_free(struct irq_domain *domain, unsigned int virq, unsigned int nvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff81738500)
Location: drivers/base/platform-msi.c:367
Inline: False
Direct callers:
  - drivers/base/platform-msi.c:platform_msi_domain_alloc
```
**Symbols:**

```
ffffffff81738500-ffffffff817385cb: platform_msi_domain_free (STB_GLOBAL)
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
