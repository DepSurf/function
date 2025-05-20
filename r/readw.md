# Function: <code>readw</code>

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
In arch/x86/kernel/early_printk.c (ffffffff81061bd4)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_vga_write
```
```
In lib/iomap.c (ffffffff81402722)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - lib/iomap.c:ioread16
```
```
In drivers/pci/access.c (ffffffff8142dd18)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/rom.c (ffffffff8143cfbf)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_get_rom_size
  - drivers/pci/rom.c:pci_get_rom_size
```
```
In drivers/acpi/osl.c (ffffffff8147a16f)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff814c087a)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8150c338)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff8156b261)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read
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
In arch/x86/kernel/early_printk.c (ffffffff810619f6)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_vga_write
```
```
In lib/iomap.c (ffffffff8144a3d2)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - lib/iomap.c:ioread16
```
```
In drivers/pci/access.c (ffffffff814790a9)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/rom.c (ffffffff81488f0d)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_get_rom_size
  - drivers/pci/rom.c:pci_get_rom_size
  - drivers/pci/rom.c:pci_get_rom_size
  - drivers/pci/rom.c:pci_get_rom_size
```
```
In drivers/pci/host/pcie-designware.c (ffffffff814a5222)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff814c8726)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81510e93)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81557319)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8155e658)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81fd39d4)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff815bfb8e)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read16le
```
```
In drivers/mailbox/pcc.c (ffffffff817507a6)
Location: arch/x86/include/asm/io.h:57
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
In arch/x86/kernel/early_printk.c (ffffffff81064aa6)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_vga_write
```
```
In lib/iomap.c (ffffffff81468d92)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - lib/iomap.c:ioread16
```
```
In drivers/pci/access.c (ffffffff8149a4b9)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/rom.c (ffffffff814aa6dd)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_get_rom_size
  - drivers/pci/rom.c:pci_get_rom_size
  - drivers/pci/rom.c:pci_get_rom_size
  - drivers/pci/rom.c:pci_get_rom_size
```
```
In drivers/pci/host/pcie-designware.c (ffffffff814c7492)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff814ea66a)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8153d003)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81583b19)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8158ac48)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff82011394)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff815eefce)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read16le
```
```
In drivers/mailbox/pcc.c (ffffffff8177c104)
Location: arch/x86/include/asm/io.h:57
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
In arch/x86/kernel/early_printk.c (ffffffff81063a7c)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_vga_write
```
```
In lib/iomap.c (ffffffff8146e45b)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - lib/iomap.c:ioread16
```
```
In drivers/pci/access.c (ffffffff814a4057)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/rom.c (ffffffff814b4a2d)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_get_rom_size
  - drivers/pci/rom.c:pci_get_rom_size
  - drivers/pci/rom.c:pci_get_rom_size
  - drivers/pci/rom.c:pci_get_rom_size
```
```
In drivers/pci/dwc/pcie-designware.c (ffffffff814d2ed2)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff814f6484)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81550ca1)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81597f29)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8159ed55)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff820f2f4a)
Location: arch/x86/include/asm/io.h:57
Inline: True
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff8160320e)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read16le
```
```
In drivers/mailbox/pcc.c (ffffffff8179ac54)
Location: arch/x86/include/asm/io.h:57
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
In arch/x86/kernel/early_printk.c (ffffffff81067bec)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_vga_write
```
```
In lib/iomap.c (ffffffff8149a790)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - lib/iomap.c:ioread16
```
```
In drivers/pci/access.c (ffffffff814e2ddd)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/rom.c (ffffffff814f424d)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_get_rom_size
  - drivers/pci/rom.c:pci_get_rom_size
  - drivers/pci/rom.c:pci_get_rom_size
  - drivers/pci/rom.c:pci_get_rom_size
```
```
In drivers/pci/dwc/pcie-designware.c (ffffffff81513362)
Location: arch/x86/include/asm/io.h:58
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff81536c45)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff815b44a4)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff815fcb69)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81604245)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81604b58)
Location: arch/x86/include/asm/io.h:58
Inline: True
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff8166b5de)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read16le
```
```
In drivers/mailbox/pcc.c (ffffffff8181102c)
Location: arch/x86/include/asm/io.h:58
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
In arch/x86/kernel/early_printk.c (ffffffff8106a858)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_vga_write
```
```
In lib/iomap.c (ffffffff814cfa53)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - lib/iomap.c:ioread16
```
```
In drivers/pci/access.c (ffffffff81512c2d)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/rom.c (ffffffff8152430d)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_get_rom_size
  - drivers/pci/rom.c:pci_get_rom_size
  - drivers/pci/rom.c:pci_get_rom_size
  - drivers/pci/rom.c:pci_get_rom_size
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff8153e5d9)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_get_cur_bus_speed
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_mode1_ECC_cap
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81548742)
Location: arch/x86/include/asm/io.h:58
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff8156c7e2)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff815ec895)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81635f49)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8163d4a5)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff8163dde8)
Location: arch/x86/include/asm/io.h:58
Inline: True
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff816a6fbb)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read16le
```
```
In drivers/mailbox/pcc.c (ffffffff8185ae65)
Location: arch/x86/include/asm/io.h:58
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
In arch/x86/kernel/early_printk.c (ffffffff810705e8)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_vga_write
```
```
In lib/iomap.c (ffffffff814e4363)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - lib/iomap.c:ioread16
```
```
In drivers/pci/access.c (ffffffff8152848d)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/rom.c (ffffffff8153a1b8)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff815559a9)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_get_cur_bus_speed
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_mode1_ECC_cap
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8155ee02)
Location: arch/x86/include/asm/io.h:58
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff81584412)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81607465)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816541f9)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8165b725)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff8165c06e)
Location: arch/x86/include/asm/io.h:58
Inline: True
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff816c7afb)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read16le
```
```
In drivers/mailbox/pcc.c (ffffffff8187a2c5)
Location: arch/x86/include/asm/io.h:58
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
In arch/x86/kernel/early_printk.c (ffffffff81074634)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_vga_write
```
```
In lib/iomap.c (ffffffff81510d36)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
```
```
In drivers/pci/access.c (ffffffff8155771d)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/rom.c (ffffffff81569c38)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff815859aa)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_get_cur_bus_speed
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_mode1_ECC_cap
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8158f284)
Location: arch/x86/include/asm/io.h:58
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff815b506b)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8163b22b)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81688c49)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81690e8f)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81691730)
Location: arch/x86/include/asm/io.h:58
Inline: True
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff81702dab)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read16le
```
```
In drivers/mailbox/pcc.c (ffffffff818bf906)
Location: arch/x86/include/asm/io.h:58
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
In arch/x86/kernel/early_printk.c (ffffffff81075604)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_vga_write
```
```
In lib/iomap.c (ffffffff815317a6)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
```
```
In drivers/pci/access.c (ffffffff81578d4d)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/rom.c (ffffffff8158ac08)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff815a738a)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_get_cur_bus_speed
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_mode1_ECC_cap
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815b0ea4)
Location: arch/x86/include/asm/io.h:58
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff815d629b)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8165d6fb)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816ab2d9)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816b38cf)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff816b4220)
Location: arch/x86/include/asm/io.h:58
Inline: True
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff817270fb)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read16le
```
```
In drivers/mailbox/pcc.c (ffffffff818f2426)
Location: arch/x86/include/asm/io.h:58
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
In arch/x86/kernel/early_printk.c (ffffffff8107c814)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_vga_write
```
```
In lib/iomap.c (ffffffff8159592f)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
```
```
In drivers/pci/access.c (ffffffff8161dd5d)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/rom.c (ffffffff816319e1)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_get_rom_size
  - drivers/pci/rom.c:pci_get_rom_size
  - drivers/pci/rom.c:pci_get_rom_size
  - drivers/pci/rom.c:pci_get_rom_size
  - drivers/pci/rom.c:pci_get_rom_size
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff8164fbe8)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_mode1_ECC_cap
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8165a9df)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_read_dbi2
```
```
In drivers/acpi/osl.c (ffffffff8167ff9a)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8170ca7e)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8175df79)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff817672ad)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81767920)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff817e36cb)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read16le
```
```
In drivers/mailbox/pcc.c (ffffffff819c7e96)
Location: arch/x86/include/asm/io.h:58
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
In arch/x86/kernel/early_printk.c (ffffffff8107c664)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_vga_write
```
```
In lib/iomap.c (ffffffff815b13bf)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
```
```
In drivers/pci/access.c (ffffffff8164457d)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/rom.c (ffffffff81656ff1)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_get_rom_size
  - drivers/pci/rom.c:pci_get_rom_size
  - drivers/pci/rom.c:pci_get_rom_size
  - drivers/pci/rom.c:pci_get_rom_size
  - drivers/pci/rom.c:pci_get_rom_size
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81673088)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_mode1_ECC_cap
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8167a764)
Location: arch/x86/include/asm/io.h:58
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff8169ea62)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8172989e)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81778df9)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff817821ed)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81782680)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff817f83db)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read16le
```
```
In drivers/mailbox/pcc.c (ffffffff819c7d66)
Location: arch/x86/include/asm/io.h:58
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
In arch/x86/kernel/early_printk.c (ffffffff8107d814)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_vga_write
```
```
In lib/iomap.c (ffffffff815bc1cf)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
```
```
In drivers/pci/access.c (ffffffff816272e1)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/rom.c (ffffffff81639acc)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81655584)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_mode1_ECC_cap
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8165d26e)
Location: arch/x86/include/asm/io.h:58
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff81681714)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8170e14b)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8175c819)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81765921)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81765f80)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff817dcb6b)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read16le
```
```
In drivers/mailbox/pcc.c (ffffffff819acca6)
Location: arch/x86/include/asm/io.h:58
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
In arch/x86/kernel/early_printk.c (ffffffff8108c244)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_vga_write
```
```
In lib/iomap.c (ffffffff8162301f)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
```
```
In drivers/pci/access.c (ffffffff81696bb1)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/rom.c (ffffffff816aa299)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff816c7441)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_mode1_ECC_cap
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_wait_cmd
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff816cfcde)
Location: arch/x86/include/asm/io.h:58
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff816f6804)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8178a8bb)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff817e097f)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff817ea231)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff817ea8c2)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff8186856b)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read16le
```
```
In drivers/mailbox/pcc.c (ffffffff81a5b1b6)
Location: arch/x86/include/asm/io.h:58
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
In arch/x86/kernel/early_printk.c (ffffffff8109cb33)
Location: arch/x86/include/asm/io.h:60
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_vga_write
```
```
In lib/iomap.c (ffffffff816f2e22)
Location: arch/x86/include/asm/io.h:60
Inline: True
Inline callers:
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
```
```
In drivers/gpio/gpio-mmio.c (ffffffff817b1915)
Location: arch/x86/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_read16
```
```
In drivers/pci/access.c (ffffffff817b7b9c)
Location: arch/x86/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/rom.c (ffffffff817cd15f)
Location: arch/x86/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff817ed451)
Location: arch/x86/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_mode1_ECC_cap
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff817f8caf)
Location: arch/x86/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_read_dbi
```
```
In drivers/acpi/osl.c (ffffffff81823618)
Location: arch/x86/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff818c2177)
Location: arch/x86/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8191f75f)
Location: arch/x86/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81929d39)
Location: arch/x86/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff8192a646)
Location: arch/x86/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff819b0fab)
Location: arch/x86/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read16le
```
```
In drivers/mailbox/pcc.c (ffffffff81bcb1e4)
Location: arch/x86/include/asm/io.h:60
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
In arch/x86/kernel/early_printk.c (ffffffff810b3970)
Location: arch/x86/include/asm/io.h:60
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_vga_write
```
```
In lib/iomap.c (ffffffff817e4cd2)
Location: arch/x86/include/asm/io.h:60
Inline: True
Inline callers:
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
```
```
In drivers/gpio/gpio-mmio.c (ffffffff818cb745)
Location: arch/x86/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_read16
```
```
In drivers/pci/access.c (ffffffff818d23dc)
Location: arch/x86/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/rom.c (ffffffff818ec5bf)
Location: arch/x86/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81914f08)
Location: arch/x86/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81924909)
Location: arch/x86/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_read_dbi
```
```
In drivers/acpi/osl.c (ffffffff81954868)
Location: arch/x86/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81a123a7)
Location: arch/x86/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81a7bc9f)
Location: arch/x86/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81a874d6)
Location: arch/x86/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81a87a76)
Location: arch/x86/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff81b2508b)
Location: arch/x86/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read16be
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read16le
```
```
In drivers/mailbox/pcc.c (ffffffff81d749e4)
Location: arch/x86/include/asm/io.h:60
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
In arch/x86/kernel/early_printk.c (ffffffff810b6a70)
Location: arch/x86/include/asm/io.h:60
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_vga_write
```
```
In lib/iomap.c (ffffffff81824d12)
Location: arch/x86/include/asm/io.h:60
Inline: True
Inline callers:
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
```
```
In drivers/gpio/gpio-mmio.c (ffffffff8190e7b5)
Location: arch/x86/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_read16
```
```
In drivers/pci/access.c (ffffffff819153dc)
Location: arch/x86/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/rom.c (ffffffff8192fa9f)
Location: arch/x86/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81958528)
Location: arch/x86/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81968659)
Location: arch/x86/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_read_dbi
```
```
In drivers/acpi/osl.c (ffffffff8199ac78)
Location: arch/x86/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81a5b3e7)
Location: arch/x86/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81ac785f)
Location: arch/x86/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81ad2aa6)
Location: arch/x86/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81ad2e0e)
Location: arch/x86/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff81b7518b)
Location: arch/x86/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read16be
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read16le
```
```
In drivers/platform/x86/intel/pmc/core_ssram.c (ffffffff81ddca85)
Location: arch/x86/include/asm/io.h:60
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/core_ssram.c:pmc_core_ssram_get_pmc
```
```
In drivers/mailbox/pcc.c (ffffffff81de2924)
Location: arch/x86/include/asm/io.h:60
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
In arch/x86/kernel/early_printk.c (ffffffff810bdeb0)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_vga_write
```
```
In lib/iomap.c (ffffffff81876722)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
```
```
In drivers/gpio/gpio-mmio.c (ffffffff81956525)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_read16
```
```
In drivers/pci/access.c (ffffffff8195d34c)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/rom.c (ffffffff8197841f)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff819a1a98)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff819b1e99)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_read_dbi
```
```
In drivers/acpi/osl.c (ffffffff819e30f8)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81aac857)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81b1a47f)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_in
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81b2284e)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81b269f6)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff81bc900b)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read16be
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read16le
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81dea6af)
Location: arch/x86/include/asm/io.h:57
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_read_word
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_read_word
```
```
In drivers/mailbox/pcc.c (ffffffff81e98878)
Location: arch/x86/include/asm/io.h:57
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
In lib/iomap.c (c0000000007e54e0)
Location: arch/powerpc/include/asm/io-defs.h:6
Inline: True
```
```
In drivers/pinctrl/pinctrl-single.c (c000000000833b78)
Location: arch/powerpc/include/asm/io-defs.h:6
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_readw
```
```
In drivers/gpio/gpio-mmio.c (c000000000848fc8)
Location: arch/powerpc/include/asm/io-defs.h:6
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_read16
```
```
In drivers/pci/access.c (c0000000008539d0)
Location: arch/powerpc/include/asm/io-defs.h:6
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/pci-sysfs.c (c00000000086b8d0)
Location: arch/powerpc/include/asm/io-defs.h:6
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/pci/rom.c (c00000000086c7bc)
Location: arch/powerpc/include/asm/io-defs.h:6
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/quirks.c (c000000000879170)
Location: arch/powerpc/include/asm/io-defs.h:6
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
```
```
In drivers/pci/controller/pcie-cadence-ep.c (c00000000088fee0)
Location: arch/powerpc/include/asm/io-defs.h:6
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_get_msi
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_msi
```
```
In drivers/virtio/virtio_mmio.c (c0000000008d2638)
Location: arch/powerpc/include/asm/io-defs.h:6
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/tty/serial/8250/8250_port.c (c00000000092d6bc)
Location: arch/powerpc/include/asm/io-defs.h:6
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (c000000000938234)
Location: arch/powerpc/include/asm/io-defs.h:6
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/tty/serial/8250/8250_early.c (c00000000093a658)
Location: arch/powerpc/include/asm/io-defs.h:6
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
```
```
In drivers/base/regmap/regmap-mmio.c (c0000000009c1000)
Location: arch/powerpc/include/asm/io-defs.h:6
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read16le
```
```
In drivers/usb/host/pci-quirks.c (c000000000b18e50)
Location: arch/powerpc/include/asm/io-defs.h:6
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
```
```
In drivers/usb/host/uhci-hcd.c (c000000000b39fec)
Location: arch/powerpc/include/asm/io-defs.h:6
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_get_frame_number
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:any_ports_active
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
```
```
In drivers/i2c/busses/i2c-designware-common.c (c000000000b9b978)
Location: arch/powerpc/include/asm/io-defs.h:6
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:dw_readl
  - drivers/i2c/busses/i2c-designware-common.c:dw_readl
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
In arch/x86/kernel/early_printk.c (ffffffff81074604)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_vga_write
```
```
In lib/iomap.c (ffffffff81529d86)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
```
```
In drivers/gpio/gpio-mmio.c (ffffffff81569a25)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_read16
```
```
In drivers/pci/access.c (ffffffff8156d26d)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/rom.c (ffffffff8157ea88)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff8159ab9a)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_get_cur_bus_speed
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_mode1_ECC_cap
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815a4664)
Location: arch/x86/include/asm/io.h:58
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff815c9ffb)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8162359b)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81670d49)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8167932f)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81679c80)
Location: arch/x86/include/asm/io.h:58
Inline: True
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff816ecedb)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read16le
```
```
In drivers/mailbox/pcc.c (ffffffff81893756)
Location: arch/x86/include/asm/io.h:58
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
In arch/x86/kernel/early_printk.c (ffffffff81064634)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_vga_write
```
```
In lib/iomap.c (ffffffff8151a066)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
```
```
In drivers/pci/access.c (ffffffff8155b9dd)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/rom.c (ffffffff8156d868)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81589d2a)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_get_cur_bus_speed
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_mode1_ECC_cap
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81593804)
Location: arch/x86/include/asm/io.h:58
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff815b307b)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81617beb)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8164fe49)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8165841f)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81658d70)
Location: arch/x86/include/asm/io.h:58
Inline: True
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff816c751b)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read16le
```
```
In drivers/mailbox/pcc.c (ffffffff8184bc56)
Location: arch/x86/include/asm/io.h:58
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
In arch/x86/kernel/early_printk.c (ffffffff810745b4)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_vga_write
```
```
In lib/iomap.c (ffffffff81525e16)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
```
```
In drivers/pci/access.c (ffffffff8156ca9d)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/rom.c (ffffffff8157e958)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff8159b0da)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_get_cur_bus_speed
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_mode1_ECC_cap
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815a4bf4)
Location: arch/x86/include/asm/io.h:58
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff815ca57b)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8165153b)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8169f119)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816a770f)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff816a8060)
Location: arch/x86/include/asm/io.h:58
Inline: True
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff8171a5bb)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read16le
```
```
In drivers/mailbox/pcc.c (ffffffff818e7256)
Location: arch/x86/include/asm/io.h:58
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
In arch/x86/kernel/early_printk.c (ffffffff81076614)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/early_printk.c:early_vga_write
```
```
In lib/iomap.c (ffffffff8153f796)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
```
```
In drivers/pci/access.c (ffffffff81586f9d)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_generic_config_read
```
```
In drivers/pci/rom.c (ffffffff81598e08)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff815b551a)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_get_cur_bus_speed
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_get_mode1_ECC_cap
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815beff4)
Location: arch/x86/include/asm/io.h:58
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff815e43f7)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8166bbcb)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816b95d9)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem16_serial_in
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816c1b6f)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff816c24c0)
Location: arch/x86/include/asm/io.h:58
Inline: True
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff8173591b)
Location: arch/x86/include/asm/io.h:58
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read16le
```
```
In drivers/mailbox/pcc.c (ffffffff81903ed6)
Location: arch/x86/include/asm/io.h:58
Inline: True
```
</details>
</li>
</ul>

## Differences
