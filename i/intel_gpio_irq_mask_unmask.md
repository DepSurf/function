# Function: <code>intel_gpio_irq_mask_unmask</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void intel_gpio_irq_mask_unmask(struct irq_data *d, bool mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff814d4f10)
Location: drivers/pinctrl/intel/pinctrl-intel.c:910
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_unmask
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_mask
```
**Symbols:**

```
ffffffff814d4f10-ffffffff814d4fdb: intel_gpio_irq_mask_unmask (STB_LOCAL)
```
</details>
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
<summary>In <code>5.11</code>: ✅</summary>

```c
void intel_gpio_irq_mask_unmask(struct irq_data *d, bool mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff816319d0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:1035
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_unmask
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_mask
```
**Symbols:**

```
ffffffff816319d0-ffffffff81631ab8: intel_gpio_irq_mask_unmask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void intel_gpio_irq_mask_unmask(struct irq_data *d, bool mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81615450)
Location: drivers/pinctrl/intel/pinctrl-intel.c:1045
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_unmask
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_mask
```
**Symbols:**

```
ffffffff81615450-ffffffff81615533: intel_gpio_irq_mask_unmask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void intel_gpio_irq_mask_unmask(struct irq_data *d, bool mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:1042
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_unmask
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_mask
```
**Symbols:**

```
ffffffff816846e0-ffffffff816847f0: intel_gpio_irq_mask_unmask (STB_LOCAL)
ffffffff81ce1200-ffffffff81ce1273: intel_gpio_irq_mask_unmask.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void intel_gpio_irq_mask_unmask(struct gpio_chip *gc, irq_hw_number_t hwirq, bool mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:1047
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_unmask
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_mask
```
**Symbols:**

```
ffffffff817a0da0-ffffffff817a0ebb: intel_gpio_irq_mask_unmask (STB_LOCAL)
ffffffff81ea79be-ffffffff81ea7a44: intel_gpio_irq_mask_unmask.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void intel_gpio_irq_mask_unmask(struct gpio_chip *gc, irq_hw_number_t hwirq, bool mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:1059
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_unmask
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_mask
```
**Symbols:**

```
ffffffff818b7fd0-ffffffff818b80eb: intel_gpio_irq_mask_unmask (STB_LOCAL)
ffffffff8208e3dd-ffffffff8208e463: intel_gpio_irq_mask_unmask.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void intel_gpio_irq_mask_unmask(struct gpio_chip *gc, irq_hw_number_t hwirq, bool mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:1071
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_unmask
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_mask
```
**Symbols:**

```
ffffffff818fb040-ffffffff818fb15b: intel_gpio_irq_mask_unmask (STB_LOCAL)
ffffffff8210e6b9-ffffffff8210e73f: intel_gpio_irq_mask_unmask.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void intel_gpio_irq_mask_unmask(struct gpio_chip *gc, irq_hw_number_t hwirq, bool mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: drivers/pinctrl/intel/pinctrl-intel.c:1039
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_unmask
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_mask
```
**Symbols:**

```
ffffffff81942660-ffffffff81942784: intel_gpio_irq_mask_unmask (STB_LOCAL)
ffffffff821ec317-ffffffff821ec39d: intel_gpio_irq_mask_unmask.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct gpio_chip *gc</code>
</li>
<li>
<b>Param added. </b>
<code>irq_hw_number_t hwirq</code>
</li>
<li>
<b>Param removed. </b>
<code>struct irq_data *d</code>
</li>
<li>
<b>Param reordered. </b>
<code>d, mask</code> ➡️ <code>gc, hwirq, mask</code>
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
