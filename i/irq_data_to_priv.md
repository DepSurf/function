# Function: <code>irq_data_to_priv</code>

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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-renesas-irqc.c (ffff800010676be4)
Location: drivers/irqchip/irq-renesas-irqc.c:56
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-irqc.c:irqc_irq_set_wake
  - drivers/irqchip/irq-renesas-irqc.c:irqc_irq_set_type
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-renesas-irqc.c (c081fa94)
Location: drivers/irqchip/irq-renesas-irqc.c:56
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-irqc.c:irqc_irq_set_wake
  - drivers/irqchip/irq-renesas-irqc.c:irqc_irq_set_type
```
```
In drivers/irqchip/irq-renesas-rza1.c (c081ffa8)
Location: drivers/irqchip/irq-renesas-rza1.c:49
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-rza1.c:rza1_irqc_set_type
  - drivers/irqchip/irq-renesas-rza1.c:rza1_irqc_eoi
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
