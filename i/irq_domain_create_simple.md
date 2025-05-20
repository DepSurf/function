# Function: <code>irq_domain_create_simple</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct irq_domain *irq_domain_create_simple(struct fwnode_handle *fwnode, unsigned int size, unsigned int first_irq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:315
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_irqchip
  - drivers/mfd/max8998-irq.c:max8998_irq_init
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff81bd3c77-ffffffff81bd3c8b: irq_domain_create_simple.cold (STB_LOCAL)
ffffffff81126000-ffffffff81126078: irq_domain_create_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct irq_domain *irq_domain_create_simple(struct fwnode_handle *fwnode, unsigned int size, unsigned int first_irq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:325
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_irqchip
  - drivers/mfd/max8998-irq.c:max8998_irq_init
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff81cadca8-ffffffff81cadcbc: irq_domain_create_simple.cold (STB_LOCAL)
ffffffff811469f0-ffffffff81146a68: irq_domain_create_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct irq_domain *irq_domain_create_simple(struct fwnode_handle *fwnode, unsigned int size, unsigned int first_irq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:325
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_irqchip
  - drivers/mfd/max8998-irq.c:max8998_irq_init
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff81e5e197-ffffffff81e5e1ab: irq_domain_create_simple.cold (STB_LOCAL)
ffffffff8116ad70-ffffffff8116ae06: irq_domain_create_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct irq_domain *irq_domain_create_simple(struct fwnode_handle *fwnode, unsigned int size, unsigned int first_irq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8119fc80)
Location: kernel/irq/irqdomain.c:349
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_irqchip
  - drivers/mfd/max8998-irq.c:max8998_irq_init
  - drivers/mfd/tps6586x.c:tps6586x_irq_init
```
**Symbols:**

```
ffffffff8119fc80-ffffffff8119fd2e: irq_domain_create_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct irq_domain *irq_domain_create_simple(struct fwnode_handle *fwnode, unsigned int size, unsigned int first_irq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811b1870)
Location: kernel/irq/irqdomain.c:356
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_irqchip
  - drivers/mfd/max8998-irq.c:max8998_irq_init
  - drivers/mfd/tps6586x.c:tps6586x_irq_init
```
**Symbols:**

```
ffffffff811b1870-ffffffff811b191e: irq_domain_create_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct irq_domain *irq_domain_create_simple(struct fwnode_handle *fwnode, unsigned int size, unsigned int first_irq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811c1620)
Location: kernel/irq/irqdomain.c:356
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_irqchip
  - drivers/mfd/max8998-irq.c:max8998_irq_init
  - drivers/mfd/tps6586x.c:tps6586x_irq_init
```
**Symbols:**

```
ffffffff811c1620-ffffffff811c16ce: irq_domain_create_simple (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
