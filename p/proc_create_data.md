# Function: <code>proc_create_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_data(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct file_operations *proc_fops, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8127f4a0)
Location: fs/proc/generic.c:484
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_if_init
  - kernel/exec_domain.c:proc_execdomains_init
  - kernel/resource.c:ioresources_init
  - kernel/resource.c:ioresources_init
  - kernel/sched/stats.c:proc_schedstat_init
  - kernel/sched/debug.c:init_sched_debug_procfs
  - kernel/irq/proc.c:init_irq_proc
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_prof_cpu_mask
  - kernel/time/timer_list.c:init_timer_list_procfs
  - kernel/time/timer_stats.c:init_tstats_procfs
  - kernel/dma.c:proc_dma_init
  - kernel/module.c:proc_modules_init
  - kernel/kallsyms.c:kallsyms_init
  - kernel/cgroup.c:cgroup_init
  - mm/vmstat.c:setup_vmstat
  - mm/vmstat.c:setup_vmstat
  - mm/vmstat.c:setup_vmstat
  - mm/vmstat.c:setup_vmstat
  - mm/slab_common.c:slab_proc_init
  - mm/vmalloc.c:proc_vmalloc_init
  - mm/swapfile.c:procswaps_init
  - fs/filesystems.c:proc_filesystems_init
  - fs/locks.c:proc_locks_init
  - fs/proc/proc_tty.c:proc_tty_register_driver
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/cmdline.c:proc_cmdline_init
  - fs/proc/consoles.c:proc_consoles_init
  - fs/proc/cpuinfo.c:proc_cpuinfo_init
  - fs/proc/devices.c:proc_devices_init
  - fs/proc/interrupts.c:proc_interrupts_init
  - fs/proc/loadavg.c:proc_loadavg_init
  - fs/proc/meminfo.c:proc_meminfo_init
  - fs/proc/stat.c:proc_stat_init
  - fs/proc/uptime.c:proc_uptime_init
  - fs/proc/version.c:proc_version_init
  - fs/proc/softirqs.c:proc_softirqs_init
  - fs/proc/kmsg.c:proc_kmsg_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/version_signature.c:proc_version_signature_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/jbd2/journal.c:jbd2_stats_proc_init
  - ipc/util.c:ipc_init_proc_interface
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - crypto/proc.c:crypto_init_proc
  - block/genhd.c:proc_genhd_init
  - block/genhd.c:proc_genhd_init
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/pci/proc.c:pci_proc_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/acpi/proc.c:acpi_sleep_proc_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/tty/sysrq.c:sysrq_init
  - drivers/char/misc.c:misc_init
  - drivers/scsi/scsi_devinfo.c:scsi_init_devinfo
  - drivers/scsi/scsi_proc.c:scsi_proc_host_add
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/rtc/rtc-proc.c:rtc_proc_add_device
  - drivers/md/md.c:md_init
  - net/core/sock.c:proto_init_net
  - net/core/neighbour.c:neigh_table_init
  - net/core/net-procfs.c:dev_mc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/sched/sch_api.c:psched_net_init
  - net/netlink/af_netlink.c:netlink_net_init
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/tcp_ipv4.c:tcp_proc_register
  - net/ipv4/raw.c:raw_init_net
  - net/ipv4/udp.c:udp_proc_register
  - net/ipv4/arp.c:arp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/ping.c:ping_v4_proc_init_net
  - net/xfrm/xfrm_proc.c:xfrm_proc_init
  - net/unix/af_unix.c:unix_net_init
  - net/ipv6/anycast.c:ac6_proc_init
  - net/ipv6/addrconf.c:if6_proc_net_init
  - net/ipv6/route.c:ip6_route_net_init_late
  - net/ipv6/route.c:ip6_route_net_init_late
  - net/ipv6/raw.c:raw6_init_net
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init
  - net/ipv6/proc.c:snmp6_register_dev
  - net/packet/af_packet.c:packet_net_init
  - net/wireless/wext-proc.c:wext_proc_init
```
**Symbols:**

```
ffffffff8127f4a0-ffffffff8127f55e: proc_create_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_data(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct file_operations *proc_fops, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812ac580)
Location: fs/proc/generic.c:489
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_if_init
  - kernel/exec_domain.c:proc_execdomains_init
  - kernel/resource.c:ioresources_init
  - kernel/resource.c:ioresources_init
  - kernel/sched/stats.c:proc_schedstat_init
  - kernel/sched/debug.c:init_sched_debug_procfs
  - kernel/irq/proc.c:init_irq_proc
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_prof_cpu_mask
  - kernel/time/timer_list.c:init_timer_list_procfs
  - kernel/time/timer_stats.c:init_tstats_procfs
  - kernel/dma.c:proc_dma_init
  - kernel/module.c:proc_modules_init
  - kernel/kallsyms.c:kallsyms_init
  - kernel/cgroup.c:cgroup_init
  - mm/vmstat.c:setup_vmstat
  - mm/vmstat.c:setup_vmstat
  - mm/vmstat.c:setup_vmstat
  - mm/vmstat.c:setup_vmstat
  - mm/slab_common.c:slab_proc_init
  - mm/vmalloc.c:proc_vmalloc_init
  - mm/swapfile.c:procswaps_init
  - fs/filesystems.c:proc_filesystems_init
  - fs/locks.c:proc_locks_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_register_driver
  - fs/proc/cmdline.c:proc_cmdline_init
  - fs/proc/consoles.c:proc_consoles_init
  - fs/proc/cpuinfo.c:proc_cpuinfo_init
  - fs/proc/devices.c:proc_devices_init
  - fs/proc/interrupts.c:proc_interrupts_init
  - fs/proc/loadavg.c:proc_loadavg_init
  - fs/proc/meminfo.c:proc_meminfo_init
  - fs/proc/stat.c:proc_stat_init
  - fs/proc/uptime.c:proc_uptime_init
  - fs/proc/version.c:proc_version_init
  - fs/proc/softirqs.c:proc_softirqs_init
  - fs/proc/kmsg.c:proc_kmsg_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/version_signature.c:proc_version_signature_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/jbd2/journal.c:jbd2_stats_proc_init
  - ipc/util.c:ipc_init_proc_interface
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - crypto/proc.c:crypto_init_proc
  - block/genhd.c:proc_genhd_init
  - block/genhd.c:proc_genhd_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/acpi/proc.c:acpi_sleep_proc_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/tty/sysrq.c:sysrq_init
  - drivers/char/misc.c:misc_init
  - drivers/scsi/scsi_devinfo.c:scsi_init_devinfo
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_host_add
  - drivers/rtc/rtc-proc.c:rtc_proc_add_device
  - drivers/md/md.c:md_init
  - net/core/sock.c:proto_init_net
  - net/core/neighbour.c:neigh_table_init
  - net/core/net-procfs.c:dev_mc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/sched/sch_api.c:psched_net_init
  - net/netlink/af_netlink.c:netlink_net_init
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/tcp_ipv4.c:tcp_proc_register
  - net/ipv4/raw.c:raw_init_net
  - net/ipv4/udp.c:udp_proc_register
  - net/ipv4/arp.c:arp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/ping.c:ping_v4_proc_init_net
  - net/xfrm/xfrm_proc.c:xfrm_proc_init
  - net/unix/af_unix.c:unix_net_init
  - net/ipv6/anycast.c:ac6_proc_init
  - net/ipv6/addrconf.c:if6_proc_net_init
  - net/ipv6/route.c:ip6_route_net_init_late
  - net/ipv6/route.c:ip6_route_net_init_late
  - net/ipv6/raw.c:raw6_init_net
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init
  - net/ipv6/proc.c:snmp6_register_dev
  - net/packet/af_packet.c:packet_net_init
  - net/wireless/wext-proc.c:wext_proc_init
```
**Symbols:**

```
ffffffff812ac580-ffffffff812ac63d: proc_create_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_data(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct file_operations *proc_fops, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812c1e70)
Location: fs/proc/generic.c:491
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_if_init
  - kernel/exec_domain.c:proc_execdomains_init
  - kernel/resource.c:ioresources_init
  - kernel/resource.c:ioresources_init
  - kernel/sched/stats.c:proc_schedstat_init
  - kernel/sched/debug.c:init_sched_debug_procfs
  - kernel/irq/proc.c:init_irq_proc
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_prof_cpu_mask
  - kernel/time/timer_list.c:init_timer_list_procfs
  - kernel/time/timer_stats.c:init_tstats_procfs
  - kernel/dma.c:proc_dma_init
  - kernel/module.c:proc_modules_init
  - kernel/kallsyms.c:kallsyms_init
  - kernel/cgroup.c:cgroup_init
  - mm/vmstat.c:setup_vmstat
  - mm/vmstat.c:setup_vmstat
  - mm/vmstat.c:setup_vmstat
  - mm/vmstat.c:setup_vmstat
  - mm/slab_common.c:slab_proc_init
  - mm/vmalloc.c:proc_vmalloc_init
  - mm/swapfile.c:procswaps_init
  - fs/filesystems.c:proc_filesystems_init
  - fs/locks.c:proc_locks_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_register_driver
  - fs/proc/cmdline.c:proc_cmdline_init
  - fs/proc/consoles.c:proc_consoles_init
  - fs/proc/cpuinfo.c:proc_cpuinfo_init
  - fs/proc/devices.c:proc_devices_init
  - fs/proc/interrupts.c:proc_interrupts_init
  - fs/proc/loadavg.c:proc_loadavg_init
  - fs/proc/meminfo.c:proc_meminfo_init
  - fs/proc/stat.c:proc_stat_init
  - fs/proc/uptime.c:proc_uptime_init
  - fs/proc/version.c:proc_version_init
  - fs/proc/softirqs.c:proc_softirqs_init
  - fs/proc/kmsg.c:proc_kmsg_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/version_signature.c:proc_version_signature_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/jbd2/journal.c:jbd2_stats_proc_init
  - ipc/util.c:ipc_init_proc_interface
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - crypto/proc.c:crypto_init_proc
  - block/genhd.c:proc_genhd_init
  - block/genhd.c:proc_genhd_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/acpi/proc.c:acpi_sleep_proc_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/tty/sysrq.c:sysrq_init
  - drivers/char/misc.c:misc_init
  - drivers/scsi/scsi_devinfo.c:scsi_init_devinfo
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_host_add
  - drivers/rtc/rtc-proc.c:rtc_proc_add_device
  - drivers/md/md.c:md_init
  - net/core/sock.c:proto_init_net
  - net/core/neighbour.c:neigh_table_init
  - net/core/net-procfs.c:dev_mc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/sched/sch_api.c:psched_net_init
  - net/netlink/af_netlink.c:netlink_net_init
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/tcp_ipv4.c:tcp_proc_register
  - net/ipv4/raw.c:raw_init_net
  - net/ipv4/udp.c:udp_proc_register
  - net/ipv4/arp.c:arp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/ping.c:ping_v4_proc_init_net
  - net/xfrm/xfrm_proc.c:xfrm_proc_init
  - net/unix/af_unix.c:unix_net_init
  - net/ipv6/anycast.c:ac6_proc_init
  - net/ipv6/addrconf.c:if6_proc_net_init
  - net/ipv6/route.c:ip6_route_net_init_late
  - net/ipv6/route.c:ip6_route_net_init_late
  - net/ipv6/raw.c:raw6_init_net
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init
  - net/ipv6/proc.c:snmp6_register_dev
  - net/packet/af_packet.c:packet_net_init
  - net/wireless/wext-proc.c:wext_proc_init
```
**Symbols:**

```
ffffffff812c1e70-ffffffff812c1f2d: proc_create_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_data(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct file_operations *proc_fops, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812cf0e0)
Location: fs/proc/generic.c:475
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_if_init
  - kernel/exec_domain.c:proc_execdomains_init
  - kernel/resource.c:ioresources_init
  - kernel/resource.c:ioresources_init
  - kernel/sched/stats.c:proc_schedstat_init
  - kernel/sched/debug.c:init_sched_debug_procfs
  - kernel/irq/proc.c:init_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_prof_cpu_mask
  - kernel/time/timer_list.c:init_timer_list_procfs
  - kernel/dma.c:proc_dma_init
  - kernel/module.c:proc_modules_init
  - kernel/kallsyms.c:kallsyms_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/slab_common.c:slab_proc_init
  - mm/vmalloc.c:proc_vmalloc_init
  - mm/swapfile.c:procswaps_init
  - fs/filesystems.c:proc_filesystems_init
  - fs/locks.c:proc_locks_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_register_driver
  - fs/proc/cmdline.c:proc_cmdline_init
  - fs/proc/consoles.c:proc_consoles_init
  - fs/proc/cpuinfo.c:proc_cpuinfo_init
  - fs/proc/devices.c:proc_devices_init
  - fs/proc/interrupts.c:proc_interrupts_init
  - fs/proc/loadavg.c:proc_loadavg_init
  - fs/proc/meminfo.c:proc_meminfo_init
  - fs/proc/stat.c:proc_stat_init
  - fs/proc/uptime.c:proc_uptime_init
  - fs/proc/version.c:proc_version_init
  - fs/proc/softirqs.c:proc_softirqs_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kmsg.c:proc_kmsg_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/version_signature.c:proc_version_signature_init
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/jbd2/journal.c:jbd2_stats_proc_init
  - ipc/util.c:ipc_init_proc_interface
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - crypto/proc.c:crypto_init_proc
  - block/genhd.c:proc_genhd_init
  - block/genhd.c:proc_genhd_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/acpi/proc.c:acpi_sleep_proc_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/tty/sysrq.c:sysrq_init
  - drivers/char/misc.c:misc_init
  - drivers/scsi/scsi_devinfo.c:scsi_init_devinfo
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_host_add
  - drivers/rtc/rtc-proc.c:rtc_proc_add_device
  - drivers/md/md.c:md_init
  - net/core/sock.c:proto_init_net
  - net/core/neighbour.c:neigh_table_init
  - net/core/net-procfs.c:dev_mc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/sched/sch_api.c:psched_net_init
  - net/netlink/af_netlink.c:netlink_net_init
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/tcp_ipv4.c:tcp_proc_register
  - net/ipv4/raw.c:raw_init_net
  - net/ipv4/udp.c:udp_proc_register
  - net/ipv4/arp.c:arp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/ping.c:ping_v4_proc_init_net
  - net/xfrm/xfrm_proc.c:xfrm_proc_init
  - net/unix/af_unix.c:unix_net_init
  - net/ipv6/anycast.c:ac6_proc_init
  - net/ipv6/addrconf.c:if6_proc_net_init
  - net/ipv6/route.c:ip6_route_net_init_late
  - net/ipv6/route.c:ip6_route_net_init_late
  - net/ipv6/raw.c:raw6_init_net
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init
  - net/ipv6/proc.c:snmp6_register_dev
  - net/packet/af_packet.c:packet_net_init
  - net/wireless/wext-proc.c:wext_proc_init
```
**Symbols:**

```
ffffffff812cf0e0-ffffffff812cf18e: proc_create_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_data(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct file_operations *proc_fops, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812f3830)
Location: fs/proc/generic.c:477
Inline: False
Direct callers:
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - fs/proc/generic.c:proc_create
  - fs/proc/proc_tty.c:proc_tty_register_driver
  - fs/ext4/sysfs.c:ext4_register_sysfs
  - fs/jbd2/journal.c:jbd2_stats_proc_init
  - ipc/util.c:ipc_init_proc_interface
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/acpi/button.c:acpi_button_add
  - drivers/scsi/scsi_proc.c:scsi_proc_host_add
  - drivers/rtc/rtc-proc.c:rtc_proc_add_device
  - net/core/neighbour.c:neigh_table_init
  - net/ipv4/tcp_ipv4.c:tcp_proc_register
  - net/ipv4/udp.c:udp_proc_register
  - net/ipv4/ping.c:ping_v4_proc_init_net
  - net/ipv6/proc.c:snmp6_register_dev
```
**Symbols:**

```
ffffffff812f3830-ffffffff812f38de: proc_create_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct proc_dir_entry *proc_create_data(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct file_operations *proc_fops, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813209c0)
Location: fs/proc/generic.c:534
Inline: True
Direct callers:
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - fs/proc/generic.c:proc_create
  - fs/jbd2/journal.c:jbd2_stats_proc_init
  - ipc/util.c:ipc_init_proc_interface
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/scsi/scsi_proc.c:scsi_proc_host_add
```
**Symbols:**

```
ffffffff813209c0-ffffffff81320a07: proc_create_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct proc_dir_entry *proc_create_data(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct file_operations *proc_fops, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81337ac0)
Location: fs/proc/generic.c:536
Inline: True
Direct callers:
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - fs/proc/generic.c:proc_create
  - fs/jbd2/journal.c:jbd2_stats_proc_init
  - ipc/util.c:ipc_init_proc_interface
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/scsi/scsi_proc.c:scsi_proc_host_add
```
**Symbols:**

```
ffffffff81337ac0-ffffffff81337b07: proc_create_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct proc_dir_entry *proc_create_data(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct file_operations *proc_fops, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8135fc30)
Location: fs/proc/generic.c:537
Inline: True
Direct callers:
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - fs/proc/generic.c:proc_create
  - fs/jbd2/journal.c:jbd2_stats_proc_init
  - ipc/util.c:ipc_init_proc_interface
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/scsi/scsi_proc.c:scsi_proc_host_add
```
**Symbols:**

```
ffffffff8135fc30-ffffffff8135fc77: proc_create_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct proc_dir_entry *proc_create_data(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct file_operations *proc_fops, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81377e90)
Location: fs/proc/generic.c:537
Inline: True
Direct callers:
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - fs/proc/generic.c:proc_create
  - fs/jbd2/journal.c:jbd2_stats_proc_init
  - ipc/util.c:ipc_init_proc_interface
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/scsi/scsi_proc.c:scsi_proc_host_add
```
**Symbols:**

```
ffffffff81377e90-ffffffff81377ed7: proc_create_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct proc_dir_entry *proc_create_data(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct proc_ops *proc_ops, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813c0ee9)
Location: fs/proc/generic.c:549
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_create
Direct callers:
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
  - ipc/util.c:ipc_init_proc_interface
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/scsi/scsi_proc.c:scsi_proc_host_add
```
**Symbols:**

```
ffffffff813c0dc0-ffffffff813c0e0d: proc_create_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct proc_dir_entry *proc_create_data(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct proc_ops *proc_ops, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813d2dd9)
Location: fs/proc/generic.c:569
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_create
Direct callers:
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
  - ipc/util.c:ipc_init_proc_interface
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/scsi/scsi_proc.c:scsi_proc_host_add
```
**Symbols:**

```
ffffffff813d2cb0-ffffffff813d2cfd: proc_create_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct proc_dir_entry *proc_create_data(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct proc_ops *proc_ops, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813d9c69)
Location: fs/proc/generic.c:564
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_create
Direct callers:
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
  - ipc/util.c:ipc_init_proc_interface
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/scsi/scsi_proc.c:scsi_proc_host_add
```
**Symbols:**

```
ffffffff813d9b40-ffffffff813d9b8d: proc_create_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct proc_dir_entry *proc_create_data(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct proc_ops *proc_ops, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8142b399)
Location: fs/proc/generic.c:564
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_create
Direct callers:
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
  - ipc/util.c:ipc_init_proc_interface
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/scsi/scsi_proc.c:scsi_proc_host_add
```
**Symbols:**

```
ffffffff8142b270-ffffffff8142b2bd: proc_create_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct proc_dir_entry *proc_create_data(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct proc_ops *proc_ops, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff814a4a69)
Location: fs/proc/generic.c:567
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_create
Direct callers:
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
  - ipc/util.c:ipc_init_proc_interface
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/scsi/scsi_proc.c:scsi_proc_host_add
```
**Symbols:**

```
ffffffff814a4910-ffffffff814a496c: proc_create_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct proc_dir_entry *proc_create_data(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct proc_ops *proc_ops, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81539f79)
Location: fs/proc/generic.c:567
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_create
Direct callers:
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
  - ipc/util.c:ipc_init_proc_interface
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/scsi/scsi_proc.c:scsi_proc_host_add
```
**Symbols:**

```
ffffffff81539df0-ffffffff81539e4c: proc_create_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct proc_dir_entry *proc_create_data(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct proc_ops *proc_ops, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81572219)
Location: fs/proc/generic.c:566
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_create
Direct callers:
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
  - ipc/util.c:ipc_init_proc_interface
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/scsi/scsi_proc.c:scsi_proc_host_add
```
**Symbols:**

```
ffffffff81572090-ffffffff815720ec: proc_create_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct proc_dir_entry *proc_create_data(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct proc_ops *proc_ops, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff815aabc9)
Location: fs/proc/generic.c:566
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_create
Direct callers:
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
  - ipc/util.c:ipc_init_proc_interface
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/scsi/scsi_proc.c:scsi_proc_host_add
```
**Symbols:**

```
ffffffff815aaa40-ffffffff815aaa9c: proc_create_data (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct proc_dir_entry *proc_create_data(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct file_operations *proc_fops, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffff800010443d38)
Location: fs/proc/generic.c:537
Inline: True
Direct callers:
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - fs/proc/generic.c:proc_create
  - fs/jbd2/journal.c:jbd2_stats_proc_init
  - ipc/util.c:ipc_init_proc_interface
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/scsi/scsi_proc.c:scsi_proc_host_add
```
**Symbols:**

```
ffff800010443d38-ffff800010443dac: proc_create_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct proc_dir_entry *proc_create_data(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct file_operations *proc_fops, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (c0608f58)
Location: fs/proc/generic.c:537
Inline: True
Direct callers:
  - arch/arm/kernel/atags_proc.c:init_atags_procfs
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - fs/proc/generic.c:proc_create
  - fs/jbd2/journal.c:jbd2_stats_proc_init
  - ipc/util.c:ipc_init_proc_interface
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/scsi/scsi_proc.c:scsi_proc_host_add
  - sound/core/info.c:snd_info_register
```
**Symbols:**

```
c0608f58-c0608fac: proc_create_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_data(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct file_operations *proc_fops, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (c0000000005594c0)
Location: fs/proc/generic.c:537
Inline: False
Direct callers:
  - arch/powerpc/kernel/proc_powerpc.c:proc_ppc64_init
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - fs/proc/generic.c:proc_create
  - fs/jbd2/journal.c:jbd2_stats_proc_init
  - ipc/util.c:ipc_init_proc_interface
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/scsi/scsi_proc.c:scsi_proc_host_add
```
**Symbols:**

```
c0000000005594c0-c000000000559530: proc_create_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct proc_dir_entry *proc_create_data(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct file_operations *proc_fops, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffe0002da7ae)
Location: fs/proc/generic.c:537
Inline: True
Direct callers:
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - fs/proc/generic.c:proc_create
  - fs/jbd2/journal.c:jbd2_stats_proc_init
  - ipc/util.c:ipc_init_proc_interface
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/scsi/scsi_proc.c:scsi_proc_host_add
```
**Symbols:**

```
ffffffe0002da7ae-ffffffe0002da810: proc_create_data (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct proc_dir_entry *proc_create_data(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct file_operations *proc_fops, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81370470)
Location: fs/proc/generic.c:537
Inline: True
Direct callers:
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - fs/proc/generic.c:proc_create
  - fs/jbd2/journal.c:jbd2_stats_proc_init
  - ipc/util.c:ipc_init_proc_interface
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/scsi/scsi_proc.c:scsi_proc_host_add
```
**Symbols:**

```
ffffffff81370470-ffffffff813704b7: proc_create_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct proc_dir_entry *proc_create_data(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct file_operations *proc_fops, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81360f00)
Location: fs/proc/generic.c:537
Inline: True
Direct callers:
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - fs/proc/generic.c:proc_create
  - fs/jbd2/journal.c:jbd2_stats_proc_init
  - ipc/util.c:ipc_init_proc_interface
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/scsi/scsi_proc.c:scsi_proc_host_add
```
**Symbols:**

```
ffffffff81360f00-ffffffff81360f47: proc_create_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct proc_dir_entry *proc_create_data(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct file_operations *proc_fops, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8136df40)
Location: fs/proc/generic.c:537
Inline: True
Direct callers:
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - fs/proc/generic.c:proc_create
  - fs/jbd2/journal.c:jbd2_stats_proc_init
  - ipc/util.c:ipc_init_proc_interface
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/scsi/scsi_proc.c:scsi_proc_host_add
```
**Symbols:**

```
ffffffff8136df40-ffffffff8136df87: proc_create_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct proc_dir_entry *proc_create_data(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct file_operations *proc_fops, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81381870)
Location: fs/proc/generic.c:537
Inline: True
Direct callers:
  - kernel/irq/proc.c:register_irq_proc
  - kernel/irq/proc.c:register_irq_proc
  - fs/proc/generic.c:proc_create
  - fs/jbd2/journal.c:jbd2_stats_proc_init
  - ipc/util.c:ipc_init_proc_interface
  - drivers/pci/proc.c:pci_proc_attach_device
  - drivers/scsi/scsi_proc.c:scsi_proc_host_add
```
**Symbols:**

```
ffffffff81381870-ffffffff813818b7: proc_create_data (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct proc_ops *proc_ops</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct file_operations *proc_fops</code>
</li>
</ul>
</details>
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
