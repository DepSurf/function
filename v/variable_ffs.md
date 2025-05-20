# Function: <code>variable_ffs</code>

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
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81089994)
Location: arch/x86/include/asm/bitops.h:305
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff83e90b5d)
Location: arch/x86/include/asm/bitops.h:305
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:set_block_size
```
```
In kernel/softirq.c (ffffffff820d6f4f)
Location: arch/x86/include/asm/bitops.h:305
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In fs/ext4/mballoc.c (ffffffff8158c6fa)
Location: arch/x86/include/asm/bitops.h:305
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/squashfs/xz_wrapper.c (ffffffff815f44a1)
Location: arch/x86/include/asm/bitops.h:305
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_comp_opts
```
```
In fs/fat/inode.c (ffffffff81602feb)
Location: arch/x86/include/asm/bitops.h:305
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In drivers/pci/pci.c (ffffffff818dcbc4)
Location: arch/x86/include/asm/bitops.h:305
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/video/fbdev/core/cfbfillrect.c (0)
Location: arch/x86/include/asm/bitops.h:305
Inline: True
```
```
In drivers/clk/clk-mux.c (ffffffff81a00f22)
Location: arch/x86/include/asm/bitops.h:305
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:__clk_hw_register_mux
  - drivers/clk/clk-mux.c:clk_mux_val_to_index
```
```
In drivers/regulator/helpers.c (ffffffff81a43dc1)
Location: arch/x86/include/asm/bitops.h:305
Inline: True
Inline callers:
  - drivers/regulator/helpers.c:regulator_set_ramp_delay_regmap
  - drivers/regulator/helpers.c:regulator_get_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_set_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
```
```
In drivers/ata/libata-core.c (ffffffff81ba6b38)
Location: arch/x86/include/asm/bitops.h:305
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:sata_down_spd_limit
```
```
In drivers/spi/spi.c (ffffffff81bd08ec)
Location: arch/x86/include/asm/bitops.h:305
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_get_gpio_descs
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81c8412e)
Location: arch/x86/include/asm/bitops.h:305
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/mmc/core/core.c (ffffffff81d4a8a6)
Location: arch/x86/include/asm/bitops.h:305
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_init_erase
  - drivers/mmc/core/core.c:mmc_init_erase
  - drivers/mmc/core/core.c:mmc_select_voltage
```
```
In net/core/gro.c (ffffffff81e096be)
Location: arch/x86/include/asm/bitops.h:305
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_flush
```
```
In net/netlink/af_netlink.c (ffffffff81e6c42e)
Location: arch/x86/include/asm/bitops.h:305
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_connect
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ff255f)
Location: arch/x86/include/asm/bitops.h:305
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108c9c4)
Location: arch/x86/include/asm/bitops.h:305
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff836b452d)
Location: arch/x86/include/asm/bitops.h:305
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:set_block_size
```
```
In kernel/softirq.c (ffffffff8215a2df)
Location: arch/x86/include/asm/bitops.h:305
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In fs/ext4/mballoc.c (ffffffff815c2896)
Location: arch/x86/include/asm/bitops.h:305
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/squashfs/xz_wrapper.c (ffffffff8162c571)
Location: arch/x86/include/asm/bitops.h:305
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_comp_opts
```
```
In fs/fat/inode.c (ffffffff8163af0b)
Location: arch/x86/include/asm/bitops.h:305
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In drivers/pci/pci.c (ffffffff8191fea4)
Location: arch/x86/include/asm/bitops.h:305
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/video/fbdev/core/cfbfillrect.c (0)
Location: arch/x86/include/asm/bitops.h:305
Inline: True
```
```
In drivers/video/fbdev/core/sysfillrect.c (0)
Location: arch/x86/include/asm/bitops.h:305
Inline: True
```
```
In drivers/clk/clk-mux.c (ffffffff81a49c22)
Location: arch/x86/include/asm/bitops.h:305
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:__clk_hw_register_mux
  - drivers/clk/clk-mux.c:clk_mux_val_to_index
```
```
In drivers/regulator/helpers.c (ffffffff81a8df55)
Location: arch/x86/include/asm/bitops.h:305
Inline: True
Inline callers:
  - drivers/regulator/helpers.c:regulator_set_ramp_delay_regmap
  - drivers/regulator/helpers.c:regulator_get_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_set_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
```
```
In drivers/ata/libata-core.c (ffffffff81bfd710)
Location: arch/x86/include/asm/bitops.h:305
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:sata_down_spd_limit
```
```
In drivers/spi/spi.c (ffffffff81c2861b)
Location: arch/x86/include/asm/bitops.h:305
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_get_gpio_descs
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81ceae2e)
Location: arch/x86/include/asm/bitops.h:305
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/mmc/core/core.c (ffffffff81db50ee)
Location: arch/x86/include/asm/bitops.h:305
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_init_erase
  - drivers/mmc/core/core.c:mmc_init_erase
  - drivers/mmc/core/core.c:mmc_select_voltage
```
```
In net/core/gro.c (ffffffff81e7be8e)
Location: arch/x86/include/asm/bitops.h:305
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_flush
```
```
In net/netlink/af_netlink.c (ffffffff81ec848e)
Location: arch/x86/include/asm/bitops.h:305
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_connect
```
```
In net/xdp/xsk_buff_pool.c (ffffffff8206e787)
Location: arch/x86/include/asm/bitops.h:305
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81092d04)
Location: arch/x86/include/asm/bitops.h:307
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff838e4e6d)
Location: arch/x86/include/asm/bitops.h:307
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:set_block_size
```
```
In kernel/softirq.c (ffffffff8223db65)
Location: arch/x86/include/asm/bitops.h:307
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In fs/ext4/mballoc.c (ffffffff815fb50e)
Location: arch/x86/include/asm/bitops.h:307
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/squashfs/xz_wrapper.c (ffffffff816659d0)
Location: arch/x86/include/asm/bitops.h:307
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_comp_opts
```
```
In fs/fat/inode.c (ffffffff8167446a)
Location: arch/x86/include/asm/bitops.h:307
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In drivers/pci/pci.c (ffffffff81968084)
Location: arch/x86/include/asm/bitops.h:307
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/video/fbdev/core/cfbfillrect.c (0)
Location: arch/x86/include/asm/bitops.h:307
Inline: True
```
```
In drivers/video/fbdev/core/sysfillrect.c (0)
Location: arch/x86/include/asm/bitops.h:307
Inline: True
```
```
In drivers/clk/clk-mux.c (ffffffff81a95742)
Location: arch/x86/include/asm/bitops.h:307
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:__clk_hw_register_mux
  - drivers/clk/clk-mux.c:clk_mux_val_to_index
```
```
In drivers/regulator/helpers.c (ffffffff81ae08f5)
Location: arch/x86/include/asm/bitops.h:307
Inline: True
Inline callers:
  - drivers/regulator/helpers.c:regulator_set_ramp_delay_regmap
  - drivers/regulator/helpers.c:regulator_get_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_set_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
```
```
In drivers/ata/libata-core.c (ffffffff81c534c6)
Location: arch/x86/include/asm/bitops.h:307
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:sata_down_spd_limit
```
```
In drivers/gpu/drm/drm_blend.c (ffffffff81c7f573)
Location: arch/x86/include/asm/bitops.h:307
Inline: True
```
```
In drivers/spi/spi.c (ffffffff81cdad6b)
Location: arch/x86/include/asm/bitops.h:307
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_get_gpio_descs
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81da05fc)
Location: arch/x86/include/asm/bitops.h:307
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/mmc/core/core.c (ffffffff81e6d53e)
Location: arch/x86/include/asm/bitops.h:307
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_init_erase
  - drivers/mmc/core/core.c:mmc_init_erase
  - drivers/mmc/core/core.c:mmc_select_voltage
```
```
In net/core/gro.c (ffffffff81f3c1de)
Location: arch/x86/include/asm/bitops.h:307
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_flush
```
```
In net/netlink/af_netlink.c (ffffffff81f8b857)
Location: arch/x86/include/asm/bitops.h:307
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_connect
```
```
In net/xdp/xsk_buff_pool.c (ffffffff8214280d)
Location: arch/x86/include/asm/bitops.h:307
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
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
