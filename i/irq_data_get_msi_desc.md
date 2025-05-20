# Function: <code>irq_data_get_msi_desc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814546da)
Location: include/linux/irq.h:647
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_set_mask_bit
  - drivers/pci/msi.c:pci_msi_domain_write_msg
```
```
In drivers/base/platform-msi.c (ffffffff8156cab6)
Location: include/linux/irq.h:647
Inline: True
Inline callers:
  - drivers/base/platform-msi.c:platform_msi_write_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814a1c85)
Location: include/linux/irq.h:676
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_domain_write_msg
  - drivers/pci/msi.c:msi_set_mask_bit
```
```
In drivers/pci/host/pcie-designware.c (0)
Location: include/linux/irq.h:676
Inline: True
```
```
In drivers/base/platform-msi.c (ffffffff815c1f86)
Location: include/linux/irq.h:676
Inline: True
Inline callers:
  - drivers/base/platform-msi.c:platform_msi_write_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814c38d5)
Location: include/linux/irq.h:693
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_domain_write_msg
  - drivers/pci/msi.c:msi_set_mask_bit
```
```
In drivers/pci/host/pcie-designware.c (0)
Location: include/linux/irq.h:693
Inline: True
```
```
In drivers/base/platform-msi.c (ffffffff815f13d6)
Location: include/linux/irq.h:693
Inline: True
Inline callers:
  - drivers/base/platform-msi.c:platform_msi_write_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814cdf25)
Location: include/linux/irq.h:743
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_domain_write_msg
  - drivers/pci/msi.c:msi_set_mask_bit
```
```
In drivers/pci/dwc/pcie-designware-host.c (0)
Location: include/linux/irq.h:743
Inline: True
```
```
In drivers/base/platform-msi.c (ffffffff81605536)
Location: include/linux/irq.h:743
Inline: True
Inline callers:
  - drivers/base/platform-msi.c:platform_msi_write_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8150e465)
Location: include/linux/irq.h:772
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_domain_write_msg
  - drivers/pci/msi.c:msi_set_mask_bit
```
```
In drivers/pci/dwc/pcie-designware-host.c (0)
Location: include/linux/irq.h:772
Inline: True
```
```
In drivers/base/platform-msi.c (ffffffff8166d936)
Location: include/linux/irq.h:772
Inline: True
Inline callers:
  - drivers/base/platform-msi.c:platform_msi_write_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81543365)
Location: include/linux/irq.h:774
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_domain_write_msg
  - drivers/pci/msi.c:msi_set_mask_bit
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff81548f85)
Location: include/linux/irq.h:774
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pci_bottom_ack
```
```
In drivers/base/platform-msi.c (ffffffff816a9375)
Location: include/linux/irq.h:774
Inline: True
Inline callers:
  - drivers/base/platform-msi.c:platform_msi_write_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8155a6e5)
Location: include/linux/irq.h:775
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_domain_write_msg
  - drivers/pci/msi.c:msi_set_mask_bit
```
```
In drivers/base/platform-msi.c (ffffffff816c9f55)
Location: include/linux/irq.h:775
Inline: True
Inline callers:
  - drivers/base/platform-msi.c:platform_msi_write_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8158a7d5)
Location: include/linux/irq.h:788
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_domain_write_msg
  - drivers/pci/msi.c:msi_set_mask_bit
```
```
In drivers/base/platform-msi.c (ffffffff817054e5)
Location: include/linux/irq.h:788
Inline: True
Inline callers:
  - drivers/base/platform-msi.c:platform_msi_write_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff815ac155)
Location: include/linux/irq.h:806
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_domain_write_msg
  - drivers/pci/msi.c:msi_set_mask_bit
```
```
In drivers/base/platform-msi.c (ffffffff81729775)
Location: include/linux/irq.h:806
Inline: True
Inline callers:
  - drivers/base/platform-msi.c:platform_msi_write_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81655255)
Location: include/linux/irq.h:836
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_domain_write_msg
  - drivers/pci/msi.c:pci_msi_unmask_irq
  - drivers/pci/msi.c:pci_msi_mask_irq
```
```
In drivers/base/platform-msi.c (ffffffff817e5fa5)
Location: include/linux/irq.h:836
Inline: True
Inline callers:
  - drivers/base/platform-msi.c:platform_msi_write_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8165ed75)
Location: include/linux/irq.h:849
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_domain_write_msg
  - drivers/pci/msi.c:pci_msi_unmask_irq
  - drivers/pci/msi.c:pci_msi_mask_irq
```
```
In drivers/base/platform-msi.c (ffffffff817fac35)
Location: include/linux/irq.h:849
Inline: True
Inline callers:
  - drivers/base/platform-msi.c:platform_msi_write_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/irqdomain.c (ffffffff81033714)
Location: include/linux/irq.h:851
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
```
```
In drivers/pci/msi.c (ffffffff81641265)
Location: include/linux/irq.h:851
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_domain_write_msg
  - drivers/pci/msi.c:pci_msi_unmask_irq
  - drivers/pci/msi.c:pci_msi_mask_irq
```
```
In drivers/base/platform-msi.c (ffffffff817df955)
Location: include/linux/irq.h:851
Inline: True
Inline callers:
  - drivers/base/platform-msi.c:platform_msi_write_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/irqdomain.c (ffffffff810388c4)
Location: include/linux/irq.h:853
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
```
```
In drivers/pci/msi.c (ffffffff816b1e65)
Location: include/linux/irq.h:853
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_domain_write_msg
  - drivers/pci/msi.c:pci_msi_unmask_irq
  - drivers/pci/msi.c:pci_msi_mask_irq
```
```
In drivers/base/platform-msi.c (ffffffff8186b415)
Location: include/linux/irq.h:853
Inline: True
Inline callers:
  - drivers/base/platform-msi.c:platform_msi_write_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/irqdomain.c (ffffffff8103e743)
Location: include/linux/irq.h:857
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_msi_free_irq
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
```
```
In drivers/pci/msi/msi.c (ffffffff817d3905)
Location: include/linux/irq.h:857
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:pci_msi_unmask_irq
  - drivers/pci/msi/msi.c:pci_msi_mask_irq
```
```
In drivers/pci/msi/irqdomain.c (ffffffff817d5675)
Location: include/linux/irq.h:857
Inline: True
Inline callers:
  - drivers/pci/msi/irqdomain.c:pci_msi_domain_write_msg
```
```
In drivers/base/platform-msi.c (ffffffff819b4195)
Location: include/linux/irq.h:857
Inline: True
Inline callers:
  - drivers/base/platform-msi.c:platform_msi_write_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/irqdomain.c (ffffffff81047793)
Location: include/linux/irq.h:859
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_msi_free_irq
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
```
```
In drivers/pci/msi/msi.c (ffffffff818f4e35)
Location: include/linux/irq.h:859
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:pci_msi_unmask_irq
  - drivers/pci/msi/msi.c:pci_msi_mask_irq
```
```
In drivers/pci/msi/irqdomain.c (ffffffff818f6565)
Location: include/linux/irq.h:859
Inline: True
Inline callers:
  - drivers/pci/msi/irqdomain.c:pci_irq_unmask_msix
  - drivers/pci/msi/irqdomain.c:pci_irq_mask_msix
  - drivers/pci/msi/irqdomain.c:pci_irq_unmask_msi
  - drivers/pci/msi/irqdomain.c:pci_irq_mask_msi
  - drivers/pci/msi/irqdomain.c:pci_msi_domain_write_msg
```
```
In drivers/base/platform-msi.c (ffffffff81b29085)
Location: include/linux/irq.h:859
Inline: True
Inline callers:
  - drivers/base/platform-msi.c:platform_msi_write_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/irqdomain.c (ffffffff810479cf)
Location: include/linux/irq.h:872
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_msi_free_irq
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
```
```
In drivers/pci/msi/msi.c (ffffffff81938265)
Location: include/linux/irq.h:872
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:pci_msi_unmask_irq
  - drivers/pci/msi/msi.c:pci_msi_mask_irq
```
```
In drivers/pci/msi/irqdomain.c (ffffffff819399c5)
Location: include/linux/irq.h:872
Inline: True
Inline callers:
  - drivers/pci/msi/irqdomain.c:pci_irq_unmask_msix
  - drivers/pci/msi/irqdomain.c:pci_irq_mask_msix
  - drivers/pci/msi/irqdomain.c:pci_irq_unmask_msi
  - drivers/pci/msi/irqdomain.c:pci_irq_mask_msi
  - drivers/pci/msi/irqdomain.c:pci_msi_domain_write_msg
```
```
In drivers/base/platform-msi.c (ffffffff81b79235)
Location: include/linux/irq.h:872
Inline: True
Inline callers:
  - drivers/base/platform-msi.c:platform_msi_write_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/irqdomain.c (ffffffff8104e79f)
Location: include/linux/irq.h:854
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_msi_free_irq
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
```
```
In drivers/pci/msi/msi.c (ffffffff819810c5)
Location: include/linux/irq.h:854
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:pci_msi_unmask_irq
  - drivers/pci/msi/msi.c:pci_msi_mask_irq
```
```
In drivers/pci/msi/irqdomain.c (ffffffff81982825)
Location: include/linux/irq.h:854
Inline: True
Inline callers:
  - drivers/pci/msi/irqdomain.c:pci_irq_unmask_msix
  - drivers/pci/msi/irqdomain.c:pci_irq_mask_msix
  - drivers/pci/msi/irqdomain.c:pci_irq_unmask_msi
  - drivers/pci/msi/irqdomain.c:pci_irq_mask_msi
  - drivers/pci/msi/irqdomain.c:pci_msi_domain_write_msg
```
```
In drivers/base/platform-msi.c (ffffffff81bcd135)
Location: include/linux/irq.h:854
Inline: True
Inline callers:
  - drivers/base/platform-msi.c:platform_msi_write_msg
```
</details>
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
In drivers/irqchip/irq-gic-v2m.c (ffff80001066d32c)
Location: include/linux/irq.h:806
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_compose_msi_msg
```
```
In drivers/irqchip/irq-gic-v3-mbi.c (ffff80001066f98c)
Location: include/linux/irq.h:806
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-mbi.c:mbi_compose_mbi_msg
  - drivers/irqchip/irq-gic-v3-mbi.c:mbi_compose_msi_msg
```
```
In drivers/irqchip/irq-gic-v3-its.c (ffff800010670c08)
Location: include/linux/irq.h:806
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_compose_msi_msg
```
```
In drivers/irqchip/irq-ls-scfg-msi.c (ffff80001067b204)
Location: include/linux/irq.h:806
Inline: True
Inline callers:
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_compose_msg
```
```
In drivers/bus/fsl-mc/fsl-mc-msi.c (ffff80001068493c)
Location: include/linux/irq.h:806
Inline: True
Inline callers:
  - drivers/bus/fsl-mc/fsl-mc-msi.c:fsl_mc_msi_write_msg
```
```
In drivers/pci/msi.c (ffff800010715bec)
Location: include/linux/irq.h:806
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_domain_write_msg
  - drivers/pci/msi.c:msi_set_mask_bit
```
```
In drivers/base/platform-msi.c (ffff80001091f5c4)
Location: include/linux/irq.h:806
Inline: True
Inline callers:
  - drivers/base/platform-msi.c:platform_msi_write_msg
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
In drivers/irqchip/irq-gic-v2m.c (0)
Location: include/linux/irq.h:806
Inline: True
```
```
In drivers/irqchip/irq-gic-v3-mbi.c (0)
Location: include/linux/irq.h:806
Inline: True
```
```
In drivers/irqchip/irq-gic-v3-its.c (0)
Location: include/linux/irq.h:806
Inline: True
```
```
In drivers/pci/msi.c (c08a0560)
Location: include/linux/irq.h:806
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_domain_write_msg
  - drivers/pci/msi.c:msi_set_mask_bit
```
```
In drivers/base/platform-msi.c (c0a047bc)
Location: include/linux/irq.h:806
Inline: True
Inline callers:
  - drivers/base/platform-msi.c:platform_msi_write_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/sysdev/xics/ics-rtas.c (c0000000000bbb90)
Location: include/linux/irq.h:806
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xics/ics-rtas.c:ics_rtas_startup
```
```
In arch/powerpc/sysdev/xics/ics-opal.c (c0000000000bc290)
Location: include/linux/irq.h:806
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xics/ics-opal.c:ics_opal_startup
```
```
In arch/powerpc/sysdev/xive/common.c (c0000000000be858)
Location: include/linux/irq.h:806
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xive/common.c:xive_irq_startup
```
```
In drivers/pci/msi.c (c000000000884700)
Location: include/linux/irq.h:806
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_set_mask_bit
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffe0004df2f0)
Location: include/linux/irq.h:806
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_domain_write_msg
  - drivers/pci/msi.c:msi_set_mask_bit
```
```
In drivers/base/platform-msi.c (ffffffe00059e544)
Location: include/linux/irq.h:806
Inline: True
Inline callers:
  - drivers/base/platform-msi.c:platform_msi_write_msg
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8159f925)
Location: include/linux/irq.h:806
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_domain_write_msg
  - drivers/pci/msi.c:msi_set_mask_bit
```
```
In drivers/base/platform-msi.c (ffffffff816ef555)
Location: include/linux/irq.h:806
Inline: True
Inline callers:
  - drivers/base/platform-msi.c:platform_msi_write_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8158eab5)
Location: include/linux/irq.h:806
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_domain_write_msg
  - drivers/pci/msi.c:msi_set_mask_bit
```
```
In drivers/base/platform-msi.c (ffffffff816c9665)
Location: include/linux/irq.h:806
Inline: True
Inline callers:
  - drivers/base/platform-msi.c:platform_msi_write_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8159fea5)
Location: include/linux/irq.h:806
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_domain_write_msg
  - drivers/pci/msi.c:msi_set_mask_bit
```
```
In drivers/base/platform-msi.c (ffffffff8171cc35)
Location: include/linux/irq.h:806
Inline: True
Inline callers:
  - drivers/base/platform-msi.c:platform_msi_write_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff815ba2d5)
Location: include/linux/irq.h:806
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_domain_write_msg
  - drivers/pci/msi.c:msi_set_mask_bit
```
```
In drivers/base/platform-msi.c (ffffffff81737f95)
Location: include/linux/irq.h:806
Inline: True
Inline callers:
  - drivers/base/platform-msi.c:platform_msi_write_msg
```
</details>
</li>
</ul>

## Differences
