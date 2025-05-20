# Function: <code>readb</code>

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
In lib/iomap.c (ffffffff814026e1)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - lib/iomap.c:ioread8
```
```
In lib/check_signature.c (ffffffff814033d8)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - lib/check_signature.c:check_signature
```
```
In drivers/pci/access.c (ffffffff8142dd29)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/rom.c (ffffffff8143cfb8)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_get_rom_size
  - drivers/pci/rom.c:pci_get_rom_size
  - drivers/pci/rom.c:pci_get_rom_size
  - drivers/pci/rom.c:pci_get_rom_size
  - drivers/pci/rom.c:pci_get_rom_size
  - drivers/pci/rom.c:pci_get_rom_size
  - drivers/pci/rom.c:pci_get_rom_size
```
```
In drivers/pci/quirks.c (ffffffff8144457c)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/video/console/vgacon.c (ffffffff8145f45c)
Location: arch/x86/include/asm/io.h:56
Inline: True
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff8147744b)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/acpi/osl.c (ffffffff8147a155)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff814c084c)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81505b09)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8150b09d)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81fa7577)
Location: arch/x86/include/asm/io.h:56
Inline: True
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8150e94c)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_tx_empty
  - drivers/tty/serial/sccnxp.c:sccnxp_get_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_console_putchar
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81522a8a)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff8156b253)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read
```
```
In drivers/usb/host/pci-quirks.c (ffffffff816309f9)
Location: arch/x86/include/asm/io.h:56
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816378a9)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
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
In lib/iomap.c (ffffffff8144a391)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - lib/iomap.c:ioread8
```
```
In lib/check_signature.c (ffffffff8144b018)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - lib/check_signature.c:check_signature
```
```
In drivers/pci/access.c (ffffffff814790ba)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/rom.c (ffffffff81488f20)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_get_rom_size
```
```
In drivers/pci/quirks.c (ffffffff8149044f)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/host/pcie-designware.c (ffffffff814a520f)
Location: arch/x86/include/asm/io.h:56
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffff814ad67f)
Location: arch/x86/include/asm/io.h:56
Inline: True
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff814c5994)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/acpi/osl.c (ffffffff814c870c)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81510e72)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff815572b9)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8155d85d)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81fd39c7)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8156142c)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_console_putchar
  - drivers/tty/serial/sccnxp.c:sccnxp_get_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_tx_empty
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8157592b)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff815bfb6e)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read8
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81691664)
Location: arch/x86/include/asm/io.h:56
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816985be)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
```
In drivers/mailbox/pcc.c (ffffffff81750798)
Location: arch/x86/include/asm/io.h:56
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
In lib/iomap.c (ffffffff81468d51)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - lib/iomap.c:ioread8
```
```
In lib/check_signature.c (ffffffff814699d8)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - lib/check_signature.c:check_signature
```
```
In drivers/pci/access.c (ffffffff8149a4ca)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/rom.c (ffffffff814aa6f0)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_get_rom_size
```
```
In drivers/pci/quirks.c (ffffffff814b1c9f)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/host/pcie-designware.c (ffffffff814c747f)
Location: arch/x86/include/asm/io.h:56
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffff814cf5f3)
Location: arch/x86/include/asm/io.h:56
Inline: True
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff814e79fc)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/acpi/osl.c (ffffffff814ea650)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8153cfe2)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81583ab9)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8158a02d)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff82011387)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8158db9c)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_console_putchar
  - drivers/tty/serial/sccnxp.c:sccnxp_get_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_tx_empty
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
```
In drivers/char/agp/intel-gtt.c (ffffffff815a1fb8)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff815eefae)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read8
```
```
In drivers/usb/host/pci-quirks.c (ffffffff816bf714)
Location: arch/x86/include/asm/io.h:56
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816c6aee)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff8177abaf)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ppfear_sts_show
```
```
In drivers/mailbox/pcc.c (ffffffff8177c0ee)
Location: arch/x86/include/asm/io.h:56
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
In lib/iomap.c (ffffffff8146e41a)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - lib/iomap.c:ioread8
```
```
In lib/check_signature.c (ffffffff8146f0b8)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - lib/check_signature.c:check_signature
```
```
In drivers/pci/access.c (ffffffff814a4047)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/rom.c (ffffffff814b4a40)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_get_rom_size
```
```
In drivers/pci/quirks.c (ffffffff814bc0f1)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/dwc/pcie-designware.c (ffffffff814d2eb2)
Location: arch/x86/include/asm/io.h:56
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffff814db711)
Location: arch/x86/include/asm/io.h:56
Inline: True
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff814f3607)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/acpi/osl.c (ffffffff814f6498)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81550c82)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81597ec9)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8159eabe)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff820f2f3c)
Location: arch/x86/include/asm/io.h:56
Inline: True
```
```
In drivers/tty/serial/sccnxp.c (ffffffff815a1c08)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_console_putchar
  - drivers/tty/serial/sccnxp.c:sccnxp_get_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_tx_empty
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
```
In drivers/char/agp/intel-gtt.c (ffffffff815b5ae7)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff816031ee)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read8
```
```
In drivers/usb/host/pci-quirks.c (ffffffff816d4113)
Location: arch/x86/include/asm/io.h:56
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816db2e1)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff81798fef)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ppfear_sts_show
```
```
In drivers/mailbox/pcc.c (ffffffff8179ac3e)
Location: arch/x86/include/asm/io.h:56
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
In lib/iomap.c (ffffffff8149a74f)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - lib/iomap.c:ioread8
```
```
In lib/check_signature.c (ffffffff8149b498)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - lib/check_signature.c:check_signature
```
```
In drivers/pci/access.c (ffffffff814e2dcd)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/rom.c (ffffffff814f4260)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_get_rom_size
```
```
In drivers/pci/quirks.c (ffffffff814fc561)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/dwc/pcie-designware.c (ffffffff81513342)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffff8151bb3c)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff81533cc7)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/acpi/osl.c (ffffffff81536c0d)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff815b4482)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff815fcb09)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81603fae)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81604b70)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81607368)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_console_putchar
  - drivers/tty/serial/sccnxp.c:sccnxp_get_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_tx_empty
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8161cb3b)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff8166b5be)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read8
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81740803)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81747a11)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff8180f2cc)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ppfear_sts_show
```
```
In drivers/mailbox/pcc.c (ffffffff81811014)
Location: arch/x86/include/asm/io.h:57
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
In lib/iomap.c (ffffffff814cfa12)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - lib/iomap.c:ioread8
```
```
In lib/check_signature.c (ffffffff814d0744)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - lib/check_signature.c:check_signature
```
```
In drivers/pci/access.c (ffffffff81512c3e)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/rom.c (ffffffff81524320)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_get_rom_size
```
```
In drivers/pci/quirks.c (ffffffff8152d249)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff8153efea)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_get_cur_bus_speed
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_mode1_ECC_cap
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_speed
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81548722)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffff815507e0)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff81569a2e)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/acpi/osl.c (ffffffff8156c855)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff815ec873)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81635ee9)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8163d36d)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff8163de00)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81640a28)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_console_putchar
  - drivers/tty/serial/sccnxp.c:sccnxp_get_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_tx_empty
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8165664e)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff816a6f9b)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read8
```
```
In drivers/usb/host/pci-quirks.c (ffffffff8178136e)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81788211)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff8185914e)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ppfear_sts_show
```
```
In drivers/mailbox/pcc.c (ffffffff8185ae59)
Location: arch/x86/include/asm/io.h:57
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
In lib/iomap.c (ffffffff814e4322)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - lib/iomap.c:ioread8
```
```
In lib/check_signature.c (ffffffff814e5074)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - lib/check_signature.c:check_signature
```
```
In drivers/pci/access.c (ffffffff8152849e)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/rom.c (ffffffff8153a1f0)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/quirks.c (ffffffff81544099)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81556418)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_get_cur_bus_speed
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_mode1_ECC_cap
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_speed
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8155ede2)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffff81568660)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff8158148e)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/acpi/osl.c (ffffffff81584485)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81607443)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81654199)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8165b5ed)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff8165c030)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8165e5ec)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_read
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816743c2)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff816c7adb)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read8
```
```
In drivers/usb/host/pci-quirks.c (ffffffff817a7b94)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817b13f1)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff818781ee)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ppfear_show
```
```
In drivers/mailbox/pcc.c (ffffffff8187a2b9)
Location: arch/x86/include/asm/io.h:57
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
In lib/iomap.c (ffffffff81510a81)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - lib/iomap.c:ioread8
```
```
In lib/check_signature.c (ffffffff81511aab)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - lib/check_signature.c:check_signature
```
```
In drivers/pci/access.c (ffffffff8155772e)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/rom.c (ffffffff81569c70)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/quirks.c (ffffffff815736d6)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81586839)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_get_cur_bus_speed
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_mode1_ECC_cap
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_speed
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8158f264)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffff8159913e)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff815b1b3f)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/acpi/osl.c (ffffffff815b5094)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8163b265)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81688be9)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81690d52)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81691743)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81693bca)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_read
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816aa4da)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff81702d8b)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read8
```
```
In drivers/usb/host/pci-quirks.c (ffffffff817e6d41)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817f207e)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff818bcf85)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ppfear_show
```
```
In drivers/mailbox/pcc.c (ffffffff818bf935)
Location: arch/x86/include/asm/io.h:57
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
In lib/iomap.c (ffffffff815314f1)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - lib/iomap.c:ioread8
```
```
In lib/check_signature.c (ffffffff815324eb)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - lib/check_signature.c:check_signature
```
```
In drivers/pci/access.c (ffffffff81578d5e)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/rom.c (ffffffff8158ac40)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/quirks.c (ffffffff81594d26)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff815a8215)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_get_cur_bus_speed
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_mode1_ECC_cap
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_speed
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815b0e84)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffff815ba4de)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff815d2abf)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/acpi/osl.c (ffffffff815d62c4)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8165d735)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816ab279)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816b1958)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:f815xxa_mem_serial_out
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff816b4233)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/tty/serial/sccnxp.c (ffffffff816b676a)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_read
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816cd21b)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff817270db)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read8
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81817c01)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81822f6e)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff818efaa5)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ppfear_show
```
```
In drivers/mailbox/pcc.c (ffffffff818f2455)
Location: arch/x86/include/asm/io.h:57
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
In lib/iomap.c (ffffffff8159578a)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - lib/iomap.c:ioread8
```
```
In lib/check_signature.c (ffffffff81596bd8)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - lib/check_signature.c:check_signature
```
```
In drivers/pci/access.c (ffffffff8161dd6e)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/rom.c (ffffffff81631a0f)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_get_rom_size
```
```
In drivers/pci/quirks.c (ffffffff81643424)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81650488)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_mode1_ECC_cap
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_speed
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8165a9d4)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_read_dbi2
```
```
In drivers/video/console/vgacon.c (ffffffff8166471e)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff8167c5d2)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
```
```
In drivers/acpi/osl.c (ffffffff8167ffc0)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8170cabe)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8175df19)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81764ed8)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:f815xxa_mem_serial_out
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81767933)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8176a582)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_console_putchar
  - drivers/tty/serial/sccnxp.c:sccnxp_get_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_tx_empty
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81781cd7)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_stolen_size
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff817e36ab)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read8
```
```
In drivers/mfd/intel_msic.c (ffffffff8180c33f)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/mfd/intel_msic.c:intel_msic_irq_read
```
```
In drivers/usb/host/pci-quirks.c (ffffffff818e8fce)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818ebdb9)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff819c3919)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ppfear_show
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff819c5286)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/mailbox/pcc.c (ffffffff819c7ec5)
Location: arch/x86/include/asm/io.h:57
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
In lib/iomap.c (ffffffff815b121a)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - lib/iomap.c:ioread8
```
```
In lib/check_signature.c (ffffffff815b25f8)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - lib/check_signature.c:check_signature
```
```
In drivers/pci/access.c (ffffffff8164458e)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/rom.c (ffffffff8165701f)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_get_rom_size
```
```
In drivers/pci/quirks.c (ffffffff81669884)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81673928)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_mode1_ECC_cap
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_speed
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8167a744)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffff816853ae)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff81bff40e)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
```
```
In drivers/acpi/osl.c (ffffffff8169ea89)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff817298de)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81778d99)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8177fdd8)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:f815xxa_mem_serial_out
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81782693)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
```
```
In drivers/tty/serial/sccnxp.c (ffffffff817851d2)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_console_putchar
  - drivers/tty/serial/sccnxp.c:sccnxp_get_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_tx_empty
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81c09c67)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_stolen_size
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff817f839b)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read8
```
```
In drivers/mfd/intel_msic.c (ffffffff8181b59f)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/mfd/intel_msic.c:intel_msic_irq_read
```
```
In drivers/usb/host/pci-quirks.c (ffffffff818f1d4e)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818f4c89)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff819c3cb9)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ppfear_show
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff819c54b6)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/mailbox/pcc.c (ffffffff819c7d95)
Location: arch/x86/include/asm/io.h:57
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
In lib/iomap.c (ffffffff815bc02a)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - lib/iomap.c:ioread8
```
```
In lib/check_signature.c (ffffffff815bd478)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - lib/check_signature.c:check_signature
```
```
In drivers/pci/access.c (ffffffff816272f6)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/rom.c (ffffffff81639b03)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/quirks.c (ffffffff8164bd36)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81bef6de)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_mode1_ECC_cap
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_speed
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8165d244)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffff81667a4e)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff81bf0f01)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
```
```
In drivers/acpi/osl.c (ffffffff8168173b)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8170e18b)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8175c7b9)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81763708)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:f815xxa_mem_serial_out
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81765f93)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81768af2)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_console_putchar
  - drivers/tty/serial/sccnxp.c:sccnxp_get_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_tx_empty
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_set_baud
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81bfb70b)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_stolen_size
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff817dcb2b)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read8
```
```
In drivers/usb/host/pci-quirks.c (ffffffff818d553e)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818d8249)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff819a82ed)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_get_low_power_modes
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ppfear_show
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff819aa482)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/mailbox/pcc.c (ffffffff819accd5)
Location: arch/x86/include/asm/io.h:57
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
In lib/iomap.c (ffffffff81622e7a)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - lib/iomap.c:ioread8
```
```
In lib/check_signature.c (ffffffff81624818)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - lib/check_signature.c:check_signature
```
```
In drivers/pci/access.c (ffffffff81696bc6)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/rom.c (ffffffff816aa2d0)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/quirks.c (ffffffff816bd706)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81cea998)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_mode1_ECC_cap
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_speed
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff816cfcb4)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffff816dacae)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff81ced5d0)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
```
```
In drivers/acpi/osl.c (ffffffff816f682b)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8178a8fb)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff817e0a0f)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff817e7ae8)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:f815xxa_mem_serial_out
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff817ea8e6)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
```
```
In drivers/tty/serial/sccnxp.c (ffffffff817eef30)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_console_putchar
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81cfc309)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_stolen_size
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff8186852b)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read8
```
```
In drivers/usb/host/pci-quirks.c (ffffffff8197018e)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81973059)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81a55546)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_ppfear_show
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff81a57d86)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/mailbox/pcc.c (ffffffff81a5b1e2)
Location: arch/x86/include/asm/io.h:57
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
In lib/iomap.c (ffffffff816f2c0d)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - lib/iomap.c:ioread8
```
```
In lib/check_signature.c (ffffffff816f4f08)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - lib/check_signature.c:check_signature
```
```
In arch/x86/lib/iomem.c (ffffffff81775d02)
Location: arch/x86/include/asm/io.h:59
Inline: True
```
```
In drivers/gpio/gpio-mmio.c (ffffffff817b18d5)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_read8
```
```
In drivers/pci/access.c (ffffffff817b7ba4)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/rom.c (ffffffff817cd184)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/quirks.c (ffffffff817e308a)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81eb1a12)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_mode1_ECC_cap
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_speed
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff817f8c99)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_read_dbi
```
```
In drivers/video/console/vgacon.c (ffffffff8180507c)
Location: arch/x86/include/asm/io.h:59
Inline: True
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff81eb4c75)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
```
```
In drivers/acpi/osl.c (ffffffff81823677)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff818c21dd)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8191f7ff)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff819275f8)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:f815xxa_mem_serial_out
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff8192a67f)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8192f050)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_console_putchar
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81ec4b53)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_stolen_size
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff819b0f6b)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read8
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81aca70d)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81ace91a)
Location: arch/x86/include/asm/io.h:59
Inline: True
```
```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81bc4d06)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_ppfear_show
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff81bc7927)
Location: arch/x86/include/asm/io.h:59
Inline: True
```
```
In drivers/mailbox/pcc.c (ffffffff81bcb273)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_send_data
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
In lib/iomap.c (ffffffff817e4a7d)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - lib/iomap.c:ioread8
```
```
In lib/check_signature.c (ffffffff817e7158)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - lib/check_signature.c:check_signature
```
```
In arch/x86/lib/iomem.c (ffffffff818a6a42)
Location: arch/x86/include/asm/io.h:59
Inline: True
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff818b029c)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_set_mux
  - drivers/pinctrl/pinctrl-amd.c:amd_set_mux
```
```
In drivers/gpio/gpio-mmio.c (ffffffff818cb6e5)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_read8
```
```
In drivers/pci/access.c (ffffffff818d23e4)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/rom.c (ffffffff818ec5e4)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/quirks.c (ffffffff81906f61)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81915ab2)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_speed
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff819248d1)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_read_dbi
```
```
In drivers/video/console/vgacon.c (ffffffff8193391c)
Location: arch/x86/include/asm/io.h:59
Inline: True
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff8194fbe9)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
```
```
In drivers/acpi/osl.c (ffffffff819548c7)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81a1240d)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81a7bd5f)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81a84338)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:f815xxa_mem_serial_out
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81a87aaf)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81a8d3b0)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_console_putchar
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81aa2af6)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_stolen_size
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff81b24edb)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read8
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81c54cfd)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81c591ba)
Location: arch/x86/include/asm/io.h:59
Inline: True
```
```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81d6cfb6)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_ppfear_show
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff81d704f7)
Location: arch/x86/include/asm/io.h:59
Inline: True
```
```
In drivers/mailbox/pcc.c (ffffffff81d74a73)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_send_data
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
In lib/iomap.c (ffffffff81824abd)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - lib/iomap.c:ioread8
```
```
In lib/check_signature.c (ffffffff81827158)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - lib/check_signature.c:check_signature
```
```
In arch/x86/lib/iomem.c (ffffffff818e98b2)
Location: arch/x86/include/asm/io.h:59
Inline: True
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff818f327c)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_set_mux
  - drivers/pinctrl/pinctrl-amd.c:amd_set_mux
```
```
In drivers/gpio/gpio-mmio.c (ffffffff8190e755)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_read8
```
```
In drivers/pci/access.c (ffffffff819153e8)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/rom.c (ffffffff8192fac4)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/quirks.c (ffffffff8194a57b)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff819590be)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_speed
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81968621)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_read_dbi
```
```
In drivers/video/console/vgacon.c (ffffffff81977dd9)
Location: arch/x86/include/asm/io.h:59
Inline: True
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff819960d9)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
```
```
In drivers/acpi/osl.c (ffffffff8199accd)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81a5b416)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81ac791f)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81acfb28)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:f815xxa_mem_serial_out
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81ad2e39)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81ad8b30)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_console_putchar
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81aee32b)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_stolen_size
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff81b74fdb)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read8
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81cbc27d)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81cc0098)
Location: arch/x86/include/asm/io.h:59
Inline: True
```
```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81dda3f2)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_ppfear_show
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff81dde1b7)
Location: arch/x86/include/asm/io.h:59
Inline: True
```
```
In drivers/mailbox/pcc.c (ffffffff81de29b0)
Location: arch/x86/include/asm/io.h:59
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_send_data
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
In lib/iomap.c (ffffffff818764cd)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - lib/iomap.c:ioread8
```
```
In lib/check_signature.c (ffffffff81878b68)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - lib/check_signature.c:check_signature
```
```
In arch/x86/lib/iomem.c (ffffffff81930d52)
Location: arch/x86/include/asm/io.h:56
Inline: True
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8193aaac)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_set_mux
  - drivers/pinctrl/pinctrl-amd.c:amd_set_mux
```
```
In drivers/gpio/gpio-mmio.c (ffffffff819564c5)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_read8
```
```
In drivers/pci/access.c (ffffffff8195d358)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/rom.c (ffffffff81978444)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/quirks.c (ffffffff8199392b)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff819a262e)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_speed
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff819b1e61)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_read_dbi
```
```
In drivers/video/console/vgacon.c (ffffffff819c1e79)
Location: arch/x86/include/asm/io.h:56
Inline: True
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff819e0759)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:chips_hw_init
```
```
In drivers/acpi/osl.c (ffffffff819e314d)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81aac886)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81b1a53f)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem_serial_in
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81b22879)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81b23988)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:f815xxa_mem_serial_out
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81b2be20)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_console_putchar
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81b4186b)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_stolen_size
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff81bc8e5b)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read8
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81d70fed)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81d74e58)
Location: arch/x86/include/asm/io.h:56
Inline: True
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff81e9408f)
Location: arch/x86/include/asm/io.h:56
Inline: True
```
```
In drivers/mailbox/pcc.c (ffffffff81e9891c)
Location: arch/x86/include/asm/io.h:56
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_send_data
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
In arch/powerpc/kernel/legacy_serial.c (c0000000000686f4)
Location: arch/powerpc/include/asm/io-defs.h:5
Inline: True
```
```
In arch/powerpc/kernel/udbg_16550.c (c000000000068ac0)
Location: arch/powerpc/include/asm/io-defs.h:5
Inline: True
Inline callers:
  - arch/powerpc/kernel/udbg_16550.c:udbg_uart_in_pio
```
```
In arch/powerpc/sysdev/i8259.c (c0000000000b9300)
Location: arch/powerpc/include/asm/io-defs.h:5
Inline: True
Inline callers:
  - arch/powerpc/sysdev/i8259.c:i8259_mask_and_ack_irq
  - arch/powerpc/sysdev/i8259.c:i8259_mask_and_ack_irq
  - arch/powerpc/sysdev/i8259.c:i8259_irq
  - arch/powerpc/sysdev/i8259.c:i8259_irq
  - arch/powerpc/sysdev/i8259.c:i8259_irq
  - arch/powerpc/sysdev/i8259.c:i8259_irq
```
```
In kernel/debug/kdb/kdb_keyboard.c (c000000000282f50)
Location: arch/powerpc/include/asm/io-defs.h:5
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state
  - kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state
  - kernel/debug/kdb/kdb_keyboard.c:kdb_kbd_cleanup_state
  - kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char
  - kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char
  - kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char
  - kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char
  - kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char
```
```
In lib/iomap.c (c0000000007e5b00)
Location: arch/powerpc/include/asm/io-defs.h:5
Inline: True
```
```
In lib/check_signature.c (c0000000007e8108)
Location: arch/powerpc/include/asm/io-defs.h:5
Inline: True
Inline callers:
  - lib/check_signature.c:check_signature
```
```
In drivers/pinctrl/pinctrl-single.c (c000000000833c18)
Location: arch/powerpc/include/asm/io-defs.h:5
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_readb
```
```
In drivers/gpio/gpio-mmio.c (c000000000849068)
Location: arch/powerpc/include/asm/io-defs.h:5
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_read8
```
```
In drivers/pci/access.c (c000000000853a20)
Location: arch/powerpc/include/asm/io-defs.h:5
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/pci-sysfs.c (c00000000086b860)
Location: arch/powerpc/include/asm/io-defs.h:5
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/pci/rom.c (c00000000086c830)
Location: arch/powerpc/include/asm/io-defs.h:5
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/quirks.c (c00000000087a48c)
Location: arch/powerpc/include/asm/io-defs.h:5
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/video/console/vgacon.c (c00000000089d200)
Location: arch/powerpc/include/asm/io-defs.h:5
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/asiliantfb.c (c0000000008c23c8)
Location: arch/powerpc/include/asm/io-defs.h:5
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/virtio/virtio_mmio.c (c0000000008d273c)
Location: arch/powerpc/include/asm/io-defs.h:5
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/tty/serial/8250/8250_port.c (c000000000933a20)
Location: arch/powerpc/include/asm/io-defs.h:5
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:io_serial_in
  - drivers/tty/serial/8250/8250_port.c:mem_serial_in
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (c000000000938540)
Location: arch/powerpc/include/asm/io-defs.h:5
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:kt_serial_in
  - drivers/tty/serial/8250/8250_pci.c:f815xxa_mem_serial_out
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqmcr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqopr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_wqopr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqopr
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_rqopr
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
```
```
In drivers/tty/serial/8250/8250_early.c (c00000000093a850)
Location: arch/powerpc/include/asm/io-defs.h:5
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
```
```
In drivers/tty/serial/sccnxp.c (c00000000093c310)
Location: arch/powerpc/include/asm/io-defs.h:5
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_read
```
```
In drivers/char/mem.c (c000000000942880)
Location: arch/powerpc/include/asm/io-defs.h:5
Inline: True
Inline callers:
  - drivers/char/mem.c:read_port
```
```
In drivers/base/regmap/regmap-mmio.c (c0000000009c10b0)
Location: arch/powerpc/include/asm/io-defs.h:5
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read8
```
```
In drivers/ata/libata-sff.c (c000000000a79c60)
Location: arch/powerpc/include/asm/io-defs.h:5
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
```
```
In drivers/usb/host/pci-quirks.c (c000000000b196a0)
Location: arch/powerpc/include/asm/io-defs.h:5
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/usb/host/ehci-hcd.c (c000000000b2911c)
Location: arch/powerpc/include/asm/io-defs.h:5
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
```
In drivers/usb/host/uhci-hcd.c (c000000000b3d980)
Location: arch/powerpc/include/asm/io-defs.h:5
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
```
```
In drivers/input/serio/i8042.c (c000000000b708cc)
Location: arch/powerpc/include/asm/io-defs.h:5
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_interrupt
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_wait_write
```
```
In drivers/rtc/rtc-mc146818-lib.c (c000000000b8f5a4)
Location: arch/powerpc/include/asm/io-defs.h:5
Inline: True
Inline callers:
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
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
In lib/iomap.c (ffffffff81529ad1)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - lib/iomap.c:ioread8
```
```
In lib/check_signature.c (ffffffff8152aacb)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - lib/check_signature.c:check_signature
```
```
In drivers/gpio/gpio-mmio.c (ffffffff81569a05)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_read8
```
```
In drivers/pci/access.c (ffffffff8156d27e)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/rom.c (ffffffff8157eac0)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/quirks.c (ffffffff81588bb6)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff8159ba25)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_get_cur_bus_speed
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_mode1_ECC_cap
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_speed
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815a4644)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffff815ae62e)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff815c6acf)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/acpi/osl.c (ffffffff815ca024)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff816235d5)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81670ce9)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816773c8)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:f815xxa_mem_serial_out
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81679c93)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8167c1ca)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_read
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81692c6a)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff816ecebb)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read8
```
```
In drivers/usb/host/pci-quirks.c (ffffffff817cffe1)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817db34e)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff81890dd5)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ppfear_show
```
```
In drivers/mailbox/pcc.c (ffffffff81893785)
Location: arch/x86/include/asm/io.h:57
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
In lib/iomap.c (ffffffff81519db1)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - lib/iomap.c:ioread8
```
```
In lib/check_signature.c (ffffffff8151adab)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - lib/check_signature.c:check_signature
```
```
In drivers/pci/access.c (ffffffff8155b9ee)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/rom.c (ffffffff8156d8a0)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/quirks.c (ffffffff81577966)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff8158abb5)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_get_cur_bus_speed
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_mode1_ECC_cap
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_speed
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815937e4)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffff8159da48)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff815b30a4)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81617c25)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8164fde9)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816564a8)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:f815xxa_mem_serial_out
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81658d83)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8165b2ba)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_read
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8167065b)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff816c74fb)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read8
```
```
In drivers/usb/host/pci-quirks.c (ffffffff817adf11)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff8184a095)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ppfear_show
```
```
In drivers/mailbox/pcc.c (ffffffff8184bc85)
Location: arch/x86/include/asm/io.h:57
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
In lib/iomap.c (ffffffff81525b61)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - lib/iomap.c:ioread8
```
```
In lib/check_signature.c (ffffffff81526b5b)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - lib/check_signature.c:check_signature
```
```
In drivers/pci/access.c (ffffffff8156caae)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/rom.c (ffffffff8157e990)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/quirks.c (ffffffff81588a76)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff8159bf65)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_get_cur_bus_speed
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_mode1_ECC_cap
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_speed
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815a4bd4)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffff815aebbe)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff815c705f)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/acpi/osl.c (ffffffff815ca5a4)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81651575)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8169f0b9)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816a5798)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:f815xxa_mem_serial_out
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff816a8073)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/tty/serial/sccnxp.c (ffffffff816aa5aa)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_read
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816c0edb)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff8171a59b)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read8
```
```
In drivers/usb/host/pci-quirks.c (ffffffff8180ca81)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81817dee)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff818e48d5)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ppfear_show
```
```
In drivers/mailbox/pcc.c (ffffffff818e7285)
Location: arch/x86/include/asm/io.h:57
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
In lib/iomap.c (ffffffff8153f4e1)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - lib/iomap.c:ioread8
```
```
In lib/check_signature.c (ffffffff815404db)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - lib/check_signature.c:check_signature
```
```
In drivers/pci/access.c (ffffffff81586fae)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/rom.c (ffffffff81598e40)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/quirks.c (ffffffff815a2f26)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff815b6395)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_get_cur_bus_speed
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_mode1_ECC_cap
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_adapter_speed
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815befd4)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/video/console/vgacon.c (ffffffff815c86b2)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff815e0bff)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/acpi/osl.c (ffffffff815e4420)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8166bc05)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816b9579)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816bfbf8)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:f815xxa_mem_serial_out
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff816c24d3)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/tty/serial/sccnxp.c (ffffffff816c4a0a)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_read
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816db4ab)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff817358fb)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read8
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81826b91)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81831dde)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff81901535)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ppfear_show
```
```
In drivers/mailbox/pcc.c (ffffffff81903f05)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
</details>
</li>
</ul>

## Differences
