# Function: <code>asic3_read_register</code>

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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
u32 asic3_read_register(struct asic3 *asic, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/asic3.c (c0a0eeac)
Location: drivers/mfd/asic3.c:97
Inline: True
Inline callers:
  - drivers/mfd/asic3.c:asic3_clk_disable
  - drivers/mfd/asic3.c:asic3_clk_enable
  - drivers/mfd/asic3.c:asic3_gpio_set
  - drivers/mfd/asic3.c:asic3_gpio_get
  - drivers/mfd/asic3.c:asic3_gpio_direction
  - drivers/mfd/asic3.c:asic3_gpio_irq_type
  - drivers/mfd/asic3.c:asic3_gpio_irq_type
  - drivers/mfd/asic3.c:asic3_gpio_irq_type
  - drivers/mfd/asic3.c:asic3_unmask_irq
  - drivers/mfd/asic3.c:asic3_unmask_gpio_irq
  - drivers/mfd/asic3.c:asic3_mask_irq
  - drivers/mfd/asic3.c:asic3_mask_gpio_irq
  - drivers/mfd/asic3.c:asic3_irq_demux
  - drivers/mfd/asic3.c:asic3_irq_demux
  - drivers/mfd/asic3.c:asic3_irq_demux
  - drivers/mfd/asic3.c:asic3_set_register
```
**Symbols:**

```
c0a0e1b8-c0a0e1e8: asic3_read_register (STB_GLOBAL)
```
</details>
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
