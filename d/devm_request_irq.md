# Function: <code>devm_request_irq</code>

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
In drivers/char/tpm/tpm_tis.c (ffffffff81528726)
Location: include/linux/interrupt.h:160
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_probe_irq_single
```
```
In drivers/misc/bmp085.c (ffffffff8157947a)
Location: include/linux/interrupt.h:160
Inline: True
Inline callers:
  - drivers/misc/bmp085.c:bmp085_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff8158bbda)
Location: include/linux/interrupt.h:160
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/da903x.c (ffffffff8158c2fb)
Location: include/linux/interrupt.h:160
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/ata/libata-core.c (ffffffff815cf79f)
Location: include/linux/interrupt.h:160
Inline: True
```
```
In drivers/ata/libata-sff.c (ffffffff815dd1e4)
Location: include/linux/interrupt.h:160
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
```
In drivers/usb/dwc2/platform.c (ffffffff8162662a)
Location: include/linux/interrupt.h:160
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
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
In drivers/pci/pcie/pcie-dpc.c (ffffffff814984c8)
Location: include/linux/interrupt.h:170
Inline: True
Inline callers:
  - drivers/pci/pcie/pcie-dpc.c:dpc_probe
```
```
In drivers/pci/host/pcie-designware-plat.c (ffffffff814a5c52)
Location: include/linux/interrupt.h:170
Inline: True
Inline callers:
  - drivers/pci/host/pcie-designware-plat.c:dw_plat_pcie_probe
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8157bb10)
Location: include/linux/interrupt.h:170
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
```
```
In drivers/mfd/ezx-pcap.c (ffffffff815e0e55)
Location: include/linux/interrupt.h:170
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/da903x.c (ffffffff815e154b)
Location: include/linux/interrupt.h:170
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/ata/libata-core.c (ffffffff816283ee)
Location: include/linux/interrupt.h:170
Inline: True
```
```
In drivers/ata/libata-sff.c (ffffffff81636ff8)
Location: include/linux/interrupt.h:170
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
```
In drivers/usb/dwc2/platform.c (ffffffff81684ac6)
Location: include/linux/interrupt.h:170
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
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
In drivers/pci/pcie/pcie-dpc.c (ffffffff814b9d78)
Location: include/linux/interrupt.h:170
Inline: True
Inline callers:
  - drivers/pci/pcie/pcie-dpc.c:dpc_probe
```
```
In drivers/pci/host/pcie-designware-plat.c (ffffffff814c7d6e)
Location: include/linux/interrupt.h:170
Inline: True
Inline callers:
  - drivers/pci/host/pcie-designware-plat.c:dw_plat_pcie_probe
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff815a7f80)
Location: include/linux/interrupt.h:170
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
```
```
In drivers/mfd/ezx-pcap.c (ffffffff8160daf2)
Location: include/linux/interrupt.h:170
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/da903x.c (ffffffff8160e1eb)
Location: include/linux/interrupt.h:170
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/ata/libata-core.c (ffffffff8165905e)
Location: include/linux/interrupt.h:170
Inline: True
```
```
In drivers/ata/libata-sff.c (ffffffff81668098)
Location: include/linux/interrupt.h:170
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
```
In drivers/usb/dwc2/platform.c (ffffffff816b1033)
Location: include/linux/interrupt.h:170
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/mailbox/pcc.c (ffffffff8177c531)
Location: include/linux/interrupt.h:170
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff81493c49)
Location: include/linux/interrupt.h:179
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pci/pcie/pcie-dpc.c (ffffffff814c4458)
Location: include/linux/interrupt.h:179
Inline: True
Inline callers:
  - drivers/pci/pcie/pcie-dpc.c:dpc_probe
```
```
In drivers/pci/dwc/pcie-designware-plat.c (ffffffff814d3c84)
Location: include/linux/interrupt.h:179
Inline: True
Inline callers:
  - drivers/pci/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff815be1c0)
Location: include/linux/interrupt.h:179
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81621bea)
Location: include/linux/interrupt.h:179
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/da903x.c (ffffffff816222ba)
Location: include/linux/interrupt.h:179
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/ata/libata-core.c (ffffffff8166d848)
Location: include/linux/interrupt.h:179
Inline: True
```
```
In drivers/ata/libata-sff.c (ffffffff8167c7cc)
Location: include/linux/interrupt.h:179
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
```
In drivers/usb/dwc2/platform.c (ffffffff816c617d)
Location: include/linux/interrupt.h:179
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81726f5e)
Location: include/linux/interrupt.h:179
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/mailbox/pcc.c (ffffffff8179b08b)
Location: include/linux/interrupt.h:179
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff814cff2a)
Location: include/linux/interrupt.h:181
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff814d65ec)
Location: include/linux/interrupt.h:181
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
```
```
In drivers/pci/pcie/pcie-dpc.c (ffffffff8150457b)
Location: include/linux/interrupt.h:181
Inline: True
Inline callers:
  - drivers/pci/pcie/pcie-dpc.c:dpc_probe
```
```
In drivers/pci/dwc/pcie-designware-plat.c (ffffffff81514114)
Location: include/linux/interrupt.h:181
Inline: True
Inline callers:
  - drivers/pci/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816248a0)
Location: include/linux/interrupt.h:181
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
```
```
In drivers/mfd/ezx-pcap.c (ffffffff8168a41a)
Location: include/linux/interrupt.h:181
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/da903x.c (ffffffff8168ab1c)
Location: include/linux/interrupt.h:181
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/ata/libata-core.c (ffffffff816d6e98)
Location: include/linux/interrupt.h:181
Inline: True
```
```
In drivers/ata/libata-sff.c (ffffffff816e5eac)
Location: include/linux/interrupt.h:181
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
```
In drivers/usb/dwc2/platform.c (ffffffff817324a6)
Location: include/linux/interrupt.h:181
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff817985ae)
Location: include/linux/interrupt.h:181
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/mailbox/pcc.c (ffffffff8181146b)
Location: include/linux/interrupt.h:181
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff815010ab)
Location: include/linux/interrupt.h:179
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pci/pcie/dpc.c (ffffffff81535917)
Location: include/linux/interrupt.h:179
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:dpc_probe
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8165ebc0)
Location: include/linux/interrupt.h:179
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
```
```
In drivers/mfd/ezx-pcap.c (ffffffff816c6542)
Location: include/linux/interrupt.h:179
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/da903x.c (ffffffff816c6bcc)
Location: include/linux/interrupt.h:179
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/ata/libata-core.c (ffffffff81712926)
Location: include/linux/interrupt.h:179
Inline: True
```
```
In drivers/ata/libata-sff.c (ffffffff8172267d)
Location: include/linux/interrupt.h:179
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
```
In drivers/usb/dwc2/platform.c (ffffffff81771da5)
Location: include/linux/interrupt.h:179
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff817db283)
Location: include/linux/interrupt.h:179
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/mailbox/pcc.c (ffffffff8185b2c7)
Location: include/linux/interrupt.h:179
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff81515b7b)
Location: include/linux/interrupt.h:179
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8167d070)
Location: include/linux/interrupt.h:179
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
```
```
In drivers/mfd/ezx-pcap.c (ffffffff816e7942)
Location: include/linux/interrupt.h:179
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/da903x.c (ffffffff816e7fec)
Location: include/linux/interrupt.h:179
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/ata/libata-core.c (ffffffff81734dd6)
Location: include/linux/interrupt.h:179
Inline: True
```
```
In drivers/ata/libata-sff.c (ffffffff81744f2d)
Location: include/linux/interrupt.h:179
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
```
In drivers/usb/dwc2/platform.c (ffffffff81796e75)
Location: include/linux/interrupt.h:179
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81802153)
Location: include/linux/interrupt.h:179
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/mailbox/pcc.c (ffffffff8187a727)
Location: include/linux/interrupt.h:179
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff81543cfc)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff816955bf)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816b410a)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81721102)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/da903x.c (ffffffff817217cc)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/ata/libata-core.c (ffffffff81770729)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_activate
```
```
In drivers/ata/libata-sff.c (ffffffff81780c4f)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
```
In drivers/usb/dwc2/platform.c (ffffffff817d5f39)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81843982)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/mailbox/pcc.c (ffffffff818bfd58)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff81564c0c)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff816b814f)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816d6dea)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81745261)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/da903x.c (ffffffff81745a6c)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/ata/libata-core.c (ffffffff81794789)
Location: include/linux/interrupt.h:190
Inline: True
```
```
In drivers/ata/libata-sff.c (ffffffff817a48ff)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
```
In drivers/usb/dwc2/platform.c (ffffffff81806dea)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81875302)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/mailbox/pcc.c (ffffffff818f2878)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff8160702c)
Location: include/linux/interrupt.h:203
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8176c22f)
Location: include/linux/interrupt.h:203
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8178b2b1)
Location: include/linux/interrupt.h:203
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81803059)
Location: include/linux/interrupt.h:203
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/da903x.c (ffffffff818036ec)
Location: include/linux/interrupt.h:203
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/ata/libata-core.c (ffffffff81858998)
Location: include/linux/interrupt.h:203
Inline: True
```
```
In drivers/ata/libata-sff.c (ffffffff81869b8f)
Location: include/linux/interrupt.h:203
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
```
In drivers/usb/dwc2/platform.c (ffffffff818d7978)
Location: include/linux/interrupt.h:203
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81949907)
Location: include/linux/interrupt.h:203
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/mailbox/pcc.c (ffffffff819c7e38)
Location: include/linux/interrupt.h:203
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff8162b90c)
Location: include/linux/interrupt.h:203
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81631422)
Location: include/linux/interrupt.h:203
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_probe
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81786d4f)
Location: include/linux/interrupt.h:203
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81c0a9a6)
Location: include/linux/interrupt.h:203
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81813ee9)
Location: include/linux/interrupt.h:203
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/da903x.c (ffffffff8181443c)
Location: include/linux/interrupt.h:203
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/ata/libata-core.c (ffffffff81868bf8)
Location: include/linux/interrupt.h:203
Inline: True
```
```
In drivers/ata/libata-sff.c (ffffffff81878992)
Location: include/linux/interrupt.h:203
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
```
In drivers/usb/dwc2/platform.c (ffffffff818e1b16)
Location: include/linux/interrupt.h:203
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8194f4c7)
Location: include/linux/interrupt.h:203
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/mailbox/pcc.c (ffffffff819c7d08)
Location: include/linux/interrupt.h:203
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff8160f5dc)
Location: include/linux/interrupt.h:207
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81614b82)
Location: include/linux/interrupt.h:207
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_probe
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81709a53)
Location: include/linux/interrupt.h:207
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8176a6af)
Location: include/linux/interrupt.h:207
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81bfc494)
Location: include/linux/interrupt.h:207
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
```
```
In drivers/mfd/ezx-pcap.c (ffffffff817f85d9)
Location: include/linux/interrupt.h:207
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/da903x.c (ffffffff817f8b1c)
Location: include/linux/interrupt.h:207
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/ata/libata-core.c (ffffffff8184b628)
Location: include/linux/interrupt.h:207
Inline: True
```
```
In drivers/ata/libata-sff.c (ffffffff8185b002)
Location: include/linux/interrupt.h:207
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
```
In drivers/usb/dwc2/platform.c (ffffffff818c4e26)
Location: include/linux/interrupt.h:207
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81933956)
Location: include/linux/interrupt.h:207
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/mailbox/pcc.c (ffffffff819acc48)
Location: include/linux/interrupt.h:207
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff8167e5a4)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81683e12)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_probe
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81785411)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff817ef7e9)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81cfd1c4)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81881a29)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/da903x.c (ffffffff81881f76)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/ata/libata-core.c (ffffffff818d8ae8)
Location: include/linux/interrupt.h:211
Inline: True
```
```
In drivers/ata/libata-sff.c (ffffffff818e9b02)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
```
In drivers/usb/dwc2/platform.c (ffffffff8195ca88)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff819d6d26)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/mailbox/pcc.c (ffffffff81a5b158)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff8179a1a2)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff817a09b1)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff818bbfd4)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8192fba5)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81ec5a66)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
```
```
In drivers/mfd/ezx-pcap.c (ffffffff819ca28d)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/da903x.c (ffffffff819ca80a)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/ata/libata-core.c (ffffffff81a29c6b)
Location: include/linux/interrupt.h:211
Inline: True
```
```
In drivers/ata/libata-sff.c (ffffffff81a3b48e)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
```
In drivers/usb/dwc2/platform.c (ffffffff81ab690d)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81b39896)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/mailbox/pcc.c (ffffffff81bcae33)
Location: include/linux/interrupt.h:211
Inline: True
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff818b079f)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818b7b5e)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a0ac35)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81a8df85)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81aaea22)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81b4171d)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/da903x.c (ffffffff81b41d12)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/ata/libata-core.c (ffffffff81bac86b)
Location: include/linux/interrupt.h:211
Inline: True
```
```
In drivers/ata/libata-sff.c (ffffffff81bc08fe)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
```
In drivers/usb/dwc2/platform.c (ffffffff81c3f385)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81ccef23)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/mailbox/pcc.c (ffffffff81d745d6)
Location: include/linux/interrupt.h:211
Inline: True
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff818f378a)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818fabd7)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a53abc)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81ad9735)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81b94a8f)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/da903x.c (ffffffff81b9508f)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/ata/libata-core.c (ffffffff81c039fb)
Location: include/linux/interrupt.h:211
Inline: True
```
```
In drivers/ata/libata-sff.c (ffffffff81c183de)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
```
In drivers/usb/dwc2/platform.c (ffffffff81ca6927)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81d37039)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/mailbox/pcc.c (ffffffff81de1f66)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_startup
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff8193afba)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81941f57)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a9f86c)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81b2ca25)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81be8a5f)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/da903x.c (ffffffff81be905f)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/ata/libata-core.c (ffffffff81c591bb)
Location: include/linux/interrupt.h:211
Inline: True
```
```
In drivers/ata/libata-sff.c (ffffffff81c6dbdb)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
```
In drivers/usb/dwc2/platform.c (ffffffff81d5b577)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81ded249)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/mailbox/pcc.c (ffffffff81e97f2a)
Location: include/linux/interrupt.h:211
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_startup
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
In drivers/irqchip/irq-renesas-irqc.c (ffff80001067691c)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-irqc.c:irqc_probe
```
```
In drivers/bus/brcmstb_gisb.c (ffff80001147694c)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe
```
```
In drivers/pinctrl/pinctrl-amd.c (ffff800010692c88)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pci/controller/pci-aardvark.c (ffff8000107202c4)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_probe
```
```
In drivers/pci/controller/pcie-rcar.c (ffff800010722070)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
```
```
In drivers/pci/controller/pcie-xilinx.c (ffff8000107236d8)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
```
```
In drivers/pci/controller/pcie-xilinx-nwl.c (ffff800010724bd8)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_bridge_init
```
```
In drivers/pci/controller/dwc/pcie-armada8k.c (ffff800010735cc0)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
```
```
In drivers/dma/mv_xor_v2.c (ffff8000108090ac)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_probe
```
```
In drivers/soc/fsl/qbman/bman_ccsr.c (ffff80001080f9dc)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/bman_ccsr.c:fsl_bman_probe
```
```
In drivers/soc/fsl/qbman/qman_ccsr.c (ffff800010810648)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/qman_ccsr.c:fsl_qman_probe
```
```
In drivers/soc/qcom/rpmh-rsc.c (ffff80001081b4d4)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_probe
```
```
In drivers/tty/serial/imx.c (ffff80001089bfc8)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_probe
```
```
In drivers/tty/serial/mvebu-uart.c (ffff8000108a61f4)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_startup
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_startup
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_startup
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffff8000108a7950)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
```
```
In drivers/char/tpm/tpm_tis_core.c (ffff8000108c24bc)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
```
```
In drivers/iommu/arm-smmu.c (ffff8000108d247c)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu.c:arm_smmu_device_probe
  - drivers/iommu/arm-smmu.c:arm_smmu_attach_dev
```
```
In drivers/iommu/arm-smmu-v3.c (ffff8000108d6f4c)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_reset
```
```
In drivers/iommu/rockchip-iommu.c (ffff8000108d800c)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_probe
```
```
In drivers/iommu/qcom_iommu.c (ffff8000108db384)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/iommu/qcom_iommu.c:qcom_iommu_ctx_probe
```
```
In drivers/mfd/ezx-pcap.c (ffff800010941144)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/da903x.c (ffff8000109422a0)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/ata/libata-core.c (ffff80001099efe0)
Location: include/linux/interrupt.h:190
Inline: True
```
```
In drivers/ata/libata-sff.c (ffff8000109afe58)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
```
In drivers/ata/libahci.c (ffff8000109b902c)
Location: include/linux/interrupt.h:190
Inline: True
```
```
In drivers/spi/spi-fsl-spi.c (ffff8000109cbc94)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
```
```
In drivers/spi/spi-omap2-mcspi.c (ffff8000109cd93c)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e9de0)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
```
```
In drivers/net/ethernet/freescale/fec_ptp.c (ffff8000109ed394)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_init
```
```
In drivers/net/ethernet/freescale/fman/fman.c (ffff8000109ee420)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/fman.c:read_dts_node
  - drivers/net/ethernet/freescale/fman/fman.c:read_dts_node
```
```
In drivers/usb/dwc2/platform.c (ffff800010a3e598)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/rtc/rtc-mv.c (ffff80001149df78)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/rtc/rtc-mv.c:mv_rtc_probe
```
```
In drivers/rtc/rtc-sun6i.c (ffff800010aad2fc)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_probe
```
```
In drivers/rtc/rtc-xgene.c (ffff800010aadf00)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/rtc/rtc-xgene.c:xgene_rtc_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffff800010aba078)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-omap.c (ffff800010abba14)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
```
```
In drivers/power/reset/ltc2952-poweroff.c (ffff800010ac9eb4)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
```
```
In drivers/edac/altera_edac.c (ffff800010b16370)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/edac/altera_edac.c:altr_edac_a10_device_add
  - drivers/edac/altera_edac.c:altr_edac_device_probe
  - drivers/edac/altera_edac.c:altr_edac_device_probe
  - drivers/edac/altera_edac.c:altr_sdram_probe
  - drivers/edac/altera_edac.c:altr_sdram_probe
```
```
In drivers/mmc/host/mmci.c (ffff800010b453ac)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:mmci_probe
  - drivers/mmc/host/mmci.c:mmci_probe
```
```
In drivers/mailbox/pcc.c (ffff800010b7bd30)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
```
```
In drivers/mailbox/bcm2835-mailbox.c (ffff800010b7c018)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/mailbox/bcm2835-mailbox.c:bcm2835_mbox_probe
```
```
In drivers/mailbox/zynqmp-ipi-mailbox.c (ffff800010b7d8bc)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/mailbox/zynqmp-ipi-mailbox.c:zynqmp_ipi_probe
```
```
In drivers/perf/arm-ccn.c (ffff800010b937e0)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_probe
```
```
In drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c (ffff800010b9700c)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_probe
```
```
In drivers/perf/hisilicon/hisi_uncore_hha_pmu.c (ffff800010b97850)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_probe
```
```
In drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c (ffff800010b98064)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_probe
```
```
In drivers/perf/qcom_l2_pmu.c (ffff800010b98c50)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/perf/qcom_l2_pmu.c:l2_cache_pmu_probe_cluster
```
```
In drivers/perf/qcom_l3_pmu.c (ffff800010b9a53c)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_probe
```
```
In drivers/perf/xgene_pmu.c (ffff800010b9bb98)
Location: include/linux/interrupt.h:190
Inline: True
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
In drivers/irqchip/irq-renesas-intc-irqpin.c (c081f32c)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_probe
  - drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_probe
```
```
In drivers/irqchip/irq-renesas-irqc.c (c081fd08)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-irqc.c:irqc_probe
```
```
In drivers/bus/brcmstb_gisb.c (c154ea8c)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe
```
```
In drivers/bus/omap_l3_noc.c (c0826400)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/bus/omap_l3_noc.c:omap_l3_probe
  - drivers/bus/omap_l3_noc.c:omap_l3_probe
```
```
In drivers/pinctrl/pinctrl-amd.c (c0835624)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/samsung/pinctrl-exynos.c (c08523d4)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_eint_gpio_init
```
```
In drivers/gpio/gpio-omap.c (c086d838)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/gpio/gpio-omap.c:omap_gpio_probe
```
```
In drivers/pci/controller/pcie-rcar.c (c08af548)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
```
```
In drivers/pci/controller/pcie-xilinx.c (c08b0290)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
```
```
In drivers/pci/controller/pci-v3-semi.c (c08b0f74)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
```
```
In drivers/pci/controller/dwc/pci-dra7xx.c (c1552450)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-armada8k.c (c08be300)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
```
```
In drivers/dma/ti/edma.c (c092ed58)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/dma/ti/edma.c:edma_probe
  - drivers/dma/ti/edma.c:edma_probe
```
```
In drivers/dma/ti/omap-dma.c (c0931638)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/dma/ti/omap-dma.c:omap_dma_probe
```
```
In drivers/tty/serial/imx.c (c099722c)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_probe
```
```
In drivers/tty/serial/mvebu-uart.c (c09a1c6c)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_startup
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_startup
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_startup
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (c09a4560)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
```
```
In drivers/char/tpm/tpm_tis_core.c (c09bacb8)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
```
```
In drivers/iommu/ipmmu-vmsa.c (c09c2760)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_probe
```
```
In drivers/iommu/omap-iommu.c (c09c39ac)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/iommu/omap-iommu.c:omap_iommu_probe
```
```
In drivers/iommu/rockchip-iommu.c (c09c5aa8)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_probe
```
```
In drivers/iommu/exynos-iommu.c (c09ca2a4)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/iommu/exynos-iommu.c:exynos_sysmmu_probe
```
```
In drivers/iommu/qcom_iommu.c (c09cc480)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/iommu/qcom_iommu.c:qcom_iommu_ctx_probe
```
```
In drivers/mfd/ezx-pcap.c (c0a2ab00)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/da903x.c (c0a2b2b8)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/ata/libata-core.c (c0a6f6a4)
Location: include/linux/interrupt.h:190
Inline: True
```
```
In drivers/ata/libata-sff.c (c0a7faf4)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
```
In drivers/ata/libahci.c (c0a86b0c)
Location: include/linux/interrupt.h:190
Inline: True
```
```
In drivers/mtd/nand/raw/omap2.c (c0aaba60)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/omap2.c:omap_nand_attach_chip
  - drivers/mtd/nand/raw/omap2.c:omap_nand_attach_chip
```
```
In drivers/mtd/nand/raw/omap_elm.c (c0aad108)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/omap_elm.c:elm_probe
```
```
In drivers/spi/spi-fsl-spi.c (c0ab53f0)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
```
```
In drivers/spi/spi-omap2-mcspi.c (c0ab7e4c)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0acaf84)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
```
```
In drivers/net/ethernet/freescale/fec_ptp.c (c0acf050)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_init
```
```
In drivers/net/ethernet/ti/cpsw.c (c0ad57d4)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_probe
  - drivers/net/ethernet/ti/cpsw.c:cpsw_probe
```
```
In drivers/usb/dwc2/platform.c (c0b11210)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/rtc/rtc-mv.c (c15a05a8)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/rtc/rtc-mv.c:mv_rtc_probe
```
```
In drivers/rtc/rtc-omap.c (c0b8c8f4)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/rtc/rtc-omap.c:omap_rtc_probe
  - drivers/rtc/rtc-omap.c:omap_rtc_probe
```
```
In drivers/rtc/rtc-s3c.c (c0b8eef0)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/rtc/rtc-s3c.c:s3c_rtc_probe
  - drivers/rtc/rtc-s3c.c:s3c_rtc_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (c0b99788)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-imx.c (c0b9bba0)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_probe
```
```
In drivers/i2c/busses/i2c-omap.c (c0b9cd40)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
```
```
In drivers/i2c/busses/i2c-s3c2410.c (c0b9e49c)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_probe
```
```
In drivers/power/avs/smartreflex.c (c0ba8f48)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/power/avs/smartreflex.c:sr_late_init
```
```
In drivers/power/reset/ltc2952-poweroff.c (c0baaba0)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
```
```
In drivers/thermal/samsung/exynos_tmu.c (c0bbe624)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_probe
```
```
In drivers/watchdog/npcm_wdt.c (c0bc2790)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/watchdog/npcm_wdt.c:npcm_wdt_probe
```
```
In drivers/mmc/host/mmci.c (c0c1f2a8)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:mmci_probe
  - drivers/mmc/host/mmci.c:mmci_probe
```
```
In drivers/mmc/host/omap_hsmmc.c (c0c2b3d8)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe
```
```
In drivers/clocksource/em_sti.c (c0c46eb8)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/clocksource/em_sti.c:em_sti_probe
```
```
In drivers/staging/emxx_udc/emxx_udc.c (c0c5bd7c)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_drv_probe
```
```
In drivers/mailbox/tegra-hsp.c (c0c616d4)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_probe
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_probe
```
```
In drivers/memory/tegra/mc.c (c0c742b4)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/memory/tegra/mc.c:tegra_mc_probe
```
```
In drivers/memory/tegra/tegra20-emc.c (c0c74d50)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/memory/tegra/tegra20-emc.c:tegra_emc_probe
```
```
In drivers/perf/arm-ccn.c (c0c7c934)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_probe
```
```
In sound/soc/fsl/fsl_ssi.c (c0cc0800)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_probe
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
In drivers/pinctrl/pinctrl-amd.c (c00000000082f544)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pci/controller/pcie-xilinx.c (c000000000892064)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (c00000000093e494)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
```
```
In drivers/char/tpm/tpm_tis_core.c (c000000000964c9c)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
```
```
In drivers/char/tpm/tpm_i2c_nuvoton.c (c000000000968098)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_i2c_nuvoton.c:i2c_nuvoton_probe
```
```
In drivers/mfd/ezx-pcap.c (c0000000009ea524)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/da903x.c (c0000000009eb008)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/ata/libata-core.c (c000000000a63558)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_activate
```
```
In drivers/ata/libata-sff.c (c000000000a78940)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
```
In drivers/spi/spi-fsl-spi.c (c000000000a8e2f8)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
```
```
In drivers/usb/dwc2/platform.c (c000000000afe4e4)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (c000000000b9d074)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/power/reset/ltc2952-poweroff.c (c000000000babc00)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
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
In drivers/pinctrl/pinctrl-amd.c (ffffffe00049f12e)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pci/controller/pcie-xilinx.c (ffffffe0004e6df0)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffe00055e252)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffe0005736f0)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
```
```
In drivers/mfd/ezx-pcap.c (ffffffe0005b4b90)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/da903x.c (ffffffe0005b5364)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/ata/libata-core.c (ffffffe0005feea4)
Location: include/linux/interrupt.h:190
Inline: True
```
```
In drivers/ata/libata-sff.c (ffffffe00060d504)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
```
In drivers/spi/spi-fsl-spi.c (ffffffe00061be3e)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
```
```
In drivers/spi/spi-sifive.c (ffffffe00061c576)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/spi/spi-sifive.c:sifive_spi_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffe00065a492)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffe0006be980)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/power/reset/ltc2952-poweroff.c (ffffffe0006c7cea)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff8155d1fc)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8167dbaf)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8169c83a)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81703301)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/ata/libata-core.c (ffffffff81759899)
Location: include/linux/interrupt.h:190
Inline: True
```
```
In drivers/ata/libata-sff.c (ffffffff817699bf)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
```
In drivers/usb/dwc2/platform.c (ffffffff817bf1ca)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/mailbox/pcc.c (ffffffff81893ba8)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
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
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8165cc9f)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8167a22a)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
```
```
In drivers/mfd/ezx-pcap.c (ffffffff816d7101)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/ata/libata-core.c (ffffffff81739739)
Location: include/linux/interrupt.h:190
Inline: True
```
```
In drivers/ata/libata-sff.c (ffffffff8174981f)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
```
In drivers/mailbox/pcc.c (ffffffff8184c0a8)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff81558f3c)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff816abf8f)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816caaaa)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81738721)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/da903x.c (ffffffff81738f2c)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/ata/libata-core.c (ffffffff81789609)
Location: include/linux/interrupt.h:190
Inline: True
```
```
In drivers/ata/libata-sff.c (ffffffff8179977f)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
```
In drivers/usb/dwc2/platform.c (ffffffff817fbc6a)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/i2c/busses/i2c-amd-mp2-pci.c (ffffffff818682f9)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-mp2-pci.c:amd_mp2_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8186a7b2)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/mailbox/pcc.c (ffffffff818e76a8)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff81572dcc)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff816c63ef)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816e4f7a)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81753cb1)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/da903x.c (ffffffff8175436c)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/ata/libata-core.c (ffffffff817a3459)
Location: include/linux/interrupt.h:190
Inline: True
```
```
In drivers/ata/libata-sff.c (ffffffff817b35ff)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
```
```
In drivers/usb/dwc2/platform.c (ffffffff81815d7a)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81884742)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/mailbox/pcc.c (ffffffff81904328)
Location: include/linux/interrupt.h:190
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
```
</details>
</li>
</ul>

## Differences
