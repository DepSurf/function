# Function: <code>__devm_irq_alloc_descs</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __devm_irq_alloc_descs(struct device *dev, int irq, unsigned int from, unsigned int cnt, int node, struct module *owner, const struct cpumask *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/devres.c (ffffffff810ea8f0)
Location: kernel/irq/devres.c:179
Inline: False
```
**Symbols:**

```
ffffffff810ea8f0-ffffffff810ea992: __devm_irq_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __devm_irq_alloc_descs(struct device *dev, int irq, unsigned int from, unsigned int cnt, int node, struct module *owner, const struct cpumask *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/devres.c (ffffffff810f2e40)
Location: kernel/irq/devres.c:179
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
**Symbols:**

```
ffffffff810f2e40-ffffffff810f2ee2: __devm_irq_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __devm_irq_alloc_descs(struct device *dev, int irq, unsigned int from, unsigned int cnt, int node, struct module *owner, const struct cpumask *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/devres.c (ffffffff810fb210)
Location: kernel/irq/devres.c:180
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
**Symbols:**

```
ffffffff810fb210-ffffffff810fb2b2: __devm_irq_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __devm_irq_alloc_descs(struct device *dev, int irq, unsigned int from, unsigned int cnt, int node, struct module *owner, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/devres.c (ffffffff811069d0)
Location: kernel/irq/devres.c:180
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
**Symbols:**

```
ffffffff811069d0-ffffffff81106a72: __devm_irq_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __devm_irq_alloc_descs(struct device *dev, int irq, unsigned int from, unsigned int cnt, int node, struct module *owner, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/devres.c (ffffffff8110ff90)
Location: kernel/irq/devres.c:178
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
```
**Symbols:**

```
ffffffff8110ff90-ffffffff81110037: __devm_irq_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __devm_irq_alloc_descs(struct device *dev, int irq, unsigned int from, unsigned int cnt, int node, struct module *owner, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/devres.c (ffffffff8111c210)
Location: kernel/irq/devres.c:178
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
**Symbols:**

```
ffffffff8111c210-ffffffff8111c2b7: __devm_irq_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __devm_irq_alloc_descs(struct device *dev, int irq, unsigned int from, unsigned int cnt, int node, struct module *owner, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/devres.c (ffffffff81128540)
Location: kernel/irq/devres.c:178
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
```
**Symbols:**

```
ffffffff81128540-ffffffff811285e7: __devm_irq_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __devm_irq_alloc_descs(struct device *dev, int irq, unsigned int from, unsigned int cnt, int node, struct module *owner, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/devres.c (ffffffff81123e80)
Location: kernel/irq/devres.c:178
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
```
**Symbols:**

```
ffffffff81123e80-ffffffff81123f27: __devm_irq_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __devm_irq_alloc_descs(struct device *dev, int irq, unsigned int from, unsigned int cnt, int node, struct module *owner, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/devres.c (ffffffff811241d0)
Location: kernel/irq/devres.c:178
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
```
**Symbols:**

```
ffffffff811241d0-ffffffff81124273: __devm_irq_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __devm_irq_alloc_descs(struct device *dev, int irq, unsigned int from, unsigned int cnt, int node, struct module *owner, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/devres.c (ffffffff811447d0)
Location: kernel/irq/devres.c:178
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
```
**Symbols:**

```
ffffffff811447d0-ffffffff8114487a: __devm_irq_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __devm_irq_alloc_descs(struct device *dev, int irq, unsigned int from, unsigned int cnt, int node, struct module *owner, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/devres.c (ffffffff811686f0)
Location: kernel/irq/devres.c:178
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
```
**Symbols:**

```
ffffffff811686f0-ffffffff811687aa: __devm_irq_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __devm_irq_alloc_descs(struct device *dev, int irq, unsigned int from, unsigned int cnt, int node, struct module *owner, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/devres.c (ffffffff8119ce80)
Location: kernel/irq/devres.c:178
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
```
**Symbols:**

```
ffffffff8119ce80-ffffffff8119cf3a: __devm_irq_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __devm_irq_alloc_descs(struct device *dev, int irq, unsigned int from, unsigned int cnt, int node, struct module *owner, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/devres.c (ffffffff811aed00)
Location: kernel/irq/devres.c:178
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
```
**Symbols:**

```
ffffffff811aed00-ffffffff811aedba: __devm_irq_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __devm_irq_alloc_descs(struct device *dev, int irq, unsigned int from, unsigned int cnt, int node, struct module *owner, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/devres.c (ffffffff811be900)
Location: kernel/irq/devres.c:178
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
```
**Symbols:**

```
ffffffff811be900-ffffffff811be9ba: __devm_irq_alloc_descs (STB_GLOBAL)
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
int __devm_irq_alloc_descs(struct device *dev, int irq, unsigned int from, unsigned int cnt, int node, struct module *owner, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/devres.c (ffff800010180888)
Location: kernel/irq/devres.c:178
Inline: False
Direct callers:
  - drivers/gpio/gpio-davinci.c:davinci_gpio_irq_setup
  - drivers/gpio/gpio-mxc.c:mxc_gpio_probe
```
**Symbols:**

```
ffff800010180888-ffff800010180960: __devm_irq_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __devm_irq_alloc_descs(struct device *dev, int irq, unsigned int from, unsigned int cnt, int node, struct module *owner, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/devres.c (c03d06dc)
Location: kernel/irq/devres.c:178
Inline: False
Direct callers:
  - drivers/gpio/gpio-mxc.c:mxc_gpio_probe
  - drivers/gpio/gpio-twl4030.c:gpio_twl4030_probe
```
**Symbols:**

```
c03d06dc-c03d078c: __devm_irq_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __devm_irq_alloc_descs(struct device *dev, int irq, unsigned int from, unsigned int cnt, int node, struct module *owner, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/devres.c (c0000000001db430)
Location: kernel/irq/devres.c:178
Inline: False
```
**Symbols:**

```
c0000000001db430-c0000000001db578: __devm_irq_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __devm_irq_alloc_descs(struct device *dev, int irq, unsigned int from, unsigned int cnt, int node, struct module *owner, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/devres.c (ffffffe000118872)
Location: kernel/irq/devres.c:178
Inline: False
```
**Symbols:**

```
ffffffe000118872-ffffffe000118918: __devm_irq_alloc_descs (STB_GLOBAL)
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
int __devm_irq_alloc_descs(struct device *dev, int irq, unsigned int from, unsigned int cnt, int node, struct module *owner, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/devres.c (ffffffff811147f0)
Location: kernel/irq/devres.c:178
Inline: False
```
**Symbols:**

```
ffffffff811147f0-ffffffff81114897: __devm_irq_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __devm_irq_alloc_descs(struct device *dev, int irq, unsigned int from, unsigned int cnt, int node, struct module *owner, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/devres.c (ffffffff81105500)
Location: kernel/irq/devres.c:178
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
**Symbols:**

```
ffffffff81105500-ffffffff811055a7: __devm_irq_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __devm_irq_alloc_descs(struct device *dev, int irq, unsigned int from, unsigned int cnt, int node, struct module *owner, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/devres.c (ffffffff811126e0)
Location: kernel/irq/devres.c:178
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
**Symbols:**

```
ffffffff811126e0-ffffffff81112787: __devm_irq_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __devm_irq_alloc_descs(struct device *dev, int irq, unsigned int from, unsigned int cnt, int node, struct module *owner, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/devres.c (ffffffff8111dd00)
Location: kernel/irq/devres.c:178
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
**Symbols:**

```
ffffffff8111dd00-ffffffff8111dda7: __devm_irq_alloc_descs (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
