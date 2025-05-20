# Function: <code>bcm2835_gpio_irq_config</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void bcm2835_gpio_irq_config(struct bcm2835_pinctrl *pc, unsigned int offset, bool enable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/bcm/pinctrl-bcm2835.c (ffff8000106a3cb8)
Location: drivers/pinctrl/bcm/pinctrl-bcm2835.c:426
Inline: True
Direct callers:
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_set_type
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_set_type
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_set_type
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_set_type
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_set_type
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_set_type
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_set_type
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_set_type
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_set_type
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_set_type
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_set_type
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_disable
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_enable
```
**Symbols:**

```
ffff8000106a3cb8-ffff8000106a3ea0: bcm2835_gpio_irq_config (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
