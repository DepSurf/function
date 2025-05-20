# Function: <code>writew</code>

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
In arch/x86/kernel/early_printk.c (ffffffff81061b5d)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_vga_write
  - arch/x86/kernel/early_printk.c:early_vga_write
  - arch/x86/kernel/early_printk.c:early_vga_write
```
```
In lib/iomap.c (ffffffff814027df)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - lib/iomap.c:iowrite16
```
```
In drivers/pci/access.c (ffffffff8142dd7a)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/video/console/vgacon.c (ffffffff8145e7e2)
Location: arch/x86/include/asm/io.h:65
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff8147a222)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff814c05c2)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8150c33e)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff8156b387)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_gather_write
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
In arch/x86/kernel/early_printk.c (ffffffff81061972)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_vga_write
  - arch/x86/kernel/early_printk.c:early_vga_write
  - arch/x86/kernel/early_printk.c:early_vga_write
```
```
In lib/iomap.c (ffffffff8144a48f)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - lib/iomap.c:iowrite16
```
```
In drivers/pci/access.c (ffffffff8147910b)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/host/pcie-designware.c (ffffffff814a517e)
Location: arch/x86/include/asm/io.h:65
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffff814aca2e)
Location: arch/x86/include/asm/io.h:65
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff814c87d9)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81510c01)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff815572f9)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_out
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8155e65e)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81fd3a3d)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff815bfb0e)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write16le
```
```
In drivers/mailbox/pcc.c (ffffffff8175081f)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_send_data
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
In arch/x86/kernel/early_printk.c (ffffffff81064a22)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_vga_write
  - arch/x86/kernel/early_printk.c:early_vga_write
  - arch/x86/kernel/early_printk.c:early_vga_write
```
```
In lib/iomap.c (ffffffff81468e4f)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - lib/iomap.c:iowrite16
```
```
In drivers/pci/access.c (ffffffff8149a51b)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/host/pcie-designware.c (ffffffff814c73ee)
Location: arch/x86/include/asm/io.h:65
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffff814ce9ae)
Location: arch/x86/include/asm/io.h:65
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff814ea71d)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8153cd71)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81583af9)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_out
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8158ac4e)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff820113fd)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff815eef4e)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write16le
```
```
In drivers/mailbox/pcc.c (ffffffff8177c167)
Location: arch/x86/include/asm/io.h:65
Inline: True
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
In arch/x86/kernel/early_printk.c (ffffffff81063962)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_vga_write
  - arch/x86/kernel/early_printk.c:early_vga_write
  - arch/x86/kernel/early_printk.c:early_vga_write
```
```
In lib/iomap.c (ffffffff8146e51a)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - lib/iomap.c:iowrite16
```
```
In drivers/pci/access.c (ffffffff814a40be)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/dwc/pcie-designware.c (ffffffff814d2f14)
Location: arch/x86/include/asm/io.h:65
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffff814da721)
Location: arch/x86/include/asm/io.h:65
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff814f6565)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81550bfe)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81597f09)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_out
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8159ed5b)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff820f2edd)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff8160318e)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write16le
```
```
In drivers/mailbox/pcc.c (ffffffff8179acb7)
Location: arch/x86/include/asm/io.h:65
Inline: True
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
In arch/x86/kernel/early_printk.c (ffffffff81067ad2)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_vga_write
  - arch/x86/kernel/early_printk.c:early_vga_write
  - arch/x86/kernel/early_printk.c:early_vga_write
```
```
In lib/iomap.c (ffffffff8149a84f)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - lib/iomap.c:iowrite16
```
```
In drivers/pci/access.c (ffffffff814e2e44)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/dwc/pcie-designware.c (ffffffff815133b6)
Location: arch/x86/include/asm/io.h:66
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffff8151a9cc)
Location: arch/x86/include/asm/io.h:66
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff81536d15)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff815b43fe)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff815fcb49)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_out
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8160424b)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81604ae7)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff8166b55e)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write16le
```
```
In drivers/mailbox/pcc.c (ffffffff8181109f)
Location: arch/x86/include/asm/io.h:66
Inline: True
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
In arch/x86/kernel/early_printk.c (ffffffff8106a89d)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_vga_write
  - arch/x86/kernel/early_printk.c:early_vga_write
  - arch/x86/kernel/early_printk.c:early_vga_write
```
```
In lib/iomap.c (ffffffff814cfaed)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - lib/iomap.c:iowrite16
```
```
In drivers/pci/access.c (ffffffff81512c9a)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff8153e728)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81548795)
Location: arch/x86/include/asm/io.h:66
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffff81550627)
Location: arch/x86/include/asm/io.h:66
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff8156c8dd)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff815ec7ef)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81635f29)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_out
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8163d4ab)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff8163dd77)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff816a6f3b)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write16le
```
```
In drivers/mailbox/pcc.c (ffffffff8185aedd)
Location: arch/x86/include/asm/io.h:66
Inline: True
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
In arch/x86/kernel/early_printk.c (ffffffff8107062d)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_vga_write
  - arch/x86/kernel/early_printk.c:early_vga_write
  - arch/x86/kernel/early_printk.c:early_vga_write
```
```
In lib/iomap.c (ffffffff814e43fd)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - lib/iomap.c:iowrite16
```
```
In drivers/pci/access.c (ffffffff815284fa)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81555af8)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8155ee55)
Location: arch/x86/include/asm/io.h:66
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffff81567eea)
Location: arch/x86/include/asm/io.h:66
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff8158450d)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff816073bf)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816541d9)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_out
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8165b72b)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff8165bfe6)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff816c7a7b)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write16le
```
```
In drivers/mailbox/pcc.c (ffffffff8187a33d)
Location: arch/x86/include/asm/io.h:66
Inline: True
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
In arch/x86/kernel/early_printk.c (ffffffff81074677)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_vga_write
  - arch/x86/kernel/early_printk.c:early_vga_write
  - arch/x86/kernel/early_printk.c:early_vga_write
```
```
In lib/iomap.c (ffffffff81510d62)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
```
```
In drivers/pci/access.c (ffffffff8155778a)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81585af6)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8158f4ab)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
```
```
In drivers/video/console/vgacon.c (ffffffff815988b8)
Location: arch/x86/include/asm/io.h:66
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff815b5147)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8163b18a)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81688c29)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_out
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81690e96)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff816916a9)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff81702d2b)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write16le
```
```
In drivers/mailbox/pcc.c (ffffffff818bf976)
Location: arch/x86/include/asm/io.h:66
Inline: True
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
In arch/x86/kernel/early_printk.c (ffffffff81075647)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_vga_write
  - arch/x86/kernel/early_printk.c:early_vga_write
  - arch/x86/kernel/early_printk.c:early_vga_write
```
```
In lib/iomap.c (ffffffff815317d2)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
```
```
In drivers/pci/access.c (ffffffff81578dba)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff815a74d6)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815b121b)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
```
```
In drivers/video/console/vgacon.c (ffffffff815b9c58)
Location: arch/x86/include/asm/io.h:66
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff815d6377)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8165d65a)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816ab2b9)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_out
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816b38d6)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff816b4199)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff8172707b)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write16le
```
```
In drivers/mailbox/pcc.c (ffffffff818f2496)
Location: arch/x86/include/asm/io.h:66
Inline: True
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
In arch/x86/kernel/early_printk.c (ffffffff8107c857)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_vga_write
  - arch/x86/kernel/early_printk.c:early_vga_write
  - arch/x86/kernel/early_printk.c:early_vga_write
```
```
In lib/iomap.c (ffffffff81595c5d)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
```
```
In drivers/pci/access.c (ffffffff8161ddca)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff816501d9)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8165aa4f)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
```
```
In drivers/video/console/vgacon.c (ffffffff81663e18)
Location: arch/x86/include/asm/io.h:66
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff81680077)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8170c9e0)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8175df59)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_out
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff817672b4)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81767a39)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff817e364b)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write16le
```
```
In drivers/mailbox/pcc.c (ffffffff819c7f06)
Location: arch/x86/include/asm/io.h:66
Inline: True
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
In arch/x86/kernel/early_printk.c (ffffffff8107c6a7)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_vga_write
  - arch/x86/kernel/early_printk.c:early_vga_write
  - arch/x86/kernel/early_printk.c:early_vga_write
```
```
In arch/x86/kernel/sev-es.c (ffffffff8108427a)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/sev-es.c:sev_es_setup_ap_jump_table
  - arch/x86/kernel/sev-es.c:sev_es_setup_ap_jump_table
```
```
In lib/iomap.c (ffffffff815b16ed)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
```
```
In drivers/pci/access.c (ffffffff816445ea)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81673679)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8167b01f)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
```
```
In drivers/video/console/vgacon.c (ffffffff81684aa8)
Location: arch/x86/include/asm/io.h:66
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff8169eb5f)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81729800)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81778dd9)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_out
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff817821f4)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81782799)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff817f82db)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write16le
```
```
In drivers/mailbox/pcc.c (ffffffff819c7dd6)
Location: arch/x86/include/asm/io.h:66
Inline: True
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
In arch/x86/kernel/early_printk.c (ffffffff8107d856)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_vga_write
  - arch/x86/kernel/early_printk.c:early_vga_write
  - arch/x86/kernel/early_printk.c:early_vga_write
```
```
In arch/x86/kernel/sev.c (ffffffff81084fdd)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:sev_es_setup_ap_jump_table
  - arch/x86/kernel/sev.c:sev_es_setup_ap_jump_table
```
```
In lib/iomap.c (ffffffff815bc4fd)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
```
```
In drivers/pci/access.c (ffffffff8162736c)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81655b9f)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8165da81)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
```
```
In drivers/video/console/vgacon.c (ffffffff81667588)
Location: arch/x86/include/asm/io.h:66
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff81681811)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8170e0ad)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8175c7f9)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_out
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81765928)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81766099)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff817dca6b)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write16le
```
```
In drivers/mailbox/pcc.c (ffffffff819acd16)
Location: arch/x86/include/asm/io.h:66
Inline: True
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
In arch/x86/kernel/early_printk.c (ffffffff8108c286)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_vga_write
  - arch/x86/kernel/early_printk.c:early_vga_write
  - arch/x86/kernel/early_printk.c:early_vga_write
```
```
In arch/x86/kernel/sev.c (ffffffff8109419d)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:sev_es_setup_ap_jump_table
  - arch/x86/kernel/sev.c:sev_es_setup_ap_jump_table
```
```
In lib/iomap.c (ffffffff8162334d)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
```
```
In drivers/pci/access.c (ffffffff81696c3c)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff816c7c45)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff816d04f1)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
```
```
In drivers/video/console/vgacon.c (ffffffff816da7c8)
Location: arch/x86/include/asm/io.h:66
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff816f6901)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8178a81d)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff817e0933)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_out
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff817ea238)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff817eaa3d)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff8186846b)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write16le
```
```
In drivers/mailbox/pcc.c (ffffffff81a5b226)
Location: arch/x86/include/asm/io.h:66
Inline: True
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
In arch/x86/kernel/early_printk.c (ffffffff8109cb7b)
Location: arch/x86/include/asm/io.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_vga_write
  - arch/x86/kernel/early_printk.c:early_vga_write
  - arch/x86/kernel/early_printk.c:early_vga_write
```
```
In arch/x86/kernel/sev.c (ffffffff834716c7)
Location: arch/x86/include/asm/io.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:sev_es_setup_ap_jump_table
  - arch/x86/kernel/sev.c:sev_es_setup_ap_jump_table
```
```
In lib/iomap.c (ffffffff816f339d)
Location: arch/x86/include/asm/io.h:68
Inline: True
Inline callers:
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
```
```
In drivers/gpio/gpio-mmio.c (ffffffff817b18f5)
Location: arch/x86/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_write16
```
```
In drivers/pci/access.c (ffffffff817b7c1b)
Location: arch/x86/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff817edbad)
Location: arch/x86/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff817f9399)
Location: arch/x86/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
```
```
In drivers/video/console/vgacon.c (ffffffff818042e8)
Location: arch/x86/include/asm/io.h:68
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff81823738)
Location: arch/x86/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff818c2069)
Location: arch/x86/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8191f713)
Location: arch/x86/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_out
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81929d3f)
Location: arch/x86/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff8192a80a)
Location: arch/x86/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff819b0eab)
Location: arch/x86/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write16le
```
```
In drivers/mailbox/pcc.c (ffffffff81bcaec1)
Location: arch/x86/include/asm/io.h:68
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
In arch/x86/kernel/early_printk.c (ffffffff810b39b8)
Location: arch/x86/include/asm/io.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_vga_write
  - arch/x86/kernel/early_printk.c:early_vga_write
  - arch/x86/kernel/early_printk.c:early_vga_write
```
```
In arch/x86/kernel/sev.c (ffffffff83e98898)
Location: arch/x86/include/asm/io.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:sev_es_setup_ap_jump_table
  - arch/x86/kernel/sev.c:sev_es_setup_ap_jump_table
```
```
In lib/iomap.c (ffffffff817e52ed)
Location: arch/x86/include/asm/io.h:68
Inline: True
Inline callers:
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
```
```
In drivers/gpio/gpio-mmio.c (ffffffff818cb715)
Location: arch/x86/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_write16
```
```
In drivers/pci/access.c (ffffffff818d246b)
Location: arch/x86/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81914fd2)
Location: arch/x86/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81925706)
Location: arch/x86/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
```
```
In drivers/video/console/vgacon.c (ffffffff81932b38)
Location: arch/x86/include/asm/io.h:68
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff81954998)
Location: arch/x86/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81a12099)
Location: arch/x86/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81a7bc43)
Location: arch/x86/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_out
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81a874dc)
Location: arch/x86/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81a87c5a)
Location: arch/x86/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff81b2587c)
Location: arch/x86/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_noinc_write
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write16be
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write16le
```
```
In drivers/mailbox/pcc.c (ffffffff81d74681)
Location: arch/x86/include/asm/io.h:68
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
In arch/x86/kernel/early_printk.c (ffffffff810b6ab8)
Location: arch/x86/include/asm/io.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_vga_write
  - arch/x86/kernel/early_printk.c:early_vga_write
  - arch/x86/kernel/early_printk.c:early_vga_write
```
```
In arch/x86/kernel/sev.c (ffffffff836bc2c8)
Location: arch/x86/include/asm/io.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:sev_es_setup_ap_jump_table
  - arch/x86/kernel/sev.c:sev_es_setup_ap_jump_table
```
```
In lib/iomap.c (ffffffff8182532d)
Location: arch/x86/include/asm/io.h:68
Inline: True
Inline callers:
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
```
```
In drivers/gpio/gpio-mmio.c (ffffffff8190e785)
Location: arch/x86/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_write16
```
```
In drivers/pci/access.c (ffffffff8191546b)
Location: arch/x86/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff819585e6)
Location: arch/x86/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff819694b6)
Location: arch/x86/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
```
```
In drivers/video/console/vgacon.c (ffffffff81976fa8)
Location: arch/x86/include/asm/io.h:68
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff8199ad98)
Location: arch/x86/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81a5b119)
Location: arch/x86/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81ac7803)
Location: arch/x86/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_out
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81ad2aac)
Location: arch/x86/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81ad2fcf)
Location: arch/x86/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff81b758d4)
Location: arch/x86/include/asm/io.h:68
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_noinc_write
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write16be
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write16le
```
```
In drivers/mailbox/pcc.c (ffffffff81de25c1)
Location: arch/x86/include/asm/io.h:68
Inline: True
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
In arch/x86/kernel/early_printk.c (ffffffff810bdef8)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_vga_write
  - arch/x86/kernel/early_printk.c:early_vga_write
  - arch/x86/kernel/early_printk.c:early_vga_write
```
```
In arch/x86/kernel/sev.c (ffffffff838ecd38)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:sev_es_setup_ap_jump_table
  - arch/x86/kernel/sev.c:sev_es_setup_ap_jump_table
```
```
In lib/iomap.c (ffffffff81876d3d)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
```
```
In drivers/gpio/gpio-mmio.c (ffffffff819564f5)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_write16
```
```
In drivers/pci/access.c (ffffffff8195d3db)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff819a1b56)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff819b1d33)
Location: arch/x86/include/asm/io.h:65
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffff819c1028)
Location: arch/x86/include/asm/io.h:65
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff819e3218)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81aac589)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81b1a423)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_out
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81b22a0f)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81b269fc)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff81bc9795)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_noinc_write
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write16be
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write16le
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81dea6ff)
Location: arch/x86/include/asm/io.h:65
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_write_word
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_write_word
```
```
In drivers/mailbox/pcc.c (ffffffff81e98621)
Location: arch/x86/include/asm/io.h:65
Inline: True
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
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (c0000000007e53c0)
Location: arch/powerpc/include/asm/io-defs.h:11
Inline: True
```
```
In drivers/pinctrl/pinctrl-single.c (c00000000083261c)
Location: arch/powerpc/include/asm/io-defs.h:11
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_writew
```
```
In drivers/gpio/gpio-mmio.c (c000000000847cdc)
Location: arch/powerpc/include/asm/io-defs.h:11
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_write16
```
```
In drivers/pci/access.c (c000000000852664)
Location: arch/powerpc/include/asm/io-defs.h:11
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/pci-sysfs.c (c00000000086b660)
Location: arch/powerpc/include/asm/io-defs.h:11
Inline: True
```
```
In drivers/pci/quirks.c (c000000000879210)
Location: arch/powerpc/include/asm/io-defs.h:11
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
```
```
In drivers/pci/controller/pcie-cadence-host.c (c00000000088eab8)
Location: arch/powerpc/include/asm/io-defs.h:11
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
```
```
In drivers/pci/controller/pcie-cadence-ep.c (c00000000088fc64)
Location: arch/powerpc/include/asm/io-defs.h:11
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_msi
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
```
```
In drivers/pci/controller/pci-ftpci100.c (c0000000008912dc)
Location: arch/powerpc/include/asm/io-defs.h:11
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_write_config
```
```
In drivers/video/console/vgacon.c (c00000000089c1c4)
Location: arch/powerpc/include/asm/io-defs.h:11
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
```
```
In drivers/virtio/virtio_mmio.c (c0000000008d11c0)
Location: arch/powerpc/include/asm/io-defs.h:11
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/tty/serial/8250/8250_port.c (c00000000092c6a0)
Location: arch/powerpc/include/asm/io-defs.h:11
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_out
```
```
In drivers/tty/serial/8250/8250_pci.c (c00000000093825c)
Location: arch/powerpc/include/asm/io-defs.h:11
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/tty/serial/8250/8250_early.c (c00000000093a4cc)
Location: arch/powerpc/include/asm/io-defs.h:11
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/base/regmap/regmap-mmio.c (c0000000009c0bd4)
Location: arch/powerpc/include/asm/io-defs.h:11
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write16le
```
```
In drivers/usb/host/pci-quirks.c (c000000000b18b64)
Location: arch/powerpc/include/asm/io-defs.h:11
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
```
```
In drivers/usb/host/uhci-hcd.c (c000000000b3e6b0)
Location: arch/powerpc/include/asm/io-defs.h:11
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:start_rh
  - drivers/usb/host/uhci-hcd.c:start_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:configure_hc
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
```
```
In drivers/i2c/busses/i2c-designware-common.c (c000000000b9bb48)
Location: arch/powerpc/include/asm/io-defs.h:11
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:dw_writel
  - drivers/i2c/busses/i2c-designware-common.c:dw_writel
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In arch/x86/kernel/early_printk.c (ffffffff81074647)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_vga_write
  - arch/x86/kernel/early_printk.c:early_vga_write
  - arch/x86/kernel/early_printk.c:early_vga_write
```
```
In lib/iomap.c (ffffffff81529db2)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
```
```
In drivers/gpio/gpio-mmio.c (ffffffff81569a15)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_write16
```
```
In drivers/pci/access.c (ffffffff8156d2da)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff8159ace6)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815a49db)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
```
```
In drivers/video/console/vgacon.c (ffffffff815adda8)
Location: arch/x86/include/asm/io.h:66
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff815ca0d7)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff816234fa)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81670d29)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_out
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81679336)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81679bf9)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff816ece5b)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write16le
```
```
In drivers/mailbox/pcc.c (ffffffff818937c6)
Location: arch/x86/include/asm/io.h:66
Inline: True
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
In arch/x86/kernel/early_printk.c (ffffffff81064677)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_vga_write
  - arch/x86/kernel/early_printk.c:early_vga_write
  - arch/x86/kernel/early_printk.c:early_vga_write
```
```
In lib/iomap.c (ffffffff8151a092)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
```
```
In drivers/pci/access.c (ffffffff8155ba4a)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81589e76)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81593b7b)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
```
```
In drivers/video/console/vgacon.c (ffffffff8159cf48)
Location: arch/x86/include/asm/io.h:66
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff815b3157)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81617b4a)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8164fe29)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_out
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81658426)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81658ce9)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff816c749b)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write16le
```
```
In drivers/mailbox/pcc.c (ffffffff8184bcc6)
Location: arch/x86/include/asm/io.h:66
Inline: True
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
In arch/x86/kernel/early_printk.c (ffffffff810745f7)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_vga_write
  - arch/x86/kernel/early_printk.c:early_vga_write
  - arch/x86/kernel/early_printk.c:early_vga_write
```
```
In lib/iomap.c (ffffffff81525e42)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
```
```
In drivers/pci/access.c (ffffffff8156cb0a)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff8159b226)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815a4f6b)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
```
```
In drivers/video/console/vgacon.c (ffffffff815ae338)
Location: arch/x86/include/asm/io.h:66
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff815ca657)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8165149a)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8169f0f9)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_out
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816a7716)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff816a7fd9)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff8171a53b)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write16le
```
```
In drivers/mailbox/pcc.c (ffffffff818e72c6)
Location: arch/x86/include/asm/io.h:66
Inline: True
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
In arch/x86/kernel/early_printk.c (ffffffff81076657)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_vga_write
  - arch/x86/kernel/early_printk.c:early_vga_write
  - arch/x86/kernel/early_printk.c:early_vga_write
```
```
In lib/iomap.c (ffffffff8153f7c2)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
```
```
In drivers/pci/access.c (ffffffff8158700a)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_write
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff815b5666)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815bf36b)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
```
```
In drivers/video/console/vgacon.c (ffffffff815c7ad8)
Location: arch/x86/include/asm/io.h:66
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff815e44f8)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8166bb2a)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_set
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816b95b9)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_out
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816c1b76)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff816c2439)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff8173589b)
Location: arch/x86/include/asm/io.h:66
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write16le
```
```
In drivers/mailbox/pcc.c (ffffffff81903f46)
Location: arch/x86/include/asm/io.h:66
Inline: True
```
</details>
</li>
</ul>

## Differences
