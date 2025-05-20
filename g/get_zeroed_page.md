# Function: <code>get_zeroed_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int get_zeroed_page(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81191b80)
Location: mm/page_alloc.c:3277
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/kernel/ldt.c:alloc_ldt_struct
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/init_64.c:spp_getpage
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:alloc_pte_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/swap.c:swsusp_write
  - mm/memory.c:__pud_alloc
  - mm/slub.c:__kmem_cache_create
  - fs/super.c:mount_fs
  - fs/kernfs/symlink.c:kernfs_iop_follow_link
  - fs/ext4/super.c:ext4_calculate_overhead
  - security/selinux/hooks.c:selinux_sb_copy_data
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_disable
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_write_load
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - drivers/xen/events/events_base.c:set_evtchn_to_irq
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/tty/tty_port.c:tty_port_alloc_xmit_buf
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_enable_v2
  - drivers/iommu/amd_iommu.c:alloc_new_range
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/host/ohci-hcd.c:debug_output
  - drivers/power/power_supply_sysfs.c:power_supply_uevent
  - drivers/extcon/extcon.c:extcon_update_state
  - net/core/dev.c:__dev_alloc_name
```
**Symbols:**

```
ffffffff81191b80-ffffffff81191bc3: get_zeroed_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int get_zeroed_page(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811a6760)
Location: mm/page_alloc.c:3745
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/kernel/ldt.c:alloc_ldt_struct
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/init_64.c:spp_getpage
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:alloc_pte_page
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/swap.c:swsusp_write
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
  - mm/memory.c:__pud_alloc
  - mm/slub.c:__kmem_cache_create
  - fs/super.c:mount_fs
  - fs/ext4/super.c:ext4_calculate_overhead
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_copy_data
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_write_load
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - drivers/xen/events/events_base.c:set_evtchn_to_irq
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/tty/tty_port.c:tty_port_alloc_xmit_buf
  - drivers/tty/serial/serial_core.c:uart_startup
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_enable_v2
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/host/ohci-hcd.c:debug_output
  - drivers/power/power_supply_sysfs.c:power_supply_uevent
  - drivers/extcon/extcon.c:extcon_update_state
  - net/core/dev.c:__dev_alloc_name
```
**Symbols:**

```
ffffffff811a6760-ffffffff811a679d: get_zeroed_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int get_zeroed_page(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811b6ac0)
Location: mm/page_alloc.c:3886
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/kernel/ldt.c:alloc_ldt_struct
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/init_64.c:spp_getpage
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:alloc_pte_page
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/swap.c:swsusp_write
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
  - mm/memory.c:__pud_alloc
  - mm/slub.c:__kmem_cache_create
  - fs/super.c:mount_fs
  - fs/ext4/super.c:ext4_calculate_overhead
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_copy_data
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_write_load
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - drivers/xen/events/events_base.c:set_evtchn_to_irq
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/tty/tty_port.c:tty_port_alloc_xmit_buf
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_enable_v2
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/usb/host/ohci-hcd.c:debug_output
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/extcon/extcon.c:extcon_sync
  - net/core/dev.c:__dev_alloc_name
```
**Symbols:**

```
ffffffff811b6ac0-ffffffff811b6ad8: get_zeroed_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int get_zeroed_page(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811be970)
Location: mm/page_alloc.c:4173
Inline: False
Direct callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/kernel/ldt.c:alloc_ldt_struct
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/init_64.c:spp_getpage
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:alloc_pte_page
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/swap.c:swsusp_write
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
  - mm/memory.c:__pud_alloc
  - mm/slub.c:__kmem_cache_create
  - fs/super.c:mount_fs
  - fs/configfs/file.c:configfs_read_file
  - fs/ext4/super.c:ext4_calculate_overhead
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_copy_data
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_write_load
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - security/apparmor/apparmorfs.c:aa_write_access
  - drivers/xen/events/events_base.c:set_evtchn_to_irq
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/tty/tty_port.c:tty_port_alloc_xmit_buf
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_enable_v2
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/host/ohci-hcd.c:debug_output
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/extcon/extcon.c:extcon_sync
  - drivers/ras/cec.c:cec_init
  - net/core/dev.c:__dev_alloc_name
```
**Symbols:**

```
ffffffff811be970-ffffffff811be988: get_zeroed_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int get_zeroed_page(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d36e0)
Location: mm/page_alloc.c:4292
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/kernel/ldt.c:alloc_ldt_struct
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/init_64.c:spp_getpage
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:alloc_pte_page
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/swap.c:swsusp_write
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
  - mm/memory.c:__pud_alloc
  - mm/slub.c:__kmem_cache_create
  - fs/super.c:mount_fs
  - fs/configfs/file.c:configfs_read_file
  - fs/ext4/super.c:ext4_calculate_overhead
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_copy_data
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_write_load
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - security/apparmor/apparmorfs.c:aa_write_access
  - drivers/xen/events/events_base.c:set_evtchn_to_irq
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/tty/tty_port.c:tty_port_alloc_xmit_buf
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_enable_v2
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/host/ohci-hcd.c:debug_output
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/extcon/extcon.c:extcon_sync
  - drivers/ras/cec.c:cec_init
  - net/core/dev.c:dev_alloc_name_ns
```
**Symbols:**

```
ffffffff811d36e0-ffffffff811d36f8: get_zeroed_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int get_zeroed_page(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f4990)
Location: mm/page_alloc.c:4424
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/kernel/ldt.c:alloc_ldt_struct
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/init_64.c:spp_getpage
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:alloc_pte_page
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/swap.c:swsusp_write
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
  - mm/memory.c:__pud_alloc
  - mm/slub.c:__kmem_cache_create
  - fs/super.c:mount_fs
  - fs/configfs/file.c:configfs_read_file
  - fs/ext4/super.c:ext4_calculate_overhead
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_copy_data
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - security/apparmor/apparmorfs.c:aa_write_access
  - drivers/xen/events/events_base.c:set_evtchn_to_irq
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/tty/tty_port.c:tty_port_alloc_xmit_buf
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_enable_v2
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/host/ohci-hcd.c:debug_output
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/extcon/extcon.c:extcon_sync
  - drivers/ras/cec.c:cec_init
  - net/core/dev.c:dev_alloc_name_ns
```
**Symbols:**

```
ffffffff811f4990-ffffffff811f49a8: get_zeroed_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int get_zeroed_page(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81206de0)
Location: mm/page_alloc.c:4598
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/kernel/ldt.c:alloc_ldt_struct
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/init_64.c:spp_getpage
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:alloc_pte_page
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/swap.c:swsusp_write
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
  - mm/memory.c:__pud_alloc
  - mm/slub.c:__kmem_cache_create
  - fs/configfs/file.c:configfs_read_file
  - fs/ext4/super.c:ext4_calculate_overhead
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/apparmor/apparmorfs.c:aa_write_access
  - drivers/xen/events/events_base.c:set_evtchn_to_irq
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/tty/tty_port.c:tty_port_alloc_xmit_buf
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_enable_v2
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/host/ohci-hcd.c:debug_output
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/extcon/extcon.c:extcon_sync
  - drivers/ras/cec.c:cec_init
  - net/core/dev.c:dev_alloc_name_ns
```
**Symbols:**

```
ffffffff81206de0-ffffffff81206df8: get_zeroed_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int get_zeroed_page(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8126ce10)
Location: mm/page_alloc.c:4765
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/kernel/ldt.c:alloc_ldt_struct
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/init_64.c:spp_getpage
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:alloc_pte_page
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/swap.c:swsusp_write
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
  - mm/memory.c:__pud_alloc
  - mm/slub.c:__kmem_cache_create
  - fs/configfs/file.c:configfs_read_file
  - fs/ext4/super.c:ext4_calculate_overhead
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/apparmor/apparmorfs.c:aa_write_access
  - drivers/xen/events/events_base.c:set_evtchn_to_irq
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/tty/tty_port.c:tty_port_alloc_xmit_buf
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_enable_v2
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/host/ohci-hcd.c:debug_output
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/extcon/extcon.c:extcon_sync
  - drivers/ras/cec.c:cec_init
  - net/core/dev.c:dev_alloc_name_ns
```
**Symbols:**

```
ffffffff8126ce10-ffffffff8126ce28: get_zeroed_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int get_zeroed_page(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127bc20)
Location: mm/page_alloc.c:4783
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/kernel/ldt.c:alloc_ldt_struct
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/init_64.c:spp_getpage
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:alloc_pte_page
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/swap.c:swsusp_write
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
  - mm/memory.c:__pud_alloc
  - mm/slub.c:__kmem_cache_create
  - fs/configfs/file.c:configfs_read_file
  - fs/ext4/super.c:ext4_calculate_overhead
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/apparmor/apparmorfs.c:aa_write_access
  - drivers/xen/events/events_base.c:set_evtchn_to_irq
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/tty/tty_port.c:tty_port_alloc_xmit_buf
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_enable_v2
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/host/ohci-hcd.c:debug_output
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/extcon/extcon.c:extcon_sync
  - drivers/ras/cec.c:cec_init
  - net/core/dev.c:dev_alloc_name_ns
```
**Symbols:**

```
ffffffff8127bc20-ffffffff8127bc38: get_zeroed_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int get_zeroed_page(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812ae220)
Location: mm/page_alloc.c:4886
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_setup_vsyscall_time_info
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/kernel/ldt.c:alloc_ldt_struct
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/init_64.c:spp_getpage
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:alloc_pmd_page
  - arch/x86/mm/pat/set_memory.c:alloc_pte_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/swap.c:get_swap_writer
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__p4d_alloc
  - mm/slub.c:__kmem_cache_create
  - fs/configfs/file.c:configfs_read_file
  - fs/ext4/super.c:ext4_calculate_overhead
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/apparmor/apparmorfs.c:aa_write_access
  - drivers/xen/events/events_base.c:set_evtchn_to_irq
  - drivers/xen/xenbus/xenbus_probe.c:xenstored_local_init
  - drivers/tty/tty_port.c:tty_port_alloc_xmit_buf
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/iommu/amd/iommu.c:__get_gcr3_pte
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_enable_v2
  - drivers/iommu/amd/iommu.c:protection_domain_alloc
  - drivers/iommu/amd/iommu.c:increase_address_space
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/usb/host/ohci-hcd.c:debug_output
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/ras/cec.c:cec_init
  - net/core/dev.c:__dev_alloc_name
```
**Symbols:**

```
ffffffff812ae220-ffffffff812ae25a: get_zeroed_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int get_zeroed_page(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812b9b40)
Location: mm/page_alloc.c:5037
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_setup_vsyscall_time_info
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/kernel/ldt.c:alloc_ldt_struct
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/init_64.c:spp_getpage
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:alloc_pmd_page
  - arch/x86/mm/pat/set_memory.c:alloc_pte_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/swap.c:swsusp_write
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__p4d_alloc
  - fs/configfs/file.c:configfs_read_file
  - fs/ext4/super.c:ext4_calculate_overhead
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/apparmor/apparmorfs.c:aa_write_access
  - drivers/xen/events/events_base.c:set_evtchn_to_irq
  - drivers/xen/xenbus/xenbus_probe.c:xenstored_local_init
  - drivers/tty/tty_port.c:tty_port_alloc_xmit_buf
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/iommu/amd/iommu.c:__get_gcr3_pte
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_enable_v2
  - drivers/iommu/amd/iommu.c:protection_domain_alloc
  - drivers/iommu/amd/iommu.c:increase_address_space
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/usb/host/ohci-hcd.c:debug_output
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/ras/cec.c:cec_init
  - net/core/dev.c:__dev_alloc_name
```
**Symbols:**

```
ffffffff812b9b40-ffffffff812b9b7a: get_zeroed_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int get_zeroed_page(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812befb0)
Location: mm/page_alloc.c:5238
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/kernel/ldt.c:alloc_ldt_struct
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/init_64.c:spp_getpage
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:alloc_pmd_page
  - arch/x86/mm/pat/set_memory.c:alloc_pte_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/swap.c:swsusp_write
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__p4d_alloc
  - fs/configfs/file.c:configfs_read_file
  - fs/ext4/super.c:ext4_calculate_overhead
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/apparmor/apparmorfs.c:aa_write_access
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/tty/tty_port.c:tty_port_alloc_xmit_buf
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/iommu/amd/iommu.c:__get_gcr3_pte
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_enable_v2
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_alloc
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/usb/host/ohci-hcd.c:debug_output
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/ras/cec.c:cec_init
  - net/core/dev.c:__dev_alloc_name
```
**Symbols:**

```
ffffffff812befb0-ffffffff812befea: get_zeroed_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int get_zeroed_page(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81301b90)
Location: mm/page_alloc.c:5427
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/kernel/ldt.c:alloc_ldt_struct
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/init_64.c:spp_getpage
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:alloc_pmd_page
  - arch/x86/mm/pat/set_memory.c:alloc_pte_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/swap.c:swsusp_write
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__p4d_alloc
  - fs/configfs/file.c:configfs_read_iter
  - fs/ext4/super.c:ext4_calculate_overhead
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/apparmor/apparmorfs.c:aa_write_access
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/tty/tty_port.c:tty_port_alloc_xmit_buf
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/iommu/amd/iommu.c:__get_gcr3_pte
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_enable_v2
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_alloc
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/usb/host/ohci-hcd.c:debug_output
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/ras/cec.c:cec_init
  - net/core/dev.c:__dev_alloc_name
```
**Symbols:**

```
ffffffff81301b90-ffffffff81301bca: get_zeroed_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int get_zeroed_page(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81369260)
Location: mm/page_alloc.c:5482
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/kernel/ldt.c:alloc_ldt_struct
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/init_64.c:spp_getpage
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:alloc_pmd_page
  - arch/x86/mm/pat/set_memory.c:alloc_pte_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/swap.c:swsusp_write
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/trace/ftrace.c:ftrace_profile_init
  - kernel/trace/ftrace.c:ftrace_profile_init
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__p4d_alloc
  - fs/libfs.c:simple_transaction_get
  - fs/configfs/file.c:configfs_read_iter
  - fs/ext4/super.c:ext4_calculate_overhead
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/apparmor/apparmorfs.c:aa_write_access
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/tty/tty_port.c:tty_port_alloc_xmit_buf
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/iommu/amd/iommu.c:__get_gcr3_pte
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_enable_v2
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_alloc
  - drivers/usb/host/ohci-hcd.c:debug_output
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/extcon/extcon.c:extcon_sync
  - drivers/ras/cec.c:cec_init
  - net/core/dev.c:__dev_alloc_name
```
**Symbols:**

```
ffffffff81369260-ffffffff813692aa: get_zeroed_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int get_zeroed_page(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813e5010)
Location: mm/page_alloc.c:5606
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/kernel/ldt.c:alloc_ldt_struct
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/init_64.c:spp_getpage
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:alloc_pmd_page
  - arch/x86/mm/pat/set_memory.c:alloc_pte_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/swap.c:swsusp_write
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/trace/ftrace.c:ftrace_profile_init
  - kernel/trace/ftrace.c:ftrace_profile_init
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__p4d_alloc
  - fs/libfs.c:simple_transaction_get
  - fs/configfs/file.c:configfs_read_iter
  - fs/ext4/super.c:ext4_calculate_overhead
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/apparmor/apparmorfs.c:aa_write_access
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/tty/tty_port.c:tty_port_alloc_xmit_buf
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/iommu/amd/iommu.c:__get_gcr3_pte
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_enable_v2
  - drivers/iommu/amd/iommu.c:protection_domain_alloc
  - drivers/iommu/amd/iommu.c:protection_domain_alloc
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pgtable
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte
  - drivers/usb/host/ohci-hcd.c:debug_output
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/extcon/extcon.c:extcon_sync
  - drivers/ras/cec.c:cec_init
  - net/core/dev.c:__dev_alloc_name
```
**Symbols:**

```
ffffffff813e5010-ffffffff813e505a: get_zeroed_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int get_zeroed_page(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81419f40)
Location: mm/page_alloc.c:4534
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/kernel/ldt.c:alloc_ldt_struct
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/init_64.c:spp_getpage
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:alloc_pmd_page
  - arch/x86/mm/pat/set_memory.c:alloc_pte_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/swap.c:swsusp_write
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/trace/ftrace.c:ftrace_profile_init
  - kernel/trace/ftrace.c:ftrace_profile_init
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__p4d_alloc
  - fs/libfs.c:simple_transaction_get
  - fs/configfs/file.c:configfs_read_iter
  - fs/ext4/super.c:ext4_calculate_overhead
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/apparmor/apparmorfs.c:aa_write_access
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/tty/tty_port.c:tty_port_alloc_xmit_buf
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/iommu/amd/iommu.c:__get_gcr3_pte
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_enable_v2
  - drivers/iommu/amd/iommu.c:protection_domain_alloc
  - drivers/iommu/amd/iommu.c:protection_domain_alloc
  - drivers/usb/host/ohci-hcd.c:debug_output
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/extcon/extcon.c:extcon_sync
  - drivers/ras/cec.c:cec_init
  - net/core/dev.c:__dev_alloc_name
```
**Symbols:**

```
ffffffff81419f40-ffffffff81419f8a: get_zeroed_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int get_zeroed_page(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81446d50)
Location: mm/page_alloc.c:4623
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/kernel/ldt.c:alloc_ldt_struct
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/init_64.c:spp_getpage
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:alloc_pmd_page
  - arch/x86/mm/pat/set_memory.c:alloc_pte_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/swap.c:swsusp_write
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/trace/ftrace.c:ftrace_profile_init
  - kernel/trace/ftrace.c:ftrace_profile_init
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
  - mm/memory.c:__p4d_alloc
  - fs/libfs.c:simple_transaction_get
  - fs/configfs/file.c:configfs_read_iter
  - fs/ext4/super.c:ext4_calculate_overhead
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/apparmor/apparmorfs.c:aa_write_access
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/tty/tty_port.c:tty_port_alloc_xmit_buf
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/iommu/amd/iommu.c:__get_gcr3_pte
  - drivers/iommu/amd/iommu.c:protection_domain_alloc
  - drivers/usb/host/ohci-hcd.c:debug_output
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/extcon/extcon.c:extcon_sync
  - drivers/ras/cec.c:cec_init
```
**Symbols:**

```
ffffffff81446d50-ffffffff81446d9a: get_zeroed_page (STB_GLOBAL)
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
long unsigned int get_zeroed_page(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010313208)
Location: mm/page_alloc.c:4783
Inline: False
Direct callers:
  - arch/arm64/kernel/vdso.c:aarch32_alloc_vdso_pages
  - arch/arm64/kernel/vdso.c:aarch32_alloc_vdso_pages
  - arch/arm/xen/enlighten.c:xen_guest_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
  - mm/slub.c:__kmem_cache_create
  - fs/configfs/file.c:configfs_read_file
  - fs/ext4/super.c:ext4_calculate_overhead
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/apparmor/apparmorfs.c:aa_write_access
  - drivers/xen/events/events_base.c:set_evtchn_to_irq
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/tty/tty_port.c:tty_port_alloc_xmit_buf
  - drivers/iommu/rockchip-iommu.c:rk_iommu_map
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/host/ohci-hcd.c:debug_output
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/extcon/extcon.c:extcon_sync
  - net/core/dev.c:dev_alloc_name_ns
```
**Symbols:**

```
ffff800010313208-ffff800010313268: get_zeroed_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int get_zeroed_page(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c05339b8)
Location: mm/page_alloc.c:4783
Inline: False
Direct callers:
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/swap.c:swsusp_write
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - mm/slub.c:__kmem_cache_create
  - fs/configfs/file.c:configfs_read_file
  - fs/ext4/super.c:ext4_calculate_overhead
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/apparmor/apparmorfs.c:aa_write_access
  - drivers/tty/tty_port.c:tty_port_alloc_xmit_buf
  - drivers/iommu/rockchip-iommu.c:rk_iommu_map
  - drivers/usb/host/ohci-hcd.c:debug_output
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - net/core/dev.c:dev_alloc_name_ns
```
**Symbols:**

```
c05339b8-c05339dc: get_zeroed_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int get_zeroed_page(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003e4740)
Location: mm/page_alloc.c:4783
Inline: False
Direct callers:
  - arch/powerpc/mm/book3s64/subpage_prot.c:__se_sys_subpage_prot
  - arch/powerpc/mm/book3s64/subpage_prot.c:__se_sys_subpage_prot
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
  - mm/slub.c:__kmem_cache_create
  - fs/configfs/file.c:configfs_read_file
  - fs/ext4/super.c:ext4_calculate_overhead
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/apparmor/apparmorfs.c:aa_write_access
  - drivers/tty/tty_port.c:tty_port_alloc_xmit_buf
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_probe
  - drivers/usb/host/ohci-hcd.c:debug_output
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - net/core/dev.c:dev_alloc_name_ns
```
**Symbols:**

```
c0000000003e4740-c0000000003e4760: get_zeroed_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int get_zeroed_page(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021ecd4)
Location: mm/page_alloc.c:4783
Inline: False
Direct callers:
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - mm/slub.c:__kmem_cache_create
  - fs/configfs/file.c:configfs_read_file
  - fs/ext4/super.c:ext4_calculate_overhead
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/apparmor/apparmorfs.c:aa_write_access
  - drivers/tty/tty_port.c:tty_port_alloc_xmit_buf
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/usb/host/ohci-hcd.c:debug_output
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
```
**Symbols:**

```
ffffffe00021ecd4-ffffffe00021ed02: get_zeroed_page (STB_GLOBAL)
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
long unsigned int get_zeroed_page(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81274270)
Location: mm/page_alloc.c:4783
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/kernel/ldt.c:alloc_ldt_struct
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/init_64.c:spp_getpage
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:alloc_pte_page
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/swap.c:swsusp_write
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
  - mm/memory.c:__pud_alloc
  - mm/slub.c:__kmem_cache_create
  - fs/configfs/file.c:configfs_read_file
  - fs/ext4/super.c:ext4_calculate_overhead
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/apparmor/apparmorfs.c:aa_write_access
  - drivers/xen/events/events_base.c:set_evtchn_to_irq
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/tty/tty_port.c:tty_port_alloc_xmit_buf
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_enable_v2
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/host/ohci-hcd.c:debug_output
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/extcon/extcon.c:extcon_sync
  - drivers/ras/cec.c:cec_init
  - net/core/dev.c:dev_alloc_name_ns
```
**Symbols:**

```
ffffffff81274270-ffffffff81274288: get_zeroed_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int get_zeroed_page(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812661e0)
Location: mm/page_alloc.c:4783
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:alloc_ldt_struct
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/init_64.c:spp_getpage
  - arch/x86/mm/pageattr.c:populate_pgd
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:alloc_pte_page
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/swap.c:swsusp_write
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
  - mm/memory.c:__pud_alloc
  - mm/slub.c:__kmem_cache_create
  - fs/configfs/file.c:configfs_read_file
  - fs/ext4/super.c:ext4_calculate_overhead
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/apparmor/apparmorfs.c:aa_write_access
  - drivers/tty/tty_port.c:tty_port_alloc_xmit_buf
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_enable_v2
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/hv/vmbus_drv.c:hv_acpi_init
  - drivers/hv/hv.c:hv_synic_alloc
  - drivers/hv/hv.c:hv_synic_alloc
  - drivers/hv/hv.c:hv_synic_alloc
  - drivers/ras/cec.c:cec_init
  - net/core/dev.c:dev_alloc_name_ns
```
**Symbols:**

```
ffffffff812661e0-ffffffff812661f8: get_zeroed_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int get_zeroed_page(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81272010)
Location: mm/page_alloc.c:4783
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/kernel/ldt.c:alloc_ldt_struct
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/init_64.c:spp_getpage
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:alloc_pte_page
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/swap.c:swsusp_write
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
  - mm/memory.c:__pud_alloc
  - mm/slub.c:__kmem_cache_create
  - fs/configfs/file.c:configfs_read_file
  - fs/ext4/super.c:ext4_calculate_overhead
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/apparmor/apparmorfs.c:aa_write_access
  - drivers/xen/events/events_base.c:set_evtchn_to_irq
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/tty/tty_port.c:tty_port_alloc_xmit_buf
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_enable_v2
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/host/ohci-hcd.c:debug_output
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/extcon/extcon.c:extcon_sync
  - drivers/ras/cec.c:cec_init
  - net/core/dev.c:dev_alloc_name_ns
```
**Symbols:**

```
ffffffff81272010-ffffffff81272028: get_zeroed_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int get_zeroed_page(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81281a70)
Location: mm/page_alloc.c:4783
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/kernel/ldt.c:alloc_ldt_struct
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/mm/init_64.c:spp_getpage
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:alloc_pte_page
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/swap.c:swsusp_write
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
  - mm/memory.c:__pud_alloc
  - mm/slub.c:__kmem_cache_create
  - fs/configfs/file.c:configfs_read_file
  - fs/ext4/super.c:ext4_calculate_overhead
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/apparmor/apparmorfs.c:aa_write_access
  - drivers/xen/events/events_base.c:set_evtchn_to_irq
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/tty/tty_port.c:tty_port_alloc_xmit_buf
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_enable_v2
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/host/ohci-hcd.c:debug_output
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/extcon/extcon.c:extcon_sync
  - drivers/ras/cec.c:cec_init
  - net/core/dev.c:dev_alloc_name_ns
```
**Symbols:**

```
ffffffff81281a70-ffffffff81281a88: get_zeroed_page (STB_GLOBAL)
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
