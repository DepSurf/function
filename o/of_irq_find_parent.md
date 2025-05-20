# Function: <code>of_irq_find_parent</code>

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
struct device_node *of_irq_find_parent(struct device_node *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/irq.c (ffff800010b74620)
Location: drivers/of/irq.c:54
Inline: True
Direct callers:
  - drivers/irqchip/irq-mvebu-gicp.c:mvebu_gicp_probe
  - drivers/irqchip/irq-ti-sci-intr.c:ti_sci_intr_irq_domain_probe
  - drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_irq_domain_probe
  - drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_request_resources
  - drivers/of/irq.c:of_irq_init
  - drivers/of/irq.c:of_irq_parse_one
  - drivers/of/irq.c:of_irq_parse_raw
  - drivers/of/irq.c:of_irq_parse_raw
```
**Symbols:**

```
ffff800010b74620-ffff800010b7470c: of_irq_find_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct device_node *of_irq_find_parent(struct device_node *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/irq.c (c0c56a40)
Location: drivers/of/irq.c:54
Inline: True
Direct callers:
  - drivers/irqchip/irq-alpine-msi.c:alpine_msix_init
  - drivers/irqchip/irq-renesas-rza1.c:rza1_irqc_probe
  - drivers/irqchip/irq-uniphier-aidet.c:uniphier_aidet_probe
  - drivers/of/irq.c:of_irq_init
  - drivers/of/irq.c:of_irq_parse_one
  - drivers/of/irq.c:of_irq_parse_raw
  - drivers/of/irq.c:of_irq_parse_raw
```
**Symbols:**

```
c0c56a40-c0c56b30: of_irq_find_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct device_node *of_irq_find_parent(struct device_node *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/irq.c (c000000000c516e0)
Location: drivers/of/irq.c:54
Inline: True
Direct callers:
  - drivers/of/irq.c:of_irq_init
  - drivers/of/irq.c:of_irq_parse_one
  - drivers/of/irq.c:of_irq_parse_raw
  - drivers/of/irq.c:of_irq_parse_raw
```
**Symbols:**

```
c000000000c516e0-c000000000c51814: of_irq_find_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct device_node *of_irq_find_parent(struct device_node *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/irq.c (ffffffe000727f6a)
Location: drivers/of/irq.c:54
Inline: True
Direct callers:
  - drivers/of/irq.c:of_irq_init
  - drivers/of/irq.c:of_irq_parse_one
  - drivers/of/irq.c:of_irq_parse_raw
  - drivers/of/irq.c:of_irq_parse_raw
```
**Symbols:**

```
ffffffe000727f6a-ffffffe00072801c: of_irq_find_parent (STB_GLOBAL)
```
</details>
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
