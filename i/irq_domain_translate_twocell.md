# Function: <code>irq_domain_translate_twocell</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int irq_domain_translate_twocell(struct irq_domain *d, struct irq_fwspec *fwspec, long unsigned int *out_hwirq, unsigned int *out_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:995
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_xlate_twocell
```
**Symbols:**

```
ffffffff8111328d-ffffffff811132a5: irq_domain_translate_twocell.cold (STB_LOCAL)
ffffffff81111500-ffffffff81111525: irq_domain_translate_twocell (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_translate_twocell(struct irq_domain *d, struct irq_fwspec *fwspec, long unsigned int *out_hwirq, unsigned int *out_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8111d7c1)
Location: kernel/irq/irqdomain.c:997
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_xlate_twocell
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_translate
```
**Symbols:**

```
ffffffff8111d760-ffffffff8111d78a: irq_domain_translate_twocell (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_translate_twocell(struct irq_domain *d, struct irq_fwspec *fwspec, long unsigned int *out_hwirq, unsigned int *out_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8112a6f6)
Location: kernel/irq/irqdomain.c:999
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_xlate_twocell
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_translate
```
**Symbols:**

```
ffffffff811299b0-ffffffff811299da: irq_domain_translate_twocell (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_translate_twocell(struct irq_domain *d, struct irq_fwspec *fwspec, long unsigned int *out_hwirq, unsigned int *out_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81126216)
Location: kernel/irq/irqdomain.c:1023
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_xlate_twocell
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_translate
```
**Symbols:**

```
ffffffff81125260-ffffffff8112528a: irq_domain_translate_twocell (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_translate_twocell(struct irq_domain *d, struct irq_fwspec *fwspec, long unsigned int *out_hwirq, unsigned int *out_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811261d1)
Location: kernel/irq/irqdomain.c:990
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_xlate_twocell
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_translate
```
**Symbols:**

```
ffffffff811255c0-ffffffff811255ea: irq_domain_translate_twocell (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_translate_twocell(struct irq_domain *d, struct irq_fwspec *fwspec, long unsigned int *out_hwirq, unsigned int *out_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81145ce1)
Location: kernel/irq/irqdomain.c:1029
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_xlate_twocell
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_translate
```
**Symbols:**

```
ffffffff81145c80-ffffffff81145caa: irq_domain_translate_twocell (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_translate_twocell(struct irq_domain *d, struct irq_fwspec *fwspec, long unsigned int *out_hwirq, unsigned int *out_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81169ed6)
Location: kernel/irq/irqdomain.c:1031
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_xlate_twocell
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_translate
```
**Symbols:**

```
ffffffff81169e50-ffffffff81169e8e: irq_domain_translate_twocell (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_translate_twocell(struct irq_domain *d, struct irq_fwspec *fwspec, long unsigned int *out_hwirq, unsigned int *out_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8119e916)
Location: kernel/irq/irqdomain.c:1088
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_xlate_twocell
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_translate
```
**Symbols:**

```
ffffffff8119e880-ffffffff8119e8be: irq_domain_translate_twocell (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_translate_twocell(struct irq_domain *d, struct irq_fwspec *fwspec, long unsigned int *out_hwirq, unsigned int *out_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811b084f)
Location: kernel/irq/irqdomain.c:1069
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_xlate_twocell
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_translate
```
**Symbols:**

```
ffffffff811b07a0-ffffffff811b07de: irq_domain_translate_twocell (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_translate_twocell(struct irq_domain *d, struct irq_fwspec *fwspec, long unsigned int *out_hwirq, unsigned int *out_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811c05cf)
Location: kernel/irq/irqdomain.c:1069
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_xlate_twocell
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_translate
```
**Symbols:**

```
ffffffff811c0520-ffffffff811c055e: irq_domain_translate_twocell (STB_GLOBAL)
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
int irq_domain_translate_twocell(struct irq_domain *d, struct irq_fwspec *fwspec, long unsigned int *out_hwirq, unsigned int *out_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffff800010182c18)
Location: kernel/irq/irqdomain.c:997
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_xlate_twocell
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_translate
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_translate
```
**Symbols:**

```
ffff800010182b48-ffff800010182bb8: irq_domain_translate_twocell (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int irq_domain_translate_twocell(struct irq_domain *d, struct irq_fwspec *fwspec, long unsigned int *out_hwirq, unsigned int *out_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c03d1edc)
Location: kernel/irq/irqdomain.c:997
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_xlate_twocell
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_translate
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_translate
```
**Symbols:**

```
c03d1edc-c03d1f38: irq_domain_translate_twocell (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int irq_domain_translate_twocell(struct irq_domain *d, struct irq_fwspec *fwspec, long unsigned int *out_hwirq, unsigned int *out_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c0000000001dd510)
Location: kernel/irq/irqdomain.c:997
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_xlate_twocell
```
**Symbols:**

```
c0000000001dd510-c0000000001dd558: irq_domain_translate_twocell (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_translate_twocell(struct irq_domain *d, struct irq_fwspec *fwspec, long unsigned int *out_hwirq, unsigned int *out_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffe00011a100)
Location: kernel/irq/irqdomain.c:997
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_xlate_twocell
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_translate
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_translate
```
**Symbols:**

```
ffffffe00011a062-ffffffe00011a0ba: irq_domain_translate_twocell (STB_GLOBAL)
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
int irq_domain_translate_twocell(struct irq_domain *d, struct irq_fwspec *fwspec, long unsigned int *out_hwirq, unsigned int *out_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81115da1)
Location: kernel/irq/irqdomain.c:997
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_xlate_twocell
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_translate
```
**Symbols:**

```
ffffffff81115d40-ffffffff81115d6a: irq_domain_translate_twocell (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_translate_twocell(struct irq_domain *d, struct irq_fwspec *fwspec, long unsigned int *out_hwirq, unsigned int *out_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81106a91)
Location: kernel/irq/irqdomain.c:997
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_xlate_twocell
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_translate
```
**Symbols:**

```
ffffffff81106a30-ffffffff81106a5a: irq_domain_translate_twocell (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_translate_twocell(struct irq_domain *d, struct irq_fwspec *fwspec, long unsigned int *out_hwirq, unsigned int *out_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81113c91)
Location: kernel/irq/irqdomain.c:997
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_xlate_twocell
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_translate
```
**Symbols:**

```
ffffffff81113c30-ffffffff81113c5a: irq_domain_translate_twocell (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_translate_twocell(struct irq_domain *d, struct irq_fwspec *fwspec, long unsigned int *out_hwirq, unsigned int *out_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8111f2b1)
Location: kernel/irq/irqdomain.c:997
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_xlate_twocell
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_translate
```
**Symbols:**

```
ffffffff8111f250-ffffffff8111f27a: irq_domain_translate_twocell (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
