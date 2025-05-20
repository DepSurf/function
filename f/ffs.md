# Function: <code>ffs</code>

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
In kernel/softirq.c (ffffffff81085921)
Location: arch/x86/include/asm/bitops.h:396
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In fs/ext4/mballoc.c (ffffffff812ce26c)
Location: arch/x86/include/asm/bitops.h:396
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/fat/inode.c (ffffffff812fd2a2)
Location: arch/x86/include/asm/bitops.h:396
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In drivers/pci/pci.c (ffffffff814345c3)
Location: arch/x86/include/asm/bitops.h:396
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff81473ae6)
Location: arch/x86/include/asm/bitops.h:396
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbfillrect.c:cfb_fillrect
```
```
In drivers/regulator/helpers.c (ffffffff814de470)
Location: arch/x86/include/asm/bitops.h:396
Inline: True
Inline callers:
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_regmap
```
```
In drivers/ata/libata-core.c (ffffffff815ca82a)
Location: arch/x86/include/asm/bitops.h:396
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:sata_down_spd_limit
```
```
In drivers/mmc/core/core.c (ffffffff816c0739)
Location: arch/x86/include/asm/bitops.h:396
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_select_voltage
  - drivers/mmc/core/core.c:mmc_init_erase
  - drivers/mmc/core/core.c:mmc_init_erase
```
```
In drivers/clk/clk-mux.c (ffffffff816ea25e)
Location: arch/x86/include/asm/bitops.h:396
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_mux_get_parent
  - drivers/clk/clk-mux.c:clk_register_mux_table
```
```
In net/netlink/af_netlink.c (ffffffff8174d115)
Location: arch/x86/include/asm/bitops.h:396
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_connect
  - net/netlink/af_netlink.c:netlink_sendmsg
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
In kernel/softirq.c (ffffffff818a1b09)
Location: arch/x86/include/asm/bitops.h:396
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In fs/ext4/mballoc.c (ffffffff812fd85e)
Location: arch/x86/include/asm/bitops.h:396
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/squashfs/xz_wrapper.c (ffffffff81326634)
Location: arch/x86/include/asm/bitops.h:396
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_comp_opts
```
```
In fs/fat/inode.c (ffffffff81330e14)
Location: arch/x86/include/asm/bitops.h:396
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In drivers/pci/pci.c (ffffffff8147ffdf)
Location: arch/x86/include/asm/bitops.h:396
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff814c1fe5)
Location: arch/x86/include/asm/bitops.h:396
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbfillrect.c:cfb_fillrect
```
```
In drivers/regulator/helpers.c (ffffffff8152f6a6)
Location: arch/x86/include/asm/bitops.h:396
Inline: True
Inline callers:
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_regmap
```
```
In drivers/ata/libata-core.c (ffffffff8162306a)
Location: arch/x86/include/asm/bitops.h:396
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:sata_down_spd_limit
```
```
In drivers/mmc/core/core.c (ffffffff81723b19)
Location: arch/x86/include/asm/bitops.h:396
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_init_erase
  - drivers/mmc/core/core.c:mmc_init_erase
  - drivers/mmc/core/core.c:mmc_select_voltage
```
```
In drivers/clk/clk-mux.c (ffffffff8174ea7d)
Location: arch/x86/include/asm/bitops.h:396
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_hw_register_mux_table
  - drivers/clk/clk-mux.c:clk_mux_get_parent
```
```
In net/netlink/af_netlink.c (ffffffff817ba9f3)
Location: arch/x86/include/asm/bitops.h:396
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_connect
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
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81043f9c)
Location: arch/x86/include/asm/bitops.h:409
Inline: True
```
```
In kernel/softirq.c (ffffffff818d7040)
Location: arch/x86/include/asm/bitops.h:409
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In fs/ext4/mballoc.c (ffffffff813138de)
Location: arch/x86/include/asm/bitops.h:409
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/squashfs/xz_wrapper.c (ffffffff8133c3e4)
Location: arch/x86/include/asm/bitops.h:409
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_comp_opts
```
```
In fs/fat/inode.c (ffffffff81346b64)
Location: arch/x86/include/asm/bitops.h:409
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In drivers/pci/pci.c (ffffffff814a162f)
Location: arch/x86/include/asm/bitops.h:409
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff814e3fd5)
Location: arch/x86/include/asm/bitops.h:409
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbfillrect.c:cfb_fillrect
```
```
In drivers/clk/clk-mux.c (ffffffff815372ed)
Location: arch/x86/include/asm/bitops.h:409
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_hw_register_mux_table
  - drivers/clk/clk-mux.c:clk_mux_get_parent
```
```
In drivers/regulator/helpers.c (ffffffff8155bd06)
Location: arch/x86/include/asm/bitops.h:409
Inline: True
Inline callers:
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_regmap
```
```
In drivers/ata/libata-core.c (ffffffff81653bea)
Location: arch/x86/include/asm/bitops.h:409
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:sata_down_spd_limit
```
```
In drivers/mmc/core/core.c (ffffffff817569d9)
Location: arch/x86/include/asm/bitops.h:409
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_init_erase
  - drivers/mmc/core/core.c:mmc_init_erase
  - drivers/mmc/core/core.c:mmc_select_voltage
```
```
In net/netlink/af_netlink.c (ffffffff817ea393)
Location: arch/x86/include/asm/bitops.h:409
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_connect
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
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81043e2a)
Location: arch/x86/include/asm/bitops.h:409
Inline: True
```
```
In kernel/softirq.c (ffffffff8190ed60)
Location: arch/x86/include/asm/bitops.h:409
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In fs/ext4/mballoc.c (ffffffff8130b1be)
Location: arch/x86/include/asm/bitops.h:409
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/squashfs/xz_wrapper.c (ffffffff81350eb4)
Location: arch/x86/include/asm/bitops.h:409
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_comp_opts
```
```
In fs/fat/inode.c (ffffffff8135b5fe)
Location: arch/x86/include/asm/bitops.h:409
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In drivers/pci/pci.c (ffffffff814ab1af)
Location: arch/x86/include/asm/bitops.h:409
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff814efd9f)
Location: arch/x86/include/asm/bitops.h:409
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbfillrect.c:cfb_fillrect
```
```
In drivers/clk/clk-mux.c (ffffffff8154a61d)
Location: arch/x86/include/asm/bitops.h:409
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_hw_register_mux_table
  - drivers/clk/clk-mux.c:clk_mux_get_parent
```
```
In drivers/regulator/helpers.c (ffffffff81570610)
Location: arch/x86/include/asm/bitops.h:409
Inline: True
Inline callers:
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_regmap
```
```
In drivers/ata/libata-core.c (ffffffff81668319)
Location: arch/x86/include/asm/bitops.h:409
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:sata_down_spd_limit
```
```
In drivers/mmc/core/core.c (ffffffff81774929)
Location: arch/x86/include/asm/bitops.h:409
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_init_erase
  - drivers/mmc/core/core.c:mmc_init_erase
  - drivers/mmc/core/core.c:mmc_select_voltage
```
```
In net/netlink/af_netlink.c (ffffffff8180a05b)
Location: arch/x86/include/asm/bitops.h:409
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_connect
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
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff810475d6)
Location: arch/x86/include/asm/bitops.h:410
Inline: True
```
```
In kernel/softirq.c (ffffffff81c0006c)
Location: arch/x86/include/asm/bitops.h:410
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In fs/ext4/mballoc.c (ffffffff8132fc4e)
Location: arch/x86/include/asm/bitops.h:410
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/squashfs/xz_wrapper.c (ffffffff81375684)
Location: arch/x86/include/asm/bitops.h:410
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_comp_opts
```
```
In fs/fat/inode.c (ffffffff81380301)
Location: arch/x86/include/asm/bitops.h:410
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In drivers/pci/pci.c (ffffffff814ea3d0)
Location: arch/x86/include/asm/bitops.h:410
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff81530420)
Location: arch/x86/include/asm/bitops.h:410
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbfillrect.c:cfb_fillrect
```
```
In drivers/clk/clk-mux.c (ffffffff815adba5)
Location: arch/x86/include/asm/bitops.h:410
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_hw_register_mux_table
  - drivers/clk/clk-mux.c:clk_mux_get_parent
```
```
In drivers/regulator/helpers.c (ffffffff815d48a0)
Location: arch/x86/include/asm/bitops.h:410
Inline: True
Inline callers:
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_regmap
```
```
In drivers/ata/libata-core.c (ffffffff816d1988)
Location: arch/x86/include/asm/bitops.h:410
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:sata_down_spd_limit
```
```
In drivers/mmc/core/core.c (ffffffff817eab79)
Location: arch/x86/include/asm/bitops.h:410
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_init_erase
  - drivers/mmc/core/core.c:mmc_init_erase
  - drivers/mmc/core/core.c:mmc_select_voltage
```
```
In net/netlink/af_netlink.c (ffffffff81888fdb)
Location: arch/x86/include/asm/bitops.h:410
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_connect
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
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81049b4e)
Location: arch/x86/include/asm/bitops.h:413
Inline: True
```
```
In kernel/softirq.c (ffffffff81c00071)
Location: arch/x86/include/asm/bitops.h:413
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In fs/ext4/mballoc.c (ffffffff8135dfc1)
Location: arch/x86/include/asm/bitops.h:413
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/squashfs/xz_wrapper.c (ffffffff813a40a2)
Location: arch/x86/include/asm/bitops.h:413
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_comp_opts
```
```
In fs/fat/inode.c (ffffffff813aea51)
Location: arch/x86/include/asm/bitops.h:413
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In drivers/pci/pci.c (ffffffff81519c67)
Location: arch/x86/include/asm/bitops.h:413
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff81565e88)
Location: arch/x86/include/asm/bitops.h:413
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbfillrect.c:cfb_fillrect
```
```
In drivers/clk/clk-mux.c (ffffffff815e5df9)
Location: arch/x86/include/asm/bitops.h:413
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_hw_register_mux_table
  - drivers/clk/clk-mux.c:clk_mux_val_to_index
```
```
In drivers/regulator/helpers.c (ffffffff8160d6ab)
Location: arch/x86/include/asm/bitops.h:413
Inline: True
Inline callers:
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_regmap
```
```
In drivers/ata/libata-core.c (ffffffff817130e9)
Location: arch/x86/include/asm/bitops.h:413
Inline: True
```
```
In drivers/mmc/core/core.c (ffffffff81833a76)
Location: arch/x86/include/asm/bitops.h:413
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_init_erase
  - drivers/mmc/core/core.c:mmc_init_erase
  - drivers/mmc/core/core.c:mmc_select_voltage
```
```
In net/netlink/af_netlink.c (ffffffff818dcb3c)
Location: arch/x86/include/asm/bitops.h:413
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_connect
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81059c03)
Location: arch/x86/include/asm/bitops.h:410
Inline: True
```
```
In kernel/softirq.c (ffffffff81e00071)
Location: arch/x86/include/asm/bitops.h:410
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In fs/ext4/mballoc.c (ffffffff81375f31)
Location: arch/x86/include/asm/bitops.h:410
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/squashfs/xz_wrapper.c (ffffffff813bcea2)
Location: arch/x86/include/asm/bitops.h:410
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_comp_opts
```
```
In fs/fat/inode.c (ffffffff813c7c4f)
Location: arch/x86/include/asm/bitops.h:410
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In drivers/pci/pci.c (ffffffff8152f727)
Location: arch/x86/include/asm/bitops.h:410
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff8157d8af)
Location: arch/x86/include/asm/bitops.h:410
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbfillrect.c:cfb_fillrect
```
```
In drivers/clk/clk-mux.c (ffffffff81600189)
Location: arch/x86/include/asm/bitops.h:410
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_hw_register_mux_table
  - drivers/clk/clk-mux.c:clk_mux_val_to_index
```
```
In drivers/regulator/helpers.c (ffffffff81629e5b)
Location: arch/x86/include/asm/bitops.h:410
Inline: True
Inline callers:
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
```
```
In drivers/ata/libata-core.c (ffffffff81735599)
Location: arch/x86/include/asm/bitops.h:410
Inline: True
```
```
In drivers/mmc/core/core.c (ffffffff8185fa06)
Location: arch/x86/include/asm/bitops.h:410
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_init_erase
  - drivers/mmc/core/core.c:mmc_init_erase
  - drivers/mmc/core/core.c:mmc_select_voltage
```
```
In net/core/dev.c (ffffffff818b6f87)
Location: arch/x86/include/asm/bitops.h:410
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_flush
```
```
In net/netlink/af_netlink.c (ffffffff8190951b)
Location: arch/x86/include/asm/bitops.h:410
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_connect
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105d177)
Location: arch/x86/include/asm/bitops.h:284
Inline: True
```
```
In kernel/softirq.c (ffffffff81e00076)
Location: arch/x86/include/asm/bitops.h:284
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In fs/ext4/mballoc.c (ffffffff8139f414)
Location: arch/x86/include/asm/bitops.h:284
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/squashfs/xz_wrapper.c (ffffffff813e7752)
Location: arch/x86/include/asm/bitops.h:284
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_comp_opts
```
```
In fs/fat/inode.c (ffffffff813f2805)
Location: arch/x86/include/asm/bitops.h:284
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In drivers/pci/pci.c (ffffffff8155ee86)
Location: arch/x86/include/asm/bitops.h:284
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff815ade61)
Location: arch/x86/include/asm/bitops.h:284
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbfillrect.c:cfb_fillrect
```
```
In drivers/clk/clk-mux.c (ffffffff81632a46)
Location: arch/x86/include/asm/bitops.h:284
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_hw_register_mux_table
  - drivers/clk/clk-mux.c:clk_mux_val_to_index
```
```
In drivers/regulator/helpers.c (ffffffff8165d9eb)
Location: arch/x86/include/asm/bitops.h:284
Inline: True
Inline callers:
  - drivers/regulator/helpers.c:regulator_get_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_set_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
```
```
In drivers/ata/libata-core.c (ffffffff81770fe8)
Location: arch/x86/include/asm/bitops.h:284
Inline: True
```
```
In drivers/mmc/core/core.c (ffffffff818a3586)
Location: arch/x86/include/asm/bitops.h:284
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_init_erase
  - drivers/mmc/core/core.c:mmc_init_erase
  - drivers/mmc/core/core.c:mmc_select_voltage
```
```
In drivers/soundwire/bus.c (ffffffff818c1855)
Location: arch/x86/include/asm/bitops.h:284
Inline: True
Inline callers:
  - drivers/soundwire/bus.c:sdw_handle_slave_alerts
  - drivers/soundwire/bus.c:sdw_fill_msg
  - drivers/soundwire/bus.c:sdw_fill_msg
```
```
In drivers/soundwire/stream.c (ffffffff818c412b)
Location: arch/x86/include/asm/bitops.h:284
Inline: True
Inline callers:
  - drivers/soundwire/stream.c:sdw_program_params
  - drivers/soundwire/stream.c:sdw_program_params
  - drivers/soundwire/stream.c:sdw_program_params
```
```
In net/core/dev.c (ffffffff81902d83)
Location: arch/x86/include/asm/bitops.h:284
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_flush
```
```
In net/netlink/af_netlink.c (ffffffff8196a82b)
Location: arch/x86/include/asm/bitops.h:284
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_connect
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105da79)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828bce62)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In kernel/softirq.c (ffffffff81e00076)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In fs/ext4/mballoc.c (ffffffff813b827f)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/squashfs/xz_wrapper.c (ffffffff814017d2)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_comp_opts
```
```
In fs/fat/inode.c (ffffffff8140c6fb)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In drivers/pci/pci.c (ffffffff8157ffbb)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff815cede1)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbfillrect.c:cfb_fillrect
```
```
In drivers/clk/clk-mux.c (ffffffff81654776)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_hw_register_mux_table
  - drivers/clk/clk-mux.c:clk_mux_val_to_index
```
```
In drivers/regulator/helpers.c (ffffffff8168015b)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/regulator/helpers.c:regulator_get_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_set_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
```
```
In drivers/ata/libata-core.c (ffffffff81794fe6)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
```
```
In drivers/mmc/core/core.c (ffffffff818d5ad6)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_init_erase
  - drivers/mmc/core/core.c:mmc_init_erase
  - drivers/mmc/core/core.c:mmc_select_voltage
```
```
In net/core/dev.c (ffffffff81935b03)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_flush
```
```
In net/netlink/af_netlink.c (ffffffff819a12b3)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_connect
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810632b7)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82ce1600)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In kernel/softirq.c (ffffffff81e00070)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In fs/ext4/mballoc.c (ffffffff81403e57)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/squashfs/xz_wrapper.c (ffffffff8144f372)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_comp_opts
```
```
In fs/fat/inode.c (ffffffff8145a631)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In drivers/pci/pci.c (ffffffff8162547b)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff816787ca)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbfillrect.c:cfb_fillrect
```
```
In drivers/clk/clk-mux.c (ffffffff81704561)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:__clk_hw_register_mux
  - drivers/clk/clk-mux.c:clk_mux_val_to_index
```
```
In drivers/regulator/helpers.c (ffffffff817311b9)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/regulator/helpers.c:regulator_get_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_set_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
```
```
In drivers/ata/libata-core.c (ffffffff8185943f)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:sata_down_spd_limit
```
```
In drivers/mmc/core/core.c (ffffffff819a84b6)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_init_erase
  - drivers/mmc/core/core.c:mmc_init_erase
  - drivers/mmc/core/core.c:mmc_select_voltage
```
```
In net/core/dev.c (ffffffff81a0a7fd)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_flush
```
```
In net/netlink/af_netlink.c (ffffffff81a7abec)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_connect
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81061737)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82fce3a7)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In kernel/softirq.c (ffffffff82000072)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In fs/ext4/mballoc.c (ffffffff814170b3)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/squashfs/xz_wrapper.c (ffffffff8146b912)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_comp_opts
```
```
In fs/fat/inode.c (ffffffff81476981)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In drivers/pci/pci.c (ffffffff8164b5ab)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff8169889a)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbfillrect.c:cfb_fillrect
```
```
In drivers/clk/clk-mux.c (ffffffff817217a1)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:__clk_hw_register_mux
  - drivers/clk/clk-mux.c:clk_mux_val_to_index
```
```
In drivers/regulator/helpers.c (ffffffff8174d299)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/regulator/helpers.c:regulator_get_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_set_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
```
```
In drivers/ata/libata-core.c (ffffffff81c17452)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:sata_down_spd_limit
```
```
In drivers/mmc/core/core.c (ffffffff819ab566)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_init_erase
  - drivers/mmc/core/core.c:mmc_init_erase
  - drivers/mmc/core/core.c:mmc_select_voltage
```
```
In net/core/dev.c (ffffffff81a0ba0d)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_flush
```
```
In net/netlink/af_netlink.c (ffffffff81a83a42)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_connect
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81061e5a)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff831d6e44)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:set_block_size
```
```
In kernel/softirq.c (ffffffff82000072)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In fs/ext4/mballoc.c (ffffffff8141dcc0)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/squashfs/xz_wrapper.c (ffffffff81470fb2)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_comp_opts
```
```
In fs/fat/inode.c (ffffffff8147c3f1)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In drivers/pci/pci.c (ffffffff8162e18b)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff8167b6ba)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbfillrect.c:cfb_fillrect
```
```
In drivers/clk/clk-mux.c (ffffffff81702ad1)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:__clk_hw_register_mux
  - drivers/clk/clk-mux.c:clk_mux_val_to_index
```
```
In drivers/regulator/helpers.c (ffffffff81731289)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/regulator/helpers.c:regulator_set_ramp_delay_regmap
  - drivers/regulator/helpers.c:regulator_get_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_set_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
```
```
In drivers/ata/libata-core.c (ffffffff81c0907f)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:sata_down_spd_limit
```
```
In drivers/spi/spi.c (ffffffff818692c3)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_get_gpio_descs
```
```
In drivers/mmc/core/core.c (ffffffff8198fa49)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_init_erase
  - drivers/mmc/core/core.c:mmc_init_erase
  - drivers/mmc/core/core.c:mmc_select_voltage
```
```
In net/core/dev.c (ffffffff819f1f5d)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_flush
```
```
In net/netlink/af_netlink.c (ffffffff81a6cb36)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_connect
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8106bbe8)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff832b9b5e)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:set_block_size
```
```
In kernel/softirq.c (ffffffff8200006f)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In fs/ext4/mballoc.c (ffffffff81471245)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/squashfs/xz_wrapper.c (ffffffff814c7a1d)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_comp_opts
```
```
In fs/fat/inode.c (ffffffff814d3af1)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In drivers/pci/pci.c (ffffffff8169cceb)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff816f028a)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbfillrect.c:cfb_fillrect
```
```
In drivers/clk/clk-mux.c (ffffffff8177d761)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:__clk_hw_register_mux
  - drivers/clk/clk-mux.c:clk_mux_val_to_index
```
```
In drivers/regulator/helpers.c (ffffffff817b128a)
Location: arch/x86/include/asm/bitops.h:283
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
In drivers/ata/libata-core.c (ffffffff818d42ae)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:sata_down_spd_limit
```
```
In drivers/spi/spi.c (ffffffff818f8bd3)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_get_gpio_descs
```
```
In drivers/mmc/core/core.c (ffffffff81a3b1c1)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_init_erase
  - drivers/mmc/core/core.c:mmc_init_erase
  - drivers/mmc/core/core.c:mmc_select_voltage
```
```
In net/core/dev.c (ffffffff81aa3866)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_flush
```
```
In net/netlink/af_netlink.c (ffffffff81b261a9)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_connect
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81078f14)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8346b7cf)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:set_block_size
```
```
In kernel/softirq.c (ffffffff82200072)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In fs/ext4/mballoc.c (ffffffff814f293c)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/squashfs/xz_wrapper.c (ffffffff81552e51)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_comp_opts
```
```
In fs/fat/inode.c (ffffffff81560d29)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In drivers/pci/pci.c (ffffffff817bec54)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff8181c3c7)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbfillrect.c:cfb_fillrect
```
```
In drivers/clk/clk-mux.c (ffffffff818b43a1)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:__clk_hw_register_mux
  - drivers/clk/clk-mux.c:clk_mux_val_to_index
```
```
In drivers/regulator/helpers.c (ffffffff818ec9cc)
Location: arch/x86/include/asm/bitops.h:283
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
In drivers/ata/libata-core.c (ffffffff81a24a68)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:sata_down_spd_limit
```
```
In drivers/spi/spi.c (ffffffff81a4a106)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_get_gpio_descs
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81af6790)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/mmc/core/core.c (ffffffff81ba80a6)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_init_erase
  - drivers/mmc/core/core.c:mmc_init_erase
  - drivers/mmc/core/core.c:mmc_select_voltage
```
```
In net/core/gro.c (ffffffff81c53faa)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_flush
```
```
In net/netlink/af_netlink.c (ffffffff81caedde)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_connect
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81e1afff)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
```
</details>
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
In arch/arm64/kernel/setup.c (ffff800011434510)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - arch/arm64/kernel/setup.c:setup_arch
```
```
In arch/arm64/kernel/insn.c (ffff80001009641c)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - arch/arm64/kernel/insn.c:aarch64_encode_immediate
```
```
In virt/kvm/arm/vgic/vgic-v2.c (ffff8000100deb4c)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-v2.c:vgic_v2_populate_lr
```
```
In virt/kvm/arm/vgic/vgic-v3.c (ffff8000100df790)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_populate_lr
```
```
In kernel/softirq.c (ffff800010081c40)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In fs/ext4/mballoc.c (ffff80001048ee40)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/squashfs/xz_wrapper.c (ffff8000104df724)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_comp_opts
```
```
In fs/fat/inode.c (ffff8000104ed4d0)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In drivers/irqchip/irq-bcm2835.c (ffff80001066ab58)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - drivers/irqchip/irq-bcm2835.c:get_next_armctrl_hwirq
  - drivers/irqchip/irq-bcm2835.c:get_next_armctrl_hwirq
  - drivers/irqchip/irq-bcm2835.c:get_next_armctrl_hwirq
  - drivers/irqchip/irq-bcm2835.c:get_next_armctrl_hwirq
  - drivers/irqchip/irq-bcm2835.c:get_next_armctrl_hwirq
```
```
In drivers/irqchip/irq-bcm2836.c (ffff80001008173c)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - drivers/irqchip/irq-bcm2836.c:bcm2836_arm_irqchip_handle_irq
  - drivers/irqchip/irq-bcm2836.c:bcm2836_arm_irqchip_handle_irq
```
```
In drivers/irqchip/irq-dw-apb-ictl.c (ffff80001066b198)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_handler
```
```
In drivers/irqchip/irq-brcmstb-l2.c (ffff8000106776d8)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - drivers/irqchip/irq-brcmstb-l2.c:brcmstb_l2_intc_irq_handle
```
```
In drivers/bus/brcmstb_gisb.c (ffff800011476a04)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_decode_addr
```
```
In drivers/pinctrl/pinctrl-single.c (ffff80001069d7b0)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_parse_one_pinctrl_entry
  - drivers/pinctrl/pinctrl-single.c:pcs_pinconf_set
```
```
In drivers/pinctrl/mvebu/pinctrl-armada-37xx.c (ffff8000106ac1a8)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_handler
```
```
In drivers/gpio/gpio-mpc8xxx.c (ffff8000106cf134)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_gpio_irq_cascade
```
```
In drivers/pci/pci.c (ffff8000106e3448)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/pci/controller/pci-xgene-msi.c (ffff800010725bac)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - drivers/pci/controller/pci-xgene-msi.c:xgene_msi_isr
  - drivers/pci/controller/pci-xgene-msi.c:xgene_msi_isr
```
```
In drivers/video/fbdev/core/cfbfillrect.c (0)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
```
```
In drivers/clk/clk-mux.c (ffff8000107c5e7c)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_hw_register_mux_table
  - drivers/clk/clk-mux.c:clk_mux_val_to_index
```
```
In drivers/clk/mediatek/clk-pll.c (ffff8000107e24c8)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - drivers/clk/mediatek/clk-pll.c:mtk_pll_set_rate
```
```
In drivers/dma/mv_xor.c (0)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
```
```
In drivers/dma/ipu/ipu_irq.c (ffff80001080a39c)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_handler
```
```
In drivers/regulator/helpers.c (ffff800010849d5c)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - drivers/regulator/helpers.c:regulator_get_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_set_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
```
```
In drivers/ata/libata-core.c (ffff800010999a04)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
```
```
In drivers/mmc/core/core.c (ffff800010b2f664)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_init_erase
  - drivers/mmc/core/core.c:mmc_init_erase
  - drivers/mmc/core/core.c:mmc_select_voltage
```
```
In drivers/mmc/host/mmci.c (ffff800010b44c80)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:mmci_get_dctrl_cfg
```
```
In drivers/mmc/host/mmci_stm32_sdmmc.c (0)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_get_dctrl_cfg
```
```
In drivers/clocksource/sh_cmt.c (ffff800010b643c8)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_setup
```
```
In drivers/memory/brcmstb_dpfe.c (ffff800010b8a6a4)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - drivers/memory/brcmstb_dpfe.c:__send_command
```
```
In net/core/dev.c (ffff800010bd45cc)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_complete_done
```
```
In net/netlink/af_netlink.c (ffff800010c4f948)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_connect
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
In arch/arm/kernel/setup.c (c1504d54)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - arch/arm/kernel/setup.c:setup_arch
```
```
In kernel/softirq.c (c0302940)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In fs/ext4/mballoc.c (c06504c0)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/squashfs/xz_wrapper.c (c06a132c)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_comp_opts
```
```
In fs/fat/inode.c (c06ab11c)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In drivers/irqchip/irq-dw-apb-ictl.c (c081451c)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_handler
```
```
In drivers/irqchip/irq-aspeed-vic.c (c0302864)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - drivers/irqchip/irq-aspeed-vic.c:avic_handle_irq
```
```
In drivers/bus/brcmstb_gisb.c (c154eb50)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_decode_addr
```
```
In drivers/pinctrl/pinctrl-single.c (c083fd28)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_pinconf_set
```
```
In drivers/gpio/gpio-mpc8xxx.c (c0869818)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_gpio_irq_cascade
```
```
In drivers/pci/pci.c (c087f2ac)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/pci/controller/pci-rcar-gen2.c (c08add70)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_parse_map_dma_ranges
```
```
In drivers/video/fbdev/core/cfbfillrect.c (0)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
```
```
In drivers/video/fbdev/omap2/omapfb/vrfb.c (c08e0b58)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - drivers/video/fbdev/omap2/omapfb/vrfb.c:omap_vrfb_restore_context
  - drivers/video/fbdev/omap2/omapfb/vrfb.c:omap_vrfb_restore_context
```
```
In drivers/clk/clk-mux.c (c08f12ac)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_hw_register_mux_table
  - drivers/clk/clk-mux.c:clk_mux_val_to_index
```
```
In drivers/clk/mediatek/clk-pll.c (c08ff75c)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - drivers/clk/mediatek/clk-pll.c:mtk_pll_set_rate
```
```
In drivers/clk/ti/mux.c (c0917098)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - drivers/clk/ti/mux.c:ti_clk_mux_set_parent
  - drivers/clk/ti/mux.c:ti_clk_mux_get_parent
```
```
In drivers/dma/mv_xor.c (c09241f8)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_add_io_win
```
```
In drivers/dma/ipu/ipu_irq.c (c0927034)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_handler
```
```
In drivers/dma/ti/omap-dma.c (c0932494)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - drivers/dma/ti/omap-dma.c:omap_dma_irq
```
```
In drivers/regulator/helpers.c (c0953424)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - drivers/regulator/helpers.c:regulator_get_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_set_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
```
```
In drivers/ata/libata-core.c (c0a699dc)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
```
```
In drivers/mtd/mtdcore.c (c0a90b0c)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - drivers/mtd/mtdcore.c:add_mtd_device
  - drivers/mtd/mtdcore.c:add_mtd_device
```
```
In drivers/mtd/mtd_blkdevs.c (c0a98418)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - drivers/mtd/mtd_blkdevs.c:register_mtd_blktrans
```
```
In drivers/mtd/nand/raw/nand_base.c (c0aa1370)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/nand_base.c:nand_detect
  - drivers/mtd/nand/raw/nand_base.c:nand_detect
  - drivers/mtd/nand/raw/nand_base.c:nand_detect
  - drivers/mtd/nand/raw/nand_base.c:nand_detect
```
```
In drivers/usb/musb/musb_core.c (c0b64640)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - drivers/usb/musb/musb_core.c:fifo_setup
```
```
In drivers/mmc/core/core.c (c0c0a9a4)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_init_erase
  - drivers/mmc/core/core.c:mmc_init_erase
  - drivers/mmc/core/core.c:mmc_select_voltage
```
```
In drivers/mmc/host/mmci.c (c0c1e830)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:mmci_get_dctrl_cfg
```
```
In drivers/mmc/host/mmci_stm32_sdmmc.c (c0c2189c)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_get_dctrl_cfg
```
```
In drivers/clocksource/sh_cmt.c (c0c44f44)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_setup
```
```
In sound/soc/soc-dapm.c (c0ca8cd4)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - sound/soc/soc-dapm.c:snd_soc_dai_link_event
```
```
In net/core/dev.c (c0cefe6c)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_complete_done
```
```
In net/netlink/af_netlink.c (c0d5fb14)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_connect
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
In arch/powerpc/kernel/eeh.c (c000000000044de4)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - arch/powerpc/kernel/eeh.c:eeh_restore_vf_config
```
```
In arch/powerpc/sysdev/xive/common.c (c0000000000bd048)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xive/common.c:xive_scan_interrupts
```
```
In arch/powerpc/kvm/book3s_hv_rm_xive.c (c000000000124d90)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_rm_xive.c:xive_rm_h_eoi
  - arch/powerpc/kvm/book3s_hv_rm_xive.c:xive_rm_h_cppr
  - arch/powerpc/kvm/book3s_hv_rm_xive.c:xive_rm_scan_interrupts
```
```
In kernel/softirq.c (c000000000eeae1c)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In fs/ext4/mballoc.c (c0000000005b6480)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/squashfs/xz_wrapper.c (c00000000061bdf8)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_comp_opts
```
```
In fs/fat/inode.c (c00000000062c1e8)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In drivers/pinctrl/pinctrl-single.c (c000000000834b7c)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_pinconf_set
```
```
In drivers/pci/pci.c (c00000000085d358)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/video/fbdev/core/cfbfillrect.c (0)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
```
```
In drivers/regulator/helpers.c (c0000000008e726c)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - drivers/regulator/helpers.c:regulator_get_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_set_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
```
```
In drivers/ata/libata-core.c (c000000000a5cb38)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
```
```
In drivers/mmc/core/core.c (c000000000c291b4)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_init_erase
  - drivers/mmc/core/core.c:mmc_init_erase
  - drivers/mmc/core/core.c:mmc_select_voltage
```
```
In net/core/dev.c (c000000000cb3680)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_complete_done
```
```
In net/netlink/af_netlink.c (c000000000d4e330)
Location: include/asm-generic/bitops/builtin-ffs.h:13
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_connect
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
In kernel/softirq.c (ffffffe0008cb314)
Location: include/asm-generic/bitops/ffs.h:13
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In fs/ext4/mballoc.c (ffffffe000313890)
Location: include/asm-generic/bitops/ffs.h:13
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/squashfs/xz_wrapper.c (ffffffe000353e5a)
Location: include/asm-generic/bitops/ffs.h:13
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_comp_opts
```
```
In fs/fat/inode.c (ffffffe00035d96e)
Location: include/asm-generic/bitops/ffs.h:13
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In drivers/pinctrl/pinctrl-single.c (ffffffe0004a1b6a)
Location: include/asm-generic/bitops/ffs.h:13
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_pinconf_set
  - drivers/pinctrl/pinctrl-single.c:pcs_pinconf_set
```
```
In drivers/pci/pci.c (ffffffe0004bc698)
Location: include/asm-generic/bitops/ffs.h:13
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcix_set_mmrbc
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/video/fbdev/core/cfbfillrect.c (0)
Location: include/asm-generic/bitops/ffs.h:13
Inline: True
```
```
In drivers/clk/clk-mux.c (ffffffe000513400)
Location: include/asm-generic/bitops/ffs.h:13
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_hw_register_mux_table
  - drivers/clk/clk-mux.c:clk_hw_register_mux_table
  - drivers/clk/clk-mux.c:clk_mux_val_to_index
  - drivers/clk/clk-mux.c:clk_mux_val_to_index
```
```
In drivers/regulator/helpers.c (ffffffe00052a114)
Location: include/asm-generic/bitops/ffs.h:13
Inline: True
Inline callers:
  - drivers/regulator/helpers.c:regulator_get_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_get_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_set_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_set_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
```
```
In drivers/ata/libata-core.c (ffffffe0005fa39c)
Location: include/asm-generic/bitops/ffs.h:13
Inline: True
```
```
In drivers/mmc/core/core.c (ffffffe00070883c)
Location: include/asm-generic/bitops/ffs.h:13
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_init_erase
  - drivers/mmc/core/core.c:mmc_init_erase
  - drivers/mmc/core/core.c:mmc_init_erase
  - drivers/mmc/core/core.c:mmc_init_erase
  - drivers/mmc/core/core.c:mmc_select_voltage
  - drivers/mmc/core/core.c:mmc_select_voltage
```
```
In net/core/dev.c (ffffffe00075df7e)
Location: include/asm-generic/bitops/ffs.h:13
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_flush
```
```
In net/netlink/af_netlink.c (ffffffe0007bb54c)
Location: include/asm-generic/bitops/ffs.h:13
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_connect
  - net/netlink/af_netlink.c:netlink_connect
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105d5f9)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
```
```
In kernel/softirq.c (ffffffff81e00076)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In fs/ext4/mballoc.c (ffffffff813b085f)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/squashfs/xz_wrapper.c (ffffffff813f9db2)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_comp_opts
```
```
In fs/fat/inode.c (ffffffff81404cdb)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In drivers/pci/pci.c (ffffffff815744db)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff815c2df1)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbfillrect.c:cfb_fillrect
```
```
In drivers/clk/clk-mux.c (ffffffff8161a7d6)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_hw_register_mux_table
  - drivers/clk/clk-mux.c:clk_mux_val_to_index
```
```
In drivers/regulator/helpers.c (ffffffff81645bdb)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/regulator/helpers.c:regulator_get_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_set_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
```
```
In drivers/ata/libata-core.c (ffffffff8175a0f6)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
```
```
In drivers/mmc/core/core.c (ffffffff81879496)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_init_erase
  - drivers/mmc/core/core.c:mmc_init_erase
  - drivers/mmc/core/core.c:mmc_select_voltage
```
```
In net/core/dev.c (ffffffff818d5ad3)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_flush
```
```
In net/netlink/af_netlink.c (ffffffff81941123)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_connect
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104d7c9)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
```
```
In kernel/softirq.c (ffffffff81e00070)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In fs/ext4/mballoc.c (ffffffff813a12ef)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/squashfs/xz_wrapper.c (ffffffff813ea832)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_comp_opts
```
```
In fs/fat/inode.c (ffffffff813f575b)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In drivers/pci/pci.c (ffffffff81562c3b)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/clk/clk-mux.c (ffffffff8160ed06)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_hw_register_mux_table
  - drivers/clk/clk-mux.c:clk_mux_val_to_index
```
```
In drivers/regulator/helpers.c (ffffffff8162603b)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/regulator/helpers.c:regulator_get_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_set_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
```
```
In drivers/ata/libata-core.c (ffffffff81739f96)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
```
```
In net/core/dev.c (ffffffff8188f943)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_flush
```
```
In net/netlink/af_netlink.c (ffffffff818fac13)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_connect
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105da29)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
```
```
In kernel/softirq.c (ffffffff81e00076)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In fs/ext4/mballoc.c (ffffffff813ae0bf)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/squashfs/xz_wrapper.c (ffffffff813f7132)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_comp_opts
```
```
In fs/fat/inode.c (ffffffff8140205b)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In drivers/pci/pci.c (ffffffff81573d0b)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff815c3381)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbfillrect.c:cfb_fillrect
```
```
In drivers/clk/clk-mux.c (ffffffff816485b6)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_hw_register_mux_table
  - drivers/clk/clk-mux.c:clk_mux_val_to_index
```
```
In drivers/regulator/helpers.c (ffffffff81673f9b)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/regulator/helpers.c:regulator_get_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_set_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
```
```
In drivers/ata/libata-core.c (ffffffff81789e66)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
```
```
In drivers/mmc/core/core.c (ffffffff818ca936)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_init_erase
  - drivers/mmc/core/core.c:mmc_init_erase
  - drivers/mmc/core/core.c:mmc_select_voltage
```
```
In net/core/dev.c (ffffffff81926b03)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_flush
```
```
In net/netlink/af_netlink.c (ffffffff819922b3)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_connect
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ef49)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828bde8f)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In kernel/softirq.c (ffffffff81e00076)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In fs/ext4/mballoc.c (ffffffff813c3409)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/squashfs/xz_wrapper.c (ffffffff8140cdc2)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_comp_opts
```
```
In fs/fat/inode.c (ffffffff8141802b)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In drivers/pci/pci.c (ffffffff8158e1eb)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff815dcf21)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbfillrect.c:cfb_fillrect
```
```
In drivers/clk/clk-mux.c (ffffffff81662b46)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_hw_register_mux_table
  - drivers/clk/clk-mux.c:clk_mux_val_to_index
```
```
In drivers/regulator/helpers.c (ffffffff8168e5fb)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/regulator/helpers.c:regulator_get_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_set_current_limit_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_regmap
  - drivers/regulator/helpers.c:regulator_set_voltage_sel_pickable_regmap
  - drivers/regulator/helpers.c:regulator_get_voltage_sel_pickable_regmap
```
```
In drivers/ata/libata-core.c (ffffffff817a3cb6)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
```
```
In drivers/mmc/core/core.c (ffffffff818e7456)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_init_erase
  - drivers/mmc/core/core.c:mmc_init_erase
  - drivers/mmc/core/core.c:mmc_select_voltage
```
```
In net/core/dev.c (ffffffff81948153)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_flush
```
```
In net/netlink/af_netlink.c (ffffffff819b4da3)
Location: arch/x86/include/asm/bitops.h:283
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_connect
```
</details>
</li>
</ul>

## Differences
