# Function: <code>irq_domain_associate_many</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void irq_domain_associate_many(struct irq_domain *domain, unsigned int irq_base, irq_hw_number_t hwirq_base, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e05a0)
Location: kernel/irq/irqdomain.c:394
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_strict_mappings
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
```
**Symbols:**

```
ffffffff810e05a0-ffffffff810e0627: irq_domain_associate_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void irq_domain_associate_many(struct irq_domain *domain, unsigned int irq_base, irq_hw_number_t hwirq_base, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e5ff0)
Location: kernel/irq/irqdomain.c:390
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_strict_mappings
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
```
**Symbols:**

```
ffffffff810e5ff0-ffffffff810e6073: irq_domain_associate_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void irq_domain_associate_many(struct irq_domain *domain, unsigned int irq_base, irq_hw_number_t hwirq_base, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ec9e0)
Location: kernel/irq/irqdomain.c:413
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_strict_mappings
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
```
**Symbols:**

```
ffffffff810ec9e0-ffffffff810eca63: irq_domain_associate_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void irq_domain_associate_many(struct irq_domain *domain, unsigned int irq_base, irq_hw_number_t hwirq_base, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ec380)
Location: kernel/irq/irqdomain.c:551
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_strict_mappings
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
```
**Symbols:**

```
ffffffff810ec380-ffffffff810ec402: irq_domain_associate_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void irq_domain_associate_many(struct irq_domain *domain, unsigned int irq_base, irq_hw_number_t hwirq_base, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810f4cc0)
Location: kernel/irq/irqdomain.c:565
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_strict_mappings
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
```
**Symbols:**

```
ffffffff810f4cc0-ffffffff810f4d42: irq_domain_associate_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void irq_domain_associate_many(struct irq_domain *domain, unsigned int irq_base, irq_hw_number_t hwirq_base, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810fd0a0)
Location: kernel/irq/irqdomain.c:567
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_strict_mappings
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
**Symbols:**

```
ffffffff810fd0a0-ffffffff810fd122: irq_domain_associate_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void irq_domain_associate_many(struct irq_domain *domain, unsigned int irq_base, irq_hw_number_t hwirq_base, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81108950)
Location: kernel/irq/irqdomain.c:567
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_strict_mappings
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
**Symbols:**

```
ffffffff81108950-ffffffff811089d2: irq_domain_associate_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void irq_domain_associate_many(struct irq_domain *domain, unsigned int irq_base, irq_hw_number_t hwirq_base, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81111f30)
Location: kernel/irq/irqdomain.c:581
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_strict_mappings
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
```
**Symbols:**

```
ffffffff81111f30-ffffffff81111fb2: irq_domain_associate_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void irq_domain_associate_many(struct irq_domain *domain, unsigned int irq_base, irq_hw_number_t hwirq_base, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8111e1b0)
Location: kernel/irq/irqdomain.c:583
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_strict_mappings
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
**Symbols:**

```
ffffffff8111e1b0-ffffffff8111e232: irq_domain_associate_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void irq_domain_associate_many(struct irq_domain *domain, unsigned int irq_base, irq_hw_number_t hwirq_base, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8112a410)
Location: kernel/irq/irqdomain.c:568
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_strict_mappings
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
```
**Symbols:**

```
ffffffff8112a410-ffffffff8112a492: irq_domain_associate_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void irq_domain_associate_many(struct irq_domain *domain, unsigned int irq_base, irq_hw_number_t hwirq_base, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81125ee0)
Location: kernel/irq/irqdomain.c:589
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_strict_mappings
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
```
**Symbols:**

```
ffffffff81125ee0-ffffffff81125f62: irq_domain_associate_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void irq_domain_associate_many(struct irq_domain *domain, unsigned int irq_base, irq_hw_number_t hwirq_base, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81125f70)
Location: kernel/irq/irqdomain.c:591
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_create_simple
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
```
**Symbols:**

```
ffffffff81125f70-ffffffff81125ff2: irq_domain_associate_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void irq_domain_associate_many(struct irq_domain *domain, unsigned int irq_base, irq_hw_number_t hwirq_base, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81146970)
Location: kernel/irq/irqdomain.c:612
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_create_simple
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
```
**Symbols:**

```
ffffffff81146970-ffffffff811469ef: irq_domain_associate_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void irq_domain_associate_many(struct irq_domain *domain, unsigned int irq_base, irq_hw_number_t hwirq_base, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8116ace0)
Location: kernel/irq/irqdomain.c:612
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_create_simple
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
```
**Symbols:**

```
ffffffff8116ace0-ffffffff8116ad6e: irq_domain_associate_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void irq_domain_associate_many(struct irq_domain *domain, unsigned int irq_base, irq_hw_number_t hwirq_base, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8119fbc0)
Location: kernel/irq/irqdomain.c:650
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_create_simple
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
```
**Symbols:**

```
ffffffff8119fbc0-ffffffff8119fc70: irq_domain_associate_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void irq_domain_associate_many(struct irq_domain *domain, unsigned int irq_base, irq_hw_number_t hwirq_base, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811b1720)
Location: kernel/irq/irqdomain.c:632
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_create_simple
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
```
**Symbols:**

```
ffffffff811b1720-ffffffff811b17d4: irq_domain_associate_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void irq_domain_associate_many(struct irq_domain *domain, unsigned int irq_base, irq_hw_number_t hwirq_base, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811c14d0)
Location: kernel/irq/irqdomain.c:632
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_create_simple
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
```
**Symbols:**

```
ffffffff811c14d0-ffffffff811c1584: irq_domain_associate_many (STB_GLOBAL)
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
void irq_domain_associate_many(struct irq_domain *domain, unsigned int irq_base, irq_hw_number_t hwirq_base, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffff800010183850)
Location: kernel/irq/irqdomain.c:583
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_strict_mappings
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
```
**Symbols:**

```
ffff800010183850-ffff800010183938: irq_domain_associate_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void irq_domain_associate_many(struct irq_domain *domain, unsigned int irq_base, irq_hw_number_t hwirq_base, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c03d2b48)
Location: kernel/irq/irqdomain.c:583
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_strict_mappings
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - drivers/soc/dove/pmu.c:dove_init_pmu_legacy
```
**Symbols:**

```
c03d2b48-c03d2c2c: irq_domain_associate_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void irq_domain_associate_many(struct irq_domain *domain, unsigned int irq_base, irq_hw_number_t hwirq_base, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c0000000001dddc0)
Location: kernel/irq/irqdomain.c:583
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_strict_mappings
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
```
**Symbols:**

```
c0000000001dddc0-c0000000001ddf08: irq_domain_associate_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void irq_domain_associate_many(struct irq_domain *domain, unsigned int irq_base, irq_hw_number_t hwirq_base, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffe00011ab36)
Location: kernel/irq/irqdomain.c:583
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_strict_mappings
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
```
**Symbols:**

```
ffffffe00011ab36-ffffffe00011abfe: irq_domain_associate_many (STB_GLOBAL)
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
void irq_domain_associate_many(struct irq_domain *domain, unsigned int irq_base, irq_hw_number_t hwirq_base, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81116790)
Location: kernel/irq/irqdomain.c:583
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_strict_mappings
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
```
**Symbols:**

```
ffffffff81116790-ffffffff81116812: irq_domain_associate_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void irq_domain_associate_many(struct irq_domain *domain, unsigned int irq_base, irq_hw_number_t hwirq_base, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81107480)
Location: kernel/irq/irqdomain.c:583
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_strict_mappings
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
**Symbols:**

```
ffffffff81107480-ffffffff81107502: irq_domain_associate_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void irq_domain_associate_many(struct irq_domain *domain, unsigned int irq_base, irq_hw_number_t hwirq_base, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81114680)
Location: kernel/irq/irqdomain.c:583
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_strict_mappings
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
**Symbols:**

```
ffffffff81114680-ffffffff81114702: irq_domain_associate_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void irq_domain_associate_many(struct irq_domain *domain, unsigned int irq_base, irq_hw_number_t hwirq_base, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8111fcb0)
Location: kernel/irq/irqdomain.c:583
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_strict_mappings
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
**Symbols:**

```
ffffffff8111fcb0-ffffffff8111fd32: irq_domain_associate_many (STB_GLOBAL)
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
