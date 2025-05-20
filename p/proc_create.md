# Function: <code>proc_create</code>

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
In arch/x86/kernel/cpu/mtrr/if.c (ffffffff81f6b4a9)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_if_init
```
```
In kernel/exec_domain.c (ffffffff81f7b843)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - kernel/exec_domain.c:proc_execdomains_init
```
```
In kernel/resource.c (ffffffff81f7ba6e)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - kernel/resource.c:ioresources_init
  - kernel/resource.c:ioresources_init
```
```
In kernel/sched/stats.c (ffffffff81f7e5d0)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - kernel/sched/stats.c:proc_schedstat_init
```
```
In kernel/sched/debug.c (ffffffff81f7e5f2)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - kernel/sched/debug.c:init_sched_debug_procfs
```
```
In kernel/irq/proc.c (ffffffff810e21f4)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - kernel/irq/proc.c:init_irq_proc
```
```
In kernel/profile.c (ffffffff81819127)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_prof_cpu_mask
```
```
In kernel/time/timer_list.c (ffffffff81f80722)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - kernel/time/timer_list.c:init_timer_list_procfs
```
```
In kernel/time/timer_stats.c (ffffffff81f80a89)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - kernel/time/timer_stats.c:init_tstats_procfs
```
```
In kernel/dma.c (ffffffff81f80c32)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - kernel/dma.c:proc_dma_init
```
```
In kernel/module.c (ffffffff81f80e2b)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - kernel/module.c:proc_modules_init
```
```
In kernel/kallsyms.c (ffffffff81f80fc6)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - kernel/kallsyms.c:kallsyms_init
```
```
In kernel/cgroup.c (ffffffff81f81f76)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_init
```
```
In mm/vmstat.c (ffffffff81f88585)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - mm/vmstat.c:setup_vmstat
  - mm/vmstat.c:setup_vmstat
  - mm/vmstat.c:setup_vmstat
  - mm/vmstat.c:setup_vmstat
```
```
In mm/slab_common.c (ffffffff81f89a6e)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - mm/slab_common.c:slab_proc_init
```
```
In mm/vmalloc.c (ffffffff81f8a935)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - mm/vmalloc.c:proc_vmalloc_init
```
```
In mm/swapfile.c (ffffffff81f8b689)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - mm/swapfile.c:procswaps_init
```
```
In fs/filesystems.c (ffffffff81f8ecae)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - fs/filesystems.c:proc_filesystems_init
```
```
In fs/locks.c (ffffffff81f9064c)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - fs/locks.c:proc_locks_init
```
```
In fs/proc/proc_tty.c (ffffffff81f90cf7)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
```
```
In fs/proc/cmdline.c (ffffffff81f90d35)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - fs/proc/cmdline.c:proc_cmdline_init
```
```
In fs/proc/consoles.c (ffffffff81f90d57)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - fs/proc/consoles.c:proc_consoles_init
```
```
In fs/proc/cpuinfo.c (ffffffff81f90d79)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - fs/proc/cpuinfo.c:proc_cpuinfo_init
```
```
In fs/proc/devices.c (ffffffff81f90d9b)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - fs/proc/devices.c:proc_devices_init
```
```
In fs/proc/interrupts.c (ffffffff81f90dbd)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - fs/proc/interrupts.c:proc_interrupts_init
```
```
In fs/proc/loadavg.c (ffffffff81f90ddf)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - fs/proc/loadavg.c:proc_loadavg_init
```
```
In fs/proc/meminfo.c (ffffffff81f90e01)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - fs/proc/meminfo.c:proc_meminfo_init
```
```
In fs/proc/stat.c (ffffffff81f90e23)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - fs/proc/stat.c:proc_stat_init
```
```
In fs/proc/uptime.c (ffffffff81f90e45)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - fs/proc/uptime.c:proc_uptime_init
```
```
In fs/proc/version.c (ffffffff81f90e67)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - fs/proc/version.c:proc_version_init
```
```
In fs/proc/softirqs.c (ffffffff81f90e89)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - fs/proc/softirqs.c:proc_softirqs_init
```
```
In fs/proc/kcore.c (ffffffff81f90f26)
Location: include/linux/proc_fs.h:30
Inline: True
```
```
In fs/proc/vmcore.c (ffffffff81f91a9f)
Location: include/linux/proc_fs.h:30
Inline: True
```
```
In fs/proc/kmsg.c (ffffffff81f91b99)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - fs/proc/kmsg.c:proc_kmsg_init
```
```
In fs/proc/page.c (ffffffff81f91bbe)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
```
```
In fs/proc/version_signature.c (ffffffff81f91c1d)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - fs/proc/version_signature.c:proc_version_signature_init
```
```
In security/keys/proc.c (ffffffff81f9805b)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
```
```
In crypto/proc.c (ffffffff81f9a5d6)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - crypto/proc.c:crypto_init_proc
```
```
In block/genhd.c (ffffffff81f9b47c)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - block/genhd.c:proc_genhd_init
  - block/genhd.c:proc_genhd_init
```
```
In drivers/pci/proc.c (ffffffff81f9f6a1)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - drivers/pci/proc.c:pci_proc_init
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff81fa0054)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/acpi/proc.c (ffffffff81fa1782)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - drivers/acpi/proc.c:acpi_sleep_proc_init
```
```
In drivers/tty/sysrq.c (ffffffff81fa635d)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_init
```
```
In drivers/char/misc.c (ffffffff81fa809e)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_init
```
```
In drivers/connector/connector.c (ffffffff81541d08)
Location: include/linux/proc_fs.h:30
Inline: True
```
```
In drivers/scsi/scsi_devinfo.c (ffffffff81faea6e)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - drivers/scsi/scsi_devinfo.c:scsi_init_devinfo
```
```
In drivers/scsi/scsi_proc.c (ffffffff81faeaf5)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
```
```
In drivers/scsi/sg.c (ffffffff81faedb2)
Location: include/linux/proc_fs.h:30
Inline: True
```
```
In drivers/input/input.c (ffffffff81fb1e94)
Location: include/linux/proc_fs.h:30
Inline: True
```
```
In drivers/md/md.c (ffffffff81fb3833)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - drivers/md/md.c:md_init
```
```
In net/core/sock.c (ffffffff817012e6)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - net/core/sock.c:proto_init_net
```
```
In net/core/net-procfs.c (ffffffff81737a46)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - net/core/net-procfs.c:dev_mc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
```
```
In net/sched/sch_api.c (ffffffff81743056)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - net/sched/sch_api.c:psched_net_init
```
```
In net/netlink/af_netlink.c (ffffffff8174ad76)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_net_init
```
```
In net/netfilter/nf_log.c (ffffffff81751c26)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_net_init
```
```
In net/ipv4/route.c (ffffffff81753a86)
Location: include/linux/proc_fs.h:30
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81784a86)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_init_net
```
```
In net/ipv4/arp.c (ffffffff8178c206)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_net_init
```
```
In net/ipv4/igmp.c (ffffffff81795996)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
```
```
In net/ipv4/fib_trie.c (ffffffff817a1686)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
```
```
In net/ipv4/proc.c (ffffffff817a6726)
Location: include/linux/proc_fs.h:30
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff817a8c2b)
Location: include/linux/proc_fs.h:30
Inline: True
```
```
In net/xfrm/xfrm_proc.c (ffffffff817bd496)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - net/xfrm/xfrm_proc.c:xfrm_proc_init
```
```
In net/unix/af_unix.c (ffffffff817bd958)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_net_init
```
```
In net/ipv6/anycast.c (ffffffff817c4456)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_proc_init
```
```
In net/ipv6/addrconf.c (ffffffff817ca1a6)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:if6_proc_net_init
```
```
In net/ipv6/route.c (ffffffff817d43a6)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_net_init_late
  - net/ipv6/route.c:ip6_route_net_init_late
```
```
In net/ipv6/raw.c (ffffffff817e5526)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_init_net
```
```
In net/ipv6/mcast.c (ffffffff817e989a)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff817f6226)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init
```
```
In net/ipv6/ip6mr.c (ffffffff817f9a11)
Location: include/linux/proc_fs.h:30
Inline: True
```
```
In net/ipv6/proc.c (ffffffff817febb6)
Location: include/linux/proc_fs.h:30
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81802cc7)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_net_init
```
```
In net/wireless/wext-proc.c (ffffffff8180aaa6)
Location: include/linux/proc_fs.h:30
Inline: True
Inline callers:
  - net/wireless/wext-proc.c:wext_proc_init
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
In arch/x86/kernel/cpu/mtrr/if.c (ffffffff81f937d8)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_if_init
```
```
In kernel/exec_domain.c (ffffffff81fa4358)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - kernel/exec_domain.c:proc_execdomains_init
```
```
In kernel/resource.c (ffffffff81fa4805)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - kernel/resource.c:ioresources_init
  - kernel/resource.c:ioresources_init
```
```
In kernel/sched/stats.c (ffffffff81fa7495)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - kernel/sched/stats.c:proc_schedstat_init
```
```
In kernel/sched/debug.c (ffffffff81fa74db)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - kernel/sched/debug.c:init_sched_debug_procfs
```
```
In kernel/irq/proc.c (ffffffff810e7c74)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - kernel/irq/proc.c:init_irq_proc
```
```
In kernel/profile.c (ffffffff81892d7e)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_prof_cpu_mask
```
```
In kernel/time/timer_list.c (ffffffff81fa978e)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - kernel/time/timer_list.c:init_timer_list_procfs
```
```
In kernel/time/timer_stats.c (ffffffff81fa9abb)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - kernel/time/timer_stats.c:init_tstats_procfs
```
```
In kernel/dma.c (ffffffff81fa9c67)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - kernel/dma.c:proc_dma_init
```
```
In kernel/module.c (ffffffff81fa9e42)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - kernel/module.c:proc_modules_init
```
```
In kernel/kallsyms.c (ffffffff81faa364)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - kernel/kallsyms.c:kallsyms_init
```
```
In kernel/cgroup.c (ffffffff81fab507)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_init
```
```
In mm/vmstat.c (ffffffff81fb1ff1)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - mm/vmstat.c:setup_vmstat
  - mm/vmstat.c:setup_vmstat
  - mm/vmstat.c:setup_vmstat
  - mm/vmstat.c:setup_vmstat
```
```
In mm/slab_common.c (ffffffff81fb34d9)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - mm/slab_common.c:slab_proc_init
```
```
In mm/vmalloc.c (ffffffff81fb457c)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - mm/vmalloc.c:proc_vmalloc_init
```
```
In mm/swapfile.c (ffffffff81fb5346)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - mm/swapfile.c:procswaps_init
```
```
In fs/filesystems.c (ffffffff81fb92a5)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/filesystems.c:proc_filesystems_init
```
```
In fs/locks.c (ffffffff81fbacbd)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/locks.c:proc_locks_init
```
```
In fs/proc/proc_tty.c (ffffffff81fbb64c)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
```
```
In fs/proc/cmdline.c (ffffffff81fbb68a)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/proc/cmdline.c:proc_cmdline_init
```
```
In fs/proc/consoles.c (ffffffff81fbb6ac)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/proc/consoles.c:proc_consoles_init
```
```
In fs/proc/cpuinfo.c (ffffffff81fbb6ce)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/proc/cpuinfo.c:proc_cpuinfo_init
```
```
In fs/proc/devices.c (ffffffff81fbb6f0)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/proc/devices.c:proc_devices_init
```
```
In fs/proc/interrupts.c (ffffffff81fbb712)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/proc/interrupts.c:proc_interrupts_init
```
```
In fs/proc/loadavg.c (ffffffff81fbb734)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/proc/loadavg.c:proc_loadavg_init
```
```
In fs/proc/meminfo.c (ffffffff81fbb756)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/proc/meminfo.c:proc_meminfo_init
```
```
In fs/proc/stat.c (ffffffff81fbb778)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/proc/stat.c:proc_stat_init
```
```
In fs/proc/uptime.c (ffffffff81fbb79a)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/proc/uptime.c:proc_uptime_init
```
```
In fs/proc/version.c (ffffffff81fbb7bc)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/proc/version.c:proc_version_init
```
```
In fs/proc/softirqs.c (ffffffff81fbb7de)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/proc/softirqs.c:proc_softirqs_init
```
```
In fs/proc/kcore.c (ffffffff81fbb87b)
Location: include/linux/proc_fs.h:31
Inline: True
```
```
In fs/proc/vmcore.c (ffffffff81fbc453)
Location: include/linux/proc_fs.h:31
Inline: True
```
```
In fs/proc/kmsg.c (ffffffff81fbc539)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/proc/kmsg.c:proc_kmsg_init
```
```
In fs/proc/page.c (ffffffff81fbc55e)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
```
```
In fs/proc/version_signature.c (ffffffff81fbc5bd)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/proc/version_signature.c:proc_version_signature_init
```
```
In security/keys/proc.c (ffffffff81fc2c5e)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
```
```
In crypto/proc.c (ffffffff81fc53fe)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - crypto/proc.c:crypto_init_proc
```
```
In block/genhd.c (ffffffff81fc681e)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - block/genhd.c:proc_genhd_init
  - block/genhd.c:proc_genhd_init
```
```
In drivers/pci/proc.c (ffffffff81fcae78)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - drivers/pci/proc.c:pci_proc_init
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff81fcb850)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/acpi/proc.c (ffffffff81fcd624)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - drivers/acpi/proc.c:acpi_sleep_proc_init
```
```
In drivers/tty/sysrq.c (ffffffff81fd26dc)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_init
```
```
In drivers/char/misc.c (ffffffff81fd44b2)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_init
```
```
In drivers/connector/connector.c (ffffffff81593648)
Location: include/linux/proc_fs.h:31
Inline: True
```
```
In drivers/scsi/scsi_devinfo.c (ffffffff81fdb4a5)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - drivers/scsi/scsi_devinfo.c:scsi_init_devinfo
```
```
In drivers/scsi/scsi_proc.c (ffffffff81fdb533)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
```
```
In drivers/scsi/sg.c (ffffffff81fdb7f1)
Location: include/linux/proc_fs.h:31
Inline: True
```
```
In drivers/input/input.c (ffffffff81fde9e8)
Location: include/linux/proc_fs.h:31
Inline: True
```
```
In drivers/md/md.c (ffffffff81fe041b)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - drivers/md/md.c:md_init
```
```
In net/core/sock.c (ffffffff81767e86)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/core/sock.c:proto_init_net
```
```
In net/core/net-procfs.c (ffffffff817a3d06)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/core/net-procfs.c:dev_mc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
```
```
In net/sched/sch_api.c (ffffffff817afee6)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/sched/sch_api.c:psched_net_init
```
```
In net/netlink/af_netlink.c (ffffffff817b79b6)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_net_init
```
```
In net/netfilter/nf_log.c (ffffffff817bdc86)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_net_init
```
```
In net/ipv4/route.c (ffffffff817bfb56)
Location: include/linux/proc_fs.h:31
Inline: True
```
```
In net/ipv4/raw.c (ffffffff817f2066)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_init_net
```
```
In net/ipv4/arp.c (ffffffff817f9826)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_net_init
```
```
In net/ipv4/igmp.c (ffffffff81803386)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
```
```
In net/ipv4/fib_trie.c (ffffffff8180f366)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
```
```
In net/ipv4/proc.c (ffffffff81814416)
Location: include/linux/proc_fs.h:31
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81816431)
Location: include/linux/proc_fs.h:31
Inline: True
```
```
In net/xfrm/xfrm_proc.c (ffffffff8182a406)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/xfrm/xfrm_proc.c:xfrm_proc_init
```
```
In net/unix/af_unix.c (ffffffff8182a8c8)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_net_init
```
```
In net/ipv6/anycast.c (ffffffff81831506)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_proc_init
```
```
In net/ipv6/addrconf.c (ffffffff818372d6)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:if6_proc_net_init
```
```
In net/ipv6/route.c (ffffffff81841aa6)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_net_init_late
  - net/ipv6/route.c:ip6_route_net_init_late
```
```
In net/ipv6/raw.c (ffffffff81853806)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_init_net
```
```
In net/ipv6/mcast.c (ffffffff818580ea)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff818653d6)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init
```
```
In net/ipv6/ip6mr.c (ffffffff81869281)
Location: include/linux/proc_fs.h:31
Inline: True
```
```
In net/ipv6/proc.c (ffffffff8186e546)
Location: include/linux/proc_fs.h:31
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81874057)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_net_init
```
```
In net/wireless/wext-proc.c (ffffffff8187c5b6)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/wireless/wext-proc.c:wext_proc_init
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
In arch/x86/kernel/cpu/mtrr/if.c (ffffffff81fcede4)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_if_init
```
```
In kernel/exec_domain.c (ffffffff81fdfc33)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - kernel/exec_domain.c:proc_execdomains_init
```
```
In kernel/resource.c (ffffffff81fe01ca)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - kernel/resource.c:ioresources_init
  - kernel/resource.c:ioresources_init
```
```
In kernel/sched/stats.c (ffffffff81fe3164)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - kernel/sched/stats.c:proc_schedstat_init
```
```
In kernel/sched/debug.c (ffffffff81fe31aa)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - kernel/sched/debug.c:init_sched_debug_procfs
```
```
In kernel/irq/proc.c (ffffffff810ee6b4)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - kernel/irq/proc.c:init_irq_proc
```
```
In kernel/profile.c (ffffffff818c7674)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_prof_cpu_mask
```
```
In kernel/time/timer_list.c (ffffffff81fe52b9)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - kernel/time/timer_list.c:init_timer_list_procfs
```
```
In kernel/time/timer_stats.c (ffffffff81fe5a70)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - kernel/time/timer_stats.c:init_tstats_procfs
```
```
In kernel/dma.c (ffffffff81fe5c1f)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - kernel/dma.c:proc_dma_init
```
```
In kernel/module.c (ffffffff81fe5e4e)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - kernel/module.c:proc_modules_init
```
```
In kernel/kallsyms.c (ffffffff81fe6370)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - kernel/kallsyms.c:kallsyms_init
```
```
In kernel/cgroup.c (ffffffff81fe777d)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_init
```
```
In mm/vmstat.c (ffffffff81feea3b)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - mm/vmstat.c:setup_vmstat
  - mm/vmstat.c:setup_vmstat
  - mm/vmstat.c:setup_vmstat
  - mm/vmstat.c:setup_vmstat
```
```
In mm/slab_common.c (ffffffff81fefe96)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - mm/slab_common.c:slab_proc_init
```
```
In mm/vmalloc.c (ffffffff81ff0f6a)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - mm/vmalloc.c:proc_vmalloc_init
```
```
In mm/swapfile.c (ffffffff81ff1d27)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - mm/swapfile.c:procswaps_init
```
```
In fs/filesystems.c (ffffffff81ff5c16)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/filesystems.c:proc_filesystems_init
```
```
In fs/locks.c (ffffffff81ff767b)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/locks.c:proc_locks_init
```
```
In fs/proc/proc_tty.c (ffffffff81ff8066)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
```
```
In fs/proc/cmdline.c (ffffffff81ff80a4)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/proc/cmdline.c:proc_cmdline_init
```
```
In fs/proc/consoles.c (ffffffff81ff80c6)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/proc/consoles.c:proc_consoles_init
```
```
In fs/proc/cpuinfo.c (ffffffff81ff80e8)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/proc/cpuinfo.c:proc_cpuinfo_init
```
```
In fs/proc/devices.c (ffffffff81ff810a)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/proc/devices.c:proc_devices_init
```
```
In fs/proc/interrupts.c (ffffffff81ff812c)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/proc/interrupts.c:proc_interrupts_init
```
```
In fs/proc/loadavg.c (ffffffff81ff814e)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/proc/loadavg.c:proc_loadavg_init
```
```
In fs/proc/meminfo.c (ffffffff81ff8170)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/proc/meminfo.c:proc_meminfo_init
```
```
In fs/proc/stat.c (ffffffff81ff8192)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/proc/stat.c:proc_stat_init
```
```
In fs/proc/uptime.c (ffffffff81ff81b4)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/proc/uptime.c:proc_uptime_init
```
```
In fs/proc/version.c (ffffffff81ff81d6)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/proc/version.c:proc_version_init
```
```
In fs/proc/softirqs.c (ffffffff81ff81f8)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/proc/softirqs.c:proc_softirqs_init
```
```
In fs/proc/kcore.c (ffffffff81ff8295)
Location: include/linux/proc_fs.h:31
Inline: True
```
```
In fs/proc/vmcore.c (ffffffff81ff8e6d)
Location: include/linux/proc_fs.h:31
Inline: True
```
```
In fs/proc/kmsg.c (ffffffff81ff8f53)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/proc/kmsg.c:proc_kmsg_init
```
```
In fs/proc/page.c (ffffffff81ff8f78)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
```
```
In fs/proc/version_signature.c (ffffffff81ff8fd7)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/proc/version_signature.c:proc_version_signature_init
```
```
In security/keys/proc.c (ffffffff81fff678)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
```
```
In crypto/proc.c (ffffffff82001de6)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - crypto/proc.c:crypto_init_proc
```
```
In block/genhd.c (ffffffff82003266)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - block/genhd.c:proc_genhd_init
  - block/genhd.c:proc_genhd_init
```
```
In drivers/pci/proc.c (ffffffff82007ede)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - drivers/pci/proc.c:pci_proc_init
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8200888b)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/acpi/proc.c (ffffffff8200a5fe)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - drivers/acpi/proc.c:acpi_sleep_proc_init
```
```
In drivers/tty/sysrq.c (ffffffff8201009c)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_init
```
```
In drivers/char/misc.c (ffffffff82011e72)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_init
```
```
In drivers/connector/connector.c (ffffffff815c0f08)
Location: include/linux/proc_fs.h:31
Inline: True
```
```
In drivers/scsi/scsi_devinfo.c (ffffffff82018fd6)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - drivers/scsi/scsi_devinfo.c:scsi_init_devinfo
```
```
In drivers/scsi/scsi_proc.c (ffffffff82019064)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
```
```
In drivers/scsi/sg.c (ffffffff82019322)
Location: include/linux/proc_fs.h:31
Inline: True
```
```
In drivers/input/input.c (ffffffff8201c63f)
Location: include/linux/proc_fs.h:31
Inline: True
```
```
In drivers/md/md.c (ffffffff8201e089)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - drivers/md/md.c:md_init
```
```
In net/core/sock.c (ffffffff81794ea6)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/core/sock.c:proto_init_net
```
```
In net/core/net-procfs.c (ffffffff817d2796)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/core/net-procfs.c:dev_mc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
```
```
In net/sched/sch_api.c (ffffffff817df5d6)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/sched/sch_api.c:psched_net_init
```
```
In net/netlink/af_netlink.c (ffffffff817e7426)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_net_init
```
```
In net/netfilter/nf_log.c (ffffffff817ed5d6)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_net_init
```
```
In net/ipv4/route.c (ffffffff817ef4a6)
Location: include/linux/proc_fs.h:31
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81822e46)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_init_net
```
```
In net/ipv4/arp.c (ffffffff8182a706)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_net_init
```
```
In net/ipv4/igmp.c (ffffffff81834326)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
```
```
In net/ipv4/fib_trie.c (ffffffff818408b6)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
```
```
In net/ipv4/proc.c (ffffffff81845b66)
Location: include/linux/proc_fs.h:31
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81847be1)
Location: include/linux/proc_fs.h:31
Inline: True
```
```
In net/xfrm/xfrm_proc.c (ffffffff8185be76)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/xfrm/xfrm_proc.c:xfrm_proc_init
```
```
In net/unix/af_unix.c (ffffffff8185c348)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_net_init
```
```
In net/ipv6/anycast.c (ffffffff81862f76)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_proc_init
```
```
In net/ipv6/addrconf.c (ffffffff81868dd6)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:if6_proc_net_init
```
```
In net/ipv6/route.c (ffffffff81873926)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_net_init_late
  - net/ipv6/route.c:ip6_route_net_init_late
```
```
In net/ipv6/raw.c (ffffffff81885516)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_init_net
```
```
In net/ipv6/mcast.c (ffffffff8188a1aa)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81897aa6)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init
```
```
In net/ipv6/ip6mr.c (ffffffff8189c0d1)
Location: include/linux/proc_fs.h:31
Inline: True
```
```
In net/ipv6/proc.c (ffffffff818a1416)
Location: include/linux/proc_fs.h:31
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818a85e7)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_net_init
```
```
In net/wireless/wext-proc.c (ffffffff818b0e66)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/wireless/wext-proc.c:wext_proc_init
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
In arch/x86/kernel/cpu/mtrr/if.c (ffffffff820af80e)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_if_init
```
```
In kernel/exec_domain.c (ffffffff820c0a19)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - kernel/exec_domain.c:proc_execdomains_init
```
```
In kernel/resource.c (ffffffff820c0ff6)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - kernel/resource.c:ioresources_init
  - kernel/resource.c:ioresources_init
```
```
In kernel/sched/stats.c (ffffffff820c3b4c)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - kernel/sched/stats.c:proc_schedstat_init
```
```
In kernel/sched/debug.c (ffffffff820c3b9c)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - kernel/sched/debug.c:init_sched_debug_procfs
```
```
In kernel/irq/proc.c (ffffffff810ee194)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - kernel/irq/proc.c:init_irq_proc
```
```
In kernel/profile.c (ffffffff818fedc4)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_prof_cpu_mask
```
```
In kernel/time/timer_list.c (ffffffff820c5f8a)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - kernel/time/timer_list.c:init_timer_list_procfs
```
```
In kernel/dma.c (ffffffff820c652d)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - kernel/dma.c:proc_dma_init
```
```
In kernel/module.c (ffffffff820c677d)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - kernel/module.c:proc_modules_init
```
```
In kernel/kallsyms.c (ffffffff820c691d)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - kernel/kallsyms.c:kallsyms_init
```
```
In kernel/cgroup/cgroup.c (ffffffff820c7cd4)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In mm/vmstat.c (ffffffff820d0aae)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
```
```
In mm/slab_common.c (ffffffff820d229a)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - mm/slab_common.c:slab_proc_init
```
```
In mm/vmalloc.c (ffffffff820d3415)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - mm/vmalloc.c:proc_vmalloc_init
```
```
In mm/swapfile.c (ffffffff820d42fb)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - mm/swapfile.c:procswaps_init
```
```
In fs/filesystems.c (ffffffff820d83be)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/filesystems.c:proc_filesystems_init
```
```
In fs/locks.c (ffffffff820da6b7)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/locks.c:proc_locks_init
```
```
In fs/proc/proc_tty.c (ffffffff820db0bf)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/proc/proc_tty.c:proc_tty_init
  - fs/proc/proc_tty.c:proc_tty_init
```
```
In fs/proc/cmdline.c (ffffffff820db102)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/proc/cmdline.c:proc_cmdline_init
```
```
In fs/proc/consoles.c (ffffffff820db129)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/proc/consoles.c:proc_consoles_init
```
```
In fs/proc/cpuinfo.c (ffffffff820db150)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/proc/cpuinfo.c:proc_cpuinfo_init
```
```
In fs/proc/devices.c (ffffffff820db177)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/proc/devices.c:proc_devices_init
```
```
In fs/proc/interrupts.c (ffffffff820db19e)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/proc/interrupts.c:proc_interrupts_init
```
```
In fs/proc/loadavg.c (ffffffff820db1c5)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/proc/loadavg.c:proc_loadavg_init
```
```
In fs/proc/meminfo.c (ffffffff820db1ec)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/proc/meminfo.c:proc_meminfo_init
```
```
In fs/proc/stat.c (ffffffff820db213)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/proc/stat.c:proc_stat_init
```
```
In fs/proc/uptime.c (ffffffff820db23a)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/proc/uptime.c:proc_uptime_init
```
```
In fs/proc/version.c (ffffffff820db261)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/proc/version.c:proc_version_init
```
```
In fs/proc/softirqs.c (ffffffff820db288)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/proc/softirqs.c:proc_softirqs_init
```
```
In fs/proc/kcore.c (ffffffff820db33e)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/proc/kcore.c:proc_kcore_init
```
```
In fs/proc/vmcore.c (ffffffff820dbeee)
Location: include/linux/proc_fs.h:31
Inline: True
```
```
In fs/proc/kmsg.c (ffffffff820dbfcb)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/proc/kmsg.c:proc_kmsg_init
```
```
In fs/proc/page.c (ffffffff820dbff5)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
```
```
In fs/proc/version_signature.c (ffffffff820dc059)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - fs/proc/version_signature.c:proc_version_signature_init
```
```
In security/keys/proc.c (ffffffff820e2946)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
```
```
In crypto/proc.c (ffffffff820e5791)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - crypto/proc.c:crypto_init_proc
```
```
In block/genhd.c (ffffffff820e6b1a)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - block/genhd.c:proc_genhd_init
  - block/genhd.c:proc_genhd_init
```
```
In drivers/pci/proc.c (ffffffff820e8fa8)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - drivers/pci/proc.c:pci_proc_init
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff820e9b53)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
```
```
In drivers/acpi/proc.c (ffffffff820ebd62)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - drivers/acpi/proc.c:acpi_sleep_proc_init
```
```
In drivers/tty/sysrq.c (ffffffff820f1b5a)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_init
```
```
In drivers/char/misc.c (ffffffff820f39f8)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_init
```
```
In drivers/connector/connector.c (ffffffff815d6a58)
Location: include/linux/proc_fs.h:31
Inline: True
```
```
In drivers/scsi/scsi_devinfo.c (ffffffff820fafe9)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - drivers/scsi/scsi_devinfo.c:scsi_init_devinfo
```
```
In drivers/scsi/scsi_proc.c (ffffffff820fb076)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
```
```
In drivers/scsi/sg.c (ffffffff820fb343)
Location: include/linux/proc_fs.h:31
Inline: True
```
```
In drivers/input/input.c (ffffffff820ff024)
Location: include/linux/proc_fs.h:31
Inline: True
```
```
In drivers/md/md.c (ffffffff82100b37)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - drivers/md/md.c:md_init
```
```
In net/core/sock.c (ffffffff817b3096)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/core/sock.c:proto_init_net
```
```
In net/core/net-procfs.c (ffffffff817f1a66)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/core/net-procfs.c:dev_mc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
```
```
In net/sched/sch_api.c (ffffffff817fea26)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/sched/sch_api.c:psched_net_init
```
```
In net/netlink/af_netlink.c (ffffffff81807146)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_net_init
```
```
In net/netfilter/nf_log.c (ffffffff8180d706)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_net_init
```
```
In net/ipv4/route.c (ffffffff8180f7b6)
Location: include/linux/proc_fs.h:31
Inline: True
```
```
In net/ipv4/raw.c (ffffffff818439f6)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_init_net
```
```
In net/ipv4/arp.c (ffffffff8184b926)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_net_init
```
```
In net/ipv4/igmp.c (ffffffff818558f6)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
```
```
In net/ipv4/fib_trie.c (ffffffff81862006)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
```
```
In net/ipv4/proc.c (ffffffff818676c6)
Location: include/linux/proc_fs.h:31
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8186b640)
Location: include/linux/proc_fs.h:31
Inline: True
```
```
In net/xfrm/xfrm_proc.c (ffffffff81880556)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/xfrm/xfrm_proc.c:xfrm_proc_init
```
```
In net/unix/af_unix.c (ffffffff81880a12)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_net_init
```
```
In net/ipv6/anycast.c (ffffffff81887786)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_proc_init
```
```
In net/ipv6/addrconf.c (ffffffff8188d496)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:if6_proc_net_init
```
```
In net/ipv6/route.c (ffffffff818985c6)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_net_init_late
  - net/ipv6/route.c:ip6_route_net_init_late
```
```
In net/ipv6/raw.c (ffffffff818ab8f6)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_init_net
```
```
In net/ipv6/mcast.c (ffffffff818b055a)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff818bde86)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init
```
```
In net/ipv6/ip6mr.c (ffffffff818c248d)
Location: include/linux/proc_fs.h:31
Inline: True
```
```
In net/ipv6/proc.c (ffffffff818c7a66)
Location: include/linux/proc_fs.h:31
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818cee27)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_net_init
```
```
In net/wireless/wext-proc.c (ffffffff818d77e6)
Location: include/linux/proc_fs.h:31
Inline: True
Inline callers:
  - net/wireless/wext-proc.c:wext_proc_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct file_operations *proc_fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812f38e0)
Location: fs/proc/generic.c:511
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
  - security/keys/proc.c:key_proc_init
  - security/keys/proc.c:key_proc_init
  - crypto/proc.c:crypto_init_proc
  - block/genhd.c:proc_genhd_init
  - block/genhd.c:proc_genhd_init
  - drivers/pci/proc.c:pci_proc_init
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/acpi/proc.c:acpi_sleep_proc_init
  - drivers/tty/sysrq.c:sysrq_init
  - drivers/char/misc.c:misc_init
  - drivers/scsi/scsi_devinfo.c:scsi_init_devinfo
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/md/md.c:md_init
  - net/core/sock.c:proto_init_net
  - net/core/net-procfs.c:dev_mc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/sched/sch_api.c:psched_net_init
  - net/netlink/af_netlink.c:netlink_net_init
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/raw.c:raw_init_net
  - net/ipv4/arp.c:arp_net_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/ipv4/ipmr.c:ipmr_net_init
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
  - net/packet/af_packet.c:packet_net_init
  - net/wireless/wext-proc.c:wext_proc_init
```
**Symbols:**

```
ffffffff812f38e0-ffffffff812f38f6: proc_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct file_operations *proc_fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81320a10)
Location: fs/proc/generic.c:550
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_if_init
  - kernel/irq/proc.c:init_irq_proc
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_prof_cpu_mask
  - kernel/module.c:proc_modules_init
  - kernel/kallsyms.c:kallsyms_init
  - mm/slab_common.c:slab_proc_init
  - mm/swapfile.c:procswaps_init
  - fs/proc/cpuinfo.c:proc_cpuinfo_init
  - fs/proc/stat.c:proc_stat_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/kmsg.c:proc_kmsg_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/version_signature.c:proc_version_signature_init
  - drivers/acpi/proc.c:acpi_sleep_proc_init
  - drivers/tty/sysrq.c:sysrq_init
  - drivers/scsi/scsi_devinfo.c:scsi_init_devinfo
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_init
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffff81320a10-ffffffff81320a26: proc_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct file_operations *proc_fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81337b10)
Location: fs/proc/generic.c:552
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_if_init
  - kernel/sched/psi.c:psi_proc_init
  - kernel/sched/psi.c:psi_proc_init
  - kernel/sched/psi.c:psi_proc_init
  - kernel/irq/proc.c:init_irq_proc
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_prof_cpu_mask
  - kernel/module.c:proc_modules_init
  - kernel/kallsyms.c:kallsyms_init
  - mm/slab_common.c:slab_proc_init
  - mm/swapfile.c:procswaps_init
  - fs/proc/cpuinfo.c:proc_cpuinfo_init
  - fs/proc/stat.c:proc_stat_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/kmsg.c:proc_kmsg_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/version_signature.c:proc_version_signature_init
  - drivers/acpi/proc.c:acpi_sleep_proc_init
  - drivers/tty/sysrq.c:sysrq_init
  - drivers/scsi/scsi_devinfo.c:scsi_init_devinfo
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_init
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffff81337b10-ffffffff81337b26: proc_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct file_operations *proc_fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8135fc80)
Location: fs/proc/generic.c:553
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_if_init
  - kernel/sched/psi.c:psi_proc_init
  - kernel/sched/psi.c:psi_proc_init
  - kernel/sched/psi.c:psi_proc_init
  - kernel/irq/proc.c:init_irq_proc
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_prof_cpu_mask
  - kernel/module.c:proc_modules_init
  - kernel/kallsyms.c:kallsyms_init
  - mm/slab_common.c:slab_proc_init
  - mm/swapfile.c:procswaps_init
  - fs/proc/cpuinfo.c:proc_cpuinfo_init
  - fs/proc/stat.c:proc_stat_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/kmsg.c:proc_kmsg_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/version_signature.c:proc_version_signature_init
  - drivers/acpi/proc.c:acpi_sleep_proc_init
  - drivers/tty/sysrq.c:sysrq_init
  - drivers/scsi/scsi_devinfo.c:scsi_init_devinfo
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_init
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffff8135fc80-ffffffff8135fc96: proc_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct file_operations *proc_fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81377ee0)
Location: fs/proc/generic.c:553
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_if_init
  - arch/x86/platform/uv/tlb_uv.c:uv_ptc_init
  - kernel/sched/psi.c:psi_proc_init
  - kernel/sched/psi.c:psi_proc_init
  - kernel/sched/psi.c:psi_proc_init
  - kernel/irq/proc.c:init_irq_proc
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_prof_cpu_mask
  - kernel/module.c:proc_modules_init
  - kernel/kallsyms.c:kallsyms_init
  - mm/slab_common.c:slab_proc_init
  - mm/swapfile.c:procswaps_init
  - fs/proc/cpuinfo.c:proc_cpuinfo_init
  - fs/proc/stat.c:proc_stat_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/kmsg.c:proc_kmsg_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/version_signature.c:proc_version_signature_init
  - drivers/acpi/proc.c:acpi_sleep_proc_init
  - drivers/tty/sysrq.c:sysrq_init
  - drivers/scsi/scsi_devinfo.c:scsi_init_devinfo
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_init
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffff81377ee0-ffffffff81377ef6: proc_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct proc_ops *proc_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813c0ec0)
Location: fs/proc/generic.c:564
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_if_init
  - arch/x86/platform/uv/tlb_uv.c:uv_ptc_init
  - kernel/sched/psi.c:psi_proc_init
  - kernel/sched/psi.c:psi_proc_init
  - kernel/sched/psi.c:psi_proc_init
  - kernel/irq/proc.c:init_irq_proc
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_prof_cpu_mask
  - kernel/module.c:proc_modules_init
  - kernel/kallsyms.c:kallsyms_init
  - mm/slab_common.c:slab_proc_init
  - mm/swapfile.c:procswaps_init
  - fs/proc/cpuinfo.c:proc_cpuinfo_init
  - fs/proc/stat.c:proc_stat_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/kmsg.c:proc_kmsg_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/version_signature.c:proc_version_signature_init
  - lib/dynamic_debug.c:dynamic_debug_init_control
  - drivers/acpi/proc.c:acpi_sleep_proc_init
  - drivers/tty/sysrq.c:sysrq_init
  - drivers/scsi/scsi_devinfo.c:scsi_init_devinfo
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_init
  - drivers/md/md.c:md_init
  - net/ipv4/route.c:ip_rt_do_proc_init
  - net/ipv4/route.c:ip_rt_do_proc_init
```
**Symbols:**

```
ffffffff813c0ec0-ffffffff813c0f2f: proc_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct proc_ops *proc_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813d2db0)
Location: fs/proc/generic.c:584
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_if_init
  - kernel/sched/psi.c:psi_proc_init
  - kernel/sched/psi.c:psi_proc_init
  - kernel/sched/psi.c:psi_proc_init
  - kernel/irq/proc.c:init_irq_proc
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_prof_cpu_mask
  - kernel/module.c:proc_modules_init
  - kernel/kallsyms.c:kallsyms_init
  - mm/slab_common.c:slab_proc_init
  - mm/swapfile.c:procswaps_init
  - fs/proc/cpuinfo.c:proc_cpuinfo_init
  - fs/proc/stat.c:proc_stat_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/kmsg.c:proc_kmsg_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/version_signature.c:proc_version_signature_init
  - lib/dynamic_debug.c:dynamic_debug_init_control
  - drivers/acpi/proc.c:acpi_sleep_proc_init
  - drivers/tty/sysrq.c:sysrq_init
  - drivers/scsi/scsi_devinfo.c:scsi_init_devinfo
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_init
  - drivers/md/md.c:md_init
  - net/ipv4/route.c:ip_rt_do_proc_init
  - net/ipv4/route.c:ip_rt_do_proc_init
```
**Symbols:**

```
ffffffff813d2db0-ffffffff813d2e1f: proc_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct proc_ops *proc_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813d9c40)
Location: fs/proc/generic.c:579
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_if_init
  - kernel/sched/psi.c:psi_proc_init
  - kernel/sched/psi.c:psi_proc_init
  - kernel/sched/psi.c:psi_proc_init
  - kernel/irq/proc.c:init_irq_proc
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_prof_cpu_mask
  - kernel/module.c:proc_modules_init
  - kernel/kallsyms.c:kallsyms_init
  - mm/slab_common.c:slab_proc_init
  - mm/swapfile.c:procswaps_init
  - fs/proc/cpuinfo.c:proc_cpuinfo_init
  - fs/proc/stat.c:proc_stat_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/kmsg.c:proc_kmsg_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/version_signature.c:proc_version_signature_init
  - lib/dynamic_debug.c:dynamic_debug_init_control
  - drivers/acpi/proc.c:acpi_sleep_proc_init
  - drivers/tty/sysrq.c:sysrq_init
  - drivers/scsi/scsi_devinfo.c:scsi_init_devinfo
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_init
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffff813d9c40-ffffffff813d9caf: proc_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct proc_ops *proc_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8142b370)
Location: fs/proc/generic.c:579
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_if_init
  - kernel/sched/psi.c:psi_proc_init
  - kernel/sched/psi.c:psi_proc_init
  - kernel/sched/psi.c:psi_proc_init
  - kernel/irq/proc.c:init_irq_proc
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_prof_cpu_mask
  - kernel/module.c:proc_modules_init
  - kernel/kallsyms.c:kallsyms_init
  - mm/slab_common.c:slab_proc_init
  - mm/swapfile.c:procswaps_init
  - fs/proc/cpuinfo.c:proc_cpuinfo_init
  - fs/proc/stat.c:proc_stat_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/kmsg.c:proc_kmsg_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/version_signature.c:proc_version_signature_init
  - lib/dynamic_debug.c:dynamic_debug_init_control
  - drivers/acpi/proc.c:acpi_sleep_proc_init
  - drivers/tty/sysrq.c:sysrq_init
  - drivers/scsi/scsi_devinfo.c:scsi_init_devinfo
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_init
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffff8142b370-ffffffff8142b3df: proc_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct proc_ops *proc_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff814a4a40)
Location: fs/proc/generic.c:582
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_if_init
  - kernel/sched/build_utility.c:psi_proc_init
  - kernel/sched/build_utility.c:psi_proc_init
  - kernel/sched/build_utility.c:psi_proc_init
  - kernel/irq/proc.c:init_irq_proc
  - kernel/module/procfs.c:proc_modules_init
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_prof_cpu_mask
  - kernel/kallsyms.c:kallsyms_init
  - mm/slab_common.c:slab_proc_init
  - mm/swapfile.c:procswaps_init
  - fs/proc/cpuinfo.c:proc_cpuinfo_init
  - fs/proc/stat.c:proc_stat_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/kmsg.c:proc_kmsg_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/version_signature.c:proc_version_signature_init
  - lib/dynamic_debug.c:dynamic_debug_init_control
  - drivers/acpi/proc.c:acpi_sleep_proc_init
  - drivers/tty/sysrq.c:sysrq_init
  - drivers/scsi/scsi_devinfo.c:scsi_init_devinfo
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_init
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffff814a4a40-ffffffff814a4abb: proc_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct proc_ops *proc_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81539f50)
Location: fs/proc/generic.c:582
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_if_init
  - kernel/sched/build_utility.c:psi_proc_init
  - kernel/sched/build_utility.c:psi_proc_init
  - kernel/sched/build_utility.c:psi_proc_init
  - kernel/irq/proc.c:init_irq_proc
  - kernel/module/procfs.c:proc_modules_init
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_prof_cpu_mask
  - kernel/kallsyms.c:kallsyms_init
  - mm/slab_common.c:slab_proc_init
  - mm/swapfile.c:procswaps_init
  - fs/proc/cpuinfo.c:proc_cpuinfo_init
  - fs/proc/stat.c:proc_stat_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/kmsg.c:proc_kmsg_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/version_signature.c:proc_version_signature_init
  - lib/dynamic_debug.c:dynamic_debug_init_control
  - drivers/acpi/proc.c:acpi_sleep_proc_init
  - drivers/tty/sysrq.c:sysrq_init
  - drivers/scsi/scsi_devinfo.c:scsi_init_devinfo
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_init
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffff81539f50-ffffffff81539fcb: proc_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct proc_ops *proc_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff815721f0)
Location: fs/proc/generic.c:581
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_if_init
  - kernel/sched/build_utility.c:psi_proc_init
  - kernel/sched/build_utility.c:psi_proc_init
  - kernel/sched/build_utility.c:psi_proc_init
  - kernel/irq/proc.c:init_irq_proc
  - kernel/module/procfs.c:proc_modules_init
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_prof_cpu_mask
  - kernel/kallsyms.c:kallsyms_init
  - mm/slab_common.c:slab_proc_init
  - mm/swapfile.c:procswaps_init
  - fs/proc/cpuinfo.c:proc_cpuinfo_init
  - fs/proc/stat.c:proc_stat_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/kmsg.c:proc_kmsg_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/version_signature.c:proc_version_signature_init
  - lib/dynamic_debug.c:dynamic_debug_init_control
  - drivers/acpi/proc.c:acpi_sleep_proc_init
  - drivers/tty/sysrq.c:sysrq_init
  - drivers/scsi/scsi_devinfo.c:scsi_init_devinfo
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_init
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffff815721f0-ffffffff8157226b: proc_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct proc_ops *proc_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff815aaba0)
Location: fs/proc/generic.c:581
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_if_init
  - kernel/sched/build_utility.c:psi_proc_init
  - kernel/sched/build_utility.c:psi_proc_init
  - kernel/sched/build_utility.c:psi_proc_init
  - kernel/irq/proc.c:init_irq_proc
  - kernel/module/procfs.c:proc_modules_init
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_prof_cpu_mask
  - kernel/kallsyms.c:kallsyms_init
  - kernel/latencytop.c:init_lstats_procfs
  - mm/slab_common.c:slab_proc_init
  - mm/swapfile.c:procswaps_init
  - fs/proc/cpuinfo.c:proc_cpuinfo_init
  - fs/proc/stat.c:proc_stat_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/kmsg.c:proc_kmsg_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/version_signature.c:proc_version_signature_init
  - lib/dynamic_debug.c:dynamic_debug_init_control
  - drivers/acpi/proc.c:acpi_sleep_proc_init
  - drivers/tty/sysrq.c:sysrq_init
  - drivers/scsi/scsi_devinfo.c:scsi_init_devinfo
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_init
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffff815aaba0-ffffffff815aac1b: proc_create (STB_GLOBAL)
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
struct proc_dir_entry *proc_create(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct file_operations *proc_fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffff800010443db0)
Location: fs/proc/generic.c:553
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_proc_init
  - kernel/sched/psi.c:psi_proc_init
  - kernel/sched/psi.c:psi_proc_init
  - kernel/irq/proc.c:init_irq_proc
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_prof_cpu_mask
  - kernel/module.c:proc_modules_init
  - kernel/kallsyms.c:kallsyms_init
  - mm/slab_common.c:slab_proc_init
  - mm/swapfile.c:procswaps_init
  - fs/proc/cpuinfo.c:proc_cpuinfo_init
  - fs/proc/stat.c:proc_stat_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/kmsg.c:proc_kmsg_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/version_signature.c:proc_version_signature_init
  - drivers/tty/sysrq.c:sysrq_init
  - drivers/scsi/scsi_devinfo.c:scsi_init_devinfo
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_init
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffff800010443db0-ffff800010443e00: proc_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct file_operations *proc_fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (c0608fac)
Location: fs/proc/generic.c:553
Inline: False
Direct callers:
  - arch/arm/mm/alignment.c:alignment_init
  - kernel/sched/psi.c:psi_proc_init
  - kernel/sched/psi.c:psi_proc_init
  - kernel/sched/psi.c:psi_proc_init
  - kernel/irq/proc.c:init_irq_proc
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_prof_cpu_mask
  - kernel/module.c:proc_modules_init
  - kernel/kallsyms.c:kallsyms_init
  - mm/slab_common.c:slab_proc_init
  - mm/swapfile.c:procswaps_init
  - fs/proc/cpuinfo.c:proc_cpuinfo_init
  - fs/proc/stat.c:proc_stat_init
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/kmsg.c:proc_kmsg_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/version_signature.c:proc_version_signature_init
  - drivers/tty/sysrq.c:sysrq_init
  - drivers/scsi/scsi_devinfo.c:scsi_init_devinfo
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_init
  - drivers/md/md.c:md_init
```
**Symbols:**

```
c0608fac-c0608fd8: proc_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct file_operations *proc_fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (c000000000559530)
Location: fs/proc/generic.c:553
Inline: False
Direct callers:
  - arch/powerpc/kernel/rtasd.c:rtas_init
  - arch/powerpc/kernel/rtas-proc.c:proc_rtas_init
  - arch/powerpc/kernel/rtas-proc.c:proc_rtas_init
  - arch/powerpc/kernel/rtas-proc.c:proc_rtas_init
  - arch/powerpc/kernel/rtas-proc.c:proc_rtas_init
  - arch/powerpc/kernel/rtas-proc.c:proc_rtas_init
  - arch/powerpc/mm/numa.c:topology_update_init
  - arch/powerpc/platforms/pseries/lpar.c:__machine_initcall_pseries_vcpudispatch_stats_procfs_init
  - arch/powerpc/platforms/pseries/lpar.c:__machine_initcall_pseries_vcpudispatch_stats_procfs_init
  - arch/powerpc/platforms/pseries/reconfig.c:__machine_initcall_pseries_proc_ppc64_create_ofdt
  - arch/powerpc/platforms/pseries/lparcfg.c:__machine_initcall_pseries_lparcfg_init
  - kernel/sched/psi.c:psi_proc_init
  - kernel/sched/psi.c:psi_proc_init
  - kernel/sched/psi.c:psi_proc_init
  - kernel/irq/proc.c:init_irq_proc
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_prof_cpu_mask
  - kernel/module.c:proc_modules_init
  - kernel/kallsyms.c:kallsyms_init
  - mm/slab_common.c:slab_proc_init
  - mm/swapfile.c:procswaps_init
  - fs/proc/cpuinfo.c:proc_cpuinfo_init
  - fs/proc/stat.c:proc_stat_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/kmsg.c:proc_kmsg_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/version_signature.c:proc_version_signature_init
  - drivers/tty/sysrq.c:sysrq_init
  - drivers/scsi/scsi_devinfo.c:scsi_init_devinfo
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_init
  - drivers/md/md.c:md_init
```
**Symbols:**

```
c000000000559530-c000000000559548: proc_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct file_operations *proc_fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffe0002da810)
Location: fs/proc/generic.c:553
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_proc_init
  - kernel/sched/psi.c:psi_proc_init
  - kernel/sched/psi.c:psi_proc_init
  - kernel/irq/proc.c:init_irq_proc
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_prof_cpu_mask
  - kernel/module.c:proc_modules_init
  - kernel/kallsyms.c:kallsyms_init
  - mm/slab_common.c:slab_proc_init
  - mm/swapfile.c:procswaps_init
  - fs/proc/cpuinfo.c:proc_cpuinfo_init
  - fs/proc/stat.c:proc_stat_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kmsg.c:proc_kmsg_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/version_signature.c:proc_version_signature_init
  - drivers/tty/sysrq.c:sysrq_init
  - drivers/scsi/scsi_devinfo.c:scsi_init_devinfo
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_init
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffe0002da810-ffffffe0002da854: proc_create (STB_GLOBAL)
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
struct proc_dir_entry *proc_create(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct file_operations *proc_fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813704c0)
Location: fs/proc/generic.c:553
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_if_init
  - kernel/sched/psi.c:psi_proc_init
  - kernel/sched/psi.c:psi_proc_init
  - kernel/sched/psi.c:psi_proc_init
  - kernel/irq/proc.c:init_irq_proc
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_prof_cpu_mask
  - kernel/module.c:proc_modules_init
  - kernel/kallsyms.c:kallsyms_init
  - mm/slab_common.c:slab_proc_init
  - mm/swapfile.c:procswaps_init
  - fs/proc/cpuinfo.c:proc_cpuinfo_init
  - fs/proc/stat.c:proc_stat_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/kmsg.c:proc_kmsg_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/version_signature.c:proc_version_signature_init
  - drivers/acpi/proc.c:acpi_sleep_proc_init
  - drivers/tty/sysrq.c:sysrq_init
  - drivers/scsi/scsi_devinfo.c:scsi_init_devinfo
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_init
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffff813704c0-ffffffff813704d6: proc_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct file_operations *proc_fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81360f50)
Location: fs/proc/generic.c:553
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_if_init
  - kernel/sched/psi.c:psi_proc_init
  - kernel/sched/psi.c:psi_proc_init
  - kernel/sched/psi.c:psi_proc_init
  - kernel/irq/proc.c:init_irq_proc
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_prof_cpu_mask
  - kernel/module.c:proc_modules_init
  - kernel/kallsyms.c:kallsyms_init
  - mm/slab_common.c:slab_proc_init
  - mm/swapfile.c:procswaps_init
  - fs/proc/cpuinfo.c:proc_cpuinfo_init
  - fs/proc/stat.c:proc_stat_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/kmsg.c:proc_kmsg_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/version_signature.c:proc_version_signature_init
  - drivers/acpi/proc.c:acpi_sleep_proc_init
  - drivers/tty/sysrq.c:sysrq_init
  - drivers/scsi/scsi_devinfo.c:scsi_init_devinfo
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_init
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffff81360f50-ffffffff81360f66: proc_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct file_operations *proc_fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8136df90)
Location: fs/proc/generic.c:553
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_if_init
  - kernel/sched/psi.c:psi_proc_init
  - kernel/sched/psi.c:psi_proc_init
  - kernel/sched/psi.c:psi_proc_init
  - kernel/irq/proc.c:init_irq_proc
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_prof_cpu_mask
  - kernel/module.c:proc_modules_init
  - kernel/kallsyms.c:kallsyms_init
  - mm/slab_common.c:slab_proc_init
  - mm/swapfile.c:procswaps_init
  - fs/proc/cpuinfo.c:proc_cpuinfo_init
  - fs/proc/stat.c:proc_stat_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/kmsg.c:proc_kmsg_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/version_signature.c:proc_version_signature_init
  - drivers/acpi/proc.c:acpi_sleep_proc_init
  - drivers/tty/sysrq.c:sysrq_init
  - drivers/scsi/scsi_devinfo.c:scsi_init_devinfo
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_init
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffff8136df90-ffffffff8136dfa6: proc_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct file_operations *proc_fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813818c0)
Location: fs/proc/generic.c:553
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_if_init
  - arch/x86/platform/uv/tlb_uv.c:uv_ptc_init
  - kernel/sched/psi.c:psi_proc_init
  - kernel/sched/psi.c:psi_proc_init
  - kernel/sched/psi.c:psi_proc_init
  - kernel/irq/proc.c:init_irq_proc
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_prof_cpu_mask
  - kernel/module.c:proc_modules_init
  - kernel/kallsyms.c:kallsyms_init
  - kernel/latencytop.c:init_lstats_procfs
  - mm/slab_common.c:slab_proc_init
  - mm/swapfile.c:procswaps_init
  - fs/proc/cpuinfo.c:proc_cpuinfo_init
  - fs/proc/stat.c:proc_stat_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/kmsg.c:proc_kmsg_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/page.c:proc_page_init
  - fs/proc/version_signature.c:proc_version_signature_init
  - drivers/acpi/proc.c:acpi_sleep_proc_init
  - drivers/tty/sysrq.c:sysrq_init
  - drivers/scsi/scsi_devinfo.c:scsi_init_devinfo
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/sg.c:init_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_init
  - drivers/md/md.c:md_init
```
**Symbols:**

```
ffffffff813818c0-ffffffff813818d6: proc_create (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
