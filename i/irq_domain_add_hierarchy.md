# Function: <code>irq_domain_add_hierarchy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff816f4d8c)
Location: include/linux/irqdomain.h:350
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff81592885)
Location: include/linux/irqdomain.h:380
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff815c0145)
Location: include/linux/irqdomain.h:387
Inline: True
```
</details>
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-mtk-sysirq.c (ffff800011475a1c)
Location: include/linux/irqdomain.h:453
Inline: True
Inline callers:
  - drivers/irqchip/irq-mtk-sysirq.c:mtk_sysirq_of_init
```
```
In drivers/irqchip/irq-mtk-cirq.c (ffff800011475bf0)
Location: include/linux/irqdomain.h:453
Inline: True
Inline callers:
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_of_init
```
```
In drivers/irqchip/irq-imx-gpcv2.c (ffff800011475d78)
Location: include/linux/irqdomain.h:453
Inline: True
Inline callers:
  - drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irqchip_init
```
```
In drivers/irqchip/irq-sni-exiu.c (ffff8000114764ec)
Location: include/linux/irqdomain.h:453
Inline: True
Inline callers:
  - drivers/irqchip/irq-sni-exiu.c:exiu_dt_init
```
```
In drivers/irqchip/irq-ti-sci-intr.c (ffff80001067e084)
Location: include/linux/irqdomain.h:453
Inline: True
Inline callers:
  - drivers/irqchip/irq-ti-sci-intr.c:ti_sci_intr_irq_domain_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/mach-exynos/suspend.c (c150c81c)
Location: include/linux/irqdomain.h:453
Inline: True
Inline callers:
  - arch/arm/mach-exynos/suspend.c:exynos_pmu_irq_init
```
```
In arch/arm/mach-imx/gpc.c (c150f210)
Location: include/linux/irqdomain.h:453
Inline: True
Inline callers:
  - arch/arm/mach-imx/gpc.c:imx_gpc_init
```
```
In arch/arm/mach-omap2/omap-wakeupgen.c (c1515094)
Location: include/linux/irqdomain.h:453
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap-wakeupgen.c:wakeupgen_init
```
```
In drivers/irqchip/irq-tegra.c (c1549ea0)
Location: include/linux/irqdomain.h:453
Inline: True
Inline callers:
  - drivers/irqchip/irq-tegra.c:tegra_ictlr_init
```
```
In drivers/irqchip/irq-renesas-rza1.c (c08204c4)
Location: include/linux/irqdomain.h:453
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-rza1.c:rza1_irqc_probe
```
```
In drivers/irqchip/irq-crossbar.c (c154dc1c)
Location: include/linux/irqdomain.h:453
Inline: True
Inline callers:
  - drivers/irqchip/irq-crossbar.c:irqcrossbar_init
```
```
In drivers/irqchip/irq-vf610-mscm-ir.c (c154dd7c)
Location: include/linux/irqdomain.h:453
Inline: True
Inline callers:
  - drivers/irqchip/irq-vf610-mscm-ir.c:vf610_mscm_ir_of_init
```
```
In drivers/irqchip/irq-mtk-sysirq.c (c154e050)
Location: include/linux/irqdomain.h:453
Inline: True
Inline callers:
  - drivers/irqchip/irq-mtk-sysirq.c:mtk_sysirq_of_init
```
```
In drivers/irqchip/irq-mtk-cirq.c (c154e22c)
Location: include/linux/irqdomain.h:453
Inline: True
Inline callers:
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_of_init
```
```
In drivers/irqchip/irq-imx-gpcv2.c (c154e390)
Location: include/linux/irqdomain.h:453
Inline: True
Inline callers:
  - drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irqchip_init
```
```
In drivers/soc/tegra/pmc.c (c093cf34)
Location: include/linux/irqdomain.h:453
Inline: True
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
