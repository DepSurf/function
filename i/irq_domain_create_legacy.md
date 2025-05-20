# Function: <code>irq_domain_create_legacy</code>

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
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct irq_domain *irq_domain_create_legacy(struct fwnode_handle *fwnode, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8112619e)
Location: kernel/irq/irqdomain.c:368
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
Direct callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
```
**Symbols:**

```
ffffffff81126000-ffffffff8112604e: irq_domain_create_legacy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct irq_domain *irq_domain_create_legacy(struct fwnode_handle *fwnode, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8112622e)
Location: kernel/irq/irqdomain.c:370
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
Direct callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
```
**Symbols:**

```
ffffffff81126080-ffffffff811260ce: irq_domain_create_legacy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct irq_domain *irq_domain_create_legacy(struct fwnode_handle *fwnode, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81146ade)
Location: kernel/irq/irqdomain.c:380
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
Direct callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
```
**Symbols:**

```
ffffffff81146a70-ffffffff81146abe: irq_domain_create_legacy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct irq_domain *irq_domain_create_legacy(struct fwnode_handle *fwnode, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8116ae8e)
Location: kernel/irq/irqdomain.c:380
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
Direct callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
```
**Symbols:**

```
ffffffff8116ae10-ffffffff8116ae6e: irq_domain_create_legacy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct irq_domain *irq_domain_create_legacy(struct fwnode_handle *fwnode, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8119fdde)
Location: kernel/irq/irqdomain.c:404
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
Direct callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
```
**Symbols:**

```
ffffffff8119fd40-ffffffff8119fda6: irq_domain_create_legacy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct irq_domain *irq_domain_create_legacy(struct fwnode_handle *fwnode, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811b1aee)
Location: kernel/irq/irqdomain.c:411
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
Direct callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
```
**Symbols:**

```
ffffffff811b17f0-ffffffff811b1856: irq_domain_create_legacy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct irq_domain *irq_domain_create_legacy(struct fwnode_handle *fwnode, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811c189e)
Location: kernel/irq/irqdomain.c:411
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
Direct callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
```
**Symbols:**

```
ffffffff811c15a0-ffffffff811c1606: irq_domain_create_legacy (STB_GLOBAL)
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
