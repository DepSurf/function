# Function: <code>IS_ERR_OR_NULL</code>

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
In init/main.c (ffffffff81f59d93)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/kernel/irq.c (ffffffff81030d07)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable
  - arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In arch/x86/kernel/irq_64.c (ffffffff81031145)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - arch/x86/kernel/irq_64.c:handle_irq
```
```
In arch/x86/kernel/irqinit.c (ffffffff810338c5)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:vector_used_by_percpu_irq
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810551ca)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:setup_vector_irq
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
```
```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81f7b2c8)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
```
```
In kernel/power/qos.c (ffffffff81f7e68f)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/power/qos.c:pm_qos_dbg_show_requests
  - kernel/power/qos.c:pm_qos_dbg_show_requests
```
```
In mm/zswap.c (ffffffff811d7ccd)
Location: include/linux/err.h:38
Inline: True
```
```
In mm/ksm.c (ffffffff811e4205)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - mm/ksm.c:break_ksm
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/huge_memory.c (ffffffff811f4557)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
```
```
In fs/namei.c (ffffffff81217beb)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - fs/namei.c:trailing_symlink
  - fs/namei.c:link_path_walk
```
```
In fs/dcache.c (ffffffff81225174)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - fs/dcache.c:prepend_path
```
```
In fs/namespace.c (ffffffff8122d165)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - fs/namespace.c:__detach_mounts
```
```
In fs/posix_acl.c (ffffffff8126e34f)
Location: include/linux/err.h:38
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81278236)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:m_stop
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/proc/base.c (ffffffff8127cb58)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
```
```
In fs/ext4/crypto.c (0)
Location: include/linux/err.h:38
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff81f97370)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
```
```
In fs/debugfs/inode.c (ffffffff8131d745)
Location: include/linux/err.h:38
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff8131f5f5)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:tracefs_remove_recursive
```
```
In security/smack/smack_lsm.c (ffffffff81361228)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/domain.c (ffffffff8137aa42)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
```
```
In security/apparmor/label.c (ffffffff8138d948)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_parse
```
```
In block/genhd.c (ffffffff813caa8b)
Location: include/linux/err.h:38
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff81487d48)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff814881f0)
Location: include/linux/err.h:38
Inline: True
```
```
In drivers/xen/pcpu.c (ffffffff814d2616)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:sync_pcpu
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff814d6182)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:push_pxx_to_hypervisor
  - drivers/xen/xen-acpi-processor.c:push_pxx_to_hypervisor
```
```
In drivers/regulator/core.c (ffffffff814dbbf9)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_put
  - drivers/regulator/core.c:regulator_resolve_supply
```
```
In drivers/tty/tty_io.c (ffffffff814e40dc)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
```
```
In drivers/lightnvm/core.c (ffffffff81542f5a)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_submit_ppa
```
```
In drivers/base/power/qos.c (ffffffff81554b1f)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_flags
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_get_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
```
```
In drivers/block/loop.c (ffffffff8156f5a9)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_attr_do_show_backing_file
```
```
In drivers/mfd/max8997-irq.c (ffffffff81591025)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_sync_unlock
  - drivers/mfd/max8997-irq.c:max8997_irq_init
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81626e9f)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
```
```
In drivers/rtc/interface.c (ffffffff81674445)
Location: include/linux/err.h:38
Inline: True
```
```
In drivers/power/power_supply_core.c (ffffffff8167f196)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/power/power_supply_core.c:power_supply_unregister
  - drivers/power/power_supply_core.c:power_supply_unregister
  - drivers/power/power_supply_core.c:__power_supply_register
  - drivers/power/power_supply_core.c:__power_supply_register
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81fb4a1e)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
```
In drivers/clk/clk.c (ffffffff816e528e)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_register
```
```
In drivers/devfreq/devfreq.c (ffffffff816ec9e6)
Location: include/linux/err.h:38
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff816ee725)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_unregister
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/flow.c (ffffffff817349ad)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_lookup
```
```
In net/netlink/af_netlink.c (ffffffff8174cdfa)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/ip_fragment.c (ffffffff8175980c)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff8175e0c1)
Location: include/linux/err.h:38
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81766a15)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
```
```
In net/ipv4/udp.c (ffffffff817878dd)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/udp_offload.c (ffffffff8178af74)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81794ae8)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/gre_offload.c (ffffffff817a522b)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b534b)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/ipv6/addrconf.c (ffffffff817d0b16)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
```
```
In net/ipv6/udp.c (ffffffff817e28cf)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/reassembly.c (ffffffff817ede06)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
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
In init/main.c (ffffffff81f81d61)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/kernel/irq.c (ffffffff8103011a)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable
  - arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable
```
```
In arch/x86/kernel/irq_64.c (ffffffff81030205)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - arch/x86/kernel/irq_64.c:handle_irq
```
```
In arch/x86/kernel/irqinit.c (ffffffff81032a90)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:vector_used_by_percpu_irq
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81055c59)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
  - arch/x86/kernel/apic/vector.c:setup_vector_irq
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
```
```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81fa3de5)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
```
```
In kernel/power/qos.c (ffffffff81fa757a)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/power/qos.c:pm_qos_dbg_show_requests
  - kernel/power/qos.c:pm_qos_dbg_show_requests
```
```
In kernel/cgroup.c (ffffffff8111faeb)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_mount
```
```
In mm/zswap.c (ffffffff811f5dcd)
Location: include/linux/err.h:38
Inline: True
```
```
In mm/ksm.c (ffffffff812053a4)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:break_ksm
```
```
In mm/khugepaged.c (ffffffff8121b900)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/namei.c (ffffffff8123edbc)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - fs/namei.c:trailing_symlink
  - fs/namei.c:link_path_walk
```
```
In fs/dcache.c (ffffffff8124b88c)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - fs/dcache.c:prepend_path
```
```
In fs/namespace.c (ffffffff81256993)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - fs/namespace.c:__detach_mounts
```
```
In fs/posix_acl.c (ffffffff81299d50)
Location: include/linux/err.h:38
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812a4496)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (ffffffff812a981a)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
```
```
In fs/squashfs/decompressor_multi_percpu.c (ffffffff81325694)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_create
```
```
In fs/hugetlbfs/inode.c (ffffffff81fc1f62)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
```
```
In fs/debugfs/inode.c (ffffffff813521e5)
Location: include/linux/err.h:38
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff81354b45)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
```
```
In security/smack/smack_lsm.c (ffffffff81394c53)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/domain.c (ffffffff813b8441)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
```
In security/apparmor/policy_unpack.c (ffffffff813bc43c)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In security/apparmor/label.c (ffffffff813c8705)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_parse
```
```
In security/apparmor/mount.c (ffffffff813cb677)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
```
```
In block/genhd.c (ffffffff8140ed5b)
Location: include/linux/err.h:38
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8146c63d)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/gpio/gpiolib.c (ffffffff814710db)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_count
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff81474c5f)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find
```
```
In drivers/pci/probe.c (ffffffff8147ccfd)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/pci/quirks.c (ffffffff81490da9)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/pcie/portdrv_acpi.c (ffffffff81495750)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_acpi.c:pcie_port_acpi_setup
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff8149b55f)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8149fd99)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/pci/pci-acpi.c (ffffffff814a4357)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
  - drivers/pci/pci-acpi.c:acpi_pci_sleep_wake
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_power_manageable
  - drivers/pci/pci-acpi.c:pci_get_hp_params
```
```
In drivers/pci/pci-label.c (ffffffff814a4d85)
Location: include/linux/err.h:38
Inline: True
```
```
In drivers/acpi/device_pm.c (ffffffff814cb372)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:to_acpi_device_node
```
```
In drivers/acpi/bus.c (ffffffff814cd3c8)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_companion_match
```
```
In drivers/acpi/glue.c (ffffffff814cd62d)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/acpi/glue.c:is_acpi_device_node
```
```
In drivers/acpi/pci_irq.c (ffffffff814d5c27)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/acpi/acpi_lpss.c (ffffffff814d6bf9)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:to_acpi_device_node
```
```
In drivers/acpi/acpi_apd.c (ffffffff814d709c)
Location: include/linux/err.h:38
Inline: True
```
```
In drivers/acpi/property.c (ffffffff814d9200)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/acpi/property.c:to_acpi_device_node
```
```
In drivers/acpi/fan.c (ffffffff814fa91c)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/acpi/fan.c:is_acpi_device_node
```
```
In drivers/acpi/pci_slot.c (ffffffff814fb2fa)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
```
```
In drivers/acpi/processor_driver.c (ffffffff814fb7c1)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:acpi_processor_start
```
```
In drivers/acpi/container.c (ffffffff814ff275)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/acpi/container.c:acpi_container_offline
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff8150b623)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
```
```
In drivers/dma/dmaengine.c (ffffffff8150d4a9)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
```
```
In drivers/dma/acpi-dma.c (ffffffff8150dfde)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
```
```
In drivers/xen/pci.c (ffffffff815226ba)
Location: include/linux/err.h:38
Inline: True
```
```
In drivers/xen/pcpu.c (ffffffff81523341)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:sync_pcpu
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81526f3a)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:push_pxx_to_hypervisor
  - drivers/xen/xen-acpi-processor.c:push_pxx_to_hypervisor
```
```
In drivers/regulator/core.c (ffffffff8152cde9)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_put
  - drivers/regulator/core.c:regulator_resolve_supply
```
```
In drivers/tty/tty_audit.c (ffffffff8153e1d1)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff8157d126)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
```
In drivers/iommu/amd_iommu.c (ffffffff8158432e)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:get_irq_domain
  - drivers/iommu/amd_iommu.c:get_irq_domain
  - drivers/iommu/amd_iommu.c:amd_iommu_get_dm_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_get_dm_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
  - drivers/iommu/amd_iommu.c:check_device
  - drivers/iommu/amd_iommu.c:check_device
  - drivers/iommu/amd_iommu.c:get_alias
  - drivers/iommu/amd_iommu.c:get_alias
```
```
In drivers/iommu/intel-iommu.c (ffffffff81589ef6)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:device_to_iommu
```
```
In drivers/lightnvm/core.c (ffffffff81594bae)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:__nvm_submit_ppa
```
```
In drivers/base/property.c (ffffffff815a3430)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_dma_attr
  - drivers/base/property.c:device_dma_supported
  - drivers/base/property.c:device_remove_properties
  - drivers/base/property.c:device_remove_properties
  - drivers/base/property.c:fwnode_property_read_string
  - drivers/base/property.c:fwnode_property_read_string
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:__fwnode_property_read_string
  - drivers/base/property.c:__fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_u64_array
  - drivers/base/property.c:fwnode_property_read_u64_array
  - drivers/base/property.c:fwnode_property_read_u32_array
  - drivers/base/property.c:fwnode_property_read_u32_array
  - drivers/base/property.c:fwnode_property_read_u16_array
  - drivers/base/property.c:fwnode_property_read_u16_array
  - drivers/base/property.c:fwnode_property_read_u8_array
  - drivers/base/property.c:fwnode_property_read_u8_array
  - drivers/base/property.c:fwnode_property_present
  - drivers/base/property.c:fwnode_property_present
  - drivers/base/property.c:__fwnode_property_present
```
```
In drivers/base/power/qos.c (ffffffff815a7c67)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_get_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:dev_pm_qos_flags
```
```
In drivers/base/power/domain.c (ffffffff815af575)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:pm_genpd_add_subdomain
  - drivers/base/power/domain.c:pm_genpd_add_subdomain
  - drivers/base/power/domain.c:__pm_genpd_add_device
  - drivers/base/power/domain.c:__pm_genpd_add_device
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:pm_genpd_complete
  - drivers/base/power/domain.c:pm_genpd_restore_noirq
  - drivers/base/power/domain.c:pm_genpd_thaw_noirq
  - drivers/base/power/domain.c:pm_genpd_freeze_noirq
  - drivers/base/power/domain.c:pm_genpd_resume_noirq
  - drivers/base/power/domain.c:pm_genpd_suspend_noirq
  - drivers/base/power/domain.c:pm_genpd_prepare
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:pm_genpd_lookup_dev
  - drivers/base/power/domain.c:pm_genpd_lookup_dev
```
```
In drivers/block/loop.c (ffffffff815c4ec5)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_attr_do_show_backing_file
```
```
In drivers/mfd/mfd-core.c (ffffffff815dfa9f)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/mfd/max8997-irq.c (ffffffff815e5f84)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_init
  - drivers/mfd/max8997-irq.c:max8997_irq_sync_unlock
```
```
In drivers/ata/libata-acpi.c (ffffffff8163ba5d)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_dissociate
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_dev_acpi_handle
```
```
In drivers/ata/libata-zpodd.c (ffffffff8163c2a8)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_init
```
```
In drivers/spi/spi.c (ffffffff81644710)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_acpi_device_match
  - drivers/spi/spi.c:spi_acpi_master_match
  - drivers/spi/spi.c:spi_register_master
  - drivers/spi/spi.c:spi_unregister_device
  - drivers/spi/spi.c:spi_add_device
```
```
In drivers/usb/core/hub.c (ffffffff8166bb8f)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
```
```
In drivers/usb/core/usb-acpi.c (ffffffff8168120d)
Location: include/linux/err.h:38
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8168a9bd)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
```
```
In drivers/usb/host/xhci-pci.c (ffffffff816c279b)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/rtc/interface.c (ffffffff816d4f15)
Location: include/linux/err.h:38
Inline: True
```
```
In drivers/i2c/i2c-core.c (ffffffff816ddc5d)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_register_adapter
  - drivers/i2c/i2c-core.c:i2c_register_adapter
  - drivers/i2c/i2c-core.c:i2c_unregister_device
  - drivers/i2c/i2c-core.c:i2c_new_device
  - drivers/i2c/i2c-core.c:i2c_device_probe
  - drivers/i2c/i2c-core.c:acpi_i2c_match_device
  - drivers/i2c/i2c-core.c:acpi_i2c_match_adapter
  - drivers/i2c/i2c-core.c:acpi_i2c_add_device
```
```
In drivers/power/power_supply_core.c (ffffffff816dfe26)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/power/power_supply_core.c:power_supply_unregister
  - drivers/power/power_supply_core.c:power_supply_unregister
  - drivers/power/power_supply_core.c:__power_supply_register
  - drivers/power/power_supply_core.c:__power_supply_register
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81fe162a)
Location: include/linux/err.h:38
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff8172dca8)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff817474f5)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
```
```
In drivers/clk/clk.c (ffffffff8174cb1d)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_disable
```
```
In drivers/devfreq/devfreq.c (ffffffff817518a6)
Location: include/linux/err.h:38
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff81753845)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_unregister
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/flow.c (ffffffff817a0a5c)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_lookup
```
```
In net/netlink/af_netlink.c (ffffffff817b91db)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/ip_fragment.c (ffffffff817c5bec)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff817ca2f8)
Location: include/linux/err.h:38
Inline: True
```
```
In net/ipv4/udp.c (ffffffff817f503b)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/udp_offload.c (ffffffff817f883c)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81802475)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81812b65)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/xfrm/xfrm_policy.c (ffffffff818236c2)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup
```
```
In net/ipv6/addrconf.c (ffffffff8183eec7)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
```
In net/ipv6/udp.c (ffffffff818509a6)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/reassembly.c (ffffffff8185c645)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
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
In init/main.c (ffffffff81fbddaa)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/kernel/irq.c (ffffffff810300d8)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable
  - arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable
```
```
In arch/x86/kernel/irq_64.c (ffffffff810301b5)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - arch/x86/kernel/irq_64.c:handle_irq
```
```
In arch/x86/kernel/irqinit.c (ffffffff81032705)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:vector_used_by_percpu_irq
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff81043110)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810589f4)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
  - arch/x86/kernel/apic/vector.c:setup_vector_irq
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
```
```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81fdf6ad)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
```
```
In kernel/power/qos.c (ffffffff81fe325c)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/power/qos.c:pm_qos_dbg_show_requests
  - kernel/power/qos.c:pm_qos_dbg_show_requests
```
```
In kernel/cgroup.c (ffffffff81127f2d)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_mount
```
```
In mm/zswap.c (ffffffff81206901)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
  - mm/zswap.c:zswap_cpu_comp_prepare
```
```
In mm/ksm.c (ffffffff81216a76)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:break_ksm
```
```
In mm/khugepaged.c (ffffffff8122d0a7)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/namei.c (ffffffff81251b91)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - fs/namei.c:trailing_symlink
  - fs/namei.c:link_path_walk
```
```
In fs/dcache.c (ffffffff8125e86c)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - fs/dcache.c:prepend_path
```
```
In fs/namespace.c (ffffffff81269996)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - fs/namespace.c:__detach_mounts
```
```
In fs/posix_acl.c (ffffffff812ae870)
Location: include/linux/err.h:38
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812b9df6)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (ffffffff812bf13a)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
```
```
In fs/hugetlbfs/inode.c (ffffffff81ffe97c)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
```
```
In fs/exportfs/expfs.c (ffffffff81356d4b)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/debugfs/inode.c (ffffffff81368495)
Location: include/linux/err.h:38
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff8136ae05)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
```
```
In security/smack/smack_lsm.c (ffffffff813adf3a)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/domain.c (ffffffff813cf82f)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
```
In security/apparmor/label.c (ffffffff813dfd1c)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_parse
```
```
In security/apparmor/mount.c (ffffffff813e2cf7)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
```
```
In block/genhd.c (ffffffff8142a0fb)
Location: include/linux/err.h:38
Inline: True
```
```
In lib/rhashtable.c (ffffffff8146691d)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8148cd6d)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8148e96d)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/gpio/gpiolib.c (ffffffff8149324b)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff814972df)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find
```
```
In drivers/pci/probe.c (ffffffff8149e25d)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/pci/setup-bus.c (ffffffff82007e93)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
```
```
In drivers/pci/quirks.c (ffffffff814b2619)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/pcie/portdrv_acpi.c (ffffffff814b7110)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_acpi.c:pcie_port_acpi_setup
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff814bd13f)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff814c1919)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/pci/pci-acpi.c (ffffffff814c6167)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
  - drivers/pci/pci-acpi.c:acpi_pci_sleep_wake
  - drivers/pci/pci-acpi.c:acpi_pci_get_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_power_manageable
  - drivers/pci/pci-acpi.c:pciehp_is_native
  - drivers/pci/pci-acpi.c:pci_get_hp_params
```
```
In drivers/pci/pci-label.c (ffffffff814c6c05)
Location: include/linux/err.h:38
Inline: True
```
```
In drivers/acpi/device_pm.c (ffffffff814ed29e)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:to_acpi_device_node
```
```
In drivers/acpi/bus.c (ffffffff814ef2f6)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_companion_match
```
```
In drivers/acpi/glue.c (ffffffff814ef56e)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/acpi/glue.c:is_acpi_device_node
```
```
In drivers/acpi/pci_irq.c (ffffffff814f827f)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/acpi/acpi_lpss.c (ffffffff814f925e)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:to_acpi_device_node
```
```
In drivers/acpi/acpi_apd.c (ffffffff814f9726)
Location: include/linux/err.h:38
Inline: True
```
```
In drivers/acpi/property.c (ffffffff814fb98b)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/acpi/property.c:to_acpi_device_node
```
```
In drivers/acpi/fan.c (ffffffff8151d58d)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/acpi/fan.c:is_acpi_device_node
```
```
In drivers/acpi/pci_slot.c (ffffffff8151df8f)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
```
```
In drivers/acpi/processor_driver.c (ffffffff8151e485)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:acpi_processor_start
```
```
In drivers/acpi/container.c (ffffffff81521f6f)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/acpi/container.c:acpi_container_offline
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff8152f843)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
```
```
In drivers/clk/clk.c (ffffffff8153537d)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_disable
```
```
In drivers/dma/dmaengine.c (ffffffff815395d9)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
```
```
In drivers/dma/acpi-dma.c (ffffffff8153a13e)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
```
```
In drivers/xen/pci.c (ffffffff8154eb9a)
Location: include/linux/err.h:38
Inline: True
```
```
In drivers/xen/pcpu.c (ffffffff8154f821)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:sync_pcpu
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff8155348a)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:push_pxx_to_hypervisor
  - drivers/xen/xen-acpi-processor.c:push_pxx_to_hypervisor
```
```
In drivers/regulator/core.c (ffffffff81559449)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_put
  - drivers/regulator/core.c:regulator_resolve_supply
```
```
In drivers/reset/core.c (ffffffff8155cc56)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_status
  - drivers/reset/core.c:reset_control_deassert
  - drivers/reset/core.c:reset_control_assert
  - drivers/reset/core.c:reset_control_reset
```
```
In drivers/tty/tty_audit.c (ffffffff8156a821)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff815a95e6)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
```
In drivers/iommu/amd_iommu.c (ffffffff815b165e)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:get_irq_domain
  - drivers/iommu/amd_iommu.c:get_irq_domain
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
  - drivers/iommu/amd_iommu.c:check_device
  - drivers/iommu/amd_iommu.c:check_device
  - drivers/iommu/amd_iommu.c:get_alias
  - drivers/iommu/amd_iommu.c:get_alias
```
```
In drivers/iommu/intel-iommu.c (ffffffff815b75a6)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:device_to_iommu
```
```
In drivers/lightnvm/core.c (ffffffff815c285e)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:__nvm_submit_ppa
```
```
In drivers/base/platform.c (ffffffff815cdc7d)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_get_irq
```
```
In drivers/base/property.c (ffffffff815d1b40)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_dma_attr
  - drivers/base/property.c:device_dma_supported
  - drivers/base/property.c:device_remove_properties
  - drivers/base/property.c:device_remove_properties
  - drivers/base/property.c:fwnode_property_read_string
  - drivers/base/property.c:fwnode_property_read_string
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:__fwnode_property_read_string
  - drivers/base/property.c:__fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_u64_array
  - drivers/base/property.c:fwnode_property_read_u64_array
  - drivers/base/property.c:fwnode_property_read_u32_array
  - drivers/base/property.c:fwnode_property_read_u32_array
  - drivers/base/property.c:fwnode_property_read_u16_array
  - drivers/base/property.c:fwnode_property_read_u16_array
  - drivers/base/property.c:fwnode_property_read_u8_array
  - drivers/base/property.c:fwnode_property_read_u8_array
  - drivers/base/property.c:fwnode_property_present
  - drivers/base/property.c:fwnode_property_present
  - drivers/base/property.c:__fwnode_property_present
```
```
In drivers/base/power/qos.c (ffffffff815d5fd7)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_get_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:dev_pm_qos_flags
```
```
In drivers/base/power/domain.c (ffffffff815de7d6)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:pm_genpd_add_subdomain
  - drivers/base/power/domain.c:pm_genpd_add_subdomain
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:__pm_genpd_add_device
  - drivers/base/power/domain.c:__pm_genpd_add_device
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:pm_genpd_complete
  - drivers/base/power/domain.c:pm_genpd_restore_noirq
  - drivers/base/power/domain.c:pm_genpd_thaw_noirq
  - drivers/base/power/domain.c:pm_genpd_freeze_noirq
  - drivers/base/power/domain.c:pm_genpd_resume_noirq
  - drivers/base/power/domain.c:pm_genpd_suspend_noirq
  - drivers/base/power/domain.c:pm_genpd_prepare
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
```
```
In drivers/block/loop.c (ffffffff815f35f5)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_attr_do_show_backing_file
```
```
In drivers/mfd/mfd-core.c (ffffffff8160c73f)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/mfd/max8997-irq.c (ffffffff81612e34)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_init
  - drivers/mfd/max8997-irq.c:max8997_irq_sync_unlock
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816221af)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
```
In drivers/ata/libata-acpi.c (ffffffff8166cadd)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_dissociate
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_dev_acpi_handle
```
```
In drivers/ata/libata-zpodd.c (ffffffff8166d328)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_init
```
```
In drivers/spi/spi.c (ffffffff816757e0)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_acpi_device_match
  - drivers/spi/spi.c:spi_acpi_master_match
  - drivers/spi/spi.c:spi_register_master
  - drivers/spi/spi.c:spi_unregister_device
  - drivers/spi/spi.c:spi_add_device
```
```
In drivers/usb/core/hub.c (ffffffff8169988f)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
```
```
In drivers/usb/core/usb-acpi.c (ffffffff816aef3d)
Location: include/linux/err.h:38
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (ffffffff816b8ae0)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
```
```
In drivers/usb/host/xhci-pci.c (ffffffff816f075b)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff816ffcb1)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
```
```
In drivers/rtc/interface.c (ffffffff81704e25)
Location: include/linux/err.h:38
Inline: True
```
```
In drivers/i2c/i2c-core.c (ffffffff8170dfd2)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_register_adapter
  - drivers/i2c/i2c-core.c:i2c_register_adapter
  - drivers/i2c/i2c-core.c:i2c_unregister_device
  - drivers/i2c/i2c-core.c:i2c_new_device
  - drivers/i2c/i2c-core.c:i2c_device_probe
  - drivers/i2c/i2c-core.c:i2c_acpi_match_device
  - drivers/i2c/i2c-core.c:i2c_acpi_match_adapter
  - drivers/i2c/i2c-core.c:i2c_acpi_find_bus_speed
  - drivers/i2c/i2c-core.c:i2c_acpi_get_info
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81710296)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8201f381)
Location: include/linux/err.h:38
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81760c68)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
```
In drivers/devfreq/devfreq.c (ffffffff8177d676)
Location: include/linux/err.h:38
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff8177f8b5)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_unregister
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/flow.c (ffffffff817cf69e)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_lookup
```
```
In net/ipv4/ip_fragment.c (ffffffff817f56ec)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff817f9f17)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/udp.c (ffffffff81826108)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/udp_offload.c (ffffffff818296ec)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81833400)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/gre_offload.c (ffffffff8184405e)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/xfrm/xfrm_policy.c (ffffffff81855012)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup
```
```
In net/ipv6/addrconf.c (ffffffff81870ada)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
```
In net/ipv6/udp.c (ffffffff818827f5)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/reassembly.c (ffffffff8188e555)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/ip6_offload.c (ffffffff818a6edf)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
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
In init/main.c (ffffffff8209deab)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/kernel/irq.c (ffffffff8102e37e)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable
  - arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable
```
```
In arch/x86/kernel/irq_64.c (ffffffff8102e415)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - arch/x86/kernel/irq_64.c:handle_irq
```
```
In arch/x86/kernel/irqinit.c (ffffffff81030943)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:vector_used_by_percpu_irq
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff8104126a)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8190ebc7)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
  - arch/x86/kernel/apic/vector.c:setup_vector_irq
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
```
```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff820c0451)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
```
```
In kernel/power/qos.c (ffffffff820c3c61)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/power/qos.c:pm_qos_dbg_show_requests
  - kernel/power/qos.c:pm_qos_dbg_show_requests
```
```
In kernel/irq/irqdomain.c (ffffffff810ec693)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8112ac7d)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
```
In mm/zswap.c (ffffffff81212021)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
  - mm/zswap.c:zswap_cpu_comp_prepare
```
```
In mm/ksm.c (ffffffff8122247f)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:break_ksm
```
```
In mm/khugepaged.c (ffffffff812397f5)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/namei.c (ffffffff8125d505)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - fs/namei.c:trailing_symlink
  - fs/namei.c:link_path_walk
```
```
In fs/dcache.c (ffffffff8126c087)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - fs/dcache.c:prepend_path
```
```
In fs/namespace.c (ffffffff81277136)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - fs/namespace.c:__detach_mounts
```
```
In fs/posix_acl.c (ffffffff812bbc01)
Location: include/linux/err.h:38
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812c7046)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (ffffffff812cd1b8)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
```
```
In fs/hugetlbfs/inode.c (ffffffff820e1be6)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
```
```
In fs/exportfs/expfs.c (ffffffff8136b93f)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/debugfs/inode.c (ffffffff8137caf5)
Location: include/linux/err.h:38
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff8137f455)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
```
```
In security/smack/smack_lsm.c (ffffffff813c2e7b)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/apparmorfs.c (ffffffff813d9197)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:remove_rawdata_dents
```
```
In security/apparmor/domain.c (ffffffff813e3471)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
```
In security/apparmor/label.c (ffffffff813ef37a)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_parse
```
```
In security/apparmor/mount.c (ffffffff813f12d3)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
```
```
In block/genhd.c (ffffffff814383fb)
Location: include/linux/err.h:38
Inline: True
```
```
In lib/rhashtable.c (ffffffff8146c162)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In drivers/pinctrl/core.c (ffffffff8148f159)
Location: include/linux/err.h:38
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8149666d)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff814970fe)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/gpio/gpiolib.c (ffffffff8149e104)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff814a0f7f)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_find
```
```
In drivers/pci/setup-bus.c (ffffffff820e8f5a)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
```
```
In drivers/pci/quirks.c (ffffffff814bc909)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
```
```
In drivers/pci/pcie/portdrv_acpi.c (ffffffff814c1a51)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_acpi.c:pcie_port_acpi_setup
```
```
In drivers/pci/hotplug/acpi_pcihp.c (ffffffff814c7910)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff814cbef8)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/pci/pci-acpi.c (ffffffff814d0133)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_cleanup
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_find_companion
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:acpi_pci_need_resume
  - drivers/pci/pci-acpi.c:acpi_pci_get_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/pci-acpi.c:acpi_pci_power_manageable
  - drivers/pci/pci-acpi.c:pciehp_is_native
  - drivers/pci/pci-acpi.c:pci_get_hp_params
```
```
In drivers/pci/pci-label.c (ffffffff814d0b75)
Location: include/linux/err.h:38
Inline: True
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff814d1a75)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_remove_epf_group
```
```
In drivers/acpi/device_pm.c (ffffffff814fa89c)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/device_pm.c:acpi_dev_pm_detach
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
  - drivers/acpi/device_pm.c:acpi_dev_resume_early
  - drivers/acpi/device_pm.c:acpi_dev_suspend_late
  - drivers/acpi/device_pm.c:acpi_dev_runtime_resume
  - drivers/acpi/device_pm.c:acpi_dev_runtime_suspend
  - drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup
  - drivers/acpi/device_pm.c:acpi_pm_device_sleep_state
  - drivers/acpi/device_pm.c:acpi_pm_device_can_wakeup
```
```
In drivers/acpi/bus.c (ffffffff814fc2b3)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_companion_match
```
```
In drivers/acpi/glue.c (ffffffff814fc933)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_platform_notify_remove
  - drivers/acpi/glue.c:acpi_platform_notify
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/acpi/pci_irq.c (ffffffff81506fdc)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815077bc)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_bind
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend_late
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/acpi_lpss.c:acpi_lpss_set_ltr
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff815087c5)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
```
```
In drivers/acpi/property.c (ffffffff8150b575)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
```
```
In drivers/acpi/fan.c (ffffffff8152e8af)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/pci_slot.c (ffffffff8152eff3)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
```
```
In drivers/acpi/processor_driver.c (ffffffff8152f633)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:acpi_processor_stop
  - drivers/acpi/processor_driver.c:acpi_processor_start
```
```
In drivers/acpi/container.c (ffffffff81533a53)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/acpi/container.c:acpi_container_offline
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff815428f3)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/pnp/pnpacpi/core.c:pnpacpi_disable_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
```
```
In drivers/clk/clk.c (ffffffff81548794)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_disable
```
```
In drivers/dma/dmaengine.c (ffffffff8154cef9)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
```
```
In drivers/dma/acpi-dma.c (ffffffff8154d998)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
```
```
In drivers/xen/pci.c (ffffffff8156310f)
Location: include/linux/err.h:38
Inline: True
```
```
In drivers/xen/pcpu.c (ffffffff81563fb4)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:sync_pcpu
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81567df7)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:push_pxx_to_hypervisor
  - drivers/xen/xen-acpi-processor.c:push_pxx_to_hypervisor
```
```
In drivers/regulator/core.c (ffffffff8156ceb9)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_put
  - drivers/regulator/core.c:regulator_resolve_supply
```
```
In drivers/reset/core.c (ffffffff8157171d)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_control_release
```
```
In drivers/tty/tty_audit.c (ffffffff8157ee35)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff815bef2d)
Location: include/linux/err.h:38
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff815c8087)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:get_irq_domain
  - drivers/iommu/amd_iommu.c:get_irq_domain
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
  - drivers/iommu/amd_iommu.c:get_alias
  - drivers/iommu/amd_iommu.c:get_alias
```
```
In drivers/iommu/intel-iommu.c (ffffffff815cd420)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:device_to_iommu
```
```
In drivers/base/platform.c (ffffffff815e26ad)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_get_irq
```
```
In drivers/base/property.c (ffffffff815e6900)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_dma_attr
  - drivers/base/property.c:device_dma_supported
  - drivers/base/property.c:device_get_next_child_node
  - drivers/base/property.c:device_remove_properties
  - drivers/base/property.c:device_remove_properties
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_int_array
  - drivers/base/property.c:fwnode_property_read_int_array
  - drivers/base/property.c:pset_fwnode_property_read_string_array
  - drivers/base/property.c:pset_fwnode_read_int_array
  - drivers/base/property.c:pset_fwnode_property_present
```
```
In drivers/base/power/qos.c (ffffffff815ea9f7)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_get_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:dev_pm_qos_flags
```
```
In drivers/base/power/domain.c (ffffffff815f3356)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:pm_genpd_add_subdomain
  - drivers/base/power/domain.c:pm_genpd_add_subdomain
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:__pm_genpd_add_device
  - drivers/base/power/domain.c:__pm_genpd_add_device
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:pm_genpd_complete
  - drivers/base/power/domain.c:pm_genpd_restore_noirq
  - drivers/base/power/domain.c:pm_genpd_thaw_noirq
  - drivers/base/power/domain.c:pm_genpd_freeze_noirq
  - drivers/base/power/domain.c:pm_genpd_resume_noirq
  - drivers/base/power/domain.c:genpd_finish_suspend
  - drivers/base/power/domain.c:pm_genpd_prepare
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
```
```
In drivers/base/dma-mapping.c (ffffffff815f635c)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dma_configure
```
```
In drivers/block/loop.c (ffffffff81607971)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_attr_do_show_backing_file
```
```
In drivers/mfd/mfd-core.c (ffffffff8162081d)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/mfd/max8997-irq.c (ffffffff81626ea2)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_init
  - drivers/mfd/max8997-irq.c:max8997_irq_sync_unlock
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81636b5c)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
```
In drivers/ata/libata-acpi.c (ffffffff816810ea)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_set_state
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_stm
  - drivers/ata/libata-acpi.c:ata_acpi_gtm
  - drivers/ata/libata-acpi.c:ata_acpi_dissociate
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
  - drivers/ata/libata-acpi.c:ata_dev_acpi_handle
```
```
In drivers/ata/libata-zpodd.c (ffffffff81681968)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_init
```
```
In drivers/spi/spi.c (ffffffff81689f20)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_acpi_device_match
  - drivers/spi/spi.c:spi_acpi_controller_match
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_unregister_device
  - drivers/spi/spi.c:spi_add_device
```
```
In drivers/usb/core/hub.c (ffffffff816aebcd)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
```
```
In drivers/usb/core/usb-acpi.c (ffffffff816c403f)
Location: include/linux/err.h:38
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (ffffffff816cce20)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
```
```
In drivers/usb/host/xhci-pci.c (ffffffff81705fe6)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817155c1)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
```
```
In drivers/rtc/interface.c (ffffffff8171a905)
Location: include/linux/err.h:38
Inline: True
```
```
In drivers/rtc/nvmem.c (ffffffff8171b56c)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/rtc/nvmem.c:rtc_nvmem_unregister
  - drivers/rtc/nvmem.c:rtc_nvmem_register
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8171f030)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_unregister_device
  - drivers/i2c/i2c-core-base.c:i2c_new_device
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81724cdd)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_match_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_match_adapter
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_bus_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff817271f3)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/i2c/busses/i2c-designware-baytrail.c (ffffffff81727d9c)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support
```
```
In drivers/power/supply/power_supply_core.c (ffffffff817286c6)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8176c492)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_unregister_driver
  - drivers/cpufreq/intel_pstate.c:intel_pstate_register_driver
```
```
In drivers/cpuidle/governors/menu.c (ffffffff8176ff1f)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff8177f4a8)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
```
In drivers/platform/x86/silead_dmi.c (ffffffff81798a2c)
Location: include/linux/err.h:38
Inline: True
```
```
In drivers/devfreq/devfreq.c (ffffffff8179c1e6)
Location: include/linux/err.h:38
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff8179ef0f)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/flow.c (ffffffff817ee841)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_lookup
```
```
In net/ipv4/ip_fragment.c (ffffffff81815b8a)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff8181a2f9)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/udp.c (ffffffff818468d5)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/udp_offload.c (ffffffff8184a6fd)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81854778)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/gre_offload.c (ffffffff818658d6)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/xfrm/xfrm_policy.c (ffffffff81878a30)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup
```
```
In net/ipv6/addrconf.c (ffffffff8189584f)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
```
In net/ipv6/udp.c (ffffffff818a90c5)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/reassembly.c (ffffffff818b4ba2)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/ip6_offload.c (ffffffff818cd934)
Location: include/linux/err.h:38
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
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
In init/main.c (ffffffff826a3e77)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/kernel/irq.c (ffffffff810301fe)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In arch/x86/kernel/irq_64.c (ffffffff81030295)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/irq_64.c:handle_irq
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff8104465a)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8105b6b7)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff826c8630)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
```
```
In kernel/power/qos.c (ffffffff826cbeb0)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/power/qos.c:pm_qos_dbg_show_requests
  - kernel/power/qos.c:pm_qos_dbg_show_requests
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81137a13)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
```
In mm/zswap.c (ffffffff8122c9f1)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
  - mm/zswap.c:zswap_cpu_comp_prepare
```
```
In mm/ksm.c (ffffffff8123d7bc)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:break_ksm
```
```
In mm/khugepaged.c (ffffffff81257f98)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/namei.c (ffffffff8127f888)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/namei.c:trailing_symlink
  - fs/namei.c:link_path_walk
```
```
In fs/dcache.c (ffffffff8128f977)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/dcache.c:prepend_path
```
```
In fs/namespace.c (ffffffff81299b76)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/namespace.c:__detach_mounts
```
```
In fs/posix_acl.c (ffffffff812df4f1)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812ebeea)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (ffffffff812f1a58)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
```
```
In fs/hugetlbfs/inode.c (ffffffff826ea86a)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
```
```
In fs/exportfs/expfs.c (ffffffff813904b2)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/debugfs/inode.c (ffffffff813a1a15)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff813a44a5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
```
```
In security/smack/smack_lsm.c (ffffffff813e913b)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/apparmorfs.c (ffffffff813ff207)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:remove_rawdata_dents
```
```
In security/apparmor/domain.c (ffffffff8140a267)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
```
In security/apparmor/label.c (ffffffff81417197)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_parse
```
```
In security/apparmor/mount.c (ffffffff814192fe)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
```
```
In block/genhd.c (ffffffff81463f3b)
Location: include/linux/err.h:39
Inline: True
```
```
In lib/rhashtable.c (ffffffff81498465)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In drivers/pinctrl/core.c (ffffffff814cb2b9)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff81511d25)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_remove_epf_group
```
```
In drivers/acpi/acpi_lpss.c (ffffffff8154a728)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff8154aba5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
```
```
In drivers/acpi/property.c (ffffffff8154e328)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_device_data_of_node
```
```
In drivers/clk/clk.c (ffffffff815abc36)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_disable
```
```
In drivers/xen/pcpu.c (ffffffff815c8104)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:sync_pcpu
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff815cbfb7)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:push_pxx_to_hypervisor
  - drivers/xen/xen-acpi-processor.c:push_pxx_to_hypervisor
```
```
In drivers/regulator/core.c (ffffffff815d1129)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_put
  - drivers/regulator/core.c:regulator_resolve_supply
```
```
In drivers/reset/core.c (ffffffff815d5bf5)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/tty/tty_audit.c (ffffffff815e39a5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
```
```
In drivers/base/property.c (ffffffff8164d8a6)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/property.c:device_remove_properties
  - drivers/base/property.c:device_remove_properties
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_int_array
  - drivers/base/property.c:fwnode_property_read_int_array
  - drivers/base/property.c:pset_fwnode_property_read_string_array
  - drivers/base/property.c:pset_fwnode_read_int_array
  - drivers/base/property.c:pset_fwnode_property_present
```
```
In drivers/base/power/qos.c (ffffffff81651da7)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_get_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:dev_pm_qos_flags
```
```
In drivers/base/power/domain.c (ffffffff8165ab36)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:pm_genpd_add_subdomain
  - drivers/base/power/domain.c:pm_genpd_add_subdomain
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:__pm_genpd_add_device
  - drivers/base/power/domain.c:__pm_genpd_add_device
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_restore_noirq
  - drivers/base/power/domain.c:genpd_thaw_noirq
  - drivers/base/power/domain.c:genpd_freeze_noirq
  - drivers/base/power/domain.c:genpd_resume_noirq
  - drivers/base/power/domain.c:genpd_finish_suspend
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/block/loop.c (ffffffff8167000e)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_attr_do_show_backing_file
```
```
In drivers/mfd/max8997-irq.c (ffffffff8168f772)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_init
  - drivers/mfd/max8997-irq.c:max8997_irq_sync_unlock
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8169e877)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81739410)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81774ead)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817867e1)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
```
```
In drivers/rtc/interface.c (ffffffff8178bba5)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/rtc/nvmem.c (ffffffff8178c80c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/rtc/nvmem.c:rtc_nvmem_unregister
  - drivers/rtc/nvmem.c:rtc_nvmem_register
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81799088)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81799dc6)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
```
In drivers/opp/core.c (ffffffff817d5cb7)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
```
```
In drivers/cpuidle/governors/ladder.c (ffffffff817e55ed)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/cpuidle/governors/ladder.c:ladder_select_state
```
```
In drivers/cpuidle/governors/menu.c (ffffffff817e583e)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/cpuidle/governors/menu.c:menu_select
```
```
In drivers/devfreq/devfreq.c (ffffffff81812576)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:find_devfreq_governor
```
```
In drivers/extcon/extcon.c (ffffffff8181606e)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/ipv4/ip_fragment.c (ffffffff81894d61)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/ip_output.c (ffffffff81898941)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/udp.c (ffffffff818c6308)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/udp_offload.c (ffffffff818ca37d)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff818d461c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/gre_offload.c (ffffffff818e5a19)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/addrconf.c (ffffffff81916cf5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
```
In net/ipv6/udp.c (ffffffff8192beff)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/reassembly.c (ffffffff81937912)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/ip6_offload.c (ffffffff8195272a)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
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
In init/main.c (ffffffff826ccf16)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/kernel/irq.c (ffffffff8103146e)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In arch/x86/kernel/irq_64.c (ffffffff81031525)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/irq_64.c:handle_irq
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff8104689f)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8105e614)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff826f27b0)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
```
```
In kernel/power/qos.c (ffffffff826f601c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/power/qos.c:pm_qos_dbg_show_requests
  - kernel/power/qos.c:pm_qos_dbg_show_requests
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8114625a)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
```
In kernel/trace/trace_events_hist.c (ffffffff811a35ba)
Location: include/linux/err.h:39
Inline: True
```
```
In mm/zswap.c (ffffffff8124f671)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
  - mm/zswap.c:zswap_cpu_comp_prepare
```
```
In mm/ksm.c (ffffffff81260ddd)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:break_ksm
```
```
In mm/khugepaged.c (ffffffff8127da17)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/namei.c (ffffffff812a6da6)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/namei.c:trailing_symlink
  - fs/namei.c:link_path_walk
```
```
In fs/namespace.c (ffffffff812bfa16)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/namespace.c:__detach_mounts
```
```
In fs/d_path.c (ffffffff812d3a49)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/posix_acl.c (ffffffff8130b4c4)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81319842)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (ffffffff8131e89b)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
```
```
In fs/hugetlbfs/inode.c (ffffffff82714cf6)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
```
```
In fs/exportfs/expfs.c (ffffffff813bf557)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/debugfs/inode.c (ffffffff813d0e45)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff813d3855)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
```
```
In fs/pstore/platform.c (ffffffff813d452c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_unregister
  - fs/pstore/platform.c:pstore_register
```
```
In security/smack/smack_lsm.c (ffffffff8141a005)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/apparmorfs.c (ffffffff81430197)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:remove_rawdata_dents
```
```
In security/apparmor/domain.c (ffffffff8143b8db)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
```
In security/apparmor/label.c (ffffffff81449615)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_strn_parse
```
```
In security/apparmor/mount.c (ffffffff8144b6f5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
```
```
In crypto/api.c (ffffffff81458884)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In block/genhd.c (ffffffff814976fb)
Location: include/linux/err.h:39
Inline: True
```
```
In lib/rhashtable.c (ffffffff814cd645)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In drivers/pinctrl/core.c (ffffffff814fc239)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff81546ed5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_remove_epf_group
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815472f5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msi
```
```
In drivers/video/backlight/backlight.c (0)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff81580d22)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff81581244)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
```
```
In drivers/acpi/property.c (ffffffff81584818)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
```
```
In drivers/clk/clk.c (ffffffff815e3c2a)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_disable
```
```
In drivers/xen/pcpu.c (ffffffff81600941)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:sync_pcpu
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff816045ef)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:push_pxx_to_hypervisor
  - drivers/xen/xen-acpi-processor.c:push_pxx_to_hypervisor
```
```
In drivers/regulator/core.c (ffffffff816093e9)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_put
  - drivers/regulator/core.c:regulator_resolve_supply
```
```
In drivers/reset/core.c (ffffffff8160ec85)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/tty/tty_audit.c (ffffffff8161ce21)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
```
```
In drivers/base/property.c (ffffffff8168929f)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/property.c:device_remove_properties
  - drivers/base/property.c:device_remove_properties
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_int_array
  - drivers/base/property.c:fwnode_property_read_int_array
  - drivers/base/property.c:pset_fwnode_property_read_string_array
  - drivers/base/property.c:pset_fwnode_read_int_array
  - drivers/base/property.c:pset_fwnode_property_present
```
```
In drivers/base/power/qos.c (ffffffff8168d687)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_get_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:dev_pm_qos_flags
```
```
In drivers/base/power/domain.c (ffffffff81696777)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:pm_genpd_add_subdomain
  - drivers/base/power/domain.c:pm_genpd_add_subdomain
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_add_device
  - drivers/base/power/domain.c:pm_genpd_add_device
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_restore_noirq
  - drivers/base/power/domain.c:genpd_thaw_noirq
  - drivers/base/power/domain.c:genpd_freeze_noirq
  - drivers/base/power/domain.c:genpd_resume_noirq
  - drivers/base/power/domain.c:genpd_finish_suspend
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/block/loop.c (ffffffff816abae6)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_attr_do_show_backing_file
```
```
In drivers/mfd/max8997-irq.c (ffffffff816cb86d)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_init
  - drivers/mfd/max8997-irq.c:max8997_irq_sync_unlock
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816daa23)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/usb/core/phy.c (0)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817794c0)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817c7819)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
```
```
In drivers/rtc/interface.c (ffffffff817cd125)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/rtc/nvmem.c (ffffffff817cee74)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/rtc/nvmem.c:rtc_nvmem_unregister
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff817db629)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/power/supply/power_supply_core.c (ffffffff817e1061)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff817ef5de)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
```
In drivers/opp/core.c (ffffffff8181e949)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
```
```
In drivers/cpuidle/governor.c (ffffffff8182ddca)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/cpuidle/governor.c:cpuidle_governor_latency_req
```
```
In drivers/devfreq/devfreq.c (ffffffff8185c475)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:find_devfreq_governor
```
```
In drivers/extcon/extcon.c (ffffffff8185ff3e)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/filter.c (ffffffff818b4c2f)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv4/ip_output.c (ffffffff818ed6ad)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/udp.c (ffffffff8191c14d)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/udp_offload.c (ffffffff81920d6f)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff8192aced)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/gre_offload.c (ffffffff8193c2cb)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/addrconf.c (ffffffff8196e3a4)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
```
In net/ipv6/udp.c (ffffffff81984415)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/ip6_offload.c (ffffffff819abcf9)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
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
In init/main.c (ffffffff82882ef7)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/kernel/irq.c (ffffffff8103270e)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In arch/x86/kernel/irq_64.c (ffffffff810327c5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/irq_64.c:handle_irq
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81055830)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105723b)
Location: include/linux/err.h:39
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8105bab7)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105d6df)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810642a4)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff828a9593)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
```
```
In kernel/power/qos.c (ffffffff828acf2d)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/power/qos.c:pm_qos_debug_show
  - kernel/power/qos.c:pm_qos_debug_show
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81151e00)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
```
```
In kernel/relay.c (ffffffff8117b26c)
Location: include/linux/err.h:39
Inline: True
```
```
In kernel/trace/trace_events_hist.c (ffffffff811b1f66)
Location: include/linux/err.h:39
Inline: True
```
```
In mm/zswap.c (ffffffff81263d61)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
  - mm/zswap.c:zswap_cpu_comp_prepare
```
```
In mm/ksm.c (ffffffff812755b4)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:break_ksm
```
```
In mm/khugepaged.c (ffffffff812914f5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/namei.c (ffffffff812bbfd1)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/namei.c:trailing_symlink
```
```
In fs/namespace.c (ffffffff812d4c16)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/namespace.c:__detach_mounts
```
```
In fs/d_path.c (ffffffff812e8c99)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/posix_acl.c (ffffffff81320f04)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81330469)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (ffffffff8133598b)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
```
```
In fs/hugetlbfs/inode.c (ffffffff828cc14f)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
```
```
In fs/exportfs/expfs.c (ffffffff813d8bb0)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/debugfs/inode.c (ffffffff813eb5b5)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff813edee5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
```
```
In fs/pstore/platform.c (ffffffff813eec07)
Location: include/linux/err.h:39
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff814367d7)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/apparmorfs.c (ffffffff8144cce7)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:remove_rawdata_dents
```
```
In security/apparmor/domain.c (ffffffff81458732)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
```
In security/apparmor/label.c (ffffffff814665a5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_strn_parse
```
```
In security/apparmor/mount.c (ffffffff81468665)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
```
```
In crypto/api.c (ffffffff81475cc4)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In block/genhd.c (ffffffff814b161b)
Location: include/linux/err.h:39
Inline: True
```
```
In block/blk-mq-debugfs.c (ffffffff814cf4b8)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
```
In lib/rhashtable.c (ffffffff814e1845)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In drivers/pinctrl/core.c (ffffffff81511149)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/gpio/gpiolib-devres.c (ffffffff81521685)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff8155d705)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_remove_epf_group
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff8155d7c5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msix
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msi
```
```
In drivers/video/backlight/backlight.c (0)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff81598987)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff81599114)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
```
```
In drivers/acpi/property.c (ffffffff8159cffd)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
```
```
In drivers/clk/clk-bulk.c (ffffffff815f8215)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/clk/clk.c (ffffffff815fe00a)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_disable
```
```
In drivers/xen/pcpu.c (ffffffff8161ba11)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:sync_pcpu
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff8161f949)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:push_pxx_to_hypervisor
  - drivers/xen/xen-acpi-processor.c:push_pxx_to_hypervisor
```
```
In drivers/regulator/core.c (ffffffff816257c9)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_put
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:set_machine_constraints
```
```
In drivers/reset/core.c (ffffffff8162b865)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/tty/tty_audit.c (ffffffff8163a0a9)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
```
```
In drivers/base/platform.c (ffffffff816a58b9)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_device_unregister
```
```
In drivers/base/property.c (ffffffff816a8652)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_int_array
  - drivers/base/property.c:fwnode_property_read_int_array
```
```
In drivers/base/swnode.c (ffffffff816aab3e)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_parent
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:software_node_put
  - drivers/base/swnode.c:software_node_get
```
```
In drivers/base/power/qos.c (ffffffff816ad8d7)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_get_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:dev_pm_qos_flags
```
```
In drivers/base/power/domain.c (ffffffff816b7107)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:pm_genpd_add_subdomain
  - drivers/base/power/domain.c:pm_genpd_add_subdomain
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_add_device
  - drivers/base/power/domain.c:pm_genpd_add_device
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_restore_noirq
  - drivers/base/power/domain.c:genpd_thaw_noirq
  - drivers/base/power/domain.c:genpd_freeze_noirq
  - drivers/base/power/domain.c:genpd_resume_noirq
  - drivers/base/power/domain.c:genpd_finish_suspend
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/block/loop.c (ffffffff816ccc17)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_attr_do_show_backing_file
```
```
In drivers/mfd/max8997-irq.c (ffffffff816ece1d)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_init
  - drivers/mfd/max8997-irq.c:max8997_irq_sync_unlock
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816fc9b7)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/spi/spi-mem.c (ffffffff8175694d)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8179f290)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817eeeb9)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
```
```
In drivers/rtc/interface.c (ffffffff817f4495)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff818029d9)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/media/cec/cec-core.c (ffffffff828ecb9b)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/media/cec/cec-core.c:cec_devnode_release
```
```
In drivers/media/cec/cec-adap.c (ffffffff81806677)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8180c6e1)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8181b4ab)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
```
In drivers/opp/core.c (ffffffff8184a7b4)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
```
```
In drivers/cpuidle/governor.c (ffffffff81859f8a)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/cpuidle/governor.c:cpuidle_governor_latency_req
```
```
In drivers/devfreq/devfreq.c (ffffffff8187b9b5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:find_devfreq_governor
```
```
In drivers/extcon/extcon.c (ffffffff8187f8cb)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/filter.c (ffffffff818da7ef)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/sched/cls_api.c (ffffffff818ffe55)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_release
```
```
In net/ipv4/ip_output.c (ffffffff8191a1aa)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/udp.c (ffffffff8194a6ea)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/udp_offload.c (ffffffff8194f8dc)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff8195a46e)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/gre_offload.c (ffffffff8196bfcc)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/addrconf.c (ffffffff819a3fc1)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
```
In net/ipv6/udp.c (ffffffff819ba942)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/ip6_offload.c (ffffffff819e28ac)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
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
In init/main.c (ffffffff82899e81)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/kernel/irq.c (ffffffff81034420)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In arch/x86/kernel/irq_64.c (ffffffff810344d5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/irq_64.c:handle_irq
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81058a81)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105a52d)
Location: include/linux/err.h:39
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8105ee23)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81060a4a)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81067967)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In kernel/power/qos.c (ffffffff810fa5ea)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_debug_show
  - kernel/power/qos.c:pm_qos_debug_show
```
```
In kernel/relay.c (ffffffff8118820f)
Location: include/linux/err.h:39
Inline: True
```
```
In kernel/trace/trace_events_hist.c (ffffffff811bfe44)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
```
In mm/zswap.c (ffffffff8127ecf1)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
  - mm/zswap.c:zswap_cpu_comp_prepare
```
```
In mm/ksm.c (ffffffff81291fbb)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:break_ksm
```
```
In mm/khugepaged.c (ffffffff812ac37c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/namei.c (ffffffff812d8b84)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/namei.c:trailing_symlink
```
```
In fs/namespace.c (ffffffff812f17d5)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/d_path.c (ffffffff8130754e)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/posix_acl.c (ffffffff813487b3)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8135829c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (ffffffff8135da1b)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
```
```
In fs/exportfs/expfs.c (ffffffff81403568)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/debugfs/inode.c (ffffffff81417695)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff8141a1a5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
```
```
In fs/pstore/platform.c (ffffffff8141ae9c)
Location: include/linux/err.h:39
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff814644d5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/apparmorfs.c (ffffffff8147a4c7)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:remove_rawdata_dents
```
```
In security/apparmor/domain.c (ffffffff81485c91)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
```
In security/apparmor/label.c (ffffffff81493ad9)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_strn_parse
```
```
In security/apparmor/mount.c (ffffffff814956e3)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
```
```
In crypto/api.c (ffffffff814a3b89)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In block/genhd.c (ffffffff814df9bb)
Location: include/linux/err.h:39
Inline: True
```
```
In block/blk-mq-debugfs.c (ffffffff814fdc5b)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
```
In lib/rhashtable.c (ffffffff8150d6a9)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In drivers/pinctrl/core.c (ffffffff8153f749)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/gpio/gpiolib-devres.c (ffffffff8154fb65)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff8158d8c5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_remove_epf_group
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff8158dc99)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_bar
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msix
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msi
```
```
In drivers/video/backlight/backlight.c (0)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815ca0e0)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff815ca4d5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
```
```
In drivers/acpi/property.c (ffffffff815ce795)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_device_data_of_node
```
```
In drivers/clk/clk-bulk.c (ffffffff8162a275)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/clk/clk.c (ffffffff81630ca5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_disable
```
```
In drivers/xen/pcpu.c (ffffffff8164f67e)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:sync_pcpu
```
```
In drivers/xen/xen-acpi-processor.c (0)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/regulator/core.c (ffffffff81657c9a)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_put
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:set_machine_constraints
```
```
In drivers/reset/core.c (ffffffff8165f665)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/tty/tty_audit.c (ffffffff8166e3b3)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
```
```
In drivers/base/platform.c (ffffffff816de889)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_device_unregister
```
```
In drivers/base/property.c (ffffffff816e1e8a)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_int_array
  - drivers/base/property.c:fwnode_property_read_int_array
```
```
In drivers/base/swnode.c (ffffffff816e472d)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_parent
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:software_node_put
  - drivers/base/swnode.c:software_node_get
  - drivers/base/swnode.c:to_software_node
```
```
In drivers/base/power/qos.c (ffffffff816e7447)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_get_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:__dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:__dev_pm_qos_hide_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:__dev_pm_qos_resume_latency
  - drivers/base/power/qos.c:dev_pm_qos_flags
```
```
In drivers/base/power/domain.c (ffffffff816f0fd1)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:pm_genpd_add_subdomain
  - drivers/base/power/domain.c:pm_genpd_add_subdomain
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_add_device
  - drivers/base/power/domain.c:pm_genpd_add_device
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_restore_noirq
  - drivers/base/power/domain.c:genpd_thaw_noirq
  - drivers/base/power/domain.c:genpd_freeze_noirq
  - drivers/base/power/domain.c:genpd_resume_noirq
  - drivers/base/power/domain.c:genpd_finish_suspend
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/block/loop.c (ffffffff81708259)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_attr_do_show_backing_file
```
```
In drivers/mfd/max8997-irq.c (ffffffff8172659f)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_init
  - drivers/mfd/max8997-irq.c:max8997_irq_sync_unlock
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81736a5a)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/spi/spi-mem.c (ffffffff81792f1a)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/slip/slhc.c (ffffffff817a8555)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817dde03)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8182fb21)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
```
```
In drivers/rtc/interface.c (ffffffff81835165)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8183b78f)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81844540)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/media/cec/cec-core.c (ffffffff8290786c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/media/cec/cec-core.c:cec_devnode_release
```
```
In drivers/media/cec/cec-adap.c (ffffffff81846413)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8184e37e)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8185d6e8)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
```
In drivers/opp/core.c (ffffffff8188d441)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
```
```
In drivers/cpuidle/governor.c (ffffffff8189d8dc)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/cpuidle/governor.c:cpuidle_governor_latency_req
```
```
In drivers/devfreq/devfreq.c (ffffffff818c5bc5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:try_then_request_governor
  - drivers/devfreq/devfreq.c:find_devfreq_governor
```
```
In drivers/extcon/extcon.c (ffffffff818c9ec8)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/filter.c (ffffffff81929fa4)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ethernet/eth.c (0)
Location: include/linux/err.h:39
Inline: True
```
```
In net/sched/cls_api.c (ffffffff819607a5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_release
```
```
In net/ipv4/ip_output.c (ffffffff8197c336)
Location: include/linux/err.h:39
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819aedee)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/udp_offload.c (ffffffff819b4117)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff819beff0)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffffffff819cfee1)
Location: include/linux/err.h:39
Inline: True
```
```
In net/ipv4/gre_offload.c (ffffffff819d2d24)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/addrconf.c (ffffffff81a10314)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
```
In net/ipv6/udp.c (ffffffff81a299b2)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/ip6_offload.c (ffffffff81a5154f)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
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
In init/main.c (ffffffff8289ce66)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/kernel/irq.c (ffffffff81034ce0)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81059351)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b3f8)
Location: include/linux/err.h:39
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8105f6ac)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810612fa)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810682a7)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106c560)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In kernel/power/qos.c (ffffffff81106ea6)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_add_request
  - kernel/power/qos.c:freq_qos_add_request
  - kernel/power/qos.c:freq_qos_read_value
  - kernel/power/qos.c:freq_qos_read_value
  - kernel/power/qos.c:pm_qos_debug_show
  - kernel/power/qos.c:pm_qos_debug_show
```
```
In kernel/relay.c (ffffffff8119414f)
Location: include/linux/err.h:39
Inline: True
```
```
In kernel/trace/trace_events_hist.c (ffffffff811cb694)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
```
In mm/zswap.c (ffffffff8128e731)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
  - mm/zswap.c:zswap_cpu_comp_prepare
```
```
In mm/ksm.c (ffffffff812a1d3b)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:break_ksm
```
```
In mm/khugepaged.c (ffffffff812be8cb)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/namei.c (ffffffff812ea694)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/namei.c:trailing_symlink
```
```
In fs/namespace.c (ffffffff81301b42)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/namespace.c:mnt_warn_timestamp_expiry
```
```
In fs/d_path.c (ffffffff8131a5ae)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/posix_acl.c (ffffffff81360a53)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813704cc)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (ffffffff81375c7b)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
```
```
In fs/exportfs/expfs.c (ffffffff8141d478)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/debugfs/inode.c (ffffffff81431555)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff81434015)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
```
```
In fs/pstore/platform.c (ffffffff81434cec)
Location: include/linux/err.h:39
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff8147e2a5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/apparmorfs.c (ffffffff814941c7)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:remove_rawdata_dents
```
```
In security/apparmor/domain.c (ffffffff8149fb29)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
```
In security/apparmor/label.c (ffffffff814ada09)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_strn_parse
```
```
In security/apparmor/mount.c (ffffffff814af613)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
```
```
In crypto/api.c (ffffffff814be7b9)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In block/genhd.c (ffffffff814f8deb)
Location: include/linux/err.h:39
Inline: True
```
```
In block/blk-mq-debugfs.c (ffffffff8151bb9b)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
```
In lib/rhashtable.c (ffffffff8152b4f9)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In drivers/pinctrl/core.c (ffffffff815605e9)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/gpio/gpiolib-devres.c (ffffffff81571055)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff815af4e5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_remove_epf_group
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815af8b9)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_bar
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msix
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msi
```
```
In drivers/video/backlight/backlight.c (0)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815eb300)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff815eb6e5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
```
```
In drivers/acpi/property.c (ffffffff815efa15)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_device_data_of_node
```
```
In drivers/acpi/processor_thermal.c (ffffffff81637854)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/acpi/processor_perflib.c (ffffffff81637c0c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
```
```
In drivers/clk/clk-bulk.c (ffffffff8164bd35)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/clk/clk.c (ffffffff81652a65)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_disable
```
```
In drivers/xen/pcpu.c (ffffffff81671c2e)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:sync_pcpu
```
```
In drivers/xen/xen-acpi-processor.c (0)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/regulator/core.c (ffffffff8167bbba)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_put
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:set_machine_constraints
```
```
In drivers/reset/core.c (ffffffff81681aba)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/reset/core.c:__devm_reset_control_get
```
```
In drivers/tty/tty_audit.c (ffffffff81690a2f)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
```
```
In drivers/base/platform.c (ffffffff81702b09)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_device_unregister
```
```
In drivers/base/property.c (ffffffff8170603a)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_int_array
  - drivers/base/property.c:fwnode_property_read_int_array
```
```
In drivers/base/swnode.c (ffffffff817089fd)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_parent
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:software_node_put
  - drivers/base/swnode.c:software_node_get
  - drivers/base/swnode.c:to_software_node
```
```
In drivers/base/power/qos.c (ffffffff8170b837)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_get_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:__dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:__dev_pm_qos_hide_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:__dev_pm_qos_resume_latency
  - drivers/base/power/qos.c:dev_pm_qos_flags
```
```
In drivers/base/power/domain.c (ffffffff81715471)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:pm_genpd_add_subdomain
  - drivers/base/power/domain.c:pm_genpd_add_subdomain
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_add_device
  - drivers/base/power/domain.c:pm_genpd_add_device
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_restore_noirq
  - drivers/base/power/domain.c:genpd_thaw_noirq
  - drivers/base/power/domain.c:genpd_freeze_noirq
  - drivers/base/power/domain.c:genpd_resume_noirq
  - drivers/base/power/domain.c:genpd_finish_suspend
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/block/loop.c (ffffffff8172c4a9)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_attr_do_show_backing_file
```
```
In drivers/mfd/max8997-irq.c (ffffffff8174a85f)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_init
  - drivers/mfd/max8997-irq.c:max8997_irq_sync_unlock
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8175a80c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/spi/spi-mem.c (ffffffff817b6a6a)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/slip/slhc.c (ffffffff817cbfc5)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8180ed53)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81861451)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
```
```
In drivers/rtc/interface.c (ffffffff81866935)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8186d11f)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8187533b)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/media/cec/cec-core.c (ffffffff82911271)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/media/cec/cec-core.c:cec_devnode_release
```
```
In drivers/media/cec/cec-adap.c (ffffffff81877d53)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8187fdbe)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8188e675)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
```
In drivers/opp/core.c (ffffffff818bf6a1)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
```
```
In drivers/cpuidle/governor.c (ffffffff818cfd6c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/cpuidle/governor.c:cpuidle_governor_latency_req
```
```
In drivers/leds/led-class.c (ffffffff818e4b5c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/leds/led-class.c:devm_led_classdev_release
```
```
In drivers/devfreq/devfreq.c (ffffffff818f974b)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/extcon/extcon.c (ffffffff818fc318)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/filter.c (ffffffff8195c334)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ethernet/eth.c (0)
Location: include/linux/err.h:39
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81997885)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_release
```
```
In net/ipv4/ip_output.c (ffffffff819b2d02)
Location: include/linux/err.h:39
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819e5b08)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/udp_offload.c (ffffffff819eae47)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff819f5c30)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffffffff81a06a71)
Location: include/linux/err.h:39
Inline: True
```
```
In net/ipv4/gre_offload.c (ffffffff81a09895)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/addrconf.c (ffffffff81a47054)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_dev_config
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
```
In net/ipv6/udp.c (ffffffff81a6050e)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/ip6_offload.c (ffffffff81a8816f)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
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
In init/main.c (ffffffff82cc3409)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/kernel/irq.c (ffffffff81036ae0)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/irq.c:common_interrupt
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105e56b)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105fc19)
Location: include/linux/err.h:39
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8106515d)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81066e9a)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8106f2b5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In arch/x86/kernel/apic/msi.c (ffffffff810737f0)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In kernel/power/qos.c (ffffffff81111305)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_qos_remove_notifier
  - kernel/power/qos.c:freq_qos_add_notifier
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_update_request
  - kernel/power/qos.c:freq_qos_add_request
  - kernel/power/qos.c:freq_qos_add_request
  - kernel/power/qos.c:freq_qos_read_value
  - kernel/power/qos.c:freq_qos_read_value
```
```
In kernel/dma/pool.c (ffffffff82cf17cc)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/dma/pool.c:dma_atomic_pool_init
```
```
In kernel/relay.c (ffffffff811a8f65)
Location: include/linux/err.h:39
Inline: True
```
```
In kernel/trace/blktrace.c (ffffffff811d07de)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
```
In kernel/trace/trace_events_hist.c (ffffffff811e72ef)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
```
In kernel/bpf/bpf_iter.c (ffffffff812158d1)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_seq_read
```
```
In mm/zswap.c (ffffffff812c1021)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
  - mm/zswap.c:zswap_cpu_comp_prepare
```
```
In mm/ksm.c (ffffffff812d59ee)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:break_ksm
```
```
In mm/khugepaged.c (ffffffff812f3e28)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_do_scan
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/namespace.c (ffffffff8133f44e)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:mnt_warn_timestamp_expiry
```
```
In fs/d_path.c (ffffffff813544ba)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/d_path.c:prepend_path
```
```
In fs/posix_acl.c (ffffffff813a6574)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813b7995)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/proc/base.c (ffffffff813be72b)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
```
```
In fs/ext4/namei.c (ffffffff81415e89)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/exportfs/expfs.c (ffffffff8146bfd8)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/debugfs/inode.c (ffffffff814810f5)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff81483d65)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove
```
```
In fs/pstore/platform.c (ffffffff81484ae8)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/pstore/platform.c:allocate_buf_for_compression
```
```
In security/smack/smack_lsm.c (ffffffff814d3c8f)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/apparmorfs.c (ffffffff814effd5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
```
```
In security/apparmor/domain.c (ffffffff814f9646)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
```
In security/apparmor/label.c (ffffffff8150c7e3)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_strn_parse
```
```
In security/apparmor/mount.c (ffffffff8150e8eb)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
```
```
In crypto/api.c (ffffffff8151eddd)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In crypto/drbg.c (ffffffff81534746)
Location: include/linux/err.h:39
Inline: True
```
```
In block/genhd.c (ffffffff81559a9b)
Location: include/linux/err.h:39
Inline: True
```
```
In block/blk-mq-debugfs.c (ffffffff8157bfe5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
```
```
In lib/rhashtable.c (ffffffff8158ea81)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
```
```
In lib/vsprintf.c (ffffffff815f69cf)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - lib/vsprintf.c:ptr_to_id
```
```
In drivers/pinctrl/core.c (ffffffff81602bf9)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/gpio/gpiolib-devres.c (ffffffff81615535)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff81658655)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_remove_epf_group
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81658b25)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_bar
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msix
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msi
```
```
In drivers/video/backlight/backlight.c (0)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff81696daf)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff81697205)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
```
```
In drivers/acpi/property.c (ffffffff8169bc66)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_name
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_device_data_of_node
```
```
In drivers/acpi/processor_thermal.c (ffffffff816e4534)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/acpi/processor_perflib.c (ffffffff816e497c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
```
```
In drivers/clk/clk-bulk.c (ffffffff816fad05)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/clk/clk.c (ffffffff81702565)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_disable
  - drivers/clk/clk.c:clk_unprepare
```
```
In drivers/dma/dmaengine.c (ffffffff81707fad)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_request_chan
```
```
In drivers/xen/pcpu.c (ffffffff817222f9)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:sync_pcpu
```
```
In drivers/xen/xen-acpi-processor.c (0)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/regulator/core.c (ffffffff8172e40f)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_free
  - drivers/regulator/core.c:regulator_bulk_get
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:set_machine_constraints
```
```
In drivers/reset/core.c (ffffffff81732bba)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/reset/core.c:__devm_reset_control_get
```
```
In drivers/tty/tty_audit.c (ffffffff817430db)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
```
```
In drivers/iommu/intel/svm.c (ffffffff817a9714)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
```
```
In drivers/base/platform.c (ffffffff817bcdc9)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_add_devices
```
```
In drivers/base/property.c (ffffffff817c0f89)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_next_child_node
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_int_array
  - drivers/base/property.c:fwnode_property_read_int_array
  - drivers/base/property.c:fwnode_property_present
  - drivers/base/property.c:fwnode_property_present
```
```
In drivers/base/swnode.c (ffffffff817c3a8d)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_register_nodes
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_parent
  - drivers/base/swnode.c:software_node_get_name_prefix
  - drivers/base/swnode.c:software_node_get_name
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:software_node_put
  - drivers/base/swnode.c:to_software_node
```
```
In drivers/base/power/qos.c (ffffffff817c6607)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_get_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:dev_pm_qos_constraints_destroy
  - drivers/base/power/qos.c:dev_pm_qos_constraints_destroy
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:__dev_pm_qos_resume_latency
  - drivers/base/power/qos.c:dev_pm_qos_flags
```
```
In drivers/base/power/domain.c (ffffffff817d0675)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_remove
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:genpd_add_subdomain
  - drivers/base/power/domain.c:genpd_add_subdomain
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/power/domain.c:pm_genpd_syscore_poweron
  - drivers/base/power/domain.c:pm_genpd_syscore_poweron
  - drivers/base/power/domain.c:pm_genpd_syscore_poweroff
  - drivers/base/power/domain.c:pm_genpd_syscore_poweroff
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_restore_noirq
  - drivers/base/power/domain.c:genpd_thaw_noirq
  - drivers/base/power/domain.c:genpd_freeze_noirq
  - drivers/base/power/domain.c:genpd_resume_noirq
  - drivers/base/power/domain.c:genpd_finish_suspend
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:genpd_dev_pm_start
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/block/loop.c (ffffffff817e8474)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_attr_backing_file_show
```
```
In drivers/mfd/max8997-irq.c (ffffffff81808811)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_init
  - drivers/mfd/max8997-irq.c:max8997_irq_sync_unlock
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8181a296)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:add_namespace_resource
```
```
In drivers/spi/spi-mem.c (ffffffff8187d87a)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/slip/slhc.c (ffffffff81896355)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818dfa23)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8193526f)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
```
```
In drivers/rtc/interface.c (ffffffff81939fc5)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81941501)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81949940)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8194ee7e)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8195d275)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
```
In drivers/opp/core.c (ffffffff819918b0)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
```
```
In drivers/cpuidle/governor.c (ffffffff819a23d6)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/cpuidle/governor.c:cpuidle_governor_latency_req
```
```
In drivers/leds/led-class.c (ffffffff819b801c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/leds/led-class.c:devm_led_classdev_release
```
```
In drivers/firmware/efi/efi.c (ffffffff82d291f1)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_debugfs_init
```
```
In drivers/devfreq/devfreq.c (ffffffff819d02ab)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/extcon/extcon.c (ffffffff819d2f03)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In drivers/interconnect/core.c (ffffffff819dcf85)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/interconnect/core.c:icc_nodes_remove
```
```
In net/core/filter.c (ffffffff81a300d4)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ethernet/eth.c (0)
Location: include/linux/err.h:39
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81a713e2)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
```
```
In net/ipv4/ip_output.c (ffffffff81a9cbb1)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output_gso
```
```
In net/ipv4/udp.c (ffffffff81ad58b4)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/udp_offload.c (ffffffff81ad8aba)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81ae4120)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffffffff81af64c7)
Location: include/linux/err.h:39
Inline: True
```
```
In net/ipv4/gre_offload.c (ffffffff81afa005)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/addrconf.c (ffffffff81b39b26)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dev_config
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
```
In net/ipv6/udp.c (ffffffff81b5901b)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/ip6_offload.c (ffffffff81b8363f)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
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
In init/main.c (ffffffff82faf46e)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/kernel/irq.c (ffffffff81037cd0)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/irq.c:common_interrupt
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105ca98)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105df09)
Location: include/linux/err.h:39
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff81063350)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810650d6)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8107081b)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In arch/x86/kernel/apic/msi.c (ffffffff810745e0)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In kernel/power/qos.c (ffffffff8110e485)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_qos_remove_notifier
  - kernel/power/qos.c:freq_qos_add_notifier
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_update_request
  - kernel/power/qos.c:freq_qos_add_request
  - kernel/power/qos.c:freq_qos_add_request
  - kernel/power/qos.c:freq_qos_read_value
  - kernel/power/qos.c:freq_qos_read_value
```
```
In kernel/power/energy_model.c (ffffffff8111789b)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_dev_register_perf_domain
```
```
In kernel/relay.c (ffffffff811a6665)
Location: include/linux/err.h:39
Inline: True
```
```
In kernel/trace/blktrace.c (ffffffff811cdc00)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
```
In kernel/trace/trace_events_hist.c (ffffffff811e4caf)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
```
In kernel/trace/bpf_trace.c (ffffffff811e6c6b)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_snprintf_btf
  - kernel/trace/bpf_trace.c:bpf_seq_printf_btf
```
```
In kernel/bpf/inode.c (ffffffff81215e12)
Location: include/linux/err.h:39
Inline: True
```
```
In kernel/bpf/bpf_iter.c (ffffffff81217783)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_seq_read
```
```
In mm/filemap.c (ffffffff8125be40)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read_get_pages
  - mm/filemap.c:generic_file_buffered_read_get_pages
```
```
In mm/madvise.c (ffffffff812c1a55)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_process_madvise
```
```
In mm/zswap.c (ffffffff812cca63)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
  - mm/zswap.c:zswap_cpu_comp_dead
  - mm/zswap.c:zswap_cpu_comp_dead
```
```
In mm/ksm.c (ffffffff812e14be)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:break_ksm
```
```
In mm/khugepaged.c (ffffffff812ff718)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_do_scan
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/namespace.c (ffffffff8134b4ae)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:mnt_warn_timestamp_expiry
```
```
In fs/d_path.c (ffffffff81360db6)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/d_path.c:prepend_path
```
```
In fs/posix_acl.c (ffffffff813b7302)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff813beec2)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/proc/task_mmu.c (ffffffff813c9425)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/proc/base.c (ffffffff813d048b)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
```
```
In fs/ext4/extents.c (ffffffff813f8309)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_clear_bb
```
```
In fs/ext4/namei.c (ffffffff81429674)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/exportfs/expfs.c (ffffffff814869fe)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
```
```
In fs/debugfs/inode.c (ffffffff8149e5a5)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff814a13b5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove
```
```
In fs/pstore/platform.c (ffffffff814a2118)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/pstore/platform.c:allocate_buf_for_compression
```
```
In security/smack/smack_lsm.c (ffffffff814f0e4f)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/apparmorfs.c (ffffffff8150d455)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
```
```
In security/apparmor/domain.c (ffffffff8151678b)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
```
In security/apparmor/label.c (ffffffff815296ad)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_strn_parse
```
```
In security/apparmor/mount.c (ffffffff8152b75b)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
```
```
In crypto/api.c (ffffffff8153bc2d)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In crypto/drbg.c (ffffffff81551696)
Location: include/linux/err.h:39
Inline: True
```
```
In block/genhd.c (ffffffff815761eb)
Location: include/linux/err.h:39
Inline: True
```
```
In block/blk-mq-debugfs.c (ffffffff81599085)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
```
```
In lib/rhashtable.c (ffffffff815ab5e1)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
```
```
In lib/vsprintf.c (ffffffff8161b9fe)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - lib/vsprintf.c:ptr_to_id
```
```
In drivers/pinctrl/core.c (ffffffff81627b09)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/gpio/gpiolib-devres.c (ffffffff81639775)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff81678ab5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_remove_epf_group
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81678f25)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_bar
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msix
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msi
```
```
In drivers/video/backlight/backlight.c (0)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff816b3eff)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff816b44d5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
```
```
In drivers/acpi/property.c (ffffffff816b8a86)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_name
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_device_data_of_node
```
```
In drivers/acpi/processor_thermal.c (ffffffff81701ff4)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/acpi/processor_perflib.c (ffffffff8170240c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
```
```
In drivers/clk/clk-bulk.c (ffffffff817176b5)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/clk/clk.c (ffffffff8171ae08)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_get_clk
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_disable
  - drivers/clk/clk.c:clk_unprepare
```
```
In drivers/dma/dmaengine.c (ffffffff8172531e)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
```
```
In drivers/xen/pcpu.c (ffffffff8173efa9)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:sync_pcpu
```
```
In drivers/xen/xen-acpi-processor.c (0)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/regulator/core.c (ffffffff81746b27)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_bulk_free
  - drivers/regulator/core.c:_regulator_get
```
```
In drivers/reset/core.c (ffffffff8174ed7a)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/reset/core.c:__devm_reset_control_get
```
```
In drivers/tty/tty_audit.c (ffffffff8175ef6f)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
```
```
In drivers/iommu/intel/svm.c (ffffffff817b5a54)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
```
```
In drivers/base/platform.c (ffffffff817d1cb9)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_add_devices
```
```
In drivers/base/property.c (ffffffff817d5cf9)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_next_child_node
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_int_array
  - drivers/base/property.c:fwnode_property_read_int_array
  - drivers/base/property.c:fwnode_property_present
  - drivers/base/property.c:fwnode_property_present
```
```
In drivers/base/swnode.c (ffffffff817d880d)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_unregister_nodes
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_parent
  - drivers/base/swnode.c:software_node_get_name_prefix
  - drivers/base/swnode.c:software_node_get_name
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:software_node_put
  - drivers/base/swnode.c:to_software_node
```
```
In drivers/base/power/qos.c (ffffffff817db087)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_get_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:dev_pm_qos_constraints_destroy
  - drivers/base/power/qos.c:dev_pm_qos_constraints_destroy
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:__dev_pm_qos_resume_latency
  - drivers/base/power/qos.c:dev_pm_qos_flags
```
```
In drivers/base/power/domain.c (ffffffff817e5aa5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_remove
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:genpd_add_subdomain
  - drivers/base/power/domain.c:genpd_add_subdomain
  - drivers/base/power/domain.c:dev_pm_genpd_remove_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_remove_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_add_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_add_notifier
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/power/domain.c:genpd_switch_state
  - drivers/base/power/domain.c:genpd_switch_state
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_restore_noirq
  - drivers/base/power/domain.c:genpd_thaw_noirq
  - drivers/base/power/domain.c:genpd_freeze_noirq
  - drivers/base/power/domain.c:genpd_resume_noirq
  - drivers/base/power/domain.c:genpd_finish_suspend
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:genpd_dev_pm_start
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/block/loop.c (ffffffff817fd704)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_attr_backing_file_show
```
```
In drivers/mfd/max8997-irq.c (ffffffff81818761)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_init
  - drivers/mfd/max8997-irq.c:max8997_irq_sync_unlock
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff818293b6)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:add_namespace_resource
```
```
In drivers/spi/spi-mem.c (ffffffff8188bd9a)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/slip/slhc.c (ffffffff818a4725)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818e9883)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
```
```
In drivers/usb/roles/class.c (ffffffff8192b735)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/usb/roles/class.c:usb_role_switch_unregister
  - drivers/usb/roles/class.c:fwnode_usb_role_switch_get
  - drivers/usb/roles/class.c:usb_role_switch_get
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8193c2df)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
```
```
In drivers/rtc/interface.c (ffffffff81940405)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff819478d1)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8194f500)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/power/supply/power_supply_core.c (ffffffff819548de)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
```
In drivers/power/supply/charger-manager.c (ffffffff81956024)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_extcon_init
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff81962d15)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81963c25)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
```
In drivers/opp/core.c (ffffffff81c292c8)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_get_opp_table
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_bw
  - drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
```
```
In drivers/cpuidle/governor.c (ffffffff819a5396)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/cpuidle/governor.c:cpuidle_governor_latency_req
```
```
In drivers/leds/led-class.c (ffffffff819ba4bc)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/leds/led-class.c:devm_led_classdev_release
```
```
In drivers/firmware/efi/efi.c (ffffffff83017909)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_debugfs_init
```
```
In drivers/devfreq/devfreq.c (ffffffff819cfd1e)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/extcon/extcon.c (ffffffff819d2adf)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In drivers/interconnect/core.c (ffffffff819dc6a5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/interconnect/core.c:icc_nodes_remove
```
```
In net/core/filter.c (ffffffff81a31dd4)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ethernet/eth.c (0)
Location: include/linux/err.h:39
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81a79e62)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
```
```
In net/ipv4/ip_output.c (ffffffff81aa6a41)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output_gso
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aadbc9)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
```
In net/ipv4/udp.c (ffffffff81ae1e4e)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
```
```
In net/ipv4/udp_offload.c (ffffffff81ae4fe7)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81af1050)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffffffff81b03343)
Location: include/linux/err.h:39
Inline: True
```
```
In net/ipv4/gre_offload.c (ffffffff81b07776)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/ip6_output.c (ffffffff81b3ef1f)
Location: include/linux/err.h:39
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81b48826)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dev_config
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
```
In net/ipv6/udp.c (ffffffff81b67658)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
```
```
In net/ipv6/ip6_offload.c (ffffffff81b92cff)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b93f72)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In init/main.c (ffffffff831b948f)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/kernel/irq.c (ffffffff81039870)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/irq.c:__common_interrupt
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105d3f8)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105e729)
Location: include/linux/err.h:39
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff81063ad0)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106574a)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8107103b)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8107509a)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In kernel/power/qos.c (ffffffff8110ef75)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_qos_remove_notifier
  - kernel/power/qos.c:freq_qos_add_notifier
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_update_request
  - kernel/power/qos.c:freq_qos_add_request
  - kernel/power/qos.c:freq_qos_add_request
  - kernel/power/qos.c:freq_qos_read_value
  - kernel/power/qos.c:freq_qos_read_value
```
```
In kernel/power/energy_model.c (ffffffff81117f63)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_dev_register_perf_domain
```
```
In kernel/irq/irqdomain.c (ffffffff8112691c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_remove
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/relay.c (ffffffff811a7205)
Location: include/linux/err.h:39
Inline: True
```
```
In kernel/trace/blktrace.c (ffffffff811cf2a0)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
```
In kernel/trace/trace_events_hist.c (ffffffff811e63dc)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
```
In kernel/trace/bpf_trace.c (ffffffff811e7f0b)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_snprintf_btf
  - kernel/trace/bpf_trace.c:bpf_seq_printf_btf
```
```
In kernel/bpf/inode.c (ffffffff812189d9)
Location: include/linux/err.h:39
Inline: True
```
```
In kernel/bpf/bpf_iter.c (ffffffff8121abf3)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_seq_read
```
```
In kernel/bpf/bpf_task_storage.c (ffffffff81225e74)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_get
```
```
In mm/madvise.c (ffffffff812c8952)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_process_madvise
```
```
In mm/zswap.c (ffffffff812d3633)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
  - mm/zswap.c:zswap_cpu_comp_dead
  - mm/zswap.c:zswap_cpu_comp_dead
```
```
In mm/ksm.c (ffffffff812e8bd6)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:break_ksm
```
```
In mm/khugepaged.c (ffffffff8130646f)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/namespace.c (ffffffff8134cf20)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/namespace.c:mount_setattr_prepare
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:mnt_warn_timestamp_expiry
```
```
In fs/d_path.c (ffffffff813678a3)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/d_path.c:prepend_path
```
```
In fs/posix_acl.c (ffffffff813be5db)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff813c5bbe)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/proc/task_mmu.c (ffffffff813d0502)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/proc/base.c (ffffffff813d739b)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
```
```
In fs/ext4/extents.c (ffffffff813fe789)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_clear_bb
```
```
In fs/ext4/namei.c (ffffffff81430368)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/exportfs/expfs.c (ffffffff8148c42e)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
```
```
In fs/debugfs/inode.c (ffffffff814a4575)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff814a74e5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove
```
```
In fs/pstore/platform.c (ffffffff814a81b8)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/pstore/platform.c:allocate_buf_for_compression
```
```
In security/smack/smack_lsm.c (ffffffff814f7c57)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/apparmorfs.c (ffffffff81513e65)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
```
```
In security/apparmor/domain.c (ffffffff8151d0d5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
```
In security/apparmor/label.c (ffffffff8152f846)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_strn_parse
```
```
In security/apparmor/mount.c (ffffffff81531a86)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
```
```
In crypto/api.c (ffffffff8154431d)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In crypto/drbg.c (ffffffff81559e86)
Location: include/linux/err.h:39
Inline: True
```
```
In block/genhd.c (ffffffff8157dfeb)
Location: include/linux/err.h:39
Inline: True
```
```
In block/blk-mq-debugfs.c (ffffffff8159fe85)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
```
```
In lib/rhashtable.c (ffffffff815b6444)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
```
```
In lib/vsprintf.c (ffffffff815ff2a5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - lib/vsprintf.c:ptr_to_id
```
```
In drivers/pinctrl/core.c (ffffffff8160b589)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/gpio/gpiolib-devres.c (ffffffff8161d3c5)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff8165b315)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_remove_epf_group
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff8165ba35)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_add_epf
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_bar
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msix
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msi
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_map_msi_irq
```
```
In drivers/video/backlight/backlight.c (0)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff816961b0)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff81696705)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
```
```
In drivers/acpi/property.c (ffffffff8169aa26)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_name
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_device_data_of_node
```
```
In drivers/acpi/processor_thermal.c (ffffffff816e38d4)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/acpi/processor_perflib.c (ffffffff816e3cfc)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
```
```
In drivers/clk/clk-bulk.c (ffffffff816f89a5)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/clk/clk.c (ffffffff816fc055)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_disable
  - drivers/clk/clk.c:clk_unprepare
```
```
In drivers/dma/dmaengine.c (ffffffff817065b5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
```
```
In drivers/xen/pcpu.c (ffffffff817229f9)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:sync_pcpu
```
```
In drivers/xen/xen-acpi-processor.c (0)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/regulator/core.c (ffffffff8172e6ef)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_free
  - drivers/regulator/core.c:regulator_bulk_get
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:set_machine_constraints
```
```
In drivers/reset/core.c (ffffffff81732a3a)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:reset_control_bulk_put
```
```
In drivers/tty/tty_audit.c (ffffffff81742e9c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
```
```
In drivers/iommu/intel/svm.c (ffffffff81798c1f)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
```
```
In drivers/base/platform.c (ffffffff817b56e9)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_add_devices
```
```
In drivers/base/property.c (ffffffff817b9d8d)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:device_get_next_child_node
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_int_array
  - drivers/base/property.c:fwnode_property_read_int_array
  - drivers/base/property.c:fwnode_property_present
  - drivers/base/property.c:fwnode_property_present
```
```
In drivers/base/swnode.c (ffffffff817bc7d3)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:device_create_managed_software_node
  - drivers/base/swnode.c:device_remove_software_node
  - drivers/base/swnode.c:device_remove_software_node
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:software_node_unregister_nodes
  - drivers/base/swnode.c:software_node_graph_parse_endpoint
  - drivers/base/swnode.c:software_node_graph_get_port_parent
  - drivers/base/swnode.c:software_node_graph_get_port_parent
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:swnode_graph_find_next_port
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_parent
  - drivers/base/swnode.c:software_node_get_name_prefix
  - drivers/base/swnode.c:software_node_get_name
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:software_node_put
  - drivers/base/swnode.c:to_software_node
```
```
In drivers/base/power/qos.c (ffffffff817bf3d7)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_get_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:dev_pm_qos_constraints_destroy
  - drivers/base/power/qos.c:dev_pm_qos_constraints_destroy
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:__dev_pm_qos_resume_latency
  - drivers/base/power/qos.c:dev_pm_qos_flags
```
```
In drivers/base/power/domain.c (ffffffff817c9eb5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_remove
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:genpd_add_subdomain
  - drivers/base/power/domain.c:genpd_add_subdomain
  - drivers/base/power/domain.c:dev_pm_genpd_remove_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_remove_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_add_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_add_notifier
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/power/domain.c:genpd_switch_state
  - drivers/base/power/domain.c:genpd_switch_state
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_restore_noirq
  - drivers/base/power/domain.c:genpd_thaw_noirq
  - drivers/base/power/domain.c:genpd_freeze_noirq
  - drivers/base/power/domain.c:genpd_resume_noirq
  - drivers/base/power/domain.c:genpd_finish_suspend
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:genpd_dev_pm_start
  - drivers/base/power/domain.c:dev_pm_genpd_set_next_wakeup
  - drivers/base/power/domain.c:dev_pm_genpd_set_next_wakeup
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/block/loop.c (ffffffff817e356d)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_attr_do_show_backing_file
```
```
In drivers/mfd/max8997-irq.c (ffffffff817fcba1)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_init
  - drivers/mfd/max8997-irq.c:max8997_irq_sync_unlock
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8180c5c6)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:add_namespace_resource
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/spi/spi-mem.c (ffffffff8186e6ea)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/slip/slhc.c (ffffffff81887185)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818cb353)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
```
```
In drivers/usb/roles/class.c (ffffffff8190eca5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/usb/roles/class.c:usb_role_switch_unregister
  - drivers/usb/roles/class.c:fwnode_usb_role_switch_get
  - drivers/usb/roles/class.c:usb_role_switch_get
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8191f87f)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
```
```
In drivers/rtc/interface.c (ffffffff81923b85)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8192b1e1)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8193398f)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8193874e)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
```
In drivers/power/supply/charger-manager.c (ffffffff8193a315)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_register_extcon
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff81946305)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81948045)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
```
In drivers/opp/core.c (ffffffff81976dd5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_sync_regulators
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_get_opp_table
  - drivers/opp/core.c:dev_pm_opp_set_opp
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_level_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
  - drivers/opp/core.c:dev_pm_opp_get_required_pstate
```
```
In drivers/cpuidle/governor.c (ffffffff8198a006)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/cpuidle/governor.c:cpuidle_governor_latency_req
```
```
In drivers/leds/led-class.c (ffffffff8199e7d9)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/firmware/efi/efi.c (ffffffff832227e1)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_debugfs_init
```
```
In drivers/devfreq/devfreq.c (ffffffff819b4e6b)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/extcon/extcon.c (ffffffff819b7d8f)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In drivers/powercap/dtpm_cpu.c (ffffffff819badf7)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/powercap/dtpm_cpu.c:pd_release
```
```
In drivers/interconnect/core.c (ffffffff819c2b05)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/interconnect/core.c:icc_nodes_remove
```
```
In net/core/filter.c (ffffffff81a18c61)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/sched/cls_api.c (ffffffff81a63182)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
```
```
In net/ipv4/ip_output.c (ffffffff81a91be5)
Location: include/linux/err.h:39
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff81a98c88)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
```
In net/ipv4/udp.c (ffffffff81acbb23)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
```
```
In net/ipv4/udp_offload.c (ffffffff81ad01fb)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81adc810)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffffffff81aeea12)
Location: include/linux/err.h:39
Inline: True
```
```
In net/ipv4/gre_offload.c (ffffffff81af2f32)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/ip6_output.c (ffffffff81b2bece)
Location: include/linux/err.h:39
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81b36590)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dev_config
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
```
In net/ipv6/udp.c (ffffffff81b55832)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
```
```
In net/ipv6/ip6_offload.c (ffffffff81b81e4f)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b8307f)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In init/main.c (ffffffff832997e8)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/kernel/irq.c (ffffffff8103f0d5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/irq.c:__common_interrupt
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81066af8)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8106dac0)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106f848)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8107cd38)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In arch/x86/kernel/apic/msi.c (ffffffff81082557)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In kernel/power/qos.c (ffffffff8112e815)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_qos_remove_notifier
  - kernel/power/qos.c:freq_qos_add_notifier
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_update_request
  - kernel/power/qos.c:freq_qos_add_request
  - kernel/power/qos.c:freq_qos_add_request
  - kernel/power/qos.c:freq_qos_read_value
  - kernel/power/qos.c:freq_qos_read_value
```
```
In kernel/power/energy_model.c (ffffffff811382c3)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_dev_register_perf_domain
```
```
In kernel/irq/irqdomain.c (ffffffff81146f19)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_remove
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/relay.c (ffffffff811d0a95)
Location: include/linux/err.h:39
Inline: True
```
```
In kernel/trace/blktrace.c (ffffffff811fb900)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
```
In kernel/trace/trace_events_hist.c (ffffffff812172b0)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
```
In kernel/trace/bpf_trace.c (ffffffff81218b8b)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_snprintf_btf
  - kernel/trace/bpf_trace.c:bpf_seq_printf_btf
```
```
In kernel/bpf/inode.c (ffffffff8124f004)
Location: include/linux/err.h:39
Inline: True
```
```
In kernel/bpf/bpf_iter.c (ffffffff812519f3)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_seq_read
```
```
In kernel/bpf/bpf_task_storage.c (ffffffff8125de94)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_get
```
```
In mm/madvise.c (ffffffff8130d8c8)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_process_madvise
```
```
In mm/zswap.c (ffffffff813190f3)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
  - mm/zswap.c:zswap_cpu_comp_dead
  - mm/zswap.c:zswap_cpu_comp_dead
```
```
In mm/ksm.c (ffffffff81330b06)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:break_ksm
```
```
In mm/khugepaged.c (ffffffff813502dc)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/namespace.c (ffffffff8139aeb0)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/namespace.c:mount_setattr_prepare
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_set_group
  - fs/namespace.c:do_set_group
  - fs/namespace.c:mnt_warn_timestamp_expiry
```
```
In fs/d_path.c (ffffffff813b6509)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/d_path.c:prepend_path
```
```
In fs/posix_acl.c (ffffffff8140e40b)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff8141604e)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/proc/task_mmu.c (ffffffff81421ca8)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/proc/base.c (ffffffff81428adb)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
```
```
In fs/ext4/extents.c (ffffffff81450ac9)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_clear_bb
```
```
In fs/ext4/namei.c (ffffffff814829b8)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/exportfs/expfs.c (ffffffff814e3c3e)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
```
```
In fs/debugfs/inode.c (ffffffff814fc645)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff814ff7d5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove
```
```
In fs/pstore/platform.c (ffffffff815004d8)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/pstore/platform.c:allocate_buf_for_compression
```
```
In security/smack/smack_lsm.c (ffffffff81552817)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/apparmorfs.c (ffffffff81571c65)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
```
```
In security/apparmor/domain.c (ffffffff8157b1f5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
```
In security/apparmor/label.c (ffffffff8158dc66)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_strn_parse
```
```
In security/apparmor/mount.c (ffffffff8158fed9)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
```
```
In security/integrity/evm/evm_main.c (ffffffff815a2a47)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_xattr_change
```
```
In crypto/api.c (ffffffff815a4abd)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_larval_destroy
```
```
In crypto/drbg.c (ffffffff815bb106)
Location: include/linux/err.h:39
Inline: True
```
```
In block/genhd.c (ffffffff815e384b)
Location: include/linux/err.h:39
Inline: True
```
```
In block/blk-mq-debugfs.c (ffffffff816086a5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
```
```
In lib/rhashtable.c (ffffffff8161c987)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
```
```
In lib/vsprintf.c (ffffffff8166d015)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - lib/vsprintf.c:ptr_to_id
```
```
In drivers/pinctrl/core.c (ffffffff8167a099)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/gpio/gpiolib-devres.c (ffffffff8168c715)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_unhinge
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff816cd4d5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_remove_epf_group
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff816ce145)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_add_epf
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_write_header
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_bar
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_map_addr
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msix
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msi
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_map_msi_irq
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_raise_irq
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff816cece5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_add_vepf
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_add_vepf
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_bind
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_bind
```
```
In drivers/video/backlight/backlight.c (0)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff8170bf60)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff8170c4a5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
```
```
In drivers/acpi/property.c (ffffffff81710886)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_name
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_device_data_of_node
```
```
In drivers/acpi/processor_thermal.c (ffffffff8175c44d)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/acpi/processor_perflib.c (ffffffff8175c979)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
```
```
In drivers/clk/clk-bulk.c (ffffffff81773165)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/clk/clk.c (ffffffff81777e15)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_disable
  - drivers/clk/clk.c:clk_unprepare
```
```
In drivers/dma/dmaengine.c (ffffffff81781e75)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
```
```
In drivers/xen/pcpu.c (ffffffff817a1849)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:sync_pcpu
```
```
In drivers/xen/xen-acpi-processor.c (0)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/regulator/core.c (ffffffff817ae2cf)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_bulk_free
  - drivers/regulator/core.c:regulator_bulk_get
  - drivers/regulator/core.c:_regulator_get
  - drivers/regulator/core.c:set_machine_constraints
```
```
In drivers/reset/core.c (ffffffff817b3341)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:reset_control_bulk_put
```
```
In drivers/tty/tty_audit.c (ffffffff817c38ec)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
```
```
In drivers/iommu/intel/svm.c (ffffffff818223f8)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_bind
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
```
```
In drivers/iommu/io-pgfault.c (ffffffff8182fe8a)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/iommu/io-pgfault.c:iopf_handle_single
```
```
In drivers/base/platform.c (ffffffff8183ebf9)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_add_devices
```
```
In drivers/base/property.c (ffffffff81843826)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_graph_get_next_endpoint
  - drivers/base/property.c:fwnode_graph_get_next_endpoint
  - drivers/base/property.c:fwnode_graph_get_next_endpoint
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_int_array
  - drivers/base/property.c:fwnode_property_read_int_array
  - drivers/base/property.c:fwnode_property_present
  - drivers/base/property.c:fwnode_property_present
```
```
In drivers/base/swnode.c (ffffffff81846c5e)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_notify_remove
  - drivers/base/swnode.c:software_node_notify_remove
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:device_create_managed_software_node
  - drivers/base/swnode.c:device_remove_software_node
  - drivers/base/swnode.c:device_remove_software_node
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:software_node_unregister_nodes
  - drivers/base/swnode.c:software_node_graph_parse_endpoint
  - drivers/base/swnode.c:software_node_graph_get_port_parent
  - drivers/base/swnode.c:software_node_graph_get_port_parent
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:swnode_graph_find_next_port
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_parent
  - drivers/base/swnode.c:software_node_get_name_prefix
  - drivers/base/swnode.c:software_node_get_name
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:software_node_put
  - drivers/base/swnode.c:to_software_node
```
```
In drivers/base/power/qos.c (ffffffff81849747)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_get_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:dev_pm_qos_constraints_destroy
  - drivers/base/power/qos.c:dev_pm_qos_constraints_destroy
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:__dev_pm_qos_resume_latency
  - drivers/base/power/qos.c:dev_pm_qos_flags
```
```
In drivers/base/power/domain.c (ffffffff81854405)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_remove
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:genpd_add_subdomain
  - drivers/base/power/domain.c:genpd_add_subdomain
  - drivers/base/power/domain.c:dev_pm_genpd_remove_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_remove_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_add_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_add_notifier
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/power/domain.c:genpd_switch_state
  - drivers/base/power/domain.c:genpd_switch_state
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_restore_noirq
  - drivers/base/power/domain.c:genpd_thaw_noirq
  - drivers/base/power/domain.c:genpd_freeze_noirq
  - drivers/base/power/domain.c:genpd_resume_noirq
  - drivers/base/power/domain.c:genpd_finish_suspend
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:genpd_dev_pm_start
  - drivers/base/power/domain.c:dev_pm_genpd_set_next_wakeup
  - drivers/base/power/domain.c:dev_pm_genpd_set_next_wakeup
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/block/loop.c (ffffffff8186fa7d)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_attr_do_show_backing_file
```
```
In drivers/mfd/max8997-irq.c (ffffffff818865e5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_init
  - drivers/mfd/max8997-irq.c:max8997_irq_sync_unlock
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81896bf6)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:add_namespace_resource
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/spi/spi-mem.c (ffffffff818fe78a)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/slip/slhc.c (ffffffff81918b75)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81964648)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
```
```
In drivers/usb/roles/class.c (ffffffff819afaa5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/usb/roles/class.c:usb_role_switch_unregister
  - drivers/usb/roles/class.c:fwnode_usb_role_switch_get
  - drivers/usb/roles/class.c:usb_role_switch_get
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff819c2639)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
```
```
In drivers/rtc/interface.c (ffffffff819c6bb5)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff819ce3b3)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff819d6d5f)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/ptp/ptp_vclock.c (ffffffff819db461)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_register
```
```
In drivers/power/supply/power_supply_core.c (ffffffff819dccae)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
```
In drivers/power/supply/charger-manager.c (ffffffff819dea91)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_register_extcon
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff819ead05)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff819ecfe5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
```
In drivers/opp/core.c (ffffffff81a1fbb5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_sync_regulators
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_get_opp_table
  - drivers/opp/core.c:dev_pm_opp_set_opp
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_level_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
  - drivers/opp/core.c:dev_pm_opp_is_turbo
  - drivers/opp/core.c:dev_pm_opp_get_required_pstate
```
```
In drivers/cpuidle/governor.c (ffffffff81a34966)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/cpuidle/governor.c:cpuidle_governor_latency_req
```
```
In drivers/leds/led-class.c (ffffffff81a4b489)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/firmware/efi/efi.c (ffffffff8330c4ad)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_debugfs_init
```
```
In drivers/devfreq/devfreq.c (ffffffff81a639db)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/extcon/extcon.c (ffffffff81a66c8f)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In drivers/powercap/dtpm_cpu.c (ffffffff81a69ef7)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/powercap/dtpm_cpu.c:pd_release
```
```
In drivers/interconnect/core.c (ffffffff81a723b5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/interconnect/core.c:icc_nodes_remove
```
```
In net/core/filter.c (ffffffff81aca471)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/core/sock_reuseport.c (ffffffff81ad1bc3)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
```
```
In net/sched/cls_api.c (ffffffff81b1c4f2)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
```
```
In net/ipv4/ip_output.c (ffffffff81b4cfd5)
Location: include/linux/err.h:39
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff81b54166)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
```
In net/ipv4/udp.c (ffffffff81b8a3b3)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
```
```
In net/ipv4/udp_offload.c (ffffffff81b8ec1b)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81b9bc02)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffffffff81baede2)
Location: include/linux/err.h:39
Inline: True
```
```
In net/ipv4/gre_offload.c (ffffffff81bb3442)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/ip6_output.c (ffffffff81bf203a)
Location: include/linux/err.h:39
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81bfcd17)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dev_config
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
```
In net/ipv6/udp.c (ffffffff81c1e30b)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
```
```
In net/ipv6/ip6_offload.c (ffffffff81c4dee3)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81c4f14d)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In init/main.c (ffffffff83447a25)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/kernel/irq.c (ffffffff810466e5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/irq.c:__common_interrupt
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81073828)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8107b0aa)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8107d0ef)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8108c388)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In arch/x86/kernel/apic/msi.c (ffffffff81092142)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff810c5dd6)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_arch_text_invalidate
```
```
In kernel/reboot.c (ffffffff81102775)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/reboot.c:unregister_sys_off_handler
```
```
In kernel/power/qos.c (ffffffff8114fc15)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_qos_remove_notifier
  - kernel/power/qos.c:freq_qos_add_notifier
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_update_request
  - kernel/power/qos.c:freq_qos_add_request
  - kernel/power/qos.c:freq_qos_add_request
  - kernel/power/qos.c:freq_qos_read_value
  - kernel/power/qos.c:freq_qos_read_value
```
```
In kernel/power/energy_model.c (ffffffff8115a947)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_dev_register_perf_domain
```
```
In kernel/irq/irqdomain.c (ffffffff8116b306)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_remove
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/relay.c (ffffffff81204f0a)
Location: include/linux/err.h:39
Inline: True
```
```
In kernel/trace/blktrace.c (ffffffff81235c0b)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
```
In kernel/trace/trace_events_hist.c (ffffffff812556e4)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
```
In kernel/trace/bpf_trace.c (ffffffff81256f18)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_snprintf_btf
  - kernel/trace/bpf_trace.c:bpf_seq_printf_btf
```
```
In kernel/bpf/syscall.c (ffffffff81270e26)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_freeze
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_check_btf
  - kernel/bpf/syscall.c:bpf_map_mmap
  - kernel/bpf/syscall.c:bpf_map_equal_kptr_off_tab
  - kernel/bpf/syscall.c:bpf_map_equal_kptr_off_tab
  - kernel/bpf/syscall.c:bpf_map_copy_kptr_off_tab
  - kernel/bpf/syscall.c:bpf_map_free_kptr_off_tab
  - kernel/bpf/syscall.c:bpf_map_kptr_off_contains
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
```
In kernel/bpf/verifier.c (ffffffff81290d42)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_map_access
```
```
In kernel/bpf/bpf_iter.c (ffffffff81299617)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_seq_read
```
```
In kernel/bpf/hashtab.c (ffffffff8129e3ae)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:check_and_free_fields
```
```
In kernel/bpf/arraymap.c (ffffffff812a0932)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_update_elem
```
```
In kernel/bpf/local_storage.c (ffffffff812a5a1b)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
```
```
In kernel/bpf/bpf_task_storage.c (ffffffff812a8240)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_get
```
```
In kernel/bpf/btf.c (ffffffff812ac832)
Location: include/linux/err.h:39
Inline: True
```
```
In mm/madvise.c (ffffffff81378d7c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_process_madvise
```
```
In mm/zswap.c (ffffffff81384333)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
  - mm/zswap.c:zswap_cpu_comp_dead
  - mm/zswap.c:zswap_cpu_comp_dead
```
```
In mm/ksm.c (ffffffff813a1727)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:break_ksm
```
```
In mm/khugepaged.c (ffffffff813c83bd)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/namespace.c (ffffffff8142371c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_set_group
  - fs/namespace.c:do_set_group
  - fs/namespace.c:mnt_warn_timestamp_expiry
```
```
In fs/d_path.c (ffffffff8143bad1)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/d_path.c:prepend_path
```
```
In fs/posix_acl.c (ffffffff81483a44)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_chmod
```
```
In fs/iomap/direct-io.c (ffffffff8148d881)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/proc/task_mmu.c (ffffffff8149a191)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/proc/base.c (ffffffff814a1e1b)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
```
```
In fs/ext4/extents.c (ffffffff814cdb2a)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_clear_bb
```
```
In fs/ext4/namei.c (ffffffff815059bc)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/squashfs/decompressor_multi_percpu.c (ffffffff81551b49)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_create
```
```
In fs/exportfs/expfs.c (ffffffff8157202e)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
```
```
In fs/debugfs/inode.c (ffffffff8158d0d9)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_remove
  - fs/debugfs/inode.c:debugfs_lookup
```
```
In fs/tracefs/inode.c (ffffffff81590855)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove
```
```
In fs/pstore/platform.c (ffffffff815918fb)
Location: include/linux/err.h:39
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff815ec2b3)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/apparmorfs.c (ffffffff8160eaa4)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
```
```
In security/apparmor/domain.c (ffffffff81619563)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
```
In security/apparmor/label.c (ffffffff8162ea06)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_strn_parse
```
```
In security/apparmor/mount.c (ffffffff81630e27)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
```
```
In security/integrity/evm/evm_main.c (ffffffff81649177)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_xattr_change
```
```
In crypto/api.c (ffffffff8164b285)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_larval_destroy
```
```
In crypto/algapi.c (ffffffff8164cb49)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_register_instance
```
```
In crypto/drbg.c (ffffffff81664b04)
Location: include/linux/err.h:39
Inline: True
```
```
In block/genhd.c (ffffffff81692a5b)
Location: include/linux/err.h:39
Inline: True
```
```
In block/blk-mq-debugfs.c (ffffffff816bc561)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
```
In lib/rhashtable.c (ffffffff816ea17c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
```
```
In lib/vsprintf.c (ffffffff81787382)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - lib/vsprintf.c:default_pointer
```
```
In drivers/pinctrl/core.c (ffffffff817955e7)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/gpio/gpiolib-devres.c (ffffffff817a9cd5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_unhinge
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff817f5d45)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_remove_epf_group
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff817f6e05)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_add_epf
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_write_header
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_bar
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_map_addr
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msix
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_msix
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msi
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_msi
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_map_msi_irq
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_raise_irq
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff817f7945)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_add_vepf
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_add_vepf
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_bind
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_bind
```
```
In drivers/video/backlight/backlight.c (0)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff8183a566)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff8183ab55)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
```
```
In drivers/acpi/property.c (ffffffff818400d5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_parent
  - drivers/acpi/property.c:acpi_fwnode_get_name
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:acpi_fwnode_device_get_dma_attr
  - drivers/acpi/property.c:acpi_fwnode_device_dma_supported
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
```
```
In drivers/acpi/processor_thermal.c (ffffffff8188f8cb)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/acpi/processor_perflib.c (ffffffff8188ffa9)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
```
```
In drivers/clk/clk-bulk.c (ffffffff818a89f5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:clk_bulk_put_all
```
```
In drivers/clk/clk.c (ffffffff818b19c5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_disable
  - drivers/clk/clk.c:clk_unprepare
```
```
In drivers/dma/dmaengine.c (ffffffff818b8871)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
```
```
In drivers/xen/pcpu.c (ffffffff818db84c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:sync_pcpu
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81ebecf3)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/regulator/core.c (ffffffff818e5085)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_put
  - drivers/regulator/core.c:_regulator_get
```
```
In drivers/reset/core.c (ffffffff818eedcf)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:reset_control_bulk_put
```
```
In drivers/tty/tty_audit.c (ffffffff81900507)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
```
```
In drivers/iommu/intel/svm.c (ffffffff819614dd)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
```
In drivers/iommu/io-pgfault.c (ffffffff819710e2)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/iommu/io-pgfault.c:iopf_handle_single
```
```
In drivers/base/core.c (ffffffff81974199)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/core.c:fw_devlink_parse_fwtree
```
```
In drivers/base/platform.c (ffffffff81981b0c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_add_devices
```
```
In drivers/base/property.c (ffffffff81986fea)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:device_get_match_data
  - drivers/base/property.c:fwnode_graph_parse_endpoint
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_graph_get_next_endpoint
  - drivers/base/property.c:fwnode_irq_get
  - drivers/base/property.c:fwnode_iomap
  - drivers/base/property.c:device_get_dma_attr
  - drivers/base/property.c:device_dma_supported
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_named_child_node
  - drivers/base/property.c:fwnode_get_next_available_child_node
  - drivers/base/property.c:fwnode_get_next_available_child_node
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_count_parents
  - drivers/base/property.c:fwnode_count_parents
  - drivers/base/property.c:fwnode_get_next_parent_dev
  - drivers/base/property.c:fwnode_get_next_parent_dev
  - drivers/base/property.c:fwnode_get_next_parent_dev
  - drivers/base/property.c:fwnode_get_name_prefix
  - drivers/base/property.c:fwnode_get_name
  - drivers/base/property.c:fwnode_property_get_reference_args
  - drivers/base/property.c:fwnode_property_get_reference_args
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_int_array
  - drivers/base/property.c:fwnode_property_read_int_array
  - drivers/base/property.c:fwnode_property_present
  - drivers/base/property.c:fwnode_property_present
```
```
In drivers/base/swnode.c (ffffffff8198b5ce)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_notify_remove
  - drivers/base/swnode.c:software_node_notify_remove
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:device_create_managed_software_node
  - drivers/base/swnode.c:device_remove_software_node
  - drivers/base/swnode.c:device_remove_software_node
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:software_node_unregister_nodes
  - drivers/base/swnode.c:software_node_graph_parse_endpoint
  - drivers/base/swnode.c:software_node_graph_get_port_parent
  - drivers/base/swnode.c:software_node_graph_get_port_parent
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:swnode_graph_find_next_port
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_name_prefix
  - drivers/base/swnode.c:software_node_get_name
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:software_node_put
```
```
In drivers/base/power/qos.c (ffffffff8198e777)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_get_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:dev_pm_qos_constraints_destroy
  - drivers/base/power/qos.c:dev_pm_qos_constraints_destroy
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:__dev_pm_qos_resume_latency
  - drivers/base/power/qos.c:dev_pm_qos_flags
```
```
In drivers/base/power/domain.c (ffffffff8199a055)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_remove
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/power/domain.c:genpd_add_subdomain
  - drivers/base/power/domain.c:genpd_add_subdomain
  - drivers/base/power/domain.c:dev_pm_genpd_remove_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_remove_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_add_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_add_notifier
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/power/domain.c:genpd_switch_state
  - drivers/base/power/domain.c:genpd_switch_state
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_restore_noirq
  - drivers/base/power/domain.c:genpd_thaw_noirq
  - drivers/base/power/domain.c:genpd_freeze_noirq
  - drivers/base/power/domain.c:genpd_resume_noirq
  - drivers/base/power/domain.c:genpd_finish_suspend
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:genpd_dev_pm_start
  - drivers/base/power/domain.c:dev_pm_genpd_set_next_wakeup
  - drivers/base/power/domain.c:dev_pm_genpd_set_next_wakeup
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/block/loop.c (ffffffff819b55b1)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_attr_backing_file_show
```
```
In drivers/mfd/max8997-irq.c (ffffffff819cf46c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_init
  - drivers/mfd/max8997-irq.c:max8997_irq_sync_unlock
```
```
In drivers/dma-buf/dma-buf.c (ffffffff819ec5e9)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:__map_dma_buf
```
```
In drivers/spi/spi-mem.c (ffffffff81a5006e)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/slip/slhc.c (ffffffff81a6d2b5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/net/slip/slhc.c:slhc_free
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81abeb58)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
```
```
In drivers/usb/roles/class.c (ffffffff81b0e425)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/usb/roles/class.c:usb_role_switch_unregister
  - drivers/usb/roles/class.c:role_show
  - drivers/usb/roles/class.c:fwnode_usb_role_switch_get
  - drivers/usb/roles/class.c:usb_role_switch_get
  - drivers/usb/roles/class.c:usb_role_switch_set_role
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81b22a1c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
```
```
In drivers/rtc/interface.c (ffffffff81b27a25)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_update_irq
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81b2eab5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_unregister_device
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81b398cf)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/ptp/ptp_vclock.c (ffffffff81b3edc7)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_register
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81b40f4e)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff81b507b5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_unregister
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_em_register
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_em_register
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81b538d8)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
```
In drivers/opp/core.c (ffffffff81b88745)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_sync_regulators
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_get_opp_table
  - drivers/opp/core.c:dev_pm_opp_set_opp
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_find_bw_floor
  - drivers/opp/core.c:dev_pm_opp_find_bw_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
  - drivers/opp/core.c:dev_pm_opp_get_required_pstate
```
```
In drivers/cpuidle/governor.c (ffffffff81ba11c6)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/cpuidle/governor.c:cpuidle_governor_latency_req
```
```
In drivers/leds/led-class.c (ffffffff81bb99f9)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_unregister
```
```
In drivers/firmware/sysfb.c (ffffffff81bbd15c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/firmware/sysfb.c:sysfb_disable
```
```
In drivers/firmware/efi/efi.c (ffffffff834c6468)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
```
In drivers/devfreq/devfreq.c (ffffffff81bd475b)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/extcon/extcon.c (ffffffff81bd81a3)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In drivers/interconnect/core.c (ffffffff81be3ef5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/interconnect/core.c:icc_nodes_remove
```
```
In net/core/filter.c (ffffffff81c47875)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/core/sock_reuseport.c (ffffffff81c4f436)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
```
```
In net/core/bpf_sk_storage.c (ffffffff81c91009)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_tracing_allowed
```
```
In net/sched/cls_api.c (ffffffff81ca1dd1)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
```
```
In net/ipv4/ip_output.c (ffffffff81cda756)
Location: include/linux/err.h:39
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ce208f)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
```
In net/ipv4/udp.c (ffffffff81d1dca0)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
```
```
In net/ipv4/udp_offload.c (ffffffff81d1f8cf)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81d2d9ca)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffffffff81d422ae)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/gre_offload.c (ffffffff81d46c61)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/ip6_output.c (ffffffff81d8ab44)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81d96687)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dev_config
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
```
In net/ipv6/udp.c (ffffffff81dba9b4)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
```
```
In net/ipv6/ip6_offload.c (ffffffff81dee5ea)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81defb54)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In init/main.c (ffffffff83e611ef)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/kernel/irq.c (ffffffff81050745)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/irq.c:__common_interrupt
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81083c38)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8108c3cc)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108e54c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810a0698)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In arch/x86/kernel/apic/msi.c (ffffffff810a7132)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff810e2b86)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_arch_text_invalidate
```
```
In kernel/reboot.c (ffffffff81127b85)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/reboot.c:unregister_sys_off_handler
```
```
In kernel/power/qos.c (ffffffff8117e4b5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_qos_remove_notifier
  - kernel/power/qos.c:freq_qos_add_notifier
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_update_request
  - kernel/power/qos.c:freq_qos_add_request
  - kernel/power/qos.c:freq_qos_add_request
  - kernel/power/qos.c:freq_qos_read_value
  - kernel/power/qos.c:freq_qos_read_value
```
```
In kernel/power/energy_model.c (ffffffff8118cfb2)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_dev_register_perf_domain
```
```
In kernel/irq/irqdomain.c (ffffffff811a00d9)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_remove
  - kernel/irq/irqdomain.c:__irq_domain_create
```
```
In kernel/relay.c (ffffffff8124cd7a)
Location: include/linux/err.h:39
Inline: True
```
```
In kernel/trace/blktrace.c (ffffffff8128264b)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
```
In kernel/trace/trace_events_hist.c (ffffffff812a4baa)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
```
In kernel/trace/bpf_trace.c (ffffffff812a61d8)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_snprintf_btf
  - kernel/trace/bpf_trace.c:bpf_seq_printf_btf
```
```
In kernel/bpf/syscall.c (ffffffff812cd84d)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:map_check_btf
  - kernel/bpf/syscall.c:bpf_map_mmap
  - kernel/bpf/syscall.c:bpf_obj_free_fields
  - kernel/bpf/syscall.c:bpf_obj_free_timer
  - kernel/bpf/syscall.c:btf_record_equal
  - kernel/bpf/syscall.c:btf_record_equal
  - kernel/bpf/syscall.c:btf_record_dup
  - kernel/bpf/syscall.c:btf_record_find
```
```
In kernel/bpf/verifier.c (ffffffff812d90e5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_map_prog_compatibility
  - kernel/bpf/verifier.c:check_map_prog_compatibility
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:process_spin_lock
  - kernel/bpf/verifier.c:check_map_access
```
```
In kernel/bpf/bpf_iter.c (ffffffff812f53f7)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_seq_read
```
```
In kernel/bpf/hashtab.c (ffffffff812fc2cd)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
```
In kernel/bpf/arraymap.c (ffffffff812fec09)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_update_elem
```
```
In kernel/bpf/local_storage.c (ffffffff813033eb)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff81305fc7)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
```
```
In kernel/bpf/btf.c (ffffffff81315f35)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_field_offs
  - kernel/bpf/btf.c:btf_check_and_fixup_fields
  - kernel/bpf/btf.c:btf_parse_fields
```
```
In kernel/bpf/bpf_cgrp_storage.c (ffffffff813257ec)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_get
```
```
In mm/vmscan.c (ffffffff81379555)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_seq_stop
```
```
In mm/madvise.c (ffffffff813f6744)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_process_madvise
```
```
In mm/zswap.c (ffffffff81401e73)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
  - mm/zswap.c:zswap_cpu_comp_dead
  - mm/zswap.c:zswap_cpu_comp_dead
```
```
In mm/ksm.c (ffffffff814206e9)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
```
```
In mm/huge_memory.c (ffffffff81442d9e)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/zsmalloc.c (ffffffff8146806d)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
```
```
In fs/namespace.c (ffffffff814afe7c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_set_group
  - fs/namespace.c:do_set_group
  - fs/namespace.c:mnt_warn_timestamp_expiry
```
```
In fs/d_path.c (ffffffff814ca0e1)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/d_path.c:prepend_path
```
```
In fs/posix_acl.c (ffffffff81516c63)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_chmod
```
```
In fs/iomap/direct-io.c (ffffffff81521031)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/proc/task_mmu.c (ffffffff8152e443)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/proc/base.c (ffffffff81536eeb)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
```
```
In fs/ext4/extents.c (ffffffff8156628a)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_clear_bb
```
```
In fs/ext4/namei.c (ffffffff815a04ec)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/squashfs/decompressor_multi_percpu.c (ffffffff815f30f8)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_create
```
```
In fs/exportfs/expfs.c (ffffffff8161749e)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
```
```
In fs/debugfs/inode.c (ffffffff81633bd9)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_lookup_and_remove
  - fs/debugfs/inode.c:debugfs_lookup
```
```
In fs/tracefs/inode.c (ffffffff81637d05)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove
```
```
In fs/pstore/platform.c (ffffffff81638f6b)
Location: include/linux/err.h:39
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff8169bf73)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/apparmorfs.c (ffffffff816c0d64)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
```
```
In security/apparmor/domain.c (ffffffff816cc45c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
```
In security/apparmor/label.c (ffffffff816e35c6)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_strn_parse
```
```
In security/apparmor/mount.c (ffffffff816e5b62)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
```
```
In crypto/api.c (ffffffff817044a5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_larval_destroy
```
```
In crypto/algapi.c (ffffffff81706af3)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_register_alg
```
```
In crypto/drbg.c (ffffffff8171ee74)
Location: include/linux/err.h:39
Inline: True
```
```
In block/genhd.c (ffffffff81750ecb)
Location: include/linux/err.h:39
Inline: True
```
```
In block/blk-mq-debugfs.c (ffffffff8177cf61)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
```
In lib/rhashtable.c (ffffffff817da39a)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
```
```
In drivers/pinctrl/core.c (ffffffff818aab57)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff818c08d1)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_find_and_request
```
```
In drivers/gpio/gpiolib-devres.c (ffffffff818c27c5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_unhinge
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff81921685)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_remove_epf_group
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff819231b5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_add_epf
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_write_header
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_bar
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_map_addr
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msix
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_msix
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msi
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_msi
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_map_msi_irq
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_raise_irq
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff81923ea5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_add_vepf
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_add_vepf
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_bind
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_bind
```
```
In drivers/video/backlight/backlight.c (0)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff8196fbe8)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff819701c5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
```
```
In drivers/acpi/property.c (ffffffff819766d5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_parent
  - drivers/acpi/property.c:acpi_fwnode_get_name
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:acpi_fwnode_device_get_dma_attr
  - drivers/acpi/property.c:acpi_fwnode_device_dma_supported
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
```
```
In drivers/acpi/processor_thermal.c (ffffffff819d2f03)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/acpi/processor_perflib.c (ffffffff819d74d9)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
```
```
In drivers/clk/clk-bulk.c (ffffffff819f3555)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:clk_bulk_put_all
```
```
In drivers/clk/clk.c (ffffffff819fdfc5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_disable
  - drivers/clk/clk.c:clk_unprepare
```
```
In drivers/dma/dmaengine.c (ffffffff81a05d6d)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
```
```
In drivers/xen/pcpu.c (ffffffff81a2e94c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:sync_pcpu
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81a32aa2)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/regulator/core.c (ffffffff81a39c95)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_put
```
```
In drivers/reset/core.c (ffffffff81a46a4f)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:reset_control_bulk_put
```
```
In drivers/tty/tty_audit.c (ffffffff81a59fc7)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
```
```
In drivers/base/core.c (ffffffff81ae61e5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:fw_devlink_parse_fwtree
```
```
In drivers/base/class.c (ffffffff81aeccc5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/class.c:class_destroy
```
```
In drivers/base/platform.c (ffffffff81aef7cc)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_add_devices
```
```
In drivers/base/property.c (ffffffff81af582a)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:device_get_match_data
  - drivers/base/property.c:fwnode_graph_parse_endpoint
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_graph_get_next_endpoint
  - drivers/base/property.c:fwnode_graph_get_next_endpoint
  - drivers/base/property.c:fwnode_irq_get
  - drivers/base/property.c:fwnode_iomap
  - drivers/base/property.c:device_get_dma_attr
  - drivers/base/property.c:device_dma_supported
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_named_child_node
  - drivers/base/property.c:fwnode_get_next_available_child_node
  - drivers/base/property.c:fwnode_get_next_available_child_node
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_count_parents
  - drivers/base/property.c:fwnode_count_parents
  - drivers/base/property.c:fwnode_get_next_parent_dev
  - drivers/base/property.c:fwnode_get_next_parent_dev
  - drivers/base/property.c:fwnode_get_next_parent_dev
  - drivers/base/property.c:fwnode_get_name_prefix
  - drivers/base/property.c:fwnode_get_name
  - drivers/base/property.c:fwnode_property_get_reference_args
  - drivers/base/property.c:fwnode_property_get_reference_args
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_int_array
  - drivers/base/property.c:fwnode_property_read_int_array
  - drivers/base/property.c:fwnode_property_present
  - drivers/base/property.c:fwnode_property_present
```
```
In drivers/base/swnode.c (ffffffff81afaafe)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_notify_remove
  - drivers/base/swnode.c:software_node_notify_remove
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:device_create_managed_software_node
  - drivers/base/swnode.c:device_remove_software_node
  - drivers/base/swnode.c:device_remove_software_node
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:software_node_unregister_nodes
  - drivers/base/swnode.c:software_node_graph_parse_endpoint
  - drivers/base/swnode.c:software_node_graph_get_port_parent
  - drivers/base/swnode.c:software_node_graph_get_port_parent
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:swnode_graph_find_next_port
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_name_prefix
  - drivers/base/swnode.c:software_node_get_name
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:software_node_put
```
```
In drivers/base/power/qos.c (ffffffff81afe787)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_get_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:dev_pm_qos_constraints_destroy
  - drivers/base/power/qos.c:dev_pm_qos_constraints_destroy
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:__dev_pm_qos_resume_latency
  - drivers/base/power/qos.c:dev_pm_qos_flags
```
```
In drivers/base/power/domain.c (ffffffff81b0b2e5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_remove
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/power/domain.c:genpd_add_subdomain
  - drivers/base/power/domain.c:genpd_add_subdomain
  - drivers/base/power/domain.c:dev_pm_genpd_remove_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_remove_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_add_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_add_notifier
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/power/domain.c:genpd_switch_state
  - drivers/base/power/domain.c:genpd_switch_state
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_finish_resume
  - drivers/base/power/domain.c:genpd_finish_suspend
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:genpd_dev_pm_start
  - drivers/base/power/domain.c:dev_pm_genpd_get_next_hrtimer
  - drivers/base/power/domain.c:dev_pm_genpd_get_next_hrtimer
  - drivers/base/power/domain.c:dev_pm_genpd_set_next_wakeup
  - drivers/base/power/domain.c:dev_pm_genpd_set_next_wakeup
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/block/loop.c (ffffffff81b2a8b1)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_attr_backing_file_show
```
```
In drivers/mfd/max8997-irq.c (ffffffff81b482ac)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_init
  - drivers/mfd/max8997-irq.c:max8997_irq_sync_unlock
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81b69419)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:__map_dma_buf
```
```
In drivers/spi/spi-mem.c (ffffffff81bd919e)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/pse-pd/pse_core.c (ffffffff81bea205)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/net/pse-pd/pse_core.c:pse_control_put
```
```
In drivers/net/tun.c (ffffffff81bf21c2)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c (ffffffff81bf42a8)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/net/slip/slhc.c (ffffffff81c00255)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/net/slip/slhc.c:slhc_free
```
```
In drivers/usb/core/hcd.c (ffffffff81c1d871)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81c483c8)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
```
```
In drivers/usb/roles/class.c (ffffffff81c9e615)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/usb/roles/class.c:usb_role_switch_unregister
  - drivers/usb/roles/class.c:role_show
  - drivers/usb/roles/class.c:fwnode_usb_role_switch_get
  - drivers/usb/roles/class.c:usb_role_switch_get
  - drivers/usb/roles/class.c:usb_role_switch_set_role
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81cb5024)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
```
```
In drivers/rtc/interface.c (ffffffff81cbb455)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_update_irq
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81cc2755)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_unregister_device
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81ccef5c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/ptp/ptp_vclock.c (ffffffff81cd5174)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_register
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81cd75de)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
```
In drivers/thermal/thermal_helpers.c (ffffffff81ce3935)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/thermal/thermal_helpers.c:thermal_zone_get_temp
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff81ce8755)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_unregister
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_em_register
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_em_register
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81cec787)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
```
In drivers/opp/core.c (ffffffff81d28495)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_sync_regulators
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_set_config
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_get_opp_table
  - drivers/opp/core.c:dev_pm_opp_set_opp
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:_find_key
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
  - drivers/opp/core.c:dev_pm_opp_get_required_pstate
  - drivers/opp/core.c:dev_pm_opp_get_supplies
```
```
In drivers/cpuidle/governor.c (ffffffff81d42ec6)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/cpuidle/governor.c:cpuidle_governor_latency_req
```
```
In drivers/leds/led-class.c (ffffffff81d5edd9)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_unregister
```
```
In drivers/firmware/sysfb.c (ffffffff81d62cec)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/firmware/sysfb.c:sysfb_disable
```
```
In drivers/firmware/efi/efi.c (ffffffff83f0723f)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
```
In drivers/devfreq/devfreq.c (ffffffff81d81488)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/extcon/extcon.c (ffffffff81d84ba2)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In drivers/interconnect/core.c (ffffffff81d8fc95)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/interconnect/core.c:icc_nodes_remove
```
```
In net/core/filter.c (ffffffff81dfbf45)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/core/sock_reuseport.c (ffffffff81e04a1e)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
```
```
In net/core/bpf_sk_storage.c (ffffffff81e4cd26)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
  - net/core/bpf_sk_storage.c:bpf_sk_storage_tracing_allowed
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
```
In net/sched/cls_api.c (ffffffff81e5e64b)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
```
```
In net/ipv4/ip_output.c (ffffffff81e9af36)
Location: include/linux/err.h:39
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea327f)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
```
In net/ipv4/udp.c (ffffffff81ee4d41)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
```
```
In net/ipv4/udp_offload.c (ffffffff81ee6abf)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81ef58ca)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0b0ee)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/gre_offload.c (ffffffff81f104b1)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/ip6_output.c (ffffffff81f58af8)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81f65068)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_init_auto_addrs
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
```
In net/ipv6/udp.c (ffffffff81f8aaca)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
```
```
In net/ipv6/ip6_offload.c (ffffffff81fc220f)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81fc3c43)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
```
In lib/vsprintf.c (ffffffff82044527)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - lib/vsprintf.c:default_pointer
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
In init/main.c (ffffffff836816c4)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/kernel/irq.c (ffffffff81051475)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/irq.c:__common_interrupt
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810861d8)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8108f21b)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810913fc)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810a3618)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In arch/x86/kernel/apic/msi.c (ffffffff810aa392)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff810ee256)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_arch_text_invalidate
```
```
In kernel/reboot.c (ffffffff81134fd5)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - kernel/reboot.c:unregister_sys_off_handler
```
```
In kernel/power/qos.c (ffffffff8118f115)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_qos_remove_notifier
  - kernel/power/qos.c:freq_qos_add_notifier
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_update_request
  - kernel/power/qos.c:freq_qos_add_request
  - kernel/power/qos.c:freq_qos_add_request
  - kernel/power/qos.c:freq_qos_read_value
  - kernel/power/qos.c:freq_qos_read_value
```
```
In kernel/power/energy_model.c (ffffffff8119e751)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_dev_register_perf_domain
```
```
In kernel/irq/irqdomain.c (ffffffff811b1f99)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_remove
  - kernel/irq/irqdomain.c:__irq_domain_create
```
```
In kernel/relay.c (ffffffff8126431a)
Location: include/linux/err.h:70
Inline: True
```
```
In kernel/trace/blktrace.c (ffffffff8129f2e8)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
```
In kernel/trace/trace_events_hist.c (ffffffff812c2a84)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
```
In kernel/trace/bpf_trace.c (ffffffff812c83e8)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_snprintf_btf
  - kernel/trace/bpf_trace.c:bpf_seq_printf_btf
```
```
In kernel/trace/trace_probe.c (ffffffff812d94f0)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_expand_meta_args
  - kernel/trace/trace_probe.c:sprint_nth_btf_arg
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:find_btf_func_proto
```
```
In kernel/bpf/syscall.c (ffffffff812ee1a2)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_freeze
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:map_check_btf
  - kernel/bpf/syscall.c:bpf_map_mmap
  - kernel/bpf/syscall.c:bpf_obj_free_fields
  - kernel/bpf/syscall.c:bpf_obj_free_timer
  - kernel/bpf/syscall.c:btf_record_equal
  - kernel/bpf/syscall.c:btf_record_equal
  - kernel/bpf/syscall.c:btf_record_dup
  - kernel/bpf/syscall.c:btf_record_find
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
```
In kernel/bpf/verifier.c (ffffffff81303085)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_map_prog_compatibility
  - kernel/bpf/verifier.c:check_map_prog_compatibility
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:process_spin_lock
  - kernel/bpf/verifier.c:check_map_access
```
```
In kernel/bpf/helpers.c (ffffffff81321750)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_dynptr_slice
  - kernel/bpf/helpers.c:bpf_obj_new_impl
```
```
In kernel/bpf/bpf_iter.c (ffffffff81323197)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_seq_read
```
```
In kernel/bpf/hashtab.c (ffffffff8132b47e)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:__bpf_hash_map_seq_show
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:bpf_obj_memcpy
```
```
In kernel/bpf/arraymap.c (ffffffff8132d0b1)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:__bpf_array_map_seq_show
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_update_elem
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
  - kernel/bpf/arraymap.c:bpf_obj_memcpy
```
```
In kernel/bpf/local_storage.c (ffffffff813323cd)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff81334d0c)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
```
```
In kernel/bpf/btf.c (ffffffff81345e13)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_and_fixup_fields
  - kernel/bpf/btf.c:btf_parse_fields
```
```
In kernel/bpf/bpf_cgrp_storage.c (ffffffff81355a3c)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_get
```
```
In kernel/events/uprobes.c (ffffffff8138160e)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/vmscan.c (ffffffff813ae025)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_seq_stop
```
```
In mm/memory.c (ffffffff813f535c)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
```
```
In mm/madvise.c (ffffffff814295ff)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_process_madvise
```
```
In mm/zswap.c (ffffffff81434d73)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
  - mm/zswap.c:zswap_cpu_comp_dead
  - mm/zswap.c:zswap_cpu_comp_dead
```
```
In mm/ksm.c (ffffffff814553b9)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
```
```
In mm/huge_memory.c (ffffffff8147866d)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/zsmalloc.c (ffffffff8149d315)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
```
```
In fs/namei.c (ffffffff814c7279)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - fs/namei.c:path_pts
```
```
In fs/namespace.c (ffffffff814e4ec5)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_set_group
  - fs/namespace.c:do_set_group
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:do_lock_mount
```
```
In fs/d_path.c (ffffffff81500321)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - fs/d_path.c:prepend_path
```
```
In fs/posix_acl.c (ffffffff8154e5a3)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_chmod
```
```
In fs/iomap/direct-io.c (ffffffff81559071)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/proc/task_mmu.c (ffffffff8156675d)
Location: include/linux/err.h:70
Inline: True
```
```
In fs/proc/base.c (ffffffff8156f0cb)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
```
```
In fs/ext4/extents.c (ffffffff8159df1a)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_clear_bb
```
```
In fs/ext4/namei.c (ffffffff815d6e4c)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/squashfs/decompressor_multi_percpu.c (ffffffff8162b1e8)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_create
```
```
In fs/exportfs/expfs.c (ffffffff8164f56e)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
```
```
In fs/debugfs/inode.c (ffffffff8166bed9)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_lookup_and_remove
  - fs/debugfs/inode.c:debugfs_lookup
```
```
In fs/tracefs/inode.c (ffffffff81670105)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove
```
```
In fs/pstore/platform.c (ffffffff816713ab)
Location: include/linux/err.h:70
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff816d4b35)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/apparmorfs.c (ffffffff816f9863)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
```
```
In security/apparmor/domain.c (ffffffff81704fab)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
```
In security/apparmor/label.c (ffffffff8171caf1)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_strn_parse
```
```
In security/apparmor/mount.c (ffffffff8171f27f)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
```
```
In crypto/api.c (ffffffff8173ece5)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_larval_destroy
```
```
In crypto/algapi.c (ffffffff81740a13)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_register_alg
```
```
In crypto/drbg.c (ffffffff8175a784)
Location: include/linux/err.h:70
Inline: True
```
```
In block/genhd.c (ffffffff8178d49b)
Location: include/linux/err.h:70
Inline: True
```
```
In block/blk-mq-debugfs.c (ffffffff817bc905)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
```
In lib/rhashtable.c (ffffffff818196aa)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
```
```
In drivers/pinctrl/core.c (ffffffff818eda37)
Location: include/linux/err.h:70
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff818fe88c)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
```
```
In drivers/gpio/gpiolib-devres.c (ffffffff819056c5)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_unhinge
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff81965035)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_remove_epf_group
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81966e95)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_add_epf
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_write_header
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_bar
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_map_addr
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msix
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_msix
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msi
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_msi
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_map_msi_irq
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_raise_irq
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff81967ab5)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_add_vepf
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_add_vepf
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_bind
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_bind
```
```
In drivers/video/backlight/backlight.c (0)
Location: include/linux/err.h:70
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff819b61a8)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff819b67d5)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
```
```
In drivers/acpi/property.c (ffffffff819bc8b5)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_parent
  - drivers/acpi/property.c:acpi_fwnode_get_name
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:acpi_fwnode_device_get_dma_attr
  - drivers/acpi/property.c:acpi_fwnode_device_dma_supported
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
```
```
In drivers/acpi/processor_thermal.c (ffffffff81a1a523)
Location: include/linux/err.h:70
Inline: True
```
```
In drivers/acpi/processor_perflib.c (ffffffff81a1eea5)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
```
```
In drivers/clk/clk-bulk.c (ffffffff81a3bbe5)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:clk_bulk_put_all
```
```
In drivers/clk/clk.c (ffffffff81a46c45)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_disable
  - drivers/clk/clk.c:clk_unprepare
```
```
In drivers/dma/dmaengine.c (ffffffff81a4ec2d)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
```
```
In drivers/xen/pcpu.c (ffffffff81a7810a)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:sync_pcpu
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81a7c403)
Location: include/linux/err.h:70
Inline: True
```
```
In drivers/regulator/core.c (ffffffff81a83875)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_put
```
```
In drivers/reset/core.c (ffffffff81a90bef)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:reset_control_bulk_put
```
```
In drivers/tty/tty_audit.c (ffffffff81aa45f5)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
```
```
In drivers/base/core.c (ffffffff81b34585)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:fw_devlink_parse_fwtree
```
```
In drivers/base/class.c (ffffffff81b3b3a5)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/base/class.c:class_destroy
```
```
In drivers/base/platform.c (ffffffff81b3dbac)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_add_devices
```
```
In drivers/base/property.c (ffffffff81b43a5a)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:device_get_match_data
  - drivers/base/property.c:fwnode_graph_parse_endpoint
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_graph_get_next_endpoint
  - drivers/base/property.c:fwnode_graph_get_next_endpoint
  - drivers/base/property.c:fwnode_irq_get
  - drivers/base/property.c:fwnode_iomap
  - drivers/base/property.c:device_get_dma_attr
  - drivers/base/property.c:device_dma_supported
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_named_child_node
  - drivers/base/property.c:fwnode_get_next_available_child_node
  - drivers/base/property.c:fwnode_get_next_available_child_node
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_count_parents
  - drivers/base/property.c:fwnode_count_parents
  - drivers/base/property.c:fwnode_get_next_parent_dev
  - drivers/base/property.c:fwnode_get_next_parent_dev
  - drivers/base/property.c:fwnode_get_next_parent_dev
  - drivers/base/property.c:fwnode_get_name_prefix
  - drivers/base/property.c:fwnode_get_name
  - drivers/base/property.c:fwnode_property_get_reference_args
  - drivers/base/property.c:fwnode_property_get_reference_args
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_int_array
  - drivers/base/property.c:fwnode_property_read_int_array
  - drivers/base/property.c:fwnode_property_present
  - drivers/base/property.c:fwnode_property_present
```
```
In drivers/base/swnode.c (ffffffff81b48eee)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_notify_remove
  - drivers/base/swnode.c:software_node_notify_remove
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:device_create_managed_software_node
  - drivers/base/swnode.c:device_remove_software_node
  - drivers/base/swnode.c:device_remove_software_node
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:software_node_graph_parse_endpoint
  - drivers/base/swnode.c:software_node_graph_get_port_parent
  - drivers/base/swnode.c:software_node_graph_get_port_parent
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:swnode_graph_find_next_port
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_name_prefix
  - drivers/base/swnode.c:software_node_get_name
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:software_node_put
```
```
In drivers/base/power/qos.c (ffffffff81b4cb47)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_get_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:dev_pm_qos_constraints_destroy
  - drivers/base/power/qos.c:dev_pm_qos_constraints_destroy
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:__dev_pm_qos_resume_latency
  - drivers/base/power/qos.c:dev_pm_qos_flags
```
```
In drivers/base/power/domain.c (ffffffff81b59325)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_remove
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/power/domain.c:genpd_add_subdomain
  - drivers/base/power/domain.c:genpd_add_subdomain
  - drivers/base/power/domain.c:dev_pm_genpd_remove_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_remove_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_add_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_add_notifier
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:genpd_switch_state
  - drivers/base/power/domain.c:genpd_switch_state
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_finish_resume
  - drivers/base/power/domain.c:genpd_finish_suspend
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:genpd_dev_pm_start
  - drivers/base/power/domain.c:dev_pm_genpd_synced_poweroff
  - drivers/base/power/domain.c:dev_pm_genpd_synced_poweroff
  - drivers/base/power/domain.c:dev_pm_genpd_get_next_hrtimer
  - drivers/base/power/domain.c:dev_pm_genpd_get_next_hrtimer
  - drivers/base/power/domain.c:dev_pm_genpd_set_next_wakeup
  - drivers/base/power/domain.c:dev_pm_genpd_set_next_wakeup
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/block/loop.c (ffffffff81b7ab91)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_attr_backing_file_show
```
```
In drivers/mfd/max8997-irq.c (ffffffff81b9b71c)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_init
  - drivers/mfd/max8997-irq.c:max8997_irq_sync_unlock
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81bbc859)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:__map_dma_buf
```
```
In drivers/spi/spi-mem.c (ffffffff81c2fb9e)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/pse-pd/pse_core.c (ffffffff81c42635)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/net/pse-pd/pse_core.c:pse_control_put
```
```
In drivers/net/tun.c (ffffffff81c4ae4b)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c (ffffffff81c578ac)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_debugfs_show
```
```
In drivers/net/slip/slhc.c (ffffffff81c65885)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/net/slip/slhc.c:slhc_free
```
```
In drivers/usb/core/hcd.c (ffffffff81c84761)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81caf998)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
```
```
In drivers/usb/roles/class.c (ffffffff81d05955)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/usb/roles/class.c:usb_role_switch_unregister
  - drivers/usb/roles/class.c:role_show
  - drivers/usb/roles/class.c:fwnode_usb_role_switch_get
  - drivers/usb/roles/class.c:usb_role_switch_get
  - drivers/usb/roles/class.c:usb_role_switch_set_role
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81d1c694)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
```
```
In drivers/rtc/interface.c (ffffffff81d22d05)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_update_irq
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81d2a175)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_unregister_device
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81d37075)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/ptp/ptp_vclock.c (ffffffff81d3cdf7)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_register
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81d3f7ae)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
```
In drivers/thermal/thermal_core.c (ffffffff81d4628d)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_cooling_device_update
```
```
In drivers/thermal/thermal_helpers.c (ffffffff81d4c115)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/thermal/thermal_helpers.c:thermal_zone_get_temp
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff81d50f15)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_unregister
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_em_register
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_em_register
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81d554a7)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
```
In drivers/opp/core.c (ffffffff81d91635)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_sync_regulators
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_set_config
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_get_opp_table
  - drivers/opp/core.c:dev_pm_opp_set_opp
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:_find_key
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
  - drivers/opp/core.c:dev_pm_opp_get_required_pstate
  - drivers/opp/core.c:dev_pm_opp_get_supplies
```
```
In drivers/cpuidle/governor.c (ffffffff81dad0e6)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/cpuidle/governor.c:cpuidle_governor_latency_req
```
```
In drivers/leds/led-class.c (ffffffff81dc9cc9)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_unregister
```
```
In drivers/firmware/sysfb.c (ffffffff81dcddbc)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/firmware/sysfb.c:sysfb_disable
```
```
In drivers/firmware/efi/efi.c (ffffffff8372d300)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
```
In drivers/hid/bpf/hid_bpf_jmp_table.c (ffffffff81dd73fd)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/hid/bpf/hid_bpf_jmp_table.c:hid_bpf_free_links_and_skel
```
```
In drivers/devfreq/devfreq.c (ffffffff81def848)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/extcon/extcon.c (ffffffff81df3155)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In drivers/interconnect/core.c (ffffffff81dfe0a5)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/interconnect/core.c:icc_nodes_remove
```
```
In net/core/filter.c (ffffffff81e6fa39)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/core/sock_reuseport.c (ffffffff81e7726e)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
```
```
In net/core/bpf_sk_storage.c (ffffffff81ea844a)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
  - net/core/bpf_sk_storage.c:bpf_sk_storage_tracing_allowed
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
```
In net/sched/cls_api.c (ffffffff81ebc3f3)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
```
```
In net/netfilter/nf_bpf_link.c (ffffffff81eeaac7)
Location: include/linux/err.h:70
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81ef9936)
Location: include/linux/err.h:70
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f01ab7)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
```
In net/ipv4/udp.c (ffffffff81f4471c)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
```
```
In net/ipv4/udp_offload.c (ffffffff81f4630c)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81f5527d)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6acb2)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/gre_offload.c (ffffffff81f701a1)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/ip6_output.c (ffffffff81fb87aa)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81fc5205)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_init_auto_addrs
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
```
In net/ipv6/udp.c (ffffffff81fea3c7)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
```
```
In net/ipv6/ip6_offload.c (ffffffff8202318f)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/inet6_hashtables.c (ffffffff82024b0e)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
```
In lib/vsprintf.c (ffffffff820c2b24)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - lib/vsprintf.c:default_pointer
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
In init/main.c (ffffffff838b06e4)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/kernel/irq.c (ffffffff810586a5)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/irq.c:__common_interrupt
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8108d0b8)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff810965ab)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810987d9)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810aa5e8)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In arch/x86/kernel/apic/msi.c (ffffffff810b1422)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff810f7d16)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_arch_text_invalidate
```
```
In kernel/reboot.c (ffffffff8113fed5)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - kernel/reboot.c:unregister_sys_off_handler
```
```
In kernel/power/qos.c (ffffffff8119dac5)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_qos_remove_notifier
  - kernel/power/qos.c:freq_qos_add_notifier
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_update_request
  - kernel/power/qos.c:freq_qos_add_request
  - kernel/power/qos.c:freq_qos_add_request
  - kernel/power/qos.c:freq_qos_read_value
  - kernel/power/qos.c:freq_qos_read_value
```
```
In kernel/power/energy_model.c (ffffffff811ad911)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_dev_register_perf_domain
```
```
In kernel/irq/irqdomain.c (ffffffff811c1d49)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_remove
  - kernel/irq/irqdomain.c:__irq_domain_create
```
```
In kernel/relay.c (ffffffff8127e10a)
Location: include/linux/err.h:70
Inline: True
```
```
In kernel/trace/blktrace.c (ffffffff812ba9f7)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
```
In kernel/trace/trace_events_hist.c (ffffffff812df334)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
```
In kernel/trace/bpf_trace.c (ffffffff812e4e78)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_snprintf_btf
  - kernel/trace/bpf_trace.c:bpf_seq_printf_btf
```
```
In kernel/trace/trace_probe.c (ffffffff812f4dcc)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:query_btf_context
```
```
In kernel/trace/fprobe.c (ffffffff812fc74c)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - kernel/trace/fprobe.c:register_fprobe_ips
  - kernel/trace/fprobe.c:register_fprobe
```
```
In kernel/bpf/syscall.c (ffffffff8130cf62)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_freeze
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:map_check_btf
  - kernel/bpf/syscall.c:bpf_map_mmap
  - kernel/bpf/syscall.c:bpf_obj_free_fields
  - kernel/bpf/syscall.c:bpf_obj_free_timer
  - kernel/bpf/syscall.c:btf_record_equal
  - kernel/bpf/syscall.c:btf_record_equal
  - kernel/bpf/syscall.c:btf_record_dup
  - kernel/bpf/syscall.c:btf_record_find
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
```
In kernel/bpf/verifier.c (ffffffff81322b90)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_map_prog_compatibility
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:process_spin_lock
  - kernel/bpf/verifier.c:check_map_access
```
```
In kernel/bpf/helpers.c (ffffffff81343ee1)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_dynptr_slice
  - kernel/bpf/helpers.c:bpf_obj_new_impl
```
```
In kernel/bpf/bpf_iter.c (ffffffff813470c7)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_seq_read
```
```
In kernel/bpf/hashtab.c (ffffffff8134f92e)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:__bpf_hash_map_seq_show
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:bpf_obj_memcpy
```
```
In kernel/bpf/arraymap.c (ffffffff81351411)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:__bpf_array_map_seq_show
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_update_elem
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
  - kernel/bpf/arraymap.c:bpf_obj_memcpy
```
```
In kernel/bpf/local_storage.c (ffffffff8135697d)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff8135945d)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
```
```
In kernel/bpf/btf.c (ffffffff8136ec34)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_and_fixup_fields
  - kernel/bpf/btf.c:btf_parse_fields
```
```
In kernel/bpf/bpf_cgrp_storage.c (ffffffff8137e56c)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_get
```
```
In mm/vmscan.c (ffffffff813d7655)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_seq_stop
```
```
In mm/madvise.c (ffffffff81462e2f)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_process_madvise
```
```
In mm/zswap.c (ffffffff8146dc43)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
  - mm/zswap.c:zswap_cpu_comp_dead
  - mm/zswap.c:zswap_cpu_comp_dead
```
```
In mm/ksm.c (ffffffff8148f2cd)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
```
```
In mm/huge_memory.c (ffffffff814a7d9d)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/zsmalloc.c (ffffffff814ccad5)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_free
```
```
In fs/namei.c (ffffffff814f9af9)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - fs/namei.c:path_pts
```
```
In fs/namespace.c (ffffffff81518cf5)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_set_group
  - fs/namespace.c:do_set_group
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:do_lock_mount
```
```
In fs/d_path.c (ffffffff81534f41)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - fs/d_path.c:prepend_path
```
```
In fs/posix_acl.c (ffffffff815843f3)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_chmod
```
```
In fs/iomap/direct-io.c (ffffffff8158f7e1)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/proc/task_mmu.c (ffffffff8159e7a9)
Location: include/linux/err.h:70
Inline: True
```
```
In fs/proc/base.c (ffffffff815a7a9b)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
```
```
In fs/ext4/extents.c (ffffffff815d6b6a)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_clear_bb
```
```
In fs/ext4/namei.c (ffffffff8160f4bc)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/squashfs/decompressor_multi_percpu.c (ffffffff816645b8)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_create
```
```
In fs/exportfs/expfs.c (ffffffff81688b4e)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
```
```
In fs/debugfs/inode.c (ffffffff816a6379)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_lookup_and_remove
  - fs/debugfs/inode.c:debugfs_lookup
```
```
In fs/tracefs/inode.c (ffffffff816aae75)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove
```
```
In security/smack/smack_lsm.c (ffffffff81710e88)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/apparmorfs.c (ffffffff81736603)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
```
```
In security/apparmor/domain.c (ffffffff81742877)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:x_table_lookup
```
```
In security/apparmor/lsm.c (ffffffff817523b8)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_userns_create
  - security/apparmor/lsm.c:apparmor_userns_create
```
```
In security/apparmor/label.c (ffffffff8175b540)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_strn_parse
```
```
In security/apparmor/mount.c (ffffffff8175dcaf)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
```
```
In crypto/api.c (ffffffff8177fb65)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_larval_destroy
```
```
In crypto/algapi.c (ffffffff817818b3)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_register_alg
```
```
In crypto/drbg.c (ffffffff8179c684)
Location: include/linux/err.h:70
Inline: True
```
```
In block/genhd.c (ffffffff817cfcfb)
Location: include/linux/err.h:70
Inline: True
```
```
In block/blk-mq-debugfs.c (ffffffff81800fc5)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
```
In lib/rhashtable.c (ffffffff8185e9fa)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
```
```
In drivers/pinctrl/core.c (ffffffff81935207)
Location: include/linux/err.h:70
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff819491e6)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_find
  - drivers/gpio/gpiolib.c:gpiod_add_hogs
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
```
```
In drivers/gpio/gpiolib-devres.c (ffffffff8194d0d5)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_unhinge
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff81954750)
Location: include/linux/err.h:70
Inline: True
```
```
In drivers/gpio/gpiolib-swnode.c (0)
Location: include/linux/err.h:70
Inline: True
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff819ae6e5)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_remove_epf_group
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff819afba5)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_bme_notify
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_init_notify
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_linkdown
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_linkup
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_add_epf
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_write_header
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_bar
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_map_addr
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msix
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_msix
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msi
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_msi
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_map_msi_irq
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_raise_irq
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_put
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff819b1215)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_add_vepf
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_add_vepf
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_bind
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_bind
```
```
In drivers/video/backlight/backlight.c (0)
Location: include/linux/err.h:70
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff81a00736)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff81a00d84)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
```
```
In drivers/acpi/property.c (ffffffff81a071a5)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_parent
  - drivers/acpi/property.c:acpi_fwnode_get_name
  - drivers/acpi/property.c:acpi_fwnode_property_read_string_array
  - drivers/acpi/property.c:acpi_fwnode_property_read_int_array
  - drivers/acpi/property.c:acpi_fwnode_property_present
  - drivers/acpi/property.c:acpi_fwnode_device_get_dma_attr
  - drivers/acpi/property.c:acpi_fwnode_device_dma_supported
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_parse_string_ref
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
```
```
In drivers/acpi/processor_thermal.c (ffffffff81a65821)
Location: include/linux/err.h:70
Inline: True
```
```
In drivers/acpi/processor_perflib.c (ffffffff81a6a1c5)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
```
```
In drivers/clk/clk-bulk.c (ffffffff81a874a5)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:clk_bulk_put_all
```
```
In drivers/clk/clk.c (ffffffff81a92735)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_disable
  - drivers/clk/clk.c:clk_unprepare
```
```
In drivers/dma/dmaengine.c (ffffffff81a9a8cd)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
```
```
In drivers/pmdomain/core.c (ffffffff81aa0ce5)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/pmdomain/core.c:genpd_remove
  - drivers/pmdomain/core.c:pm_genpd_init
  - drivers/pmdomain/core.c:genpd_add_subdomain
  - drivers/pmdomain/core.c:genpd_add_subdomain
  - drivers/pmdomain/core.c:dev_pm_genpd_remove_notifier
  - drivers/pmdomain/core.c:dev_pm_genpd_remove_notifier
  - drivers/pmdomain/core.c:dev_pm_genpd_add_notifier
  - drivers/pmdomain/core.c:dev_pm_genpd_add_notifier
  - drivers/pmdomain/core.c:pm_genpd_remove_device
  - drivers/pmdomain/core.c:pm_genpd_remove_device
  - drivers/pmdomain/core.c:genpd_switch_state
  - drivers/pmdomain/core.c:genpd_switch_state
  - drivers/pmdomain/core.c:genpd_complete
  - drivers/pmdomain/core.c:genpd_finish_resume
  - drivers/pmdomain/core.c:genpd_finish_suspend
  - drivers/pmdomain/core.c:genpd_prepare
  - drivers/pmdomain/core.c:genpd_runtime_resume
  - drivers/pmdomain/core.c:genpd_runtime_suspend
  - drivers/pmdomain/core.c:genpd_dev_pm_qos_notifier
  - drivers/pmdomain/core.c:genpd_dev_pm_start
  - drivers/pmdomain/core.c:dev_pm_genpd_synced_poweroff
  - drivers/pmdomain/core.c:dev_pm_genpd_synced_poweroff
  - drivers/pmdomain/core.c:dev_pm_genpd_get_next_hrtimer
  - drivers/pmdomain/core.c:dev_pm_genpd_get_next_hrtimer
  - drivers/pmdomain/core.c:dev_pm_genpd_set_next_wakeup
  - drivers/pmdomain/core.c:dev_pm_genpd_set_next_wakeup
  - drivers/pmdomain/core.c:dev_pm_genpd_set_performance_state
  - drivers/pmdomain/core.c:dev_pm_genpd_set_performance_state
  - drivers/pmdomain/core.c:genpd_dev_pm_set_performance_state
```
```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81ac8e9e)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
```
```
In drivers/xen/pcpu.c (ffffffff81aca349)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:sync_pcpu
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81ace8b3)
Location: include/linux/err.h:70
Inline: True
```
```
In drivers/regulator/core.c (ffffffff81ad6025)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_put
```
```
In drivers/reset/core.c (ffffffff81ae365f)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:__reset_control_put_internal
```
```
In drivers/tty/tty_audit.c (ffffffff81af6ff6)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
```
```
In drivers/base/core.c (ffffffff81b8bf85)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:fw_devlink_parse_fwtree
```
```
In drivers/base/class.c (ffffffff81b92ef5)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/base/class.c:class_destroy
```
```
In drivers/base/platform.c (ffffffff81b956ec)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_add_devices
```
```
In drivers/base/property.c (ffffffff81b9baaa)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:fwnode_graph_devcon_matches
  - drivers/base/property.c:device_get_match_data
  - drivers/base/property.c:fwnode_graph_parse_endpoint
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_count
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_endpoint_by_id
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_remote_port
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_graph_get_port_parent
  - drivers/base/property.c:fwnode_graph_get_next_endpoint
  - drivers/base/property.c:fwnode_graph_get_next_endpoint
  - drivers/base/property.c:fwnode_irq_get
  - drivers/base/property.c:fwnode_iomap
  - drivers/base/property.c:device_get_dma_attr
  - drivers/base/property.c:device_dma_supported
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_named_child_node
  - drivers/base/property.c:fwnode_get_next_available_child_node
  - drivers/base/property.c:fwnode_get_next_available_child_node
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_is_ancestor_of
  - drivers/base/property.c:fwnode_count_parents
  - drivers/base/property.c:fwnode_count_parents
  - drivers/base/property.c:fwnode_get_next_parent_dev
  - drivers/base/property.c:fwnode_get_next_parent_dev
  - drivers/base/property.c:fwnode_get_next_parent_dev
  - drivers/base/property.c:fwnode_name_eq
  - drivers/base/property.c:fwnode_get_name_prefix
  - drivers/base/property.c:fwnode_property_get_reference_args
  - drivers/base/property.c:fwnode_property_get_reference_args
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_int_array
  - drivers/base/property.c:fwnode_property_read_int_array
  - drivers/base/property.c:fwnode_property_present
  - drivers/base/property.c:fwnode_property_present
```
```
In drivers/base/swnode.c (ffffffff81ba12de)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_notify_remove
  - drivers/base/swnode.c:software_node_notify_remove
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:device_create_managed_software_node
  - drivers/base/swnode.c:device_remove_software_node
  - drivers/base/swnode.c:device_remove_software_node
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:software_node_graph_parse_endpoint
  - drivers/base/swnode.c:software_node_graph_get_port_parent
  - drivers/base/swnode.c:software_node_graph_get_port_parent
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_graph_get_remote_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:software_node_graph_get_next_endpoint
  - drivers/base/swnode.c:swnode_graph_find_next_port
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_name_prefix
  - drivers/base/swnode.c:software_node_get_name
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:software_node_put
```
```
In drivers/base/power/qos.c (ffffffff81ba5017)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_get_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:dev_pm_qos_constraints_destroy
  - drivers/base/power/qos.c:dev_pm_qos_constraints_destroy
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:__dev_pm_qos_resume_latency
  - drivers/base/power/qos.c:dev_pm_qos_flags
```
```
In drivers/block/loop.c (ffffffff81bce961)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_attr_backing_file_show
```
```
In drivers/mfd/max8997-irq.c (ffffffff81bef6dc)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_init
  - drivers/mfd/max8997-irq.c:max8997_irq_sync_unlock
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81c10fa9)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:__map_dma_buf
```
```
In drivers/gpu/drm/drm_gem.c (ffffffff81c9cef9)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem.c:drm_gem_handle_delete
```
```
In drivers/gpu/drm/drm_sysfs.c (ffffffff81cb2e9c)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_sysfs.c:drm_sysfs_destroy
```
```
In drivers/gpu/drm/drm_privacy_screen.c (ffffffff81cbc755)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_privacy_screen.c:drm_privacy_screen_unregister
  - drivers/gpu/drm/drm_privacy_screen.c:drm_privacy_screen_put
```
```
In drivers/gpu/drm/drm_encoder_slave.c (ffffffff81cc8774)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_encoder_slave.c:drm_i2c_encoder_init
```
```
In drivers/spi/spi-mem.c (ffffffff81ce2a5e)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/pse-pd/pse_core.c (ffffffff81cf7cf5)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/net/pse-pd/pse_core.c:pse_control_put
```
```
In drivers/net/tun.c (ffffffff81d0077a)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/slip/slhc.c (ffffffff81d1c2b5)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/net/slip/slhc.c:slhc_free
```
```
In drivers/usb/core/hcd.c (ffffffff81d39161)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_setup_local_mem
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81d646a8)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
```
```
In drivers/usb/roles/class.c (ffffffff81dbb314)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/usb/roles/class.c:fwnode_usb_role_switch_get
  - drivers/usb/roles/class.c:usb_role_switch_get
  - drivers/usb/roles/class.c:usb_role_switch_set_role
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81dd23e4)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
```
```
In drivers/rtc/interface.c (ffffffff81dd8a65)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_update_irq
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81de0035)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_unregister_device
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81ded284)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/ptp/ptp_vclock.c (ffffffff81df3766)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_register
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81df615e)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
```
In drivers/thermal/thermal_core.c (ffffffff81dfcc6d)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_cooling_device_update
```
```
In drivers/thermal/thermal_helpers.c (ffffffff81e02ea5)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/thermal/thermal_helpers.c:thermal_zone_get_temp
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff81e07c65)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_unregister
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_em_register
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_em_register
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81e0c3a7)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
```
In drivers/opp/core.c (ffffffff81e492c5)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/core.c:dev_pm_opp_unregister_notifier
  - drivers/opp/core.c:dev_pm_opp_register_notifier
  - drivers/opp/core.c:dev_pm_opp_sync_regulators
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_set_config
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
  - drivers/opp/core.c:dev_pm_opp_remove
  - drivers/opp/core.c:dev_pm_opp_get_opp_table
  - drivers/opp/core.c:dev_pm_opp_set_opp
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:_find_key
  - drivers/opp/core.c:dev_pm_opp_get_opp_count
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_suspend_opp_freq
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
  - drivers/opp/core.c:dev_pm_opp_get_max_volt_latency
  - drivers/opp/core.c:dev_pm_opp_get_required_pstate
  - drivers/opp/core.c:dev_pm_opp_get_supplies
```
```
In drivers/cpuidle/governor.c (ffffffff81e65186)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/cpuidle/governor.c:cpuidle_governor_latency_req
```
```
In drivers/leds/led-class.c (ffffffff81e82899)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_unregister
```
```
In drivers/firmware/sysfb.c (ffffffff81e868fc)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/firmware/sysfb.c:sysfb_disable
```
```
In drivers/firmware/efi/efi.c (ffffffff839616da)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
```
In drivers/hid/bpf/hid_bpf_jmp_table.c (ffffffff81e8f69d)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/hid/bpf/hid_bpf_jmp_table.c:hid_bpf_free_links_and_skel
```
```
In drivers/devfreq/devfreq.c (ffffffff81ea5e08)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/extcon/extcon.c (ffffffff81ea97a3)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In drivers/interconnect/core.c (ffffffff81eb4a95)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - drivers/interconnect/core.c:icc_nodes_remove
```
```
In net/core/filter.c (ffffffff81f2f1f2)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/core/sock_reuseport.c (ffffffff81f3722e)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
```
```
In net/core/bpf_sk_storage.c (ffffffff81f6af0a)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:diag_get
  - net/core/bpf_sk_storage.c:bpf_sk_storage_tracing_allowed
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
```
In net/sched/cls_api.c (ffffffff81f7f610)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
```
```
In net/netfilter/nf_bpf_link.c (ffffffff81fae977)
Location: include/linux/err.h:70
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81fbd856)
Location: include/linux/err.h:70
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc65a8)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lookup_run_sk_lookup
```
```
In net/ipv4/udp.c (ffffffff8200a6fe)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:__udp4_lib_lookup
```
```
In net/ipv4/udp_offload.c (ffffffff8200c44c)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff8201b4ed)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffffffff82031362)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/gre_offload.c (ffffffff820368d1)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/tcp_ao.c (ffffffff8205996c)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - net/ipv4/tcp_ao.c:tcp_ao_get_repair
```
```
In net/ipv6/ip6_output.c (ffffffff82085d50)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff820927c1)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_init_auto_addrs
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
```
In net/ipv6/udp.c (ffffffff820b8293)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_lookup
```
```
In net/ipv6/ip6_offload.c (ffffffff820f21da)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820f371b)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_run_sk_lookup
```
```
In net/devlink/netlink.c (ffffffff82101568)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - net/devlink/netlink.c:devlink_nl_notify_filter
```
```
In lib/vsprintf.c (ffffffff8219d4a4)
Location: include/linux/err.h:70
Inline: True
Inline callers:
  - lib/vsprintf.c:default_pointer
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
In init/main.c (ffff800011430e78)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In virt/kvm/kvm_main.c (ffff8000100b6814)
Location: include/linux/err.h:39
Inline: True
```
```
In kernel/power/qos.c (ffff80001016dc48)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_add_request
  - kernel/power/qos.c:freq_qos_add_request
  - kernel/power/qos.c:freq_qos_read_value
  - kernel/power/qos.c:freq_qos_read_value
  - kernel/power/qos.c:pm_qos_debug_show
  - kernel/power/qos.c:pm_qos_debug_show
```
```
In kernel/irq/irqdomain.c (ffff800010184f40)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_strict_mappings
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_domain_associate_many
  - kernel/irq/irqdomain.c:irq_find_matching_fwspec
  - kernel/irq/irqdomain.c:irq_domain_remove
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/relay.c (ffff80001020bb7c)
Location: include/linux/err.h:39
Inline: True
```
```
In kernel/trace/trace_events_hist.c (ffff80001024aa48)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
```
In mm/zswap.c (ffff80001032af78)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
  - mm/zswap.c:zswap_cpu_comp_prepare
```
```
In mm/ksm.c (ffff800010341588)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:break_ksm
```
```
In mm/khugepaged.c (ffff80001035f8e4)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/namei.c (ffff800010393d9c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/namei.c:trailing_symlink
```
```
In fs/namespace.c (ffff8000103b41ec)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/namespace.c:mnt_warn_timestamp_expiry
```
```
In fs/d_path.c (ffff8000103d1838)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/posix_acl.c (ffff800010426cf4)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/proc/task_mmu.c (ffff80001043a19c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (ffff800010441010)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
```
```
In fs/exportfs/expfs.c (ffff8000104ff1ec)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/debugfs/inode.c (ffff800010516290)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/tracefs/inode.c (ffff800010519b08)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
```
```
In fs/pstore/platform.c (ffff80001051ac40)
Location: include/linux/err.h:39
Inline: True
```
```
In security/smack/smack_lsm.c (ffff80001056f128)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/apparmorfs.c (ffff800010589824)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:remove_rawdata_dents
```
```
In security/apparmor/domain.c (ffff800010595ad8)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
```
In security/apparmor/label.c (ffff8000105a4eb0)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_strn_parse
```
```
In security/apparmor/mount.c (ffff8000105a6d24)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
```
```
In crypto/api.c (ffff8000105b77c8)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In block/genhd.c (ffff8000105fa2a8)
Location: include/linux/err.h:39
Inline: True
```
```
In block/blk-mq-debugfs.c (ffff800010624218)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
```
In lib/rhashtable.c (ffff800010636bd4)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In drivers/irqchip/irq-gic.c (ffff80001066b978)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_irq_domain_translate
```
```
In drivers/irqchip/irq-gic-v2m.c (ffff800011472320)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_init
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_teardown
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_irq_domain_alloc
```
```
In drivers/irqchip/irq-gic-v3.c (ffff80001066dc88)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_irq_domain_translate
```
```
In drivers/irqchip/irq-gic-v3-mbi.c (ffff800011473670)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-mbi.c:mbi_init
  - drivers/irqchip/irq-gic-v3-mbi.c:mbi_irq_domain_alloc
```
```
In drivers/irqchip/irq-gic-v3-its.c (ffff8000114745fc)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_init
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_gic_domain_alloc
```
```
In drivers/irqchip/irq-gic-v3-its-platform-msi.c (ffff8000106750a4)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its-platform-msi.c:its_pmsi_prepare
```
```
In drivers/irqchip/irq-mbigen.c (ffff800010676158)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/irqchip/irq-mbigen.c:mbigen_domain_translate
```
```
In drivers/irqchip/irq-mtk-sysirq.c (ffff800010677b60)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/irqchip/irq-mtk-sysirq.c:mtk_sysirq_domain_translate
```
```
In drivers/irqchip/irq-mtk-cirq.c (ffff8000106780a0)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_domain_translate
```
```
In drivers/irqchip/irq-imx-gpcv2.c (ffff800010678644)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_domain_alloc
```
```
In drivers/irqchip/irq-mvebu-icu.c (ffff800010679588)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-icu.c:mvebu_icu_subset_probe
```
```
In drivers/irqchip/irq-sni-exiu.c (ffff80001067bf68)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/irqchip/irq-sni-exiu.c:exiu_domain_alloc
```
```
In drivers/irqchip/irq-meson-gpio.c (ffff80001067c8a8)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/irqchip/irq-meson-gpio.c:meson_gpio_irq_domain_alloc
```
```
In drivers/irqchip/qcom-pdc.c (ffff80001067cd28)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/irqchip/qcom-pdc.c:qcom_pdc_alloc
```
```
In drivers/pinctrl/core.c (ffff80001068d098)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffff8000106c5290)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_translate
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpiolib-devres.c (ffff8000106c7268)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/pwm/core.c (ffff8000106d8ba4)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
```
```
In drivers/pci/msi.c (ffff800010715d04)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_domain_get_msi_rid
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (ffff80001071ab30)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_remove_epf_group
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffff80001071be58)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_bar
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msix
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msi
```
```
In drivers/video/backlight/backlight.c (ffff800010741cc4)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:devm_of_find_backlight
```
```
In drivers/acpi/acpi_apd.c (ffff800010776d00)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
```
```
In drivers/acpi/property.c (ffff80001077a860)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_device_data_of_node
```
```
In drivers/acpi/processor_perflib.c (ffff8000107a31a0)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
```
```
In drivers/acpi/arm64/iort.c (ffff800011481c20)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/arm64/iort.c:acpi_iort_init
```
```
In drivers/clk/clk-bulk.c (ffff8000107ba880)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/clk/clk.c (ffff8000107c35d8)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/clk/clk.c:__of_clk_get
  - drivers/clk/clk.c:of_clk_get_from_provider
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_disable
```
```
In drivers/clk/actions/owl-common.c (ffff8000107c9a84)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/clk/actions/owl-common.c:owl_clk_probe
```
```
In drivers/clk/imx/clk-imx8mm.c (ffff8000107d7a24)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
```
```
In drivers/clk/imx/clk-imx8mn.c (ffff8000107dad50)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
```
```
In drivers/clk/imx/clk-imx8mq.c (ffff8000107dd8bc)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
```
```
In drivers/clk/mediatek/clk-mtk.c (ffff8000107e1e20)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/clk/mediatek/clk-mtk.c:mtk_clk_register_dividers
  - drivers/clk/mediatek/clk-mtk.c:mtk_clk_register_composites
  - drivers/clk/mediatek/clk-mtk.c:mtk_clk_register_gates_with_dev
  - drivers/clk/mediatek/clk-mtk.c:mtk_clk_register_factors
  - drivers/clk/mediatek/clk-mtk.c:mtk_clk_register_fixed_clks
```
```
In drivers/clk/mediatek/clk-mux.c (ffff8000107e39b4)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_register_muxes
```
```
In drivers/clk/renesas/renesas-cpg-mssr.c (ffff8000114885e0)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_register_core_clk
```
```
In drivers/regulator/core.c (ffff800010844890)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_put
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:set_machine_constraints
```
```
In drivers/reset/core.c (ffff80001084ce4c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_control_array_get
  - drivers/reset/core.c:__devm_reset_control_get
```
```
In drivers/tty/tty_audit.c (ffff8000108637e4)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
```
```
In drivers/tty/serial/8250/8250_dw.c (ffff8000108918dc)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dw.c:dw8250_probe
```
```
In drivers/iommu/iommu.c (ffff8000108c53c8)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/iommu/dma-iommu.c (ffff8000108c8c5c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_get_resv_regions
```
```
In drivers/iommu/qcom_iommu.c (ffff8000108da144)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/iommu/qcom_iommu.c:qcom_iommu_add_device
```
```
In drivers/base/platform.c (ffff8000108ee640)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_device_unregister
```
```
In drivers/base/property.c (ffff8000108f32b0)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_irq_get
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_int_array
  - drivers/base/property.c:fwnode_property_read_int_array
```
```
In drivers/base/swnode.c (ffff8000108f6740)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_parent
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:software_node_put
  - drivers/base/swnode.c:software_node_get
  - drivers/base/swnode.c:to_software_node
```
```
In drivers/base/power/qos.c (ffff8000108fa38c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_get_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:__dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:__dev_pm_qos_hide_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:__dev_pm_qos_resume_latency
  - drivers/base/power/qos.c:dev_pm_qos_flags
```
```
In drivers/base/power/domain.c (ffff800010905efc)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_dev_pm_sync
  - drivers/base/power/domain.c:genpd_dev_pm_detach
  - drivers/base/power/domain.c:of_genpd_add_provider_onecell
  - drivers/base/power/domain.c:of_genpd_add_provider_simple
  - drivers/base/power/domain.c:genpd_remove
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:genpd_add_subdomain
  - drivers/base/power/domain.c:genpd_add_subdomain
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_restore_noirq
  - drivers/base/power/domain.c:genpd_thaw_noirq
  - drivers/base/power/domain.c:genpd_freeze_noirq
  - drivers/base/power/domain.c:genpd_resume_noirq
  - drivers/base/power/domain.c:genpd_finish_suspend
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/block/loop.c (ffff8000109221a8)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_attr_do_show_backing_file
```
```
In drivers/mfd/max8997-irq.c (ffff800010948588)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_init
  - drivers/mfd/max8997-irq.c:max8997_irq_sync_unlock
```
```
In drivers/nvdimm/namespace_devs.c (ffff80001095c110)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/spi/spi-mem.c (ffff8000109ca6c0)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/slip/slhc.c (ffff800010a05d40)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (ffff800010a47814)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
```
```
In drivers/usb/host/xhci-mtk-sch.c (ffff800010a8daf8)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_add_ep_quirk
```
```
In drivers/usb/roles/class.c (ffff800010a91618)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/usb/roles/class.c:usb_role_switch_unregister
  - drivers/usb/roles/class.c:role_store
  - drivers/usb/roles/class.c:role_show
```
```
In drivers/rtc/interface.c (ffff800010aa7be0)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffff800010ab03bc)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffff800010aba0ac)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/media/cec/cec-core.c (ffff80001149eeb0)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/media/cec/cec-core.c:cec_devnode_release
```
```
In drivers/media/cec/cec-adap.c (ffff800010abf81c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid
```
```
In drivers/power/supply/power_supply_core.c (ffff800010acc640)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/thermal/cpu_cooling.c (ffff800010adc31c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register
```
```
In drivers/watchdog/watchdog_dev.c (ffff800010ae0aa0)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
```
In drivers/edac/altera_edac.c (ffff800010b1620c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/edac/altera_edac.c:altr_edac_a10_device_add
  - drivers/edac/altera_edac.c:altr_edac_a10_device_add
  - drivers/edac/altera_edac.c:altr_init_a10_ecc_device_type
```
```
In drivers/opp/core.c (ffff800010b1aae4)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
```
```
In drivers/opp/of.c (ffff800010b1b450)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/cpuidle/governor.c (ffff800010b28060)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/cpuidle/governor.c:cpuidle_governor_latency_req
```
```
In drivers/mmc/core/block.c (ffff800010b416d4)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_remove
  - drivers/mmc/core/block.c:mmc_blk_remove
```
```
In drivers/leds/led-core.c (ffff800010b4898c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_compose_name
```
```
In drivers/leds/led-class.c (ffff800010b49948)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/leds/led-class.c:devm_led_classdev_release
```
```
In drivers/firmware/ti_sci.c (ffff800010b55478)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/firmware/ti_sci.c:ti_sci_cmd_rm_udmap_rx_flow_cfg
  - drivers/firmware/ti_sci.c:ti_sci_cmd_rm_udmap_rx_ch_cfg
  - drivers/firmware/ti_sci.c:ti_sci_cmd_rm_udmap_tx_ch_cfg
  - drivers/firmware/ti_sci.c:ti_sci_cmd_ring_get_config
  - drivers/firmware/ti_sci.c:ti_sci_cmd_ring_config
```
```
In drivers/firmware/arm_scmi/driver.c (ffff800010b560c8)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/driver.c:scmi_mbox_free_channel
```
```
In drivers/firmware/imx/scu-pd.c (ffff800010b62cc8)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/of/property.c (ffff800010b6ed60)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/of/property.c:of_fwnode_graph_parse_endpoint
  - drivers/of/property.c:of_fwnode_graph_get_port_parent
  - drivers/of/property.c:of_fwnode_graph_get_remote_endpoint
  - drivers/of/property.c:of_fwnode_graph_get_next_endpoint
  - drivers/of/property.c:of_fwnode_graph_get_next_endpoint
  - drivers/of/property.c:of_fwnode_get_reference_args
  - drivers/of/property.c:of_fwnode_get_reference_args
  - drivers/of/property.c:of_fwnode_get_named_child_node
  - drivers/of/property.c:of_fwnode_get_next_child_node
  - drivers/of/property.c:of_fwnode_get_next_child_node
  - drivers/of/property.c:of_fwnode_get_parent
  - drivers/of/property.c:of_fwnode_property_read_string_array
  - drivers/of/property.c:of_fwnode_property_read_int_array
  - drivers/of/property.c:of_fwnode_property_present
  - drivers/of/property.c:of_fwnode_device_is_available
  - drivers/of/property.c:of_fwnode_put
  - drivers/of/property.c:of_fwnode_get
```
```
In drivers/devfreq/devfreq.c (ffff800010b85e08)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:try_then_request_governor
  - drivers/devfreq/devfreq.c:find_devfreq_governor
```
```
In drivers/extcon/extcon.c (ffff800010b88cac)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/filter.c (ffff800010bfe1c8)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ethernet/eth.c (ffff800010c36fa4)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_platform_get_mac_address
```
```
In net/sched/cls_api.c (ffff800010c44924)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_release
```
```
In net/ipv4/ip_output.c (ffff800010c64204)
Location: include/linux/err.h:39
Inline: True
```
```
In net/ipv4/udp.c (ffff800010c9e464)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/udp_offload.c (ffff800010ca0a18)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffff800010cab880)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffff800010cbf8c4)
Location: include/linux/err.h:39
Inline: True
```
```
In net/ipv4/gre_offload.c (ffff800010cc2c0c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/addrconf.c (ffff800010d09c1c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_dev_config
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
```
In net/ipv6/udp.c (ffff800010d25b2c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/ip6_offload.c (ffff800010d54cdc)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
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
In init/main.c (c1500e10)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/arm/mach-exynos/suspend.c (c032d87c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/arm/mach-exynos/suspend.c:exynos_pmu_domain_translate
```
```
In arch/arm/mach-imx/gpc.c (c0332898)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/arm/mach-imx/gpc.c:imx_gpc_domain_translate
```
```
In arch/arm/mach-omap2/timer.c (c1512a6c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/arm/mach-omap2/timer.c:omap_dm_timer_init_one
```
```
In arch/arm/mach-omap2/omap_hwmod.c (c1513f5c)
Location: include/linux/err.h:39
Inline: True
```
```
In arch/arm/mach-omap2/omap-wakeupgen.c (c033c120)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap-wakeupgen.c:wakeupgen_domain_translate
```
```
In kernel/power/qos.c (c03b8b84)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_add_request
  - kernel/power/qos.c:freq_qos_add_request
  - kernel/power/qos.c:freq_qos_read_value
  - kernel/power/qos.c:freq_qos_read_value
  - kernel/power/qos.c:pm_qos_debug_show
  - kernel/power/qos.c:pm_qos_debug_show
```
```
In kernel/irq/irqdomain.c (c03d4048)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_domain_associate_many
  - kernel/irq/irqdomain.c:irq_find_matching_fwspec
  - kernel/irq/irqdomain.c:irq_domain_remove
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/relay.c (c044ac24)
Location: include/linux/err.h:39
Inline: True
```
```
In mm/zswap.c (c0541740)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
  - mm/zswap.c:zswap_cpu_comp_prepare
```
```
In mm/ksm.c (c05465f4)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:break_ksm
```
```
In fs/namei.c (c057bdc8)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/namei.c:trailing_symlink
```
```
In fs/namespace.c (c0596910)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:mnt_warn_timestamp_expiry
```
```
In fs/d_path.c (c05ac5b4)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/d_path.c:prepend_path
```
```
In fs/posix_acl.c (c05efa38)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/proc/task_mmu.c (c0600dd0)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (c0606974)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
```
```
In fs/exportfs/expfs.c (c06bc174)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/debugfs/inode.c (c06d1084)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/tracefs/inode.c (c06d41d4)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
```
```
In fs/pstore/platform.c (c06d5070)
Location: include/linux/err.h:39
Inline: True
```
```
In security/smack/smack_lsm.c (c0722b2c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/apparmorfs.c (c073aa38)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:remove_rawdata_dents
```
```
In security/apparmor/domain.c (c0746990)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
```
In security/apparmor/label.c (c075515c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_strn_parse
```
```
In security/apparmor/mount.c (c0756d60)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
```
```
In crypto/api.c (c076649c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In block/genhd.c (c07a5358)
Location: include/linux/err.h:39
Inline: True
```
```
In block/blk-mq-debugfs.c (c07cb82c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
```
In lib/rhashtable.c (c07dc954)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In drivers/irqchip/irq-alpine-msi.c (c0813278)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/irqchip/irq-alpine-msi.c:alpine_msix_middle_domain_alloc
```
```
In drivers/irqchip/exynos-combiner.c (c081380c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/irqchip/exynos-combiner.c:combiner_irq_domain_xlate
```
```
In drivers/irqchip/irq-hip04.c (c0813b64)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/irqchip/irq-hip04.c:hip04_irq_domain_xlate
```
```
In drivers/irqchip/irq-tegra.c (c081416c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/irqchip/irq-tegra.c:tegra_ictlr_domain_translate
```
```
In drivers/irqchip/irq-gic.c (c0814c28)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_irq_domain_translate
```
```
In drivers/irqchip/irq-gic-v2m.c (c154b700)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_init
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_of_init
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_of_init
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_irq_domain_alloc
```
```
In drivers/irqchip/irq-gic-v3.c (c0816a5c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_irq_domain_translate
```
```
In drivers/irqchip/irq-gic-v3-mbi.c (c154c310)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-mbi.c:mbi_init
  - drivers/irqchip/irq-gic-v3-mbi.c:mbi_irq_domain_alloc
```
```
In drivers/irqchip/irq-gic-v3-its.c (c154cb20)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_init
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_gic_domain_alloc
```
```
In drivers/irqchip/irq-gic-v3-its-platform-msi.c (c081d464)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its-platform-msi.c:its_pmsi_prepare
```
```
In drivers/irqchip/irq-crossbar.c (c08205bc)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/irqchip/irq-crossbar.c:crossbar_domain_translate
  - drivers/irqchip/irq-crossbar.c:crossbar_domain_alloc
```
```
In drivers/irqchip/irq-vf610-mscm-ir.c (c154ddac)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/irqchip/irq-vf610-mscm-ir.c:vf610_mscm_ir_of_init
```
```
In drivers/irqchip/irq-mtk-sysirq.c (c0820ebc)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/irqchip/irq-mtk-sysirq.c:mtk_sysirq_domain_translate
```
```
In drivers/irqchip/irq-mtk-cirq.c (c0821254)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_domain_translate
```
```
In drivers/irqchip/irq-imx-gpcv2.c (c0821804)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_domain_alloc
```
```
In drivers/irqchip/irq-meson-gpio.c (c0822398)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/irqchip/irq-meson-gpio.c:meson_gpio_irq_domain_alloc
```
```
In drivers/irqchip/qcom-pdc.c (c0822888)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/irqchip/qcom-pdc.c:qcom_pdc_alloc
```
```
In drivers/bus/ti-sysc.c (c08275d4)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/pinctrl/core.c (c082f140)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/gpio/gpiolib.c (c085de90)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_translate
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpiolib-devres.c (c0864c04)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/pwm/core.c (c0875448)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
```
```
In drivers/pci/msi.c (c08a0640)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_domain_get_msi_rid
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (c08a49a4)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_remove_epf_group
```
```
In drivers/pci/endpoint/pci-epc-core.c (c08a4b00)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msix
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msi
```
```
In drivers/video/backlight/backlight.c (c08c6710)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:devm_of_find_backlight
```
```
In drivers/clk/clk-bulk.c (c08e6928)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/clk/clk.c (c08eefcc)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/clk/clk.c:__of_clk_get
  - drivers/clk/clk.c:of_clk_get_from_provider
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_disable
```
```
In drivers/clk/actions/owl-common.c (c08f5918)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/clk/actions/owl-common.c:owl_clk_probe
```
```
In drivers/clk/imx/clk-imx5.c (c155bd24)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx51_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx51_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx51_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx51_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx51_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx51_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx51_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx51_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx51_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx51_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx51_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx51_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx51_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx51_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx51_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx51_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx51_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx51_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx51_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx51_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx51_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx51_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx51_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx51_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx50_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx50_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx50_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx50_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx50_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx50_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx50_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx50_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx50_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx50_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx50_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx50_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx50_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx50_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx50_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx50_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx50_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx50_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx50_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx50_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx50_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
```
```
In drivers/clk/imx/clk-vf610.c (c15786e0)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
```
```
In drivers/clk/mediatek/clk-mtk.c (c08ff0a8)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/clk/mediatek/clk-mtk.c:mtk_clk_register_dividers
  - drivers/clk/mediatek/clk-mtk.c:mtk_clk_register_composites
  - drivers/clk/mediatek/clk-mtk.c:mtk_clk_register_gates_with_dev
  - drivers/clk/mediatek/clk-mtk.c:mtk_clk_register_factors
  - drivers/clk/mediatek/clk-mtk.c:mtk_clk_register_fixed_clks
```
```
In drivers/clk/mediatek/clk-mux.c (c09009bc)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_register_muxes
```
```
In drivers/clk/renesas/renesas-cpg-mssr.c (c158144c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_register_core_clk
```
```
In drivers/clk/tegra/clk.c (c158630c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/clk/tegra/clk.c:tegra_register_devclks
  - drivers/clk/tegra/clk.c:tegra_init_from_table
```
```
In drivers/clk/ti/clkctrl.c (c158d074)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/clk/ti/clkctrl.c:_ti_omap4_clkctrl_setup
  - drivers/clk/ti/clkctrl.c:_ti_clkctrl_clk_register
```
```
In drivers/clk/ti/adpll.c (c091ae60)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/clk/ti/adpll.c:ti_adpll_free_resources
```
```
In drivers/soc/tegra/flowctrl.c (c093ac10)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/soc/tegra/flowctrl.c:flowctrl_read_cpu_csr
  - drivers/soc/tegra/flowctrl.c:flowctrl_update
```
```
In drivers/regulator/core.c (c094eb30)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_put
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:set_machine_constraints
```
```
In drivers/reset/core.c (c09592c8)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_control_array_get
  - drivers/reset/core.c:__devm_reset_control_get
```
```
In drivers/tty/tty_audit.c (c0969518)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
```
```
In drivers/iommu/iommu.c (c09bd210)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/iommu/qcom_iommu.c (c09cb6c4)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/iommu/qcom_iommu.c:qcom_iommu_add_device
```
```
In drivers/base/platform.c (c09dc1a8)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_device_unregister
```
```
In drivers/base/property.c (c09dfc1c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_irq_get
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_int_array
  - drivers/base/property.c:fwnode_property_read_int_array
```
```
In drivers/base/swnode.c (c09e2788)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_parent
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:software_node_put
  - drivers/base/swnode.c:software_node_get
  - drivers/base/swnode.c:to_software_node
```
```
In drivers/base/power/qos.c (c09e57ec)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_get_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:__dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:__dev_pm_qos_hide_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:__dev_pm_qos_resume_latency
  - drivers/base/power/qos.c:dev_pm_qos_flags
```
```
In drivers/base/power/domain.c (c09efc64)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_dev_pm_sync
  - drivers/base/power/domain.c:genpd_dev_pm_detach
  - drivers/base/power/domain.c:of_genpd_add_provider_onecell
  - drivers/base/power/domain.c:of_genpd_add_provider_simple
  - drivers/base/power/domain.c:genpd_remove
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:genpd_add_subdomain
  - drivers/base/power/domain.c:genpd_add_subdomain
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_restore_noirq
  - drivers/base/power/domain.c:genpd_thaw_noirq
  - drivers/base/power/domain.c:genpd_freeze_noirq
  - drivers/base/power/domain.c:genpd_resume_noirq
  - drivers/base/power/domain.c:genpd_finish_suspend
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/block/loop.c (c0a05fbc)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_attr_do_show_backing_file
```
```
In drivers/mfd/max8997-irq.c (c0a316dc)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_init
  - drivers/mfd/max8997-irq.c:max8997_irq_sync_unlock
```
```
In drivers/mtd/mtdcore.c (c0a90a34)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/mtd/mtdcore.c:add_mtd_device
  - drivers/mtd/mtdcore.c:add_mtd_device
  - drivers/mtd/mtdcore.c:add_mtd_device
  - drivers/mtd/mtdcore.c:add_mtd_device
```
```
In drivers/mtd/nand/raw/omap2.c (c0aab0f0)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/omap2.c:omap_nand_probe
```
```
In drivers/spi/spi-mem.c (c0ab3cd4)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/slip/slhc.c (c0ae0fcc)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (c0b19fc8)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
```
```
In drivers/usb/host/xhci-mtk-sch.c (c0b601e8)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_add_ep_quirk
```
```
In drivers/usb/roles/class.c (c0b74e50)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/usb/roles/class.c:usb_role_switch_unregister
  - drivers/usb/roles/class.c:role_store
  - drivers/usb/roles/class.c:role_show
```
```
In drivers/rtc/interface.c (c0b870d0)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (c0b919dc)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy
```
```
In drivers/i2c/busses/i2c-designware-master.c (c0b997b8)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/media/cec/cec-core.c (c15a11c0)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/media/cec/cec-core.c:cec_devnode_release
```
```
In drivers/media/cec/cec-adap.c (c0ba151c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid
```
```
In drivers/power/supply/power_supply_core.c (c0bac730)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/thermal/cpu_cooling.c (c0bbc86c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register
```
```
In drivers/watchdog/watchdog_dev.c (c0bc0d20)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
```
In drivers/opp/core.c (c0bf55f8)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
```
```
In drivers/opp/of.c (c0bf5b68)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/opp/of.c:_opp_table_free_required_tables
```
```
In drivers/cpuidle/governor.c (c0c02cf4)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/cpuidle/governor.c:cpuidle_governor_latency_req
```
```
In drivers/mmc/core/block.c (c0c1c4c4)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_remove
  - drivers/mmc/core/block.c:mmc_blk_remove
```
```
In drivers/mmc/host/omap_hsmmc.c (c0c2b570)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe
```
```
In drivers/mmc/host/sdhci-esdhc-imx.c (c0c2d884)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_readl_le
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_readl_le
```
```
In drivers/leds/led-core.c (c0c32408)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_compose_name
```
```
In drivers/leds/led-class.c (c0c32da8)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/leds/led-class.c:devm_led_classdev_release
```
```
In drivers/firmware/arm_scmi/driver.c (c0c3768c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/driver.c:scmi_mbox_free_channel
```
```
In drivers/firmware/imx/scu-pd.c (c0c41418)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/of/property.c (c0c51b1c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/of/property.c:of_fwnode_graph_parse_endpoint
  - drivers/of/property.c:of_fwnode_graph_get_port_parent
  - drivers/of/property.c:of_fwnode_graph_get_remote_endpoint
  - drivers/of/property.c:of_fwnode_graph_get_next_endpoint
  - drivers/of/property.c:of_fwnode_graph_get_next_endpoint
  - drivers/of/property.c:of_fwnode_get_reference_args
  - drivers/of/property.c:of_fwnode_get_reference_args
  - drivers/of/property.c:of_fwnode_get_named_child_node
  - drivers/of/property.c:of_fwnode_get_next_child_node
  - drivers/of/property.c:of_fwnode_get_next_child_node
  - drivers/of/property.c:of_fwnode_get_parent
  - drivers/of/property.c:of_fwnode_property_read_string_array
  - drivers/of/property.c:of_fwnode_property_read_int_array
  - drivers/of/property.c:of_fwnode_property_present
  - drivers/of/property.c:of_fwnode_device_is_available
  - drivers/of/property.c:of_fwnode_put
  - drivers/of/property.c:of_fwnode_get
```
```
In drivers/devfreq/devfreq.c (c0c68e6c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/extcon/extcon.c (c0c6dcb8)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/filter.c (c0d18938)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ethernet/eth.c (c0d49904)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_platform_get_mac_address
```
```
In net/sched/cls_api.c (c0d551e0)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_release
```
```
In net/ipv4/ip_output.c (c0d73068)
Location: include/linux/err.h:39
Inline: True
```
```
In net/ipv4/udp.c (c0da923c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/udp_offload.c (c0dadbcc)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (c0db877c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/inet_fragment.c (c0dcb2a8)
Location: include/linux/err.h:39
Inline: True
```
```
In net/ipv4/gre_offload.c (c0dce440)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/addrconf.c (c0e10288)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_dev_config
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
```
In net/ipv6/udp.c (c0e293a4)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/ip6_offload.c (c0e55304)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
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
In init/main.c (c000000001343f54)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/powerpc/sysdev/mpic.c (c0000000000b4354)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/powerpc/sysdev/mpic.c:mpic_host_match
```
```
In arch/powerpc/sysdev/mpic_msi.c (c0000000000b6f7c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/powerpc/sysdev/mpic_msi.c:mpic_msi_init_allocator
```
```
In arch/powerpc/sysdev/i8259.c (c0000000000b8c84)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/powerpc/sysdev/i8259.c:i8259_host_match
```
```
In arch/powerpc/platforms/powernv/opal-irqchip.c (c0000000000cce14)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-irqchip.c:opal_event_match
```
```
In kernel/power/qos.c (c0000000001c542c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_add_request
  - kernel/power/qos.c:freq_qos_add_request
  - kernel/power/qos.c:freq_qos_read_value
  - kernel/power/qos.c:freq_qos_read_value
  - kernel/power/qos.c:pm_qos_debug_show
  - kernel/power/qos.c:pm_qos_debug_show
```
```
In kernel/irq/irqdomain.c (c0000000001df398)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_strict_mappings
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_domain_associate_many
  - kernel/irq/irqdomain.c:irq_find_matching_fwspec
  - kernel/irq/irqdomain.c:irq_domain_remove
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/relay.c (c000000000289c18)
Location: include/linux/err.h:39
Inline: True
```
```
In kernel/trace/trace_events_hist.c (c0000000002e5e8c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
```
In mm/zswap.c (c000000000401f40)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
  - mm/zswap.c:zswap_cpu_comp_prepare
```
```
In mm/ksm.c (c00000000041ca34)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:break_ksm
```
```
In mm/khugepaged.c (c00000000044b254)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/namei.c (c00000000048ee10)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/namei.c:trailing_symlink
```
```
In fs/namespace.c (c0000000004b022c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/namespace.c:mnt_warn_timestamp_expiry
```
```
In fs/d_path.c (c0000000004d42f4)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/posix_acl.c (c000000000536408)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/proc/task_mmu.c (c00000000054dc10)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (c000000000555f64)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
```
```
In fs/exportfs/expfs.c (c0000000006428f8)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/debugfs/inode.c (c00000000065ee38)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/tracefs/inode.c (c000000000663258)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
```
```
In fs/pstore/platform.c (c000000000664870)
Location: include/linux/err.h:39
Inline: True
```
```
In security/smack/smack_lsm.c (c0000000006d5bf4)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/apparmorfs.c (c0000000006fa8d0)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:remove_rawdata_dents
```
```
In security/apparmor/domain.c (c00000000070b180)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
```
In security/apparmor/label.c (c000000000720dc4)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_strn_parse
```
```
In security/apparmor/mount.c (c000000000723434)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
```
```
In crypto/api.c (c00000000073c498)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_larval_destroy
```
```
In block/genhd.c (c0000000007932f4)
Location: include/linux/err.h:39
Inline: True
```
```
In block/blk-mq-debugfs.c (c0000000007c4dd8)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
```
In lib/rhashtable.c (c0000000007dcae4)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In drivers/pinctrl/core.c (c000000000825dec)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/gpio/gpiolib.c (c000000000841e50)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/gpio/gpiolib-devres.c (c000000000843b14)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_unhinge
```
```
In drivers/pwm/core.c (c00000000084f98c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (c00000000088ad00)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_remove_epf_group
```
```
In drivers/pci/endpoint/pci-epc-core.c (c00000000088b224)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_bar
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msi
```
```
In drivers/video/backlight/backlight.c (c0000000008a1f5c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:devm_of_find_backlight
```
```
In drivers/regulator/core.c (c0000000008e0c3c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_put
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:set_machine_constraints
```
```
In drivers/reset/core.c (c0000000008ebf40)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_control_array_get
  - drivers/reset/core.c:__devm_reset_control_get
```
```
In drivers/tty/tty_audit.c (c000000000902700)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
```
```
In drivers/iommu/iommu.c (c00000000096cec0)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/base/platform.c (c000000000987184)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_device_unregister
```
```
In drivers/base/property.c (c00000000098cef0)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_irq_get
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_int_array
  - drivers/base/property.c:fwnode_property_read_int_array
```
```
In drivers/base/swnode.c (c000000000991adc)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_parent
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:software_node_put
  - drivers/base/swnode.c:software_node_get
  - drivers/base/swnode.c:to_software_node
```
```
In drivers/base/power/qos.c (c0000000009967c8)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_get_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:__dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:__dev_pm_qos_hide_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:__dev_pm_qos_resume_latency
  - drivers/base/power/qos.c:dev_pm_qos_flags
```
```
In drivers/base/power/domain.c (c0000000009a4bd4)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_dev_pm_sync
  - drivers/base/power/domain.c:genpd_dev_pm_detach
  - drivers/base/power/domain.c:of_genpd_add_provider_onecell
  - drivers/base/power/domain.c:of_genpd_add_provider_simple
  - drivers/base/power/domain.c:genpd_remove
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:genpd_add_subdomain
  - drivers/base/power/domain.c:genpd_add_subdomain
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_restore_noirq
  - drivers/base/power/domain.c:genpd_thaw_noirq
  - drivers/base/power/domain.c:genpd_freeze_noirq
  - drivers/base/power/domain.c:genpd_resume_noirq
  - drivers/base/power/domain.c:genpd_finish_suspend
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/block/loop.c (c0000000009c7a78)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_attr_do_show_backing_file
```
```
In drivers/mfd/max8997-irq.c (c0000000009f36f4)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_init
  - drivers/mfd/max8997-irq.c:max8997_irq_sync_unlock
```
```
In drivers/nvdimm/namespace_devs.c (c000000000a0d534)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/spi/spi-mem.c (c000000000a8bfd4)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/slip/slhc.c (c000000000aacf68)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (c000000000b0c434)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
```
```
In drivers/rtc/interface.c (c000000000b89e48)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (c000000000b93304)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy
```
```
In drivers/i2c/busses/i2c-designware-master.c (c000000000b9d0b0)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/media/cec/cec-core.c (c0000000013b5144)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/media/cec/cec-core.c:cec_devnode_release
```
```
In drivers/media/cec/cec-adap.c (c000000000ba13b8)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid
```
```
In drivers/power/supply/power_supply_core.c (c000000000badc48)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/thermal/cpu_cooling.c (c000000000bc46a8)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register
```
```
In drivers/watchdog/watchdog_dev.c (c000000000bc7114)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
```
In drivers/opp/core.c (c000000000c0c9ec)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
```
```
In drivers/opp/of.c (c000000000c0d338)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/opp/of.c:_opp_table_free_required_tables
```
```
In drivers/cpuidle/governor.c (c000000000c1f56c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/cpuidle/governor.c:cpuidle_governor_latency_req
```
```
In drivers/leds/led-core.c (c000000000c3d110)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_compose_name
```
```
In drivers/leds/led-class.c (c000000000c3e038)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/leds/led-class.c:devm_led_classdev_release
```
```
In drivers/of/property.c (c000000000c49d38)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/of/property.c:of_fwnode_graph_parse_endpoint
  - drivers/of/property.c:of_fwnode_graph_get_port_parent
  - drivers/of/property.c:of_fwnode_graph_get_remote_endpoint
  - drivers/of/property.c:of_fwnode_graph_get_next_endpoint
  - drivers/of/property.c:of_fwnode_graph_get_next_endpoint
  - drivers/of/property.c:of_fwnode_get_reference_args
  - drivers/of/property.c:of_fwnode_get_reference_args
  - drivers/of/property.c:of_fwnode_get_named_child_node
  - drivers/of/property.c:of_fwnode_get_next_child_node
  - drivers/of/property.c:of_fwnode_get_next_child_node
  - drivers/of/property.c:of_fwnode_get_parent
  - drivers/of/property.c:of_fwnode_property_read_string_array
  - drivers/of/property.c:of_fwnode_property_read_int_array
  - drivers/of/property.c:of_fwnode_property_present
  - drivers/of/property.c:of_fwnode_device_is_available
  - drivers/of/property.c:of_fwnode_put
  - drivers/of/property.c:of_fwnode_get
```
```
In drivers/devfreq/devfreq.c (c000000000c649f0)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/extcon/extcon.c (c000000000c68e24)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/filter.c (c000000000ce5c84)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ethernet/eth.c (c000000000d2f348)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_platform_get_mac_address
```
```
In net/sched/cls_api.c (c000000000d3fc64)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_release
```
```
In net/ipv4/ip_output.c (c000000000d6716c)
Location: include/linux/err.h:39
Inline: True
```
```
In net/ipv4/udp.c (c000000000db0530)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/udp_offload.c (c000000000db3348)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (c000000000dc2230)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/inet_fragment.c (c000000000dda6fc)
Location: include/linux/err.h:39
Inline: True
```
```
In net/ipv4/gre_offload.c (c000000000ddeacc)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/addrconf.c (c000000000e344ec)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_dev_config
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
```
In net/ipv6/udp.c (c000000000e5570c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/ip6_offload.c (c000000000e8d8f0)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
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
In init/main.c (ffffffe000000b38)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In kernel/power/qos.c (ffffffe00010d27a)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_add_request
  - kernel/power/qos.c:freq_qos_add_request
  - kernel/power/qos.c:freq_qos_read_value
  - kernel/power/qos.c:freq_qos_read_value
  - kernel/power/qos.c:pm_qos_debug_show
  - kernel/power/qos.c:pm_qos_debug_show
```
```
In kernel/irq/irqdomain.c (ffffffe00011bd7c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_domain_associate_many
  - kernel/irq/irqdomain.c:irq_find_matching_fwspec
  - kernel/irq/irqdomain.c:irq_domain_remove
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/relay.c (ffffffe00016d4f8)
Location: include/linux/err.h:39
Inline: True
```
```
In mm/zswap.c (ffffffe00022a06c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
  - mm/zswap.c:zswap_cpu_comp_prepare
```
```
In mm/ksm.c (ffffffe000234f58)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:break_ksm
```
```
In fs/namei.c (ffffffe000262a7e)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/namei.c:trailing_symlink
```
```
In fs/namespace.c (ffffffe000277a3e)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/namespace.c:mnt_warn_timestamp_expiry
```
```
In fs/d_path.c (ffffffe00028cf5a)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/posix_acl.c (ffffffe0002c5562)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffe0002d1fa2)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (ffffffe0002d7ffc)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
```
```
In fs/exportfs/expfs.c (ffffffe00036cf4c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/debugfs/inode.c (ffffffe00037f9d6)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/tracefs/inode.c (ffffffe000382dca)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
```
```
In fs/pstore/platform.c (ffffffe000383c8a)
Location: include/linux/err.h:39
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffe0003c4fec)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/apparmorfs.c (ffffffe0003d8714)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:remove_rawdata_dents
```
```
In security/apparmor/domain.c (ffffffe0003e2742)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
```
In security/apparmor/label.c (ffffffe0003eed5c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_strn_parse
```
```
In security/apparmor/mount.c (ffffffe0003f068c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
```
```
In crypto/api.c (ffffffe0003fde5c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In block/genhd.c (ffffffe00043695c)
Location: include/linux/err.h:39
Inline: True
```
```
In block/blk-mq-debugfs.c (ffffffe000455dca)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
```
In lib/rhashtable.c (ffffffe000464172)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In drivers/pinctrl/core.c (ffffffe00049926c)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffe0004a5084)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_translate
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpiolib-devres.c (ffffffe0004aaca6)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/pwm/core.c (ffffffe0004b1ade)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
```
```
In drivers/pci/msi.c (ffffffe0004df3e6)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_domain_get_msi_rid
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffe0004e241a)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_remove_epf_group
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffe0004e260c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_bar
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msi
```
```
In drivers/clk/clk-bulk.c (ffffffe0005099aa)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/clk/clk.c (ffffffe000510f5a)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/clk/clk.c:__of_clk_get
  - drivers/clk/clk.c:of_clk_get_from_provider
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_disable
```
```
In drivers/regulator/core.c (ffffffe000525eb4)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_put
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:set_machine_constraints
```
```
In drivers/reset/core.c (ffffffe00052c65e)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_control_array_get
  - drivers/reset/core.c:__devm_reset_control_get
```
```
In drivers/tty/tty_audit.c (ffffffe00053a0ee)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
```
```
In drivers/base/platform.c (ffffffe00058159e)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_device_unregister
```
```
In drivers/base/property.c (ffffffe000584b5a)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_irq_get
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_int_array
  - drivers/base/property.c:fwnode_property_read_int_array
```
```
In drivers/base/swnode.c (ffffffe000587634)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_parent
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:software_node_put
  - drivers/base/swnode.c:software_node_get
  - drivers/base/swnode.c:to_software_node
```
```
In drivers/base/power/qos.c (ffffffe000589b70)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_get_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:__dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:__dev_pm_qos_hide_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:__dev_pm_qos_resume_latency
  - drivers/base/power/qos.c:dev_pm_qos_flags
```
```
In drivers/base/power/domain.c (ffffffe00058d594)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_dev_pm_sync
  - drivers/base/power/domain.c:genpd_dev_pm_detach
  - drivers/base/power/domain.c:of_genpd_add_provider_onecell
  - drivers/base/power/domain.c:of_genpd_add_provider_simple
  - drivers/base/power/domain.c:genpd_remove
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:genpd_add_subdomain
  - drivers/base/power/domain.c:genpd_add_subdomain
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/block/loop.c (ffffffe0005a115a)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_attr_do_show_backing_file
```
```
In drivers/mfd/max8997-irq.c (ffffffe0005ba536)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_init
  - drivers/mfd/max8997-irq.c:max8997_irq_sync_unlock
```
```
In drivers/nvdimm/namespace_devs.c (ffffffe0005ca646)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/spi/spi-mem.c (ffffffe00061a080)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/slip/slhc.c (ffffffe000630004)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (ffffffe0006642cc)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
```
```
In drivers/rtc/interface.c (ffffffe0006b3e0a)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffe0006b85a4)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffe0006be9b2)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/media/cec/cec-core.c (ffffffe000037096)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/media/cec/cec-core.c:cec_devnode_release
```
```
In drivers/media/cec/cec-adap.c (ffffffe0006c10d2)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid
```
```
In drivers/power/supply/power_supply_core.c (ffffffe0006c912a)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/watchdog/watchdog_dev.c (ffffffe0006d7dcc)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
```
In drivers/opp/core.c (ffffffe000703112)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
```
```
In drivers/opp/of.c (ffffffe00070355c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/opp/of.c:_opp_table_free_required_tables
```
```
In drivers/mmc/core/block.c (ffffffe0007185e6)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_remove
  - drivers/mmc/core/block.c:mmc_blk_remove
```
```
In drivers/leds/led-core.c (ffffffe00071c658)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_compose_name
```
```
In drivers/leds/led-class.c (ffffffe00071cf5e)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/leds/led-class.c:devm_led_classdev_release
```
```
In drivers/of/property.c (ffffffe000723432)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/of/property.c:of_fwnode_graph_parse_endpoint
  - drivers/of/property.c:of_fwnode_graph_get_port_parent
  - drivers/of/property.c:of_fwnode_graph_get_remote_endpoint
  - drivers/of/property.c:of_fwnode_graph_get_next_endpoint
  - drivers/of/property.c:of_fwnode_graph_get_next_endpoint
  - drivers/of/property.c:of_fwnode_get_reference_args
  - drivers/of/property.c:of_fwnode_get_reference_args
  - drivers/of/property.c:of_fwnode_get_named_child_node
  - drivers/of/property.c:of_fwnode_get_next_child_node
  - drivers/of/property.c:of_fwnode_get_next_child_node
  - drivers/of/property.c:of_fwnode_get_parent
  - drivers/of/property.c:of_fwnode_property_read_string_array
  - drivers/of/property.c:of_fwnode_property_read_int_array
  - drivers/of/property.c:of_fwnode_property_present
  - drivers/of/property.c:of_fwnode_device_is_available
  - drivers/of/property.c:of_fwnode_put
  - drivers/of/property.c:of_fwnode_get
```
```
In drivers/devfreq/devfreq.c (ffffffe00072f2d6)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:find_devfreq_governor
```
```
In drivers/extcon/extcon.c (ffffffe000731d26)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/filter.c (ffffffe000780294)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ethernet/eth.c (ffffffe0007a88e8)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_platform_get_mac_address
```
```
In net/sched/cls_api.c (ffffffe0007b2966)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_release
```
```
In net/ipv4/ip_output.c (ffffffe0007cb180)
Location: include/linux/err.h:39
Inline: True
```
```
In net/ipv4/udp.c (ffffffe0007f82f6)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/udp_offload.c (ffffffe0007fd0ce)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffe0008064e6)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffffffe000815510)
Location: include/linux/err.h:39
Inline: True
```
```
In net/ipv4/gre_offload.c (ffffffe00081804c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/addrconf.c (ffffffe000851796)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_dev_config
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
```
In net/ipv6/udp.c (ffffffe000866566)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/ip6_offload.c (ffffffe00088c5ec)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
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
In init/main.c (ffffffff8288ae66)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/kernel/irq.c (ffffffff81034e40)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81058ed1)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105af78)
Location: include/linux/err.h:39
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8105f22c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81060e7a)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81067d97)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106c050)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In kernel/power/qos.c (ffffffff811001b6)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_add_request
  - kernel/power/qos.c:freq_qos_add_request
  - kernel/power/qos.c:freq_qos_read_value
  - kernel/power/qos.c:freq_qos_read_value
  - kernel/power/qos.c:pm_qos_debug_show
  - kernel/power/qos.c:pm_qos_debug_show
```
```
In kernel/relay.c (ffffffff8118c76f)
Location: include/linux/err.h:39
Inline: True
```
```
In kernel/trace/trace_events_hist.c (ffffffff811c3cb4)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
```
In mm/zswap.c (ffffffff81286d11)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
  - mm/zswap.c:zswap_cpu_comp_prepare
```
```
In mm/ksm.c (ffffffff8129a31b)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:break_ksm
```
```
In mm/khugepaged.c (ffffffff812b6eab)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/namei.c (ffffffff812e2c74)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/namei.c:trailing_symlink
```
```
In fs/namespace.c (ffffffff812fa122)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/namespace.c:mnt_warn_timestamp_expiry
```
```
In fs/d_path.c (ffffffff81312b8e)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/posix_acl.c (ffffffff81359033)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81368aac)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (ffffffff8136e25b)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
```
```
In fs/exportfs/expfs.c (ffffffff81415a58)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/debugfs/inode.c (ffffffff81429b35)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff8142c5f5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
```
```
In fs/pstore/platform.c (ffffffff8142d2cc)
Location: include/linux/err.h:39
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff81476885)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/apparmorfs.c (ffffffff8148c7a7)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:remove_rawdata_dents
```
```
In security/apparmor/domain.c (ffffffff81498109)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
```
In security/apparmor/label.c (ffffffff814a5fe9)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_strn_parse
```
```
In security/apparmor/mount.c (ffffffff814a7bf3)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
```
```
In crypto/api.c (ffffffff814b6d99)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In block/genhd.c (ffffffff814f13cb)
Location: include/linux/err.h:39
Inline: True
```
```
In block/blk-mq-debugfs.c (ffffffff8151417b)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
```
In lib/rhashtable.c (ffffffff81523ad9)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In drivers/pinctrl/core.c (ffffffff81558bd9)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/gpio/gpiolib-devres.c (ffffffff81566815)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff815a2ca5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_remove_epf_group
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815a3079)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_bar
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msix
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msi
```
```
In drivers/video/backlight/backlight.c (0)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/acpi/acpi_apd.c (ffffffff815dacf5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
```
```
In drivers/acpi/property.c (ffffffff815de6a5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_device_data_of_node
```
```
In drivers/acpi/processor_thermal.c (ffffffff81606a84)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/acpi/processor_perflib.c (ffffffff81606e3c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
```
```
In drivers/clk/clk-bulk.c (ffffffff81611d95)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/clk/clk.c (ffffffff81618ac5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_disable
```
```
In drivers/xen/pcpu.c (ffffffff81637cee)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:sync_pcpu
```
```
In drivers/xen/xen-acpi-processor.c (0)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/regulator/core.c (ffffffff816415fa)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_put
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:set_machine_constraints
```
```
In drivers/reset/core.c (ffffffff8164753a)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/reset/core.c:__devm_reset_control_get
```
```
In drivers/tty/tty_audit.c (ffffffff816564af)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
```
```
In drivers/base/platform.c (ffffffff816c8259)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_device_unregister
```
```
In drivers/base/property.c (ffffffff816cb78a)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_int_array
  - drivers/base/property.c:fwnode_property_read_int_array
```
```
In drivers/base/swnode.c (ffffffff816ce14d)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_parent
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:software_node_put
  - drivers/base/swnode.c:software_node_get
  - drivers/base/swnode.c:to_software_node
```
```
In drivers/base/power/qos.c (ffffffff816d0f87)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_get_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:__dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:__dev_pm_qos_hide_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:__dev_pm_qos_resume_latency
  - drivers/base/power/qos.c:dev_pm_qos_flags
```
```
In drivers/base/power/domain.c (ffffffff816db7a1)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:pm_genpd_add_subdomain
  - drivers/base/power/domain.c:pm_genpd_add_subdomain
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_add_device
  - drivers/base/power/domain.c:pm_genpd_add_device
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_restore_noirq
  - drivers/base/power/domain.c:genpd_thaw_noirq
  - drivers/base/power/domain.c:genpd_freeze_noirq
  - drivers/base/power/domain.c:genpd_resume_noirq
  - drivers/base/power/domain.c:genpd_finish_suspend
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/block/loop.c (ffffffff816f2289)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_attr_do_show_backing_file
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8170eefc)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/spi/spi-mem.c (ffffffff8177b54a)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/slip/slhc.c (ffffffff81790aa5)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817c7133)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
```
```
In drivers/rtc/interface.c (ffffffff818195e5)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/media/cec/cec-core.c (ffffffff828f711d)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/media/cec/cec-core.c:cec_devnode_release
```
```
In drivers/media/cec/cec-adap.c (ffffffff818202c3)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8182832e)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff818344f5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
```
In drivers/opp/core.c (ffffffff81863dc1)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
```
```
In drivers/cpuidle/governor.c (ffffffff8187380c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/cpuidle/governor.c:cpuidle_governor_latency_req
```
```
In drivers/devfreq/devfreq.c (ffffffff8189aa7b)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/extcon/extcon.c (ffffffff8189d648)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/filter.c (ffffffff818fc304)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ethernet/eth.c (0)
Location: include/linux/err.h:39
Inline: True
```
```
In net/sched/cls_api.c (ffffffff819376f5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_release
```
```
In net/ipv4/ip_output.c (ffffffff81952b72)
Location: include/linux/err.h:39
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81985978)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/udp_offload.c (ffffffff8198acb7)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff819959d0)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffffffff819a6811)
Location: include/linux/err.h:39
Inline: True
```
```
In net/ipv4/gre_offload.c (ffffffff819a9635)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/addrconf.c (ffffffff819e66e4)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_dev_config
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
```
In net/ipv6/udp.c (ffffffff819ffb9e)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/ip6_offload.c (ffffffff81a277ff)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
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
In init/main.c (ffffffff82888e06)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/kernel/irq.c (ffffffff81024780)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810490d1)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104b108)
Location: include/linux/err.h:39
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8104f55c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810512da)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81058107)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8105c370)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In kernel/power/qos.c (ffffffff810f03a6)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_add_request
  - kernel/power/qos.c:freq_qos_add_request
  - kernel/power/qos.c:freq_qos_read_value
  - kernel/power/qos.c:freq_qos_read_value
  - kernel/power/qos.c:pm_qos_debug_show
  - kernel/power/qos.c:pm_qos_debug_show
```
```
In kernel/relay.c (ffffffff8117f84f)
Location: include/linux/err.h:39
Inline: True
```
```
In kernel/trace/trace_events_hist.c (ffffffff811b6a94)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
```
In mm/zswap.c (ffffffff81278b71)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
  - mm/zswap.c:zswap_cpu_comp_prepare
```
```
In mm/ksm.c (ffffffff8128bedb)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:break_ksm
```
```
In mm/khugepaged.c (ffffffff812a807b)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/namei.c (ffffffff812d38b4)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/namei.c:trailing_symlink
```
```
In fs/namespace.c (ffffffff812ead42)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/namespace.c:mnt_warn_timestamp_expiry
```
```
In fs/d_path.c (ffffffff8130379e)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/posix_acl.c (ffffffff81349ce3)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81359d5e)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (ffffffff8135eceb)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
```
```
In fs/exportfs/expfs.c (ffffffff814064d8)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/debugfs/inode.c (ffffffff8141a5b5)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff8141d075)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
```
```
In fs/pstore/platform.c (ffffffff8141dd4c)
Location: include/linux/err.h:39
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff814672a5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/apparmorfs.c (ffffffff8147d1c7)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:remove_rawdata_dents
```
```
In security/apparmor/domain.c (ffffffff81488b29)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
```
In security/apparmor/label.c (ffffffff81496a09)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_strn_parse
```
```
In security/apparmor/mount.c (ffffffff81498613)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
```
```
In crypto/api.c (ffffffff814a77b9)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In block/genhd.c (ffffffff814e190b)
Location: include/linux/err.h:39
Inline: True
```
```
In block/blk-mq-debugfs.c (ffffffff8150448b)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
```
In lib/rhashtable.c (ffffffff81513db9)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In drivers/pinctrl/core.c (ffffffff81549099)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/gpio/gpiolib-devres.c (ffffffff81557665)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff81591e45)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_remove_epf_group
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81592219)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_bar
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msix
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msi
```
```
In drivers/video/backlight/backlight.c (0)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815c5d20)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff815c6105)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
```
```
In drivers/acpi/property.c (ffffffff815c9ce5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_device_data_of_node
```
```
In drivers/acpi/processor_thermal.c (ffffffff815f1b54)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/acpi/processor_perflib.c (ffffffff815f1f0c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
```
```
In drivers/acpi/nfit/core.c (ffffffff815f8104)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/nfit/core.c:acpi_nfit_init
```
```
In drivers/clk/clk-bulk.c (ffffffff816062e5)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/clk/clk.c (ffffffff8160cff5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_disable
```
```
In drivers/regulator/core.c (ffffffff81621a9a)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_put
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:set_machine_constraints
```
```
In drivers/reset/core.c (ffffffff8162799a)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/reset/core.c:__devm_reset_control_get
```
```
In drivers/tty/tty_audit.c (ffffffff8163683f)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
```
```
In drivers/base/platform.c (ffffffff816a3559)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_device_unregister
```
```
In drivers/base/property.c (ffffffff816a6aba)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_int_array
  - drivers/base/property.c:fwnode_property_read_int_array
```
```
In drivers/base/swnode.c (ffffffff816a947d)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_parent
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:software_node_put
  - drivers/base/swnode.c:software_node_get
  - drivers/base/swnode.c:to_software_node
```
```
In drivers/base/power/qos.c (ffffffff816ac2a7)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_get_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:__dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:__dev_pm_qos_hide_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:__dev_pm_qos_resume_latency
  - drivers/base/power/qos.c:dev_pm_qos_flags
```
```
In drivers/base/power/domain.c (ffffffff816b5e21)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:pm_genpd_add_subdomain
  - drivers/base/power/domain.c:pm_genpd_add_subdomain
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_add_device
  - drivers/base/power/domain.c:pm_genpd_add_device
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_restore_noirq
  - drivers/base/power/domain.c:genpd_thaw_noirq
  - drivers/base/power/domain.c:genpd_freeze_noirq
  - drivers/base/power/domain.c:genpd_resume_noirq
  - drivers/base/power/domain.c:genpd_finish_suspend
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/block/loop.c (ffffffff816cc383)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_attr_do_show_backing_file
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816e297c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/nvdimm/btt.c (ffffffff828e845f)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/nvdimm/btt.c:nd_btt_init
  - drivers/nvdimm/btt.c:btt_debugfs_init
  - drivers/nvdimm/btt.c:btt_debugfs_init
```
```
In drivers/spi/spi-mem.c (ffffffff8175b2fa)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/slip/slhc.c (ffffffff81779875)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/rtc/interface.c (ffffffff817e0cd5)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/media/cec/cec-core.c (ffffffff828eea2f)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/media/cec/cec-core.c:cec_devnode_release
```
```
In drivers/media/cec/cec-adap.c (ffffffff817e7963)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid
```
```
In drivers/power/supply/power_supply_core.c (ffffffff817ef9be)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff817fbb85)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
```
In drivers/opp/core.c (ffffffff8182ca71)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
```
```
In drivers/cpuidle/governor.c (ffffffff8183d5fc)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/cpuidle/governor.c:cpuidle_governor_latency_req
```
```
In drivers/devfreq/devfreq.c (ffffffff81857f4b)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In net/core/filter.c (ffffffff818b6134)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ethernet/eth.c (0)
Location: include/linux/err.h:39
Inline: True
```
```
In net/sched/cls_api.c (ffffffff818f11f5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_release
```
```
In net/ipv4/ip_output.c (ffffffff8190c662)
Location: include/linux/err.h:39
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8193f438)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/udp_offload.c (ffffffff81944777)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff8194f490)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffffffff819602d1)
Location: include/linux/err.h:39
Inline: True
```
```
In net/ipv4/gre_offload.c (ffffffff819630f5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/addrconf.c (ffffffff819a34a4)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_dev_config
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
```
In net/ipv6/udp.c (ffffffff819bc95e)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/ip6_offload.c (ffffffff819e45bf)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
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
In init/main.c (ffffffff8289de66)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/kernel/irq.c (ffffffff81034ca0)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81059301)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b3a8)
Location: include/linux/err.h:39
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8105f65c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810612aa)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81068247)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106c500)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In kernel/power/qos.c (ffffffff810fd376)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_add_request
  - kernel/power/qos.c:freq_qos_add_request
  - kernel/power/qos.c:freq_qos_read_value
  - kernel/power/qos.c:freq_qos_read_value
  - kernel/power/qos.c:pm_qos_debug_show
  - kernel/power/qos.c:pm_qos_debug_show
```
```
In kernel/relay.c (ffffffff8118a53f)
Location: include/linux/err.h:39
Inline: True
```
```
In kernel/trace/trace_events_hist.c (ffffffff811c1a84)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
```
In mm/zswap.c (ffffffff81284b21)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
  - mm/zswap.c:zswap_cpu_comp_prepare
```
```
In mm/ksm.c (ffffffff8129812b)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:break_ksm
```
```
In mm/khugepaged.c (ffffffff812b4cbb)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/namei.c (ffffffff812e0a84)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/namei.c:trailing_symlink
```
```
In fs/namespace.c (ffffffff812f7f12)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/namespace.c:mnt_warn_timestamp_expiry
```
```
In fs/d_path.c (ffffffff8131097e)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/posix_acl.c (ffffffff81356b03)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8136657c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (ffffffff8136bd2b)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
```
```
In fs/exportfs/expfs.c (ffffffff81412dd8)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/debugfs/inode.c (ffffffff81425cd5)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff81428795)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
```
```
In fs/pstore/platform.c (ffffffff8142946c)
Location: include/linux/err.h:39
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff81472925)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/apparmorfs.c (ffffffff81488847)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:remove_rawdata_dents
```
```
In security/apparmor/domain.c (ffffffff814941a9)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
```
In security/apparmor/label.c (ffffffff814a2089)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_strn_parse
```
```
In security/apparmor/mount.c (ffffffff814a3c93)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
```
```
In crypto/api.c (ffffffff814b2e29)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In block/genhd.c (ffffffff814ed45b)
Location: include/linux/err.h:39
Inline: True
```
```
In block/blk-mq-debugfs.c (ffffffff8151020b)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
```
In lib/rhashtable.c (ffffffff8151fb69)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In drivers/pinctrl/core.c (ffffffff81554919)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/gpio/gpiolib-devres.c (ffffffff81565385)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff815a3235)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_remove_epf_group
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815a3609)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_bar
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msix
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msi
```
```
In drivers/video/backlight/backlight.c (0)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815df5e0)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff815df9c5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
```
```
In drivers/acpi/property.c (ffffffff815e3cf5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_device_data_of_node
```
```
In drivers/acpi/processor_thermal.c (ffffffff8162bb34)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/acpi/processor_perflib.c (ffffffff8162beec)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
```
```
In drivers/clk/clk-bulk.c (ffffffff8163fb75)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/clk/clk.c (ffffffff816468a5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_disable
```
```
In drivers/xen/pcpu.c (ffffffff81665a6e)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:sync_pcpu
```
```
In drivers/xen/xen-acpi-processor.c (0)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/regulator/core.c (ffffffff8166f9fa)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_put
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:set_machine_constraints
```
```
In drivers/reset/core.c (ffffffff816758fa)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/reset/core.c:__devm_reset_control_get
```
```
In drivers/tty/tty_audit.c (ffffffff8168486f)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
```
```
In drivers/base/platform.c (ffffffff816f67c9)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_device_unregister
```
```
In drivers/base/property.c (ffffffff816f9cfa)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_int_array
  - drivers/base/property.c:fwnode_property_read_int_array
```
```
In drivers/base/swnode.c (ffffffff816fc6bd)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_parent
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:software_node_put
  - drivers/base/swnode.c:software_node_get
  - drivers/base/swnode.c:to_software_node
```
```
In drivers/base/power/qos.c (ffffffff816ff4f7)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_get_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:__dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:__dev_pm_qos_hide_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:__dev_pm_qos_resume_latency
  - drivers/base/power/qos.c:dev_pm_qos_flags
```
```
In drivers/base/power/domain.c (ffffffff81709131)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:pm_genpd_add_subdomain
  - drivers/base/power/domain.c:pm_genpd_add_subdomain
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_add_device
  - drivers/base/power/domain.c:pm_genpd_add_device
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_restore_noirq
  - drivers/base/power/domain.c:genpd_thaw_noirq
  - drivers/base/power/domain.c:genpd_freeze_noirq
  - drivers/base/power/domain.c:genpd_resume_noirq
  - drivers/base/power/domain.c:genpd_finish_suspend
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/block/loop.c (ffffffff8171f969)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_attr_do_show_backing_file
```
```
In drivers/mfd/max8997-irq.c (ffffffff8173dd1f)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_init
  - drivers/mfd/max8997-irq.c:max8997_irq_sync_unlock
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8174dccc)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/spi/spi-mem.c (ffffffff817ab8ea)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/slip/slhc.c (ffffffff817c0e45)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81803bd3)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff818555e1)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
```
```
In drivers/rtc/interface.c (ffffffff8185aac5)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff818612af)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8186a7eb)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/media/cec/cec-core.c (ffffffff8290be41)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/media/cec/cec-core.c:cec_devnode_release
```
```
In drivers/media/cec/cec-adap.c (ffffffff8186d203)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8187526e)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81883b25)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
```
In drivers/opp/core.c (ffffffff818b4b51)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
```
```
In drivers/cpuidle/governor.c (ffffffff818c521c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/cpuidle/governor.c:cpuidle_governor_latency_req
```
```
In drivers/leds/led-class.c (ffffffff818d99bc)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/leds/led-class.c:devm_led_classdev_release
```
```
In drivers/devfreq/devfreq.c (ffffffff818ea16b)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/extcon/extcon.c (ffffffff818ecd38)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/filter.c (ffffffff8194d334)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ethernet/eth.c (0)
Location: include/linux/err.h:39
Inline: True
```
```
In net/sched/cls_api.c (ffffffff81988885)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_release
```
```
In net/netfilter/nfnetlink_queue.c (ffffffff8199a9d3)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_queue.c:nfqnl_enqueue_packet
```
```
In net/ipv4/ip_output.c (ffffffff819bd342)
Location: include/linux/err.h:39
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819f0148)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/udp_offload.c (ffffffff819f5487)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81a00270)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffffffff81a110b1)
Location: include/linux/err.h:39
Inline: True
```
```
In net/ipv4/gre_offload.c (ffffffff81a13ed5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/addrconf.c (ffffffff81a51164)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_dev_config
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
```
In net/ipv6/udp.c (ffffffff81a6a61e)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/ip6_offload.c (ffffffff81a933af)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
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
In init/main.c (ffffffff8289de66)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/kernel/irq.c (ffffffff81035bf6)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/irq.c:do_IRQ
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105a7a1)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c868)
Location: include/linux/err.h:39
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff81060bbc)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81062865)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81069927)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106dc00)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In kernel/power/qos.c (ffffffff811085e6)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_add_request
  - kernel/power/qos.c:freq_qos_add_request
  - kernel/power/qos.c:freq_qos_read_value
  - kernel/power/qos.c:freq_qos_read_value
  - kernel/power/qos.c:pm_qos_debug_show
  - kernel/power/qos.c:pm_qos_debug_show
```
```
In kernel/relay.c (ffffffff81197eaf)
Location: include/linux/err.h:39
Inline: True
```
```
In kernel/trace/trace_events_hist.c (ffffffff811cfb24)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
```
In mm/zswap.c (ffffffff812947c1)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_dead
  - mm/zswap.c:zswap_cpu_comp_prepare
```
```
In mm/ksm.c (ffffffff812a7ec7)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:break_ksm
```
```
In mm/khugepaged.c (ffffffff812c4ae1)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/namei.c (ffffffff812f3485)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/namei.c:trailing_symlink
```
```
In fs/namespace.c (ffffffff81309852)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/namespace.c:mnt_warn_timestamp_expiry
```
```
In fs/d_path.c (ffffffff81322171)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/posix_acl.c (ffffffff8136a1e3)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81378fee)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (ffffffff8137f5eb)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_mem_open
```
```
In fs/exportfs/expfs.c (ffffffff81428a58)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/debugfs/inode.c (ffffffff8143cb95)
Location: include/linux/err.h:39
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff8143f655)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
```
```
In fs/pstore/platform.c (ffffffff8144032c)
Location: include/linux/err.h:39
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff8148a215)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
```
```
In security/apparmor/apparmorfs.c (ffffffff814a0387)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:remove_rawdata_dents
```
```
In security/apparmor/domain.c (ffffffff814ac1d5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
```
In security/apparmor/label.c (ffffffff814ba849)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_strn_parse
```
```
In security/apparmor/mount.c (ffffffff814bc51b)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
```
```
In crypto/api.c (ffffffff814cb8a9)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In block/genhd.c (ffffffff8150666b)
Location: include/linux/err.h:39
Inline: True
```
```
In block/blk-mq-debugfs.c (ffffffff815299cb)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
```
In lib/rhashtable.c (ffffffff81539455)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In drivers/pinctrl/core.c (ffffffff8156e7a9)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/gpio/gpiolib-devres.c (ffffffff8157f2a5)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff815bd635)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_remove_epf_group
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815bda09)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_bar
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msix
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msi
```
```
In drivers/video/backlight/backlight.c (0)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815f94a0)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff815f9885)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
```
```
In drivers/acpi/property.c (ffffffff815fdbb5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_device_is_available
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
  - drivers/acpi/property.c:is_acpi_graph_node
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/property.c:acpi_device_data_of_node
```
```
In drivers/acpi/processor_thermal.c (ffffffff816459d4)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/acpi/processor_perflib.c (ffffffff81645d8c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
```
```
In drivers/clk/clk-bulk.c (ffffffff81659ec5)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/clk/clk.c (ffffffff81660e35)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_disable
```
```
In drivers/xen/pcpu.c (ffffffff8168001e)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:sync_pcpu
```
```
In drivers/xen/xen-acpi-processor.c (0)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/regulator/core.c (ffffffff8168a05a)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_put
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:set_machine_constraints
```
```
In drivers/reset/core.c (ffffffff8168ff5a)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/reset/core.c:__devm_reset_control_get
```
```
In drivers/tty/tty_audit.c (ffffffff8169ee7f)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
```
```
In drivers/base/platform.c (ffffffff81711069)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/base/platform.c:platform_device_register_full
  - drivers/base/platform.c:platform_device_unregister
```
```
In drivers/base/property.c (ffffffff8171459a)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_string_array
  - drivers/base/property.c:fwnode_property_read_int_array
  - drivers/base/property.c:fwnode_property_read_int_array
```
```
In drivers/base/swnode.c (ffffffff81716f5d)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:software_node_notify
  - drivers/base/swnode.c:fwnode_remove_software_node
  - drivers/base/swnode.c:software_node_get_reference_args
  - drivers/base/swnode.c:software_node_get_named_child_node
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_next_child
  - drivers/base/swnode.c:software_node_get_parent
  - drivers/base/swnode.c:software_node_read_string_array
  - drivers/base/swnode.c:software_node_read_int_array
  - drivers/base/swnode.c:software_node_property_present
  - drivers/base/swnode.c:software_node_put
  - drivers/base/swnode.c:software_node_get
  - drivers/base/swnode.c:to_software_node
```
```
In drivers/base/power/qos.c (ffffffff81719b07)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_get_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:__dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:__dev_pm_qos_hide_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_remove_notifier
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:dev_pm_qos_read_value
  - drivers/base/power/qos.c:__dev_pm_qos_resume_latency
  - drivers/base/power/qos.c:dev_pm_qos_flags
```
```
In drivers/base/power/domain.c (ffffffff81723ca1)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_remove
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:pm_genpd_remove_subdomain
  - drivers/base/power/domain.c:pm_genpd_add_subdomain
  - drivers/base/power/domain.c:pm_genpd_add_subdomain
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_remove_device
  - drivers/base/power/domain.c:pm_genpd_add_device
  - drivers/base/power/domain.c:pm_genpd_add_device
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_restore_noirq
  - drivers/base/power/domain.c:genpd_thaw_noirq
  - drivers/base/power/domain.c:genpd_freeze_noirq
  - drivers/base/power/domain.c:genpd_resume_noirq
  - drivers/base/power/domain.c:genpd_finish_suspend
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/power/domain.c:genpd_runtime_resume
  - drivers/base/power/domain.c:genpd_runtime_suspend
  - drivers/base/power/domain.c:genpd_dev_pm_qos_notifier
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/block/loop.c (ffffffff8173997d)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_attr_do_show_backing_file
```
```
In drivers/mfd/max8997-irq.c (ffffffff8175915f)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_init
  - drivers/mfd/max8997-irq.c:max8997_irq_sync_unlock
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8176914c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/spi/spi-mem.c (ffffffff817c587a)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/slip/slhc.c (ffffffff817db105)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8181dce3)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81870711)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_off
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
```
```
In drivers/rtc/interface.c (ffffffff81875bf5)
Location: include/linux/err.h:39
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8187c4bf)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:__unregister_dummy
  - drivers/i2c/i2c-core-base.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8188477b)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/media/cec/cec-core.c (ffffffff829122d3)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/media/cec/cec-core.c:cec_devnode_release
```
```
In drivers/media/cec/cec-adap.c (ffffffff81887193)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81890c0e)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8189f5e5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
```
In drivers/opp/core.c (ffffffff818d0e01)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
```
```
In drivers/cpuidle/governor.c (ffffffff818e167c)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/cpuidle/governor.c:cpuidle_governor_latency_req
```
```
In drivers/leds/led-class.c (ffffffff818f64dc)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/leds/led-class.c:devm_led_classdev_release
```
```
In drivers/devfreq/devfreq.c (ffffffff8190b1eb)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/extcon/extcon.c (ffffffff8190ddb8)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In net/core/filter.c (ffffffff8196ecf4)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ethernet/eth.c (0)
Location: include/linux/err.h:39
Inline: True
```
```
In net/sched/cls_api.c (ffffffff819aa805)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_release
```
```
In net/ipv4/ip_output.c (ffffffff819c6c52)
Location: include/linux/err.h:39
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819fa9cf)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/udp_offload.c (ffffffff819ff687)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81a0a2c0)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1ba19)
Location: include/linux/err.h:39
Inline: True
```
```
In net/ipv4/gre_offload.c (ffffffff81a1e8c5)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/addrconf.c (ffffffff81a5d0b4)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_dev_config
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
```
```
In net/ipv6/udp.c (ffffffff81a76c3b)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
```
```
In net/ipv6/ip6_offload.c (ffffffff81a9f4ff)
Location: include/linux/err.h:39
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
</details>
</li>
</ul>

## Differences
