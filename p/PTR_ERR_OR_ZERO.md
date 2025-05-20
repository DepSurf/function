# Function: <code>PTR_ERR_OR_ZERO</code>

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
In arch/x86/kernel/sysfb.c (ffffffff81f74e23)
Location: include/linux/err.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/sysfb.c:sysfb_init
```
```
In mm/mmap.c (ffffffff811c81f5)
Location: include/linux/err.h:56
Inline: True
Inline callers:
  - mm/mmap.c:install_special_mapping
```
```
In block/ioctl.c (ffffffff813c8dd5)
Location: include/linux/err.h:56
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81fae02b)
Location: include/linux/err.h:56
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_init
```
```
In drivers/usb/phy/phy-generic.c (ffffffff81621328)
Location: include/linux/err.h:56
Inline: True
Inline callers:
  - drivers/usb/phy/phy-generic.c:usb_phy_gen_create_phy
  - drivers/usb/phy/phy-generic.c:usb_phy_gen_create_phy
```
```
In drivers/power/power_supply_core.c (ffffffff8167f60c)
Location: include/linux/err.h:56
Inline: True
Inline callers:
  - drivers/power/power_supply_core.c:__power_supply_register
  - drivers/power/power_supply_core.c:__power_supply_register
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
In arch/x86/kernel/sysfb.c (ffffffff81f9d5af)
Location: include/linux/err.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/sysfb.c:sysfb_init
```
```
In mm/mmap.c (ffffffff811e4335)
Location: include/linux/err.h:56
Inline: True
Inline callers:
  - mm/mmap.c:install_special_mapping
```
```
In block/ioctl.c (ffffffff8140d08c)
Location: include/linux/err.h:56
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
```
```
In drivers/nvdimm/bus.c (ffffffff815ed4ec)
Location: include/linux/err.h:56
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
```
```
In drivers/nvdimm/claim.c (ffffffff815f6add)
Location: include/linux/err.h:56
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
```
In drivers/power/power_supply_core.c (ffffffff816e0480)
Location: include/linux/err.h:56
Inline: True
Inline callers:
  - drivers/power/power_supply_core.c:__power_supply_register
  - drivers/power/power_supply_core.c:__power_supply_register
```
```
In drivers/clk/clk.c (ffffffff8174d104)
Location: include/linux/err.h:56
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
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
In arch/x86/kernel/sysfb.c (ffffffff81fd8b3b)
Location: include/linux/err.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/sysfb.c:sysfb_init
```
```
In mm/mmap.c (ffffffff811f4375)
Location: include/linux/err.h:56
Inline: True
Inline callers:
  - mm/mmap.c:install_special_mapping
```
```
In block/ioctl.c (ffffffff814283fd)
Location: include/linux/err.h:56
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
```
```
In drivers/clk/clk.c (ffffffff81535974)
Location: include/linux/err.h:56
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
```
```
In drivers/nvdimm/bus.c (ffffffff8161a2fc)
Location: include/linux/err.h:56
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
```
```
In drivers/nvdimm/claim.c (ffffffff81624cad)
Location: include/linux/err.h:56
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
```
In drivers/power/supply/power_supply_core.c (ffffffff817108f0)
Location: include/linux/err.h:56
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
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
In arch/x86/kernel/sysfb.c (ffffffff820b9993)
Location: include/linux/err.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/sysfb.c:sysfb_init
```
```
In mm/mmap.c (ffffffff811ff2f5)
Location: include/linux/err.h:56
Inline: True
Inline callers:
  - mm/mmap.c:install_special_mapping
```
```
In block/ioctl.c (ffffffff81436743)
Location: include/linux/err.h:56
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
```
```
In drivers/clk/clk.c (ffffffff81548d36)
Location: include/linux/err.h:56
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
```
```
In drivers/nvdimm/bus.c (ffffffff8162e3fc)
Location: include/linux/err.h:56
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
```
```
In drivers/nvdimm/claim.c (ffffffff81639d0d)
Location: include/linux/err.h:56
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81728c40)
Location: include/linux/err.h:56
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
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
In arch/x86/kernel/sysfb.c (ffffffff826c0342)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/sysfb.c:sysfb_init
```
```
In kernel/cgroup/cgroup.c (ffffffff81133717)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81136755)
Location: include/linux/err.h:57
Inline: True
```
```
In mm/mmap.c (ffffffff812178f5)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - mm/mmap.c:install_special_mapping
```
```
In block/ioctl.c (ffffffff814624d3)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
```
```
In drivers/clk/clk.c (ffffffff815ac296)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
```
```
In drivers/nvdimm/bus.c (ffffffff81696bbc)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
```
```
In drivers/nvdimm/claim.c (ffffffff816a290d)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8179a3bf)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
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
In arch/x86/kernel/sysfb.c (ffffffff826ea560)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/sysfb.c:sysfb_init
```
```
In kernel/workqueue.c (ffffffff810aab27)
Location: include/linux/err.h:57
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff81141deb)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81144cab)
Location: include/linux/err.h:57
Inline: True
```
```
In mm/mmap.c (ffffffff81238c45)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - mm/mmap.c:install_special_mapping
```
```
In fs/sysfs/group.c (ffffffff813306e1)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
```
```
In block/ioctl.c (ffffffff81495df1)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
```
```
In drivers/acpi/acpi_apd.c (ffffffff81581112)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:st_misc_setup
```
```
In drivers/clk/clk.c (ffffffff815e41e6)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
```
```
In drivers/virtio/virtio_mmio.c (ffffffff815ed3e2)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8166032a)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
```
In drivers/nvdimm/bus.c (ffffffff816d2d24)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
```
```
In drivers/nvdimm/claim.c (ffffffff816deaba)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
```
In drivers/power/supply/power_supply_core.c (ffffffff817e1851)
Location: include/linux/err.h:57
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
In arch/x86/kernel/pcspeaker.c (ffffffff828a0dcc)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In arch/x86/kernel/sysfb.c (ffffffff828a1209)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/sysfb.c:sysfb_init
```
```
In kernel/workqueue.c (ffffffff810b3ab7)
Location: include/linux/err.h:57
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8114d85b)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811508cb)
Location: include/linux/err.h:57
Inline: True
```
```
In mm/mmap.c (ffffffff8124c605)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - mm/mmap.c:install_special_mapping
```
```
In fs/sysfs/group.c (ffffffff81347ab1)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
```
```
In block/ioctl.c (ffffffff814afca1)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
```
```
In block/bsg-lib.c (ffffffff814c0634)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_transport_fill_hdr
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81552a01)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
```
```
In drivers/acpi/acpi_apd.c (ffffffff815992b2)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:st_misc_setup
```
```
In drivers/clk/clk.c (ffffffff815fe5d6)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81607cc8)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8167e99c)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
```
In drivers/nvdimm/bus.c (ffffffff816f4454)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
```
```
In drivers/nvdimm/claim.c (ffffffff81700e8a)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8180cf80)
Location: include/linux/err.h:57
Inline: True
```
```
In net/sched/cls_api.c (ffffffff818fe0ce)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_cb_register
  - net/sched/cls_api.c:__tc_indr_block_cb_register
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
In arch/x86/kernel/pcspeaker.c (ffffffff828b901d)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In arch/x86/kernel/sysfb.c (ffffffff828b9459)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/sysfb.c:sysfb_init
```
```
In kernel/workqueue.c (ffffffff810b9871)
Location: include/linux/err.h:57
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8115961b)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115c32b)
Location: include/linux/err.h:57
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811a1529)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/trace/trace.c:instance_mkdir
```
```
In mm/mmap.c (ffffffff8125ea35)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - mm/mmap.c:install_special_mapping
```
```
In fs/sysfs/group.c (ffffffff8136fee0)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
```
```
In block/ioctl.c (ffffffff814de067)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815828e7)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
```
```
In drivers/acpi/acpi_apd.c (ffffffff815ca73b)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:st_misc_setup
```
```
In drivers/clk/clk.c (ffffffff8162fde6)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:of_clk_hw_register
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8163bae5)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff816b5555)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
```
```
In drivers/base/swnode.c (ffffffff816e4206)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_register
```
```
In drivers/nvdimm/bus.c (ffffffff8172da3b)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
```
```
In drivers/nvdimm/claim.c (ffffffff8173ad1a)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8184eb27)
Location: include/linux/err.h:57
Inline: True
```
```
In drivers/power/supply/power_supply_hwmon.c (ffffffff8184fb72)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
```
In net/core/bpf_sk_storage.c (ffffffff81953534)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
```
```
In net/sched/cls_api.c (ffffffff81962ac7)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tc_indr_block_cb_register
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
In arch/x86/kernel/pcspeaker.c (ffffffff828bf50b)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In arch/x86/kernel/sysfb.c (ffffffff828bf947)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/sysfb.c:sysfb_init
```
```
In kernel/workqueue.c (ffffffff810bfc31)
Location: include/linux/err.h:57
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8116528b)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811682cb)
Location: include/linux/err.h:57
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811acf79)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/trace/trace.c:instance_mkdir
```
```
In kernel/bpf/xskmap.c (ffffffff81201174)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
```
```
In mm/mmap.c (ffffffff8126d245)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - mm/mmap.c:install_special_mapping
```
```
In fs/sysfs/group.c (ffffffff813884a0)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
```
```
In security/lockdown/lockdown.c (ffffffff828f1a48)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - security/lockdown/lockdown.c:lockdown_secfs_init
```
```
In block/ioctl.c (ffffffff814f74c4)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815a42c7)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
```
```
In drivers/acpi/acpi_apd.c (ffffffff815eb94b)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:st_misc_setup
```
```
In drivers/clk/clk.c (ffffffff81652396)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:of_clk_hw_register
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8165df8f)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff816d8235)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
```
```
In drivers/base/swnode.c (ffffffff81708906)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_register
```
```
In drivers/base/power/wakeup_stats.c (ffffffff82908bd0)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:wakeup_sources_sysfs_init
```
```
In drivers/nvdimm/bus.c (ffffffff81751cdb)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
```
```
In drivers/nvdimm/claim.c (ffffffff8175e9ea)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
```
In drivers/net/phy/mdio_bus.c (ffffffff817be028)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817d76b8)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8187536f)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81880557)
Location: include/linux/err.h:57
Inline: True
```
```
In drivers/power/supply/power_supply_hwmon.c (ffffffff818815c1)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
```
In net/core/flow_offload.c (ffffffff81963fcb)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/core/bpf_sk_storage.c (ffffffff819898e4)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
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
In arch/x86/kernel/pcspeaker.c (ffffffff82ce37fe)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In arch/x86/kernel/sysfb.c (ffffffff82ce3c3a)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/sysfb.c:sysfb_init
```
```
In kernel/cgroup/cgroup.c (ffffffff811763ad)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8117986e)
Location: include/linux/err.h:57
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811bf231)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/trace/trace.c:instance_mkdir
```
```
In mm/mmap.c (ffffffff8129d445)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - mm/mmap.c:install_special_mapping
```
```
In fs/sysfs/group.c (ffffffff813d31f3)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
```
```
In security/lockdown/lockdown.c (ffffffff82d06a9f)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - security/lockdown/lockdown.c:lockdown_secfs_init
```
```
In block/partitions/core.c (ffffffff8155d91b)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - block/partitions/core.c:bdev_add_partition
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8164ceb7)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
```
```
In drivers/acpi/acpi_apd.c (ffffffff8169739b)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:st_misc_setup
```
```
In drivers/clk/clk.c (ffffffff81701316)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:of_clk_hw_register
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8170d0a1)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8178c802)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
```
```
In drivers/base/swnode.c (ffffffff817c38b9)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_register_nodes
```
```
In drivers/base/power/wakeup_stats.c (ffffffff82d1efbe)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:wakeup_sources_sysfs_init
```
```
In drivers/nvdimm/bus.c (ffffffff8181063e)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
```
```
In drivers/nvdimm/claim.c (ffffffff8181ee03)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818a3cac)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_attach
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81949970)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8194a2ee)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8194ea23)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
```
In drivers/power/supply/power_supply_hwmon.c (ffffffff8194fd9f)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
```
In net/core/devlink.c (ffffffff81a5889e)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_region_new
```
```
In net/core/bpf_sk_storage.c (ffffffff81a61e84)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
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
In arch/x86/kernel/pcspeaker.c (ffffffff82fd0af7)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In arch/x86/kernel/sysfb.c (ffffffff82fd0f33)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/sysfb.c:sysfb_init
```
```
In kernel/cgroup/cgroup.c (ffffffff8117309d)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811765de)
Location: include/linux/err.h:57
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811bce61)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/trace/trace.c:instance_mkdir
```
```
In kernel/bpf/bpf_inode_storage.c (ffffffff8122143c)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_update_elem
```
```
In kernel/bpf/bpf_task_storage.c (ffffffff812218a5)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem
```
```
In mm/filemap.c (ffffffff8125c0ac)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read_get_pages
  - mm/filemap.c:generic_file_buffered_read_get_pages
```
```
In mm/mmap.c (ffffffff812a8845)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - mm/mmap.c:install_special_mapping
```
```
In fs/iomap/direct-io.c (ffffffff813beedd)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/sysfs/group.c (ffffffff813e4f53)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
```
```
In security/lockdown/lockdown.c (ffffffff82ff3e92)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - security/lockdown/lockdown.c:lockdown_secfs_init
```
```
In block/partitions/core.c (ffffffff815797eb)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - block/partitions/core.c:bdev_add_partition
```
```
In lib/scatterlist.c (ffffffff815a3805)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_alloc_table_from_pages
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81671207)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
```
```
In drivers/acpi/acpi_apd.c (ffffffff816b440b)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:fch_misc_setup
```
```
In drivers/clk/clk.c (ffffffff8171e836)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:of_clk_hw_register
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81c04762)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff817a2dcb)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
```
```
In drivers/base/swnode.c (ffffffff817d8013)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_register
```
```
In drivers/base/power/wakeup_stats.c (ffffffff8300ce69)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:wakeup_sources_sysfs_init
```
```
In drivers/nvdimm/bus.c (ffffffff8181f57e)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
```
```
In drivers/nvdimm/claim.c (ffffffff8182dd50)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
```
In drivers/spi/spi-mem.c (ffffffff8188bdc8)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b2c7c)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_attach
```
```
In drivers/usb/roles/class.c (ffffffff83010fcf)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/usb/roles/class.c:usb_roles_init
```
```
In drivers/rtc/nvmem.c (ffffffff81c24624)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/rtc/nvmem.c:devm_rtc_nvmem_register
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8194f530)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8194fe7e)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/power/supply/power_supply_core.c (ffffffff819544d1)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
```
In drivers/power/supply/power_supply_hwmon.c (ffffffff8195575f)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
```
In net/core/devlink.c (ffffffff81a6088f)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_region_new
```
```
In net/core/bpf_sk_storage.c (ffffffff81a69494)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
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
In arch/x86/kernel/pcspeaker.c (ffffffff831db7c9)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In arch/x86/kernel/sysfb.c (ffffffff831dbbff)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/sysfb.c:sysfb_init
```
```
In kernel/cgroup/cgroup.c (ffffffff81173caa)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8117713e)
Location: include/linux/err.h:57
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811bc95b)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/trace/trace.c:instance_mkdir
```
```
In kernel/bpf/bpf_task_storage.c (ffffffff81225c51)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem
```
```
In kernel/bpf/bpf_inode_storage.c (ffffffff812260fc)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_update_elem
```
```
In mm/mmap.c (ffffffff812adcf5)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - mm/mmap.c:install_special_mapping
```
```
In fs/iomap/direct-io.c (ffffffff813c5bd9)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/sysfs/group.c (ffffffff813ebb53)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
```
```
In fs/fuse/file.c (ffffffff81498c10)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_open_common
```
```
In security/lockdown/lockdown.c (ffffffff831fe9ac)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - security/lockdown/lockdown.c:lockdown_secfs_init
```
```
In block/partitions/core.c (ffffffff815814bb)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - block/partitions/core.c:bdev_add_partition
```
```
In lib/scatterlist.c (ffffffff815aa3b5)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_alloc_table_from_pages
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81653717)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
```
```
In drivers/acpi/acpi_apd.c (ffffffff8169663b)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:fch_misc_setup
```
```
In drivers/clk/clk.c (ffffffff816ff876)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:of_clk_hw_register
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81bf644b)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff81785ab7)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
```
```
In drivers/base/swnode.c (ffffffff817bbf03)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_register
```
```
In drivers/base/power/wakeup_stats.c (ffffffff83217cc5)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:wakeup_sources_sysfs_init
```
```
In drivers/nvdimm/bus.c (ffffffff8180288e)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
```
```
In drivers/nvdimm/claim.c (ffffffff81811020)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
```
In drivers/spi/spi-mem.c (ffffffff8186e728)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818972e8)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
```
In drivers/usb/roles/class.c (ffffffff8321bfbc)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/usb/roles/class.c:usb_roles_init
```
```
In drivers/rtc/nvmem.c (ffffffff81c166e1)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/rtc/nvmem.c:devm_rtc_nvmem_register
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81933a5a)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81933d35)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81938300)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
```
In drivers/power/supply/power_supply_hwmon.c (ffffffff81939535)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
```
In drivers/opp/core.c (ffffffff81978201)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/opp/core.c:_add_opp_table_indexed
```
```
In drivers/platform/x86/intel_scu_pcidrv.c (ffffffff819aa984)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_pcidrv.c:intel_scu_pci_probe
```
```
In net/core/devlink.c (ffffffff81a428e0)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_region_new
```
```
In net/core/bpf_sk_storage.c (ffffffff81a51c24)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
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
In arch/x86/kernel/pcspeaker.c (ffffffff832beb62)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In kernel/cgroup/cgroup.c (ffffffff8119ad00)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8119e86e)
Location: include/linux/err.h:57
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811e73fb)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/trace/trace.c:instance_mkdir
```
```
In kernel/bpf/bpf_task_storage.c (ffffffff8125dc71)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem
```
```
In kernel/bpf/bpf_inode_storage.c (ffffffff8125e11c)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_update_elem
```
```
In mm/mmap.c (ffffffff812ef465)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - mm/mmap.c:install_special_mapping
```
```
In fs/iomap/direct-io.c (ffffffff81416069)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/sysfs/group.c (ffffffff8143d8e2)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
```
```
In fs/fuse/file.c (ffffffff814f06b0)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/inode.c (ffffffff814f55f3)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_tree
```
```
In security/lockdown/lockdown.c (ffffffff832e5cbe)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - security/lockdown/lockdown.c:lockdown_secfs_init
```
```
In block/partitions/core.c (ffffffff815e6859)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - block/partitions/core.c:bdev_add_partition
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff816c549d)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
```
```
In drivers/acpi/acpi_apd.c (ffffffff8170c3db)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:fch_misc_setup
```
```
In drivers/clk/clk.c (ffffffff8177a03d)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:of_clk_hw_register
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81cf4f77)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8180c6c9)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
```
```
In drivers/base/swnode.c (ffffffff818460a3)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_register
```
```
In drivers/base/power/wakeup_stats.c (ffffffff833016db)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:wakeup_sources_sysfs_init
```
```
In drivers/nvdimm/claim.c (ffffffff8189b6c0)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
```
In drivers/spi/spi-mem.c (ffffffff818fe7c8)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/usb/roles/class.c (ffffffff83305bfa)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/usb/roles/class.c:usb_roles_init
```
```
In drivers/rtc/nvmem.c (ffffffff81d25186)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/rtc/nvmem.c:devm_rtc_nvmem_register
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff819d6e2a)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff819d7135)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/power/supply/power_supply_core.c (ffffffff819dc75f)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
```
In drivers/power/supply/power_supply_hwmon.c (ffffffff819ddc35)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
```
In drivers/opp/core.c (ffffffff81a21171)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/opp/core.c:_add_opp_table_indexed
```
```
In drivers/platform/x86/intel_scu_pcidrv.c (ffffffff81a58414)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_pcidrv.c:intel_scu_pci_probe
```
```
In net/core/devlink.c (ffffffff81afaf80)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_region_new
```
```
In net/core/bpf_sk_storage.c (ffffffff81b0a8b4)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
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
In arch/x86/kernel/pcspeaker.c (ffffffff8347093c)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In kernel/cgroup/cgroup.c (ffffffff811caea4)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811cefcf)
Location: include/linux/err.h:57
Inline: True
```
```
In kernel/trace/trace.c (ffffffff8121f37b)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/trace/trace.c:instance_mkdir
```
```
In kernel/bpf/verifier.c (ffffffff81291296)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_func_arg
```
```
In kernel/bpf/bpf_task_storage.c (ffffffff812a7ffa)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem
```
```
In kernel/bpf/bpf_inode_storage.c (ffffffff812a8550)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_update_elem
```
```
In mm/mmap.c (ffffffff81352925)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - mm/mmap.c:install_special_mapping
```
```
In fs/iomap/direct-io.c (ffffffff8148d8c1)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/sysfs/group.c (ffffffff814b8eb0)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
```
```
In fs/fuse/file.c (ffffffff8157fe68)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/inode.c (ffffffff815856e2)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_tree
```
```
In security/lockdown/lockdown.c (ffffffff8349cad4)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - security/lockdown/lockdown.c:lockdown_secfs_init
```
```
In block/partitions/core.c (ffffffff816959ba)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - block/partitions/core.c:bdev_add_partition
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff817eb28f)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
```
```
In drivers/acpi/acpi_apd.c (ffffffff8183aa5e)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:fch_misc_setup
```
```
In drivers/clk/clk.c (ffffffff818b048d)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:of_clk_hw_register
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81ebd0ec)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8194cd61)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
```
```
In drivers/base/swnode.c (ffffffff8198acc2)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_register
```
```
In drivers/base/power/wakeup_stats.c (ffffffff834ba540)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:wakeup_sources_sysfs_init
```
```
In drivers/nvdimm/claim.c (ffffffff819e4e20)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
```
In drivers/spi/spi-mem.c (ffffffff81a500bf)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/usb/roles/class.c (ffffffff834bed49)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/usb/roles/class.c:usb_roles_init
```
```
In drivers/rtc/nvmem.c (ffffffff81ef0f6b)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/rtc/nvmem.c:devm_rtc_nvmem_register
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81b34cdd)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_setup_smbus_alert
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81b39992)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81b39dba)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81b40825)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
```
In drivers/power/supply/power_supply_hwmon.c (ffffffff81b4220d)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
```
In drivers/opp/core.c (ffffffff81b8a0f0)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/opp/core.c:_add_opp_table_indexed
```
```
In drivers/platform/x86/intel_scu_pcidrv.c (ffffffff81bc7ff4)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_pcidrv.c:intel_scu_pci_probe
```
```
In net/core/devlink.c (ffffffff81c7fafb)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_region_new
```
```
In net/core/bpf_sk_storage.c (ffffffff81c90e3d)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
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
In arch/x86/kernel/pcspeaker.c (ffffffff83e97758)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In kernel/cgroup/cgroup.c (ffffffff8120e2a4)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8121290f)
Location: include/linux/err.h:57
Inline: True
```
```
In kernel/trace/trace.c (ffffffff81269dcb)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/trace/trace.c:instance_mkdir
```
```
In kernel/bpf/bpf_task_storage.c (ffffffff8130682a)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem
```
```
In kernel/bpf/bpf_inode_storage.c (ffffffff81306fb0)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_update_elem
```
```
In kernel/bpf/btf.c (ffffffff8131a6f6)
Location: include/linux/err.h:57
Inline: True
```
```
In kernel/bpf/bpf_cgrp_storage.c (ffffffff81325ab5)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_update_elem
```
```
In mm/mmap.c (ffffffff813cc9a5)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - mm/mmap.c:install_special_mapping
```
```
In fs/iomap/direct-io.c (ffffffff81521071)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/sysfs/group.c (ffffffff815505b0)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
```
```
In fs/fuse/file.c (ffffffff81625ba8)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/inode.c (ffffffff8162b8f2)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_tree
```
```
In security/lockdown/lockdown.c (ffffffff83ed41e5)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - security/lockdown/lockdown.c:lockdown_secfs_init
```
```
In block/partitions/core.c (ffffffff81754bcd)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - block/partitions/core.c:bdev_add_partition
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818b7747)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
```
```
In drivers/gpio/gpiolib-swnode.c (ffffffff818cb568)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-swnode.c:swnode_find_gpio
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81911666)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
```
```
In drivers/acpi/acpi_apd.c (ffffffff819700c5)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:fch_misc_setup
```
```
In drivers/clk/clk.c (ffffffff819fc97d)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:of_clk_hw_register
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81a1264b)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff81ab0e92)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
```
```
In drivers/base/swnode.c (ffffffff81afa172)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_register
```
```
In drivers/base/power/wakeup_stats.c (ffffffff83ef7cce)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:wakeup_sources_sysfs_init
```
```
In drivers/mfd/twl6040.c (ffffffff81b3f0f7)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/nvdimm/claim.c (ffffffff81b60bd0)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
```
In drivers/spi/spi-mem.c (ffffffff81bd91ef)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/tun.c (ffffffff81bf1e08)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c (ffffffff81bf3662)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_debugfs
```
```
In drivers/usb/roles/class.c (ffffffff83efcfbe)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/usb/roles/class.c:usb_roles_init
```
```
In drivers/rtc/nvmem.c (ffffffff81cbd545)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/rtc/nvmem.c:devm_rtc_nvmem_register
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81cc9dbd)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_setup_smbus_alert
```
```
In drivers/i2c/busses/i2c-designware-master.c (0)
Location: include/linux/err.h:57
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81ccf73a)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/power/supply/power_supply_hwmon.c (ffffffff81cd891d)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
```
In drivers/opp/core.c (ffffffff81d2990e)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/opp/core.c:_add_opp_table_indexed
```
```
In drivers/platform/x86/intel_scu_pcidrv.c (ffffffff81d70c64)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_pcidrv.c:intel_scu_pci_probe
```
```
In net/core/devlink.c (ffffffff81e38baa)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_region_new
```
```
In net/core/bpf_sk_storage.c (ffffffff81e4c22d)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
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
In arch/x86/kernel/pcspeaker.c (ffffffff836bb308)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In kernel/cgroup/cgroup.c (ffffffff81223cb2)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff812282bf)
Location: include/linux/err.h:105
Inline: True
```
```
In kernel/trace/trace.c (ffffffff81280f4b)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - kernel/trace/trace.c:instance_mkdir
```
```
In kernel/bpf/bpf_task_storage.c (ffffffff8133578b)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem
```
```
In kernel/bpf/bpf_inode_storage.c (ffffffff81335e9e)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_update_elem
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/err.h:105
Inline: True
```
```
In kernel/bpf/bpf_cgrp_storage.c (ffffffff81355d05)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_update_elem
```
```
In mm/mmap.c (ffffffff81401275)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - mm/mmap.c:install_special_mapping
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/err.h:105
Inline: True
```
```
In fs/sysfs/group.c (ffffffff815882a0)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
```
```
In fs/fuse/file.c (ffffffff8165df24)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/inode.c (ffffffff81663b25)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_tree
```
```
In security/lockdown/lockdown.c (ffffffff836f9325)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - security/lockdown/lockdown.c:lockdown_secfs_init
```
```
In block/partitions/core.c (ffffffff81791294)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - block/partitions/core.c:bdev_add_partition
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818fa892)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
```
```
In drivers/gpio/gpiolib-swnode.c (ffffffff8190e5d8)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-swnode.c:swnode_find_gpio
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/linux/err.h:105
Inline: True
```
```
In drivers/acpi/acpi_apd.c (ffffffff819b668f)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:fch_misc_setup
```
```
In drivers/clk/clk.c (ffffffff81a453ef)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:of_clk_hw_register
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81a5b67b)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff81afce6f)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
```
```
In drivers/base/swnode.c (ffffffff81b48602)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_register
```
```
In drivers/base/power/wakeup_stats.c (ffffffff8371d865)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:wakeup_sources_sysfs_init
```
```
In drivers/mfd/twl6040.c (ffffffff81b92577)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/nvdimm/claim.c (ffffffff81bb4150)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
```
In drivers/spi/spi-mem.c (ffffffff81c2fbef)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/tun.c (ffffffff81c4aa70)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c (ffffffff81c5699f)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_debugfs
```
```
In drivers/rtc/nvmem.c (ffffffff81d24e55)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - drivers/rtc/nvmem.c:devm_rtc_nvmem_register
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81d31b0d)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_setup_smbus_alert
```
```
In drivers/i2c/busses/i2c-designware-master.c (0)
Location: include/linux/err.h:105
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81d37b65)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/power/supply/power_supply_hwmon.c (ffffffff81d40b4d)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
```
In drivers/opp/core.c (ffffffff81d92b2a)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - drivers/opp/core.c:_add_opp_table_indexed
```
```
In drivers/platform/x86/intel_scu_pcidrv.c (ffffffff81dde924)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_pcidrv.c:intel_scu_pci_probe
```
```
In net/core/bpf_sk_storage.c (ffffffff81ea7959)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
```
```
In net/devlink/leftover.c (ffffffff82039cfa)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_nl_cmd_region_new
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
In arch/x86/kernel/pcspeaker.c (ffffffff838ebce8)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In kernel/cgroup/cgroup.c (ffffffff8123b9a2)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff812400bf)
Location: include/linux/err.h:105
Inline: True
```
```
In kernel/trace/trace.c (ffffffff8129b1bd)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - kernel/trace/trace.c:instance_mkdir
```
```
In kernel/bpf/bpf_task_storage.c (ffffffff81359deb)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem
```
```
In kernel/bpf/bpf_inode_storage.c (ffffffff8135a4fe)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_update_elem
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/err.h:105
Inline: True
```
```
In kernel/bpf/bpf_cgrp_storage.c (ffffffff8137e835)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_update_elem
```
```
In mm/mmap.c (ffffffff8142d8c5)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - mm/mmap.c:install_special_mapping
```
```
In fs/iomap/direct-io.c (0)
Location: include/linux/err.h:105
Inline: True
```
```
In fs/sysfs/group.c (ffffffff815c0e60)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
```
```
In fs/fuse/file.c (ffffffff81697c64)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/inode.c (ffffffff8169dc7c)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_tree
```
```
In security/lockdown/lockdown.c (ffffffff8392c745)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - security/lockdown/lockdown.c:lockdown_secfs_init
```
```
In block/partitions/core.c (ffffffff817d4bbc)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - block/partitions/core.c:bdev_add_partition
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81941c12)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
```
```
In drivers/gpio/gpiolib-swnode.c (ffffffff81956335)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-swnode.c:swnode_find_gpio
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/linux/err.h:105
Inline: True
```
```
In drivers/acpi/acpi_apd.c (ffffffff81a00c0f)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:fch_misc_setup
```
```
In drivers/clk/clk.c (ffffffff81a90edf)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:of_clk_hw_register
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81aacaeb)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff81b5047f)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
```
```
In drivers/base/swnode.c (ffffffff81ba09f2)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_register
```
```
In drivers/base/power/wakeup_stats.c (ffffffff839513d5)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:wakeup_sources_sysfs_init
```
```
In drivers/mfd/twl6040.c (ffffffff81be6517)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/nvdimm/claim.c (ffffffff81c086a0)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
```
In drivers/spi/spi-mem.c (ffffffff81ce2aaf)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/tun.c (ffffffff81d003d6)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c (ffffffff81d0d13f)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_debugfs
```
```
In drivers/rtc/nvmem.c (ffffffff81ddabb9)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - drivers/rtc/nvmem.c:devm_rtc_nvmem_register
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81de7aed)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_setup_smbus_alert
```
```
In drivers/i2c/busses/i2c-designware-master.c (0)
Location: include/linux/err.h:105
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81dedde5)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/power/supply/power_supply_hwmon.c (ffffffff81df74fd)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
```
In drivers/opp/core.c (ffffffff81e4a41f)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - drivers/opp/core.c:_add_opp_table_indexed
```
```
In drivers/platform/x86/intel_scu_pcidrv.c (ffffffff81e94834)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_pcidrv.c:intel_scu_pci_probe
```
```
In net/core/bpf_sk_storage.c (ffffffff81f6a409)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
```
```
In net/devlink/region.c (ffffffff82110de6)
Location: include/linux/err.h:105
Inline: True
Inline callers:
  - net/devlink/region.c:devlink_nl_region_new_doit
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
In arch/arm64/kernel/vdso.c (ffff800010095e70)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - arch/arm64/kernel/vdso.c:aarch32_setup_additional_pages
  - arch/arm64/kernel/vdso.c:aarch32_setup_additional_pages
```
```
In virt/kvm/arm/vgic/vgic-its.c (ffff8000100ea84c)
Location: include/linux/err.h:57
Inline: True
```
```
In kernel/workqueue.c (ffff80001011c73c)
Location: include/linux/err.h:57
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffff8000101d6d00)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
```
In kernel/cgroup/cgroup-v1.c (ffff8000101db4d8)
Location: include/linux/err.h:57
Inline: True
```
```
In kernel/trace/trace.c (ffff800010229f3c)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/trace/trace.c:instance_mkdir
```
```
In kernel/bpf/xskmap.c (ffff8000102891e4)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
```
```
In mm/mmap.c (ffff8000103042dc)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - mm/mmap.c:install_special_mapping
```
```
In fs/sysfs/group.c (ffff800010458758)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
```
```
In security/lockdown/lockdown.c (ffff80001146bcd4)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - security/lockdown/lockdown.c:lockdown_secfs_init
```
```
In block/ioctl.c (ffff8000105f8308)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
```
```
In drivers/phy/phy-xgene.c (ffff800010688140)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/phy/phy-xgene.c:xgene_phy_probe
```
```
In drivers/gpio/gpiolib-of.c (0)
Location: include/linux/err.h:57
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffff80001070cf40)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
```
```
In drivers/pci/controller/dwc/pcie-qcom.c (ffff800010734068)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_1_0
```
```
In drivers/clk/clk.c (ffff8000107c2fa4)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/clk/clk.c:of_clk_hw_register
  - drivers/clk/clk.c:clk_hw_register
```
```
In drivers/clk/mvebu/armada-37xx-periph.c (ffff8000107e9214)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/clk/mvebu/armada-37xx-periph.c:armada_3700_periph_clock_probe
```
```
In drivers/clk/sunxi/clk-sun8i-apb0.c (ffff8000107f3d8c)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun8i-apb0.c:sun8i_a23_apb0_clk_probe
```
```
In drivers/soc/imx/soc-imx-scu.c (ffff800011490294)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/soc/imx/soc-imx-scu.c:imx_scu_soc_init
```
```
In drivers/virtio/virtio_mmio.c (ffff800010826014)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
```
```
In drivers/char/tpm/tpm_crb.c (ffff8000108c3824)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
```
```
In drivers/iommu/arm-smmu-v3.c (ffff8000108d6834)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_add_device
```
```
In drivers/iommu/qcom_iommu.c (0)
Location: include/linux/err.h:57
Inline: True
```
```
In drivers/iommu/virtio-iommu.c (0)
Location: include/linux/err.h:57
Inline: True
```
```
In drivers/base/swnode.c (ffff8000108f61b8)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_register
```
```
In drivers/base/power/wakeup_stats.c (ffff800011497630)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:wakeup_sources_sysfs_init
```
```
In drivers/misc/vexpress-syscfg.c (ffff80001092bae8)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/misc/vexpress-syscfg.c:vexpress_syscfg_probe
```
```
In drivers/nvdimm/bus.c (ffff800010952440)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
```
```
In drivers/nvdimm/claim.c (ffff8000109601f8)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
```
In drivers/net/phy/mdio_bus.c (ffff8000109d6fa4)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
```
```
In drivers/usb/roles/class.c (ffff80001149d4f8)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/usb/roles/class.c:usb_roles_init
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffff800010aba23c)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/power/supply/power_supply_core.c (ffff800010acc110)
Location: include/linux/err.h:57
Inline: True
```
```
In drivers/power/supply/power_supply_hwmon.c (ffff800010acd9f8)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
```
In drivers/thermal/armada_thermal.c (ffff800010ade010)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
```
```
In drivers/cpufreq/cpufreq-dt.c (ffff800010b26128)
Location: include/linux/err.h:57
Inline: True
```
```
In drivers/cpufreq/cpufreq-dt-platdev.c (ffff8000114a1f98)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq-dt-platdev.c:cpufreq_dt_platdev_init
```
```
In drivers/firmware/efi/arm-init.c (ffff8000114a7240)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/firmware/efi/arm-init.c:register_gop_device
```
```
In drivers/of/of_mdio.c (ffff800010b75d7c)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/of/of_mdio.c:of_phy_register_fixed_link
```
```
In drivers/nvmem/zynqmp_nvmem.c (ffff800010ba097c)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/nvmem/zynqmp_nvmem.c:zynqmp_nvmem_probe
```
```
In net/core/flow_offload.c (ffff800010c08684)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/core/bpf_sk_storage.c (ffff800010c32148)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
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
In arch/arm/kernel/vdso.c (c0319bdc)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - arch/arm/kernel/vdso.c:arm_install_vdso
```
```
In arch/arm/mach-omap2/fb.c (c1512754)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - arch/arm/mach-omap2/fb.c:omap_init_vrfb
```
```
In kernel/workqueue.c (c0371630)
Location: include/linux/err.h:57
Inline: True
```
```
In kernel/cgroup/cgroup.c (c04199e0)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
```
In kernel/cgroup/cgroup-v1.c (c041d6d8)
Location: include/linux/err.h:57
Inline: True
```
```
In kernel/trace/trace.c (c04675c4)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/trace/trace.c:instance_mkdir
```
```
In kernel/bpf/xskmap.c (c04b8a8c)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
```
```
In mm/mmap.c (c0522a5c)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - mm/mmap.c:install_special_mapping
```
```
In fs/sysfs/group.c (c061a090)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
```
```
In security/lockdown/lockdown.c (c154496c)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - security/lockdown/lockdown.c:lockdown_secfs_init
```
```
In block/ioctl.c (c07a366c)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
```
```
In drivers/phy/marvell/phy-armada375-usb2.c (c082bc88)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/phy/marvell/phy-armada375-usb2.c:armada375_usb_phy_probe
```
```
In drivers/phy/samsung/phy-exynos-dp-video.c (c082c0c4)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/phy/samsung/phy-exynos-dp-video.c:exynos_dp_video_phy_probe
```
```
In drivers/phy/samsung/phy-exynos-mipi-video.c (c082c280)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/phy/samsung/phy-exynos-mipi-video.c:exynos_mipi_video_phy_probe
```
```
In drivers/phy/samsung/phy-exynos-pcie.c (c082c968)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos_pcie_phy_probe
```
```
In drivers/gpio/gpiolib-of.c (0)
Location: include/linux/err.h:57
Inline: True
```
```
In drivers/gpio/gpio-vf610.c (c0873880)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/gpio/gpio-vf610.c:vf610_gpio_probe
  - drivers/gpio/gpio-vf610.c:vf610_gpio_probe
```
```
In drivers/pci/controller/dwc/pcie-qcom.c (c08bcd6c)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_1_0
```
```
In drivers/clk/clk.c (c08edbc0)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/clk/clk.c:of_clk_hw_register
  - drivers/clk/clk.c:clk_hw_register
```
```
In drivers/soc/imx/soc-imx-scu.c (c158fdd4)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/soc/imx/soc-imx-scu.c:imx_scu_soc_init
```
```
In drivers/virtio/virtio_mmio.c (c0944a84)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
```
```
In drivers/iommu/qcom_iommu.c (c09cb6f4)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/iommu/qcom_iommu.c:qcom_iommu_add_device
```
```
In drivers/base/swnode.c (c09e22ac)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_register
```
```
In drivers/base/power/wakeup_stats.c (c15984d8)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:wakeup_sources_sysfs_init
```
```
In drivers/misc/vexpress-syscfg.c (c0a0a7b0)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/misc/vexpress-syscfg.c:vexpress_syscfg_probe
```
```
In drivers/net/phy/mdio_bus.c (c0abe768)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
```
```
In drivers/usb/phy/phy-generic.c (c0b0b6ac)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/usb/phy/phy-generic.c:usb_phy_gen_create_phy
  - drivers/usb/phy/phy-generic.c:usb_phy_gen_create_phy
```
```
In drivers/usb/roles/class.c (c159faf8)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/usb/roles/class.c:usb_roles_init
```
```
In drivers/i2c/busses/i2c-designware-master.c (c0b99974)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/power/supply/power_supply_core.c (c0bad0fc)
Location: include/linux/err.h:57
Inline: True
```
```
In drivers/power/supply/power_supply_hwmon.c (c0bae3d4)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
```
In drivers/thermal/armada_thermal.c (c0bbfbd8)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
```
```
In drivers/opp/ti-opp-supply.c (c0bf7c20)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/opp/ti-opp-supply.c:ti_opp_supply_probe
```
```
In drivers/cpufreq/cpufreq-dt.c (c0bfff84)
Location: include/linux/err.h:57
Inline: True
```
```
In drivers/cpufreq/cpufreq-dt-platdev.c (c15a3fc4)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq-dt-platdev.c:cpufreq_dt_platdev_init
```
```
In drivers/firmware/efi/arm-init.c (c15a9cfc)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/firmware/efi/arm-init.c:register_gop_device
```
```
In drivers/of/of_mdio.c (c0c58130)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/of/of_mdio.c:of_phy_register_fixed_link
```
```
In net/core/flow_offload.c (c0d2187c)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/core/bpf_sk_storage.c (c0d48bac)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
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
In arch/powerpc/kernel/time.c (c000000001348be4)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - arch/powerpc/kernel/time.c:rtc_init
```
```
In arch/powerpc/platforms/powernv/opal-rtc.c (c00000000135c3b4)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-rtc.c:__machine_initcall_powernv_opal_time_init
```
```
In arch/powerpc/platforms/powernv/opal-sensor.c (c00000000135d680)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-sensor.c:opal_sensor_init
```
```
In kernel/workqueue.c (c000000000165d90)
Location: include/linux/err.h:57
Inline: True
```
```
In kernel/cgroup/cgroup.c (c000000000242fa4)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
```
In kernel/cgroup/cgroup-v1.c (c000000000248008)
Location: include/linux/err.h:57
Inline: True
```
```
In kernel/trace/trace.c (c0000000002b1a1c)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/trace/trace.c:instance_mkdir
```
```
In kernel/bpf/xskmap.c (c0000000003345d0)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
```
```
In mm/mmap.c (c0000000003d108c)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - mm/mmap.c:install_special_mapping
```
```
In fs/sysfs/group.c (c0000000005724a4)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
```
```
In security/lockdown/lockdown.c (c00000000139a950)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - security/lockdown/lockdown.c:lockdown_secfs_init
```
```
In block/ioctl.c (c000000000790520)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
```
```
In drivers/gpio/gpiolib-of.c (0)
Location: include/linux/err.h:57
Inline: True
```
```
In drivers/virtio/virtio_mmio.c (c0000000008d14d4)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
```
```
In drivers/base/swnode.c (c00000000099131c)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_register
```
```
In drivers/base/power/wakeup_stats.c (c0000000013aaec4)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:wakeup_sources_sysfs_init
```
```
In drivers/nvdimm/bus.c (c0000000009ff2fc)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
```
```
In drivers/nvdimm/claim.c (c000000000a12fd8)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
```
In drivers/net/phy/mdio_bus.c (c000000000a9879c)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
```
```
In drivers/vfio/pci/vfio_pci.c (c000000000ab6bc4)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (c000000000b9d320)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/power/supply/power_supply_core.c (c000000000baec4c)
Location: include/linux/err.h:57
Inline: True
```
```
In drivers/power/supply/power_supply_hwmon.c (c000000000bb057c)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
```
In drivers/of/of_mdio.c (c000000000c5365c)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/of/of_mdio.c:of_phy_register_fixed_link
```
```
In net/core/flow_offload.c (c000000000cf2dbc)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/core/bpf_sk_storage.c (c000000000d2b1d8)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
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
In kernel/workqueue.c (ffffffe0000d6b0a)
Location: include/linux/err.h:57
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffe00014fe3a)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
```
In kernel/cgroup/cgroup-v1.c (ffffffe0001532d4)
Location: include/linux/err.h:57
Inline: True
```
```
In kernel/trace/trace.c (ffffffe0001845ca)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/trace/trace.c:instance_mkdir
```
```
In kernel/bpf/xskmap.c (ffffffe0001bd51a)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
```
```
In mm/mmap.c (ffffffe000210b52)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - mm/mmap.c:install_special_mapping
```
```
In fs/sysfs/group.c (ffffffe0002e9802)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
```
```
In security/lockdown/lockdown.c (ffffffe000026cd2)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - security/lockdown/lockdown.c:lockdown_secfs_init
```
```
In block/ioctl.c (ffffffe000435186)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
```
```
In drivers/gpio/gpiolib-of.c (0)
Location: include/linux/err.h:57
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffe0004d96ea)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
```
```
In drivers/clk/clk.c (ffffffe000510952)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/clk/clk.c:of_clk_hw_register
  - drivers/clk/clk.c:clk_hw_register
```
```
In drivers/virtio/virtio_mmio.c (ffffffe00051d094)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
```
```
In drivers/tty/hvc/hvc_riscv_sbi.c (ffffffe00002e9e6)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_riscv_sbi.c:hvc_sbi_init
```
```
In drivers/base/swnode.c (ffffffe00058719a)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_register
```
```
In drivers/nvdimm/bus.c (ffffffe0005c1f4a)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
```
```
In drivers/nvdimm/claim.c (ffffffe0005cdcd2)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
```
In drivers/net/phy/mdio_bus.c (ffffffe000622e32)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffe0006beb06)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/power/supply/power_supply_core.c (ffffffe0006c999c)
Location: include/linux/err.h:57
Inline: True
```
```
In drivers/power/supply/power_supply_hwmon.c (ffffffe0006caa06)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
```
In drivers/of/of_mdio.c (ffffffe000729326)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/of/of_mdio.c:of_phy_register_fixed_link
```
```
In net/core/flow_offload.c (ffffffe000786538)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/core/bpf_sk_storage.c (ffffffe0007a78ba)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
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
In arch/x86/kernel/pcspeaker.c (ffffffff828aa4e1)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In arch/x86/kernel/sysfb.c (ffffffff828aa91d)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/sysfb.c:sysfb_init
```
```
In kernel/workqueue.c (ffffffff810b9fa1)
Location: include/linux/err.h:57
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8115d8ab)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811608eb)
Location: include/linux/err.h:57
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811a5599)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/trace/trace.c:instance_mkdir
```
```
In kernel/bpf/xskmap.c (ffffffff811f9794)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
```
```
In mm/mmap.c (ffffffff81265895)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - mm/mmap.c:install_special_mapping
```
```
In fs/sysfs/group.c (ffffffff81380a80)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
```
```
In security/lockdown/lockdown.c (ffffffff828da8fc)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - security/lockdown/lockdown.c:lockdown_secfs_init
```
```
In block/ioctl.c (ffffffff814efaa4)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81597ad7)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
```
```
In drivers/clk/clk.c (ffffffff816183f6)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:of_clk_hw_register
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81623e2f)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8169dc85)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
```
```
In drivers/base/swnode.c (ffffffff816ce056)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_register
```
```
In drivers/base/power/wakeup_stats.c (ffffffff828f03a1)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:wakeup_sources_sysfs_init
```
```
In drivers/nvdimm/bus.c (ffffffff817063cb)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
```
```
In drivers/nvdimm/claim.c (ffffffff817130da)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81782af8)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81828ac7)
Location: include/linux/err.h:57
Inline: True
```
```
In drivers/power/supply/power_supply_hwmon.c (ffffffff81829b31)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
```
In net/core/flow_offload.c (ffffffff81903f9b)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/core/bpf_sk_storage.c (ffffffff81929754)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
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
In arch/x86/kernel/pcspeaker.c (ffffffff828a27aa)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In arch/x86/kernel/sysfb.c (ffffffff828a2be9)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/sysfb.c:sysfb_init
```
```
In kernel/workqueue.c (ffffffff810a88e1)
Location: include/linux/err.h:57
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff81150b9b)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81153b5b)
Location: include/linux/err.h:57
Inline: True
```
```
In kernel/trace/trace.c (ffffffff81198549)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/trace/trace.c:instance_mkdir
```
```
In kernel/bpf/xskmap.c (ffffffff811ec4e4)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
```
```
In mm/mmap.c (ffffffff81257cb5)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - mm/mmap.c:install_special_mapping
```
```
In fs/sysfs/group.c (ffffffff81371510)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
```
```
In security/lockdown/lockdown.c (ffffffff828d3018)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - security/lockdown/lockdown.c:lockdown_secfs_init
```
```
In block/ioctl.c (ffffffff814dffe4)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81586c67)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
```
```
In drivers/acpi/acpi_apd.c (ffffffff815c636b)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:st_misc_setup
```
```
In drivers/clk/clk.c (ffffffff8160c926)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:of_clk_hw_register
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8161847f)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8167b675)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
```
```
In drivers/base/swnode.c (ffffffff816a9386)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_register
```
```
In drivers/base/power/wakeup_stats.c (ffffffff828e7828)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:wakeup_sources_sysfs_init
```
```
In drivers/nvdimm/bus.c (ffffffff816d9e4b)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
```
```
In drivers/nvdimm/claim.c (ffffffff816e6b5a)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
```
In drivers/dax/pmem/pmem.c (ffffffff816f2060)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/dax/pmem/pmem.c:dax_pmem_probe
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81762888)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff81781768)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
```
In drivers/power/supply/power_supply_core.c (ffffffff817f0157)
Location: include/linux/err.h:57
Inline: True
```
```
In drivers/power/supply/power_supply_hwmon.c (ffffffff817f11c1)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
```
In net/core/flow_offload.c (ffffffff818bddcb)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/core/bpf_sk_storage.c (ffffffff818e3504)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
```
```
In net/ipv4/ip_tunnel.c (ffffffff81968837)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:ip_tunnel_init_net
  - net/ipv4/ip_tunnel.c:ip_tunnel_ioctl
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
In arch/x86/kernel/pcspeaker.c (ffffffff828bd3e0)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In arch/x86/kernel/sysfb.c (ffffffff828bd81c)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/sysfb.c:sysfb_init
```
```
In kernel/workqueue.c (ffffffff810b9501)
Location: include/linux/err.h:57
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8115b67b)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115e6bb)
Location: include/linux/err.h:57
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811a3369)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/trace/trace.c:instance_mkdir
```
```
In kernel/bpf/xskmap.c (ffffffff811f7564)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
```
```
In mm/mmap.c (ffffffff81263635)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - mm/mmap.c:install_special_mapping
```
```
In fs/sysfs/group.c (ffffffff8137e550)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
```
```
In security/lockdown/lockdown.c (ffffffff828ed670)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - security/lockdown/lockdown.c:lockdown_secfs_init
```
```
In block/ioctl.c (ffffffff814ebb34)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
```
```
In lib/libcrc32c.c (ffffffff828f1918)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - lib/libcrc32c.c:libcrc32c_mod_init
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81598017)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
```
```
In drivers/acpi/acpi_apd.c (ffffffff815dfc2b)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:st_misc_setup
```
```
In drivers/clk/clk.c (ffffffff816461d6)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:of_clk_hw_register
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81651dcf)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff816cbef5)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
```
```
In drivers/base/swnode.c (ffffffff816fc5c6)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_register
```
```
In drivers/base/power/wakeup_stats.c (ffffffff82903ef3)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:wakeup_sources_sysfs_init
```
```
In drivers/nvdimm/bus.c (ffffffff8174519b)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
```
```
In drivers/nvdimm/claim.c (ffffffff81751eaa)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
```
In drivers/net/phy/mdio_bus.c (ffffffff817b2ea8)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817cc538)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8186a81f)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81875a07)
Location: include/linux/err.h:57
Inline: True
```
```
In drivers/power/supply/power_supply_hwmon.c (ffffffff81876a71)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
```
In net/core/flow_offload.c (ffffffff81954fcb)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/core/bpf_sk_storage.c (ffffffff8197a8e4)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
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
In arch/x86/kernel/pcspeaker.c (ffffffff828c052d)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/pcspeaker.c:add_pcspkr
```
```
In arch/x86/kernel/sysfb.c (ffffffff828c0969)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/sysfb.c:sysfb_init
```
```
In kernel/workqueue.c (ffffffff810c2021)
Location: include/linux/err.h:57
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8116875b)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8116baeb)
Location: include/linux/err.h:57
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811b10f9)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/trace/trace.c:instance_mkdir
```
```
In kernel/bpf/xskmap.c (ffffffff81205ae4)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
```
```
In mm/mmap.c (ffffffff81272ff5)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - mm/mmap.c:install_special_mapping
```
```
In fs/sysfs/group.c (ffffffff8139182d)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
```
```
In security/lockdown/lockdown.c (ffffffff828f2a92)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - security/lockdown/lockdown.c:lockdown_secfs_init
```
```
In block/ioctl.c (ffffffff81504b44)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815b2457)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
```
```
In drivers/acpi/acpi_apd.c (ffffffff815f9aeb)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:st_misc_setup
```
```
In drivers/clk/clk.c (ffffffff81660766)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:of_clk_hw_register
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8166c45f)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff816e63c5)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
```
```
In drivers/base/swnode.c (ffffffff81716a36)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_register
```
```
In drivers/base/power/wakeup_stats.c (ffffffff82909c32)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:wakeup_sources_sysfs_init
```
```
In drivers/nvdimm/bus.c (ffffffff817605db)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
```
```
In drivers/nvdimm/claim.c (ffffffff8176d32a)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:devm_nsio_enable
```
```
In drivers/net/phy/mdio_bus.c (ffffffff817cce58)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817e67d8)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff818847af)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/power/supply/power_supply_core.c (ffffffff818913a7)
Location: include/linux/err.h:57
Inline: True
```
```
In drivers/power/supply/power_supply_hwmon.c (ffffffff81892411)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
```
In net/core/flow_offload.c (ffffffff81976fc3)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/core/bpf_sk_storage.c (ffffffff8199ce14)
Location: include/linux/err.h:57
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
```
</details>
</li>
</ul>

## Differences
