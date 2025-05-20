# Function: <code>generic_handle_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int generic_handle_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810d9fb0)
Location: kernel/irq/irqdesc.c:344
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/gpio/gpio-intel-mid.c:intel_mid_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-zx.c:zx_irq_handler
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
  - drivers/mfd/htc-i2cpld.c:htcpld_handler
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
```
**Symbols:**

```
ffffffff810d9fb0-ffffffff810d9fdd: generic_handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int generic_handle_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810df470)
Location: kernel/irq/irqdesc.c:402
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/gpio/gpio-zx.c:zx_irq_handler
  - drivers/pci/host/pcie-designware.c:dw_handle_msi_irq
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
  - drivers/mfd/htc-i2cpld.c:htcpld_handler
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
```
**Symbols:**

```
ffffffff810df470-ffffffff810df49d: generic_handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int generic_handle_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810e5ab0)
Location: kernel/irq/irqdesc.c:590
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/pci/host/pcie-designware.c:dw_handle_msi_irq
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
  - drivers/mfd/htc-i2cpld.c:htcpld_handler
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/i2c/i2c-core.c:i2c_handle_smbus_host_notify
```
**Symbols:**

```
ffffffff810e5ab0-ffffffff810e5add: generic_handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int generic_handle_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810e50c0)
Location: kernel/irq/irqdesc.c:607
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/pci/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify
```
**Symbols:**

```
ffffffff810e50c0-ffffffff810e50ed: generic_handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int generic_handle_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810ed320)
Location: kernel/irq/irqdesc.c:600
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/pci/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify
```
**Symbols:**

```
ffffffff810ed320-ffffffff810ed353: generic_handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int generic_handle_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810f56e0)
Location: kernel/irq/irqdesc.c:617
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify
```
**Symbols:**

```
ffffffff810f56e0-ffffffff810f5713: generic_handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int generic_handle_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81100e70)
Location: kernel/irq/irqdesc.c:622
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify
```
**Symbols:**

```
ffffffff81100e70-ffffffff81100ea3: generic_handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int generic_handle_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81109670)
Location: kernel/irq/irqdesc.c:638
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify
```
**Symbols:**

```
ffffffff81109670-ffffffff811096a3: generic_handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int generic_handle_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81115a40)
Location: kernel/irq/irqdesc.c:638
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify
```
**Symbols:**

```
ffffffff81115a40-ffffffff81115a73: generic_handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int generic_handle_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff811213f0)
Location: kernel/irq/irqdesc.c:638
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/gpio/gpio-msic.c:msic_gpio_irq_handler
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_fifo.c:consume_one_event
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify
```
**Symbols:**

```
ffffffff811213f0-ffffffff81121447: generic_handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int generic_handle_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8111d3d0)
Location: kernel/irq/irqdesc.c:640
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_community_irq_handler
  - drivers/gpio/gpio-msic.c:msic_gpio_irq_handler
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify
```
**Symbols:**

```
ffffffff8111d3d0-ffffffff8111d427: generic_handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int generic_handle_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8111d750)
Location: kernel/irq/irqdesc.c:640
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_community_irq_handler
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify
```
**Symbols:**

```
ffffffff8111d750-ffffffff8111d7a7: generic_handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int generic_handle_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8113db40)
Location: kernel/irq/irqdesc.c:656
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_community_irq_handler
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify
```
**Symbols:**

```
ffffffff8113db40-ffffffff8113db61: generic_handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int generic_handle_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81161a80)
Location: kernel/irq/irqdesc.c:661
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_community_irq_handler
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
```
**Symbols:**

```
ffffffff81161a80-ffffffff81161aa9: generic_handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int generic_handle_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81195190)
Location: kernel/irq/irqdesc.c:664
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_community_irq_handler
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
```
**Symbols:**

```
ffffffff81195190-ffffffff811951b9: generic_handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int generic_handle_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff811a6b20)
Location: kernel/irq/irqdesc.c:685
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
```
**Symbols:**

```
ffffffff811a6b20-ffffffff811a6b49: generic_handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int generic_handle_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff811b6640)
Location: kernel/irq/irqdesc.c:685
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
```
**Symbols:**

```
ffffffff811b6640-ffffffff811b6669: generic_handle_irq (STB_GLOBAL)
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
int generic_handle_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffff800010177270)
Location: kernel/irq/irqdesc.c:638
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:handle_domain_nmi
  - kernel/irq/irqdesc.c:__handle_domain_irq
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_handler
  - drivers/irqchip/irq-bcm2835.c:bcm2836_chained_handle_irq
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_handler
  - drivers/irqchip/irq-sunxi-nmi.c:sunxi_sc_nmi_handle_irq
  - drivers/irqchip/irq-sunxi-nmi.c:sunxi_sc_nmi_handle_irq
  - drivers/irqchip/irq-gic.c:gic_handle_cascade_irq
  - drivers/irqchip/irq-partition-percpu.c:partition_handle_irq
  - drivers/irqchip/irq-renesas-irqc.c:irqc_irq_handler
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_irq_handle
  - drivers/irqchip/irq-brcmstb-l2.c:brcmstb_l2_intc_irq_handle
  - drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_handle_cascade_irq
  - drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_handle_cascade_irq
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_irq_handler
  - drivers/irqchip/qcom-irq-combiner.c:combiner_handle_irq
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_handler
  - drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_irq_handler
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_demux
  - drivers/pinctrl/pinctrl-single.c:pcs_irq_handle
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_handler
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_handler
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_handle_bank
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_irq_handler
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_handler
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_handler
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_irq_handler
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_irq_handler
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_irq_handler
  - drivers/gpio/gpio-davinci.c:gpio_irq_handler
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_irq_handler
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_gpio_irq_cascade
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_irq_handler
  - drivers/gpio/gpio-mxc.c:mxc_gpio_irq_handler
  - drivers/gpio/gpio-mxc.c:mxc_gpio_irq_handler
  - drivers/gpio/gpio-pl061.c:pl061_irq_handler
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_handler
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_msi_irq
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_handle_msi_irq
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_leg_handler
  - drivers/pci/controller/pci-xgene-msi.c:xgene_msi_isr
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_handler
  - drivers/pci/controller/pcie-altera.c:altera_pcie_isr
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_isr
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_intr_handler
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_intr_handler
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_isr
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_isr
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_legacy_irq_handler
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_msi_irq_handler
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_handler
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify
  - drivers/edac/altera_edac.c:altr_edac_a10_irq_handler
```
**Symbols:**

```
ffff800010177270-ffff8000101772bc: generic_handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int generic_handle_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (c03c8ec8)
Location: kernel/irq/irqdesc.c:638
Inline: False
Direct callers:
  - arch/arm/mach-omap2/prm_common.c:omap_prcm_irq_handler
  - arch/arm/mach-omap2/prm_common.c:omap_prcm_irq_handler
  - kernel/irq/irqdesc.c:handle_domain_nmi
  - kernel/irq/irqdesc.c:__handle_domain_irq
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_handler
  - drivers/irqchip/exynos-combiner.c:combiner_handle_cascade_irq
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_handler
  - drivers/irqchip/irq-orion.c:orion_bridge_irq_handler
  - drivers/irqchip/irq-gic.c:gic_handle_cascade_irq
  - drivers/irqchip/irq-partition-percpu.c:partition_handle_irq
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_handle_cascade_irq
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_handle_msi_irq
  - drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_irq_handler
  - drivers/irqchip/irq-renesas-irqc.c:irqc_irq_handler
  - drivers/irqchip/irq-aspeed-i2c-ic.c:aspeed_i2c_ic_irq_handler
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_handler
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_demux
  - drivers/pinctrl/pinctrl-single.c:pcs_irq_handle
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_handler
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_handler
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_irq_handler
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_handler
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_irq_demux_eint16_31
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_irq_eint0_15
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_eint_gpio_irq
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_irq_handler
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_irq_handler
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_irq_handler
  - drivers/gpio/gpio-htc-egpio.c:egpio_handler
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_gpio_irq_cascade
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_irq_handler
  - drivers/gpio/gpio-mxc.c:mxc_gpio_irq_handler
  - drivers/gpio/gpio-omap.c:omap_gpio_irq_handler
  - drivers/gpio/gpio-pl061.c:pl061_irq_handler
  - drivers/gpio/gpio-tegra.c:tegra_gpio_irq_handler
  - drivers/gpio/gpio-vf610.c:vf610_gpio_irq_handler
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_handler
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_msi_irq
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_msi_irq
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler
  - drivers/pci/controller/pcie-altera.c:altera_pcie_isr
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_isr
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_intr_handler
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_intr_handler
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_msi_irq_handler
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_irq_handler
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_handler
  - drivers/soc/dove/pmu.c:pmu_irq_handler
  - drivers/mfd/asic3.c:asic3_irq_demux
  - drivers/mfd/asic3.c:asic3_irq_demux
  - drivers/mfd/t7l66xb.c:t7l66xb_irq
  - drivers/mfd/tc6393xb.c:tc6393xb_irq
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify
  - drivers/memory/omap-gpmc.c:gpmc_handle_irq
```
**Symbols:**

```
c03c8ec8-c03c8f0c: generic_handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int generic_handle_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (c0000000001d0b90)
Location: kernel/irq/irqdesc.c:638
Inline: False
Direct callers:
  - arch/powerpc/kernel/irq.c:__do_irq
  - arch/powerpc/sysdev/mpic.c:mpic_cascade
  - arch/powerpc/platforms/powernv/opal-irqchip.c:opal_handle_events
  - arch/powerpc/platforms/pseries/setup.c:pseries_8259_cascade
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_handler
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-single.c:pcs_irq_handle
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_handler
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_irq_handler
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_handler
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify
```
**Symbols:**

```
c0000000001d0b90-c0000000001d0bf8: generic_handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int generic_handle_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffe000112146)
Location: kernel/irq/irqdesc.c:638
Inline: False
Direct callers:
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_handler
  - drivers/irqchip/irq-sifive-plic.c:plic_handle_irq
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/pinctrl-single.c:pcs_irq_handle
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_handler
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_irq_handler
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_handler
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intr_handler
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify
```
**Symbols:**

```
ffffffe000112146-ffffffe000112188: generic_handle_irq (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int generic_handle_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8110e020)
Location: kernel/irq/irqdesc.c:638
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
```
**Symbols:**

```
ffffffff8110e020-ffffffff8110e053: generic_handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int generic_handle_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810fed80)
Location: kernel/irq/irqdesc.c:638
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
```
**Symbols:**

```
ffffffff810fed80-ffffffff810fedb3: generic_handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int generic_handle_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8110bf10)
Location: kernel/irq/irqdesc.c:638
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify
```
**Symbols:**

```
ffffffff8110bf10-ffffffff8110bf43: generic_handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int generic_handle_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81117440)
Location: kernel/irq/irqdesc.c:638
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify
```
**Symbols:**

```
ffffffff81117440-ffffffff81117473: generic_handle_irq (STB_GLOBAL)
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
