# Function: <code>irq_create_fwspec_mapping</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int irq_create_fwspec_mapping(struct irq_fwspec *fwspec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e1460)
Location: kernel/irq/irqdomain.c:571
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_of_mapping
```
**Symbols:**

```
ffffffff810e1460-ffffffff810e15e4: irq_create_fwspec_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int irq_create_fwspec_mapping(struct irq_fwspec *fwspec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e6fe0)
Location: kernel/irq/irqdomain.c:567
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_of_mapping
```
**Symbols:**

```
ffffffff810e6fe0-ffffffff810e724d: irq_create_fwspec_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int irq_create_fwspec_mapping(struct irq_fwspec *fwspec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ed9d0)
Location: kernel/irq/irqdomain.c:590
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_of_mapping
```
**Symbols:**

```
ffffffff810ed9d0-ffffffff810edc3d: irq_create_fwspec_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int irq_create_fwspec_mapping(struct irq_fwspec *fwspec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ed3a0)
Location: kernel/irq/irqdomain.c:728
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_of_mapping
```
**Symbols:**

```
ffffffff810ed3a0-ffffffff810ed5ef: irq_create_fwspec_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int irq_create_fwspec_mapping(struct irq_fwspec *fwspec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810f5da0)
Location: kernel/irq/irqdomain.c:742
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_of_mapping
```
**Symbols:**

```
ffffffff810f5da0-ffffffff810f6009: irq_create_fwspec_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
unsigned int irq_create_fwspec_mapping(struct irq_fwspec *fwspec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:744
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_of_mapping
```
**Symbols:**

```
ffffffff810fe50c-ffffffff810fe546: irq_create_fwspec_mapping.cold.29 (STB_LOCAL)
ffffffff810fe140-ffffffff810fe389: irq_create_fwspec_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
unsigned int irq_create_fwspec_mapping(struct irq_fwspec *fwspec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:744
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_of_mapping
```
**Symbols:**

```
ffffffff81109cdc-ffffffff81109d16: irq_create_fwspec_mapping.cold.28 (STB_LOCAL)
ffffffff81109910-ffffffff81109b59: irq_create_fwspec_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
unsigned int irq_create_fwspec_mapping(struct irq_fwspec *fwspec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:759
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_of_mapping
```
**Symbols:**

```
ffffffff811133b4-ffffffff81113405: irq_create_fwspec_mapping.cold (STB_LOCAL)
ffffffff81112f00-ffffffff8111313c: irq_create_fwspec_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
unsigned int irq_create_fwspec_mapping(struct irq_fwspec *fwspec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:761
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_of_mapping
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
```
**Symbols:**

```
ffffffff8111f54f-ffffffff8111f589: irq_create_fwspec_mapping.cold (STB_LOCAL)
ffffffff8111f190-ffffffff8111f3da: irq_create_fwspec_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
unsigned int irq_create_fwspec_mapping(struct irq_fwspec *fwspec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:746
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_of_mapping
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
```
**Symbols:**

```
ffffffff8112ba8e-ffffffff8112bac8: irq_create_fwspec_mapping.cold (STB_LOCAL)
ffffffff8112b6d0-ffffffff8112b91a: irq_create_fwspec_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
unsigned int irq_create_fwspec_mapping(struct irq_fwspec *fwspec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:770
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_of_mapping
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
```
**Symbols:**

```
ffffffff81be1c34-ffffffff81be1c6e: irq_create_fwspec_mapping.cold (STB_LOCAL)
ffffffff81127190-ffffffff811273dc: irq_create_fwspec_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
unsigned int irq_create_fwspec_mapping(struct irq_fwspec *fwspec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:737
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_of_mapping
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
```
**Symbols:**

```
ffffffff81bd3ceb-ffffffff81bd3d25: irq_create_fwspec_mapping.cold (STB_LOCAL)
ffffffff81127450-ffffffff8112769c: irq_create_fwspec_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
unsigned int irq_create_fwspec_mapping(struct irq_fwspec *fwspec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:760
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_of_mapping
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
```
**Symbols:**

```
ffffffff81cadcfb-ffffffff81cadd35: irq_create_fwspec_mapping.cold (STB_LOCAL)
ffffffff811479b0-ffffffff81147c0b: irq_create_fwspec_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
unsigned int irq_create_fwspec_mapping(struct irq_fwspec *fwspec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:760
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_of_mapping
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
```
**Symbols:**

```
ffffffff81e5e1eb-ffffffff81e5e21f: irq_create_fwspec_mapping.cold (STB_LOCAL)
ffffffff8116be30-ffffffff8116c08a: irq_create_fwspec_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int irq_create_fwspec_mapping(struct irq_fwspec *fwspec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811a06d0)
Location: kernel/irq/irqdomain.c:810
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_of_mapping
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
```
**Symbols:**

```
ffffffff811a06d0-ffffffff811a0957: irq_create_fwspec_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int irq_create_fwspec_mapping(struct irq_fwspec *fwspec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811b2540)
Location: kernel/irq/irqdomain.c:791
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_of_mapping
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
```
**Symbols:**

```
ffffffff811b2540-ffffffff811b27ca: irq_create_fwspec_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int irq_create_fwspec_mapping(struct irq_fwspec *fwspec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811c2330)
Location: kernel/irq/irqdomain.c:791
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_of_mapping
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
```
**Symbols:**

```
ffffffff811c2330-ffffffff811c25ba: irq_create_fwspec_mapping (STB_GLOBAL)
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
unsigned int irq_create_fwspec_mapping(struct irq_fwspec *fwspec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffff800010184cf8)
Location: kernel/irq/irqdomain.c:761
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_of_mapping
  - drivers/irqchip/irq-gic-v3.c:gic_populate_ppi_partitions
  - drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_request_resources
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/acpi/irq.c:acpi_irq_get
  - drivers/acpi/irq.c:acpi_register_gsi
```
**Symbols:**

```
ffff800010184cf8-ffff800010185008: irq_create_fwspec_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int irq_create_fwspec_mapping(struct irq_fwspec *fwspec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c03d3da0)
Location: kernel/irq/irqdomain.c:761
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_of_mapping
  - drivers/irqchip/irq-gic-v3.c:gic_populate_ppi_partitions
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
```
**Symbols:**

```
c03d3da0-c03d40f0: irq_create_fwspec_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int irq_create_fwspec_mapping(struct irq_fwspec *fwspec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c0000000001df110)
Location: kernel/irq/irqdomain.c:761
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_of_mapping
```
**Symbols:**

```
c0000000001df110-c0000000001df484: irq_create_fwspec_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int irq_create_fwspec_mapping(struct irq_fwspec *fwspec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffe00011bb82)
Location: kernel/irq/irqdomain.c:761
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_of_mapping
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
```
**Symbols:**

```
ffffffe00011bb82-ffffffe00011bde8: irq_create_fwspec_mapping (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
unsigned int irq_create_fwspec_mapping(struct irq_fwspec *fwspec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:761
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_of_mapping
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
```
**Symbols:**

```
ffffffff81117b2f-ffffffff81117b69: irq_create_fwspec_mapping.cold (STB_LOCAL)
ffffffff81117770-ffffffff811179ba: irq_create_fwspec_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
unsigned int irq_create_fwspec_mapping(struct irq_fwspec *fwspec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:761
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_of_mapping
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
```
**Symbols:**

```
ffffffff8110881f-ffffffff81108859: irq_create_fwspec_mapping.cold (STB_LOCAL)
ffffffff81108460-ffffffff811086aa: irq_create_fwspec_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
unsigned int irq_create_fwspec_mapping(struct irq_fwspec *fwspec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:761
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_of_mapping
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
```
**Symbols:**

```
ffffffff81115a1f-ffffffff81115a59: irq_create_fwspec_mapping.cold (STB_LOCAL)
ffffffff81115660-ffffffff811158aa: irq_create_fwspec_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
unsigned int irq_create_fwspec_mapping(struct irq_fwspec *fwspec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:761
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_of_mapping
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
```
**Symbols:**

```
ffffffff8112104f-ffffffff81121089: irq_create_fwspec_mapping.cold (STB_LOCAL)
ffffffff81120c90-ffffffff81120eda: irq_create_fwspec_mapping (STB_GLOBAL)
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
