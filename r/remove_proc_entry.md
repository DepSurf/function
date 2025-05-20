# Function: <code>remove_proc_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void remove_proc_entry(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8127f930)
Location: fs/proc/generic.c:549
Inline: False
Direct callers:
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - fs/proc/proc_tty.c:proc_tty_unregister_driver
  - fs/proc/proc_net.c:proc_net_ns_exit
  - fs/ext4/sysfs.c:ext4_unregister_sysfs
  - fs/ext4/sysfs.c:ext4_unregister_sysfs
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/jbd2/journal.c:jbd2_stats_proc_exit
  - fs/jbd2/journal.c:jbd2_stats_proc_exit
  - fs/jbd2/journal.c:jbd2_remove_jbd_stats_proc_entry
  - crypto/proc.c:crypto_exit_proc
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/char/misc.c:misc_init
  - drivers/connector/connector.c:cn_fini
  - drivers/scsi/scsi_devinfo.c:scsi_init_devinfo
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm
  - drivers/scsi/scsi_proc.c:scsi_proc_host_rm
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/sg.c:exit_sg
  - drivers/scsi/sg.c:exit_sg
  - drivers/input/input.c:input_proc_exit
  - drivers/input/input.c:input_proc_exit
  - drivers/input/input.c:input_proc_exit
  - drivers/rtc/rtc-proc.c:rtc_proc_del_device
  - drivers/md/md.c:md_exit
  - net/core/sock.c:proto_exit_net
  - net/core/neighbour.c:neigh_table_clear
  - net/core/net-procfs.c:dev_mc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/sched/sch_api.c:psched_net_exit
  - net/netlink/af_netlink.c:netlink_net_exit
  - net/netfilter/core.c:netfilter_net_exit
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net
  - net/ipv4/raw.c:raw_exit_net
  - net/ipv4/udp.c:udp4_proc_exit_net
  - net/ipv4/arp.c:arp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/ping.c:ping_v4_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/xfrm/xfrm_proc.c:xfrm_proc_fini
  - net/unix/af_unix.c:unix_net_exit
  - net/ipv6/anycast.c:ac6_proc_exit
  - net/ipv6/addrconf.c:if6_proc_net_exit
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/raw.c:raw6_exit_net
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/packet/af_packet.c:packet_net_exit
  - net/wireless/wext-proc.c:wext_proc_exit
```
**Symbols:**

```
ffffffff8127f930-ffffffff8127faaf: remove_proc_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void remove_proc_entry(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812ac970)
Location: fs/proc/generic.c:554
Inline: False
Direct callers:
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - fs/proc/proc_tty.c:proc_tty_unregister_driver
  - fs/proc/proc_net.c:proc_net_ns_exit
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ext4/sysfs.c:ext4_unregister_sysfs
  - fs/ext4/sysfs.c:ext4_unregister_sysfs
  - fs/jbd2/journal.c:jbd2_remove_jbd_stats_proc_entry
  - fs/jbd2/journal.c:jbd2_stats_proc_exit
  - fs/jbd2/journal.c:jbd2_stats_proc_exit
  - crypto/proc.c:crypto_exit_proc
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/char/misc.c:misc_init
  - drivers/connector/connector.c:cn_fini
  - drivers/scsi/scsi_devinfo.c:scsi_init_devinfo
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_host_rm
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm
  - drivers/scsi/sg.c:exit_sg
  - drivers/scsi/sg.c:exit_sg
  - drivers/input/input.c:input_proc_exit
  - drivers/input/input.c:input_proc_exit
  - drivers/input/input.c:input_proc_exit
  - drivers/rtc/rtc-proc.c:rtc_proc_del_device
  - drivers/md/md.c:md_exit
  - net/core/sock.c:proto_exit_net
  - net/core/neighbour.c:neigh_table_clear
  - net/core/net-procfs.c:dev_mc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/sched/sch_api.c:psched_net_exit
  - net/netlink/af_netlink.c:netlink_net_exit
  - net/netfilter/core.c:netfilter_net_exit
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net
  - net/ipv4/raw.c:raw_exit_net
  - net/ipv4/udp.c:udp4_proc_exit_net
  - net/ipv4/arp.c:arp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/ping.c:ping_v4_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/xfrm/xfrm_proc.c:xfrm_proc_fini
  - net/unix/af_unix.c:unix_net_exit
  - net/ipv6/anycast.c:ac6_proc_exit
  - net/ipv6/addrconf.c:if6_proc_net_exit
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/raw.c:raw6_exit_net
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/packet/af_packet.c:packet_net_exit
  - net/wireless/wext-proc.c:wext_proc_exit
```
**Symbols:**

```
ffffffff812ac970-ffffffff812acaef: remove_proc_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void remove_proc_entry(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812c2260)
Location: fs/proc/generic.c:556
Inline: False
Direct callers:
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - fs/proc/proc_tty.c:proc_tty_unregister_driver
  - fs/proc/proc_net.c:proc_net_ns_exit
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ext4/sysfs.c:ext4_unregister_sysfs
  - fs/ext4/sysfs.c:ext4_unregister_sysfs
  - fs/jbd2/journal.c:jbd2_remove_jbd_stats_proc_entry
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - crypto/proc.c:crypto_exit_proc
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/char/misc.c:misc_init
  - drivers/connector/connector.c:cn_fini
  - drivers/scsi/scsi_devinfo.c:scsi_init_devinfo
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_host_rm
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm
  - drivers/scsi/sg.c:exit_sg
  - drivers/scsi/sg.c:exit_sg
  - drivers/input/input.c:input_proc_exit
  - drivers/input/input.c:input_proc_exit
  - drivers/input/input.c:input_proc_exit
  - drivers/rtc/rtc-proc.c:rtc_proc_del_device
  - drivers/md/md.c:md_exit
  - net/core/sock.c:proto_exit_net
  - net/core/neighbour.c:neigh_table_clear
  - net/core/net-procfs.c:dev_mc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/sched/sch_api.c:psched_net_exit
  - net/netlink/af_netlink.c:netlink_net_exit
  - net/netfilter/core.c:netfilter_net_exit
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net
  - net/ipv4/raw.c:raw_exit_net
  - net/ipv4/udp.c:udp4_proc_exit_net
  - net/ipv4/arp.c:arp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/ping.c:ping_v4_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/xfrm/xfrm_proc.c:xfrm_proc_fini
  - net/unix/af_unix.c:unix_net_exit
  - net/ipv6/anycast.c:ac6_proc_exit
  - net/ipv6/addrconf.c:if6_proc_net_exit
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/raw.c:raw6_exit_net
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/packet/af_packet.c:packet_net_exit
  - net/wireless/wext-proc.c:wext_proc_exit
```
**Symbols:**

```
ffffffff812c2260-ffffffff812c23df: remove_proc_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void remove_proc_entry(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812cf520)
Location: fs/proc/generic.c:540
Inline: False
Direct callers:
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - fs/proc/proc_tty.c:proc_tty_unregister_driver
  - fs/proc/proc_net.c:proc_net_ns_exit
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ext4/sysfs.c:ext4_unregister_sysfs
  - fs/ext4/sysfs.c:ext4_unregister_sysfs
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - crypto/proc.c:crypto_exit_proc
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/char/misc.c:misc_init
  - drivers/connector/connector.c:cn_fini
  - drivers/scsi/scsi_devinfo.c:scsi_init_devinfo
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_host_rm
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm
  - drivers/scsi/sg.c:exit_sg
  - drivers/scsi/sg.c:exit_sg
  - drivers/input/input.c:input_proc_exit
  - drivers/input/input.c:input_proc_exit
  - drivers/input/input.c:input_proc_exit
  - drivers/rtc/rtc-proc.c:rtc_proc_del_device
  - drivers/md/md.c:md_exit
  - net/core/sock.c:proto_exit_net
  - net/core/neighbour.c:neigh_table_clear
  - net/core/net-procfs.c:dev_mc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/sched/sch_api.c:psched_net_exit
  - net/netlink/af_netlink.c:netlink_net_exit
  - net/netfilter/core.c:netfilter_net_exit
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net
  - net/ipv4/raw.c:raw_exit_net
  - net/ipv4/udp.c:udp4_proc_exit_net
  - net/ipv4/arp.c:arp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/ping.c:ping_v4_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/xfrm/xfrm_proc.c:xfrm_proc_fini
  - net/unix/af_unix.c:unix_net_exit
  - net/ipv6/anycast.c:ac6_proc_exit
  - net/ipv6/addrconf.c:if6_proc_net_exit
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/raw.c:raw6_exit_net
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/packet/af_packet.c:packet_net_exit
  - net/wireless/wext-proc.c:wext_proc_exit
```
**Symbols:**

```
ffffffff812cf520-ffffffff812cf67f: remove_proc_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void remove_proc_entry(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812f3ca0)
Location: fs/proc/generic.c:550
Inline: False
Direct callers:
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - fs/proc/proc_tty.c:proc_tty_unregister_driver
  - fs/proc/proc_net.c:proc_net_ns_exit
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ext4/sysfs.c:ext4_unregister_sysfs
  - fs/ext4/sysfs.c:ext4_unregister_sysfs
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - crypto/proc.c:crypto_exit_proc
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/char/misc.c:misc_init
  - drivers/connector/connector.c:cn_fini
  - drivers/scsi/scsi_devinfo.c:scsi_init_devinfo
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_host_rm
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm
  - drivers/scsi/sg.c:exit_sg
  - drivers/scsi/sg.c:exit_sg
  - drivers/input/input.c:input_proc_exit
  - drivers/input/input.c:input_proc_exit
  - drivers/input/input.c:input_proc_exit
  - drivers/rtc/rtc-proc.c:rtc_proc_del_device
  - drivers/md/md.c:md_exit
  - net/core/sock.c:proto_exit_net
  - net/core/neighbour.c:neigh_table_clear
  - net/core/net-procfs.c:dev_mc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/sched/sch_api.c:psched_net_exit
  - net/netlink/af_netlink.c:netlink_net_exit
  - net/netfilter/core.c:netfilter_net_exit
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net
  - net/ipv4/raw.c:raw_exit_net
  - net/ipv4/udp.c:udp4_proc_exit_net
  - net/ipv4/arp.c:arp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/ping.c:ping_v4_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/xfrm/xfrm_proc.c:xfrm_proc_fini
  - net/unix/af_unix.c:unix_net_exit
  - net/ipv6/anycast.c:ac6_proc_exit
  - net/ipv6/addrconf.c:if6_proc_net_exit
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/raw.c:raw6_exit_net
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/wireless/wext-proc.c:wext_proc_exit
```
**Symbols:**

```
ffffffff812f3ca0-ffffffff812f3dd8: remove_proc_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void remove_proc_entry(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81320d40)
Location: fs/proc/generic.c:652
Inline: False
Direct callers:
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - fs/proc/proc_tty.c:proc_tty_unregister_driver
  - fs/proc/proc_net.c:proc_net_ns_exit
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/jbd2/journal.c:jbd2_remove_jbd_stats_proc_entry
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - crypto/proc.c:crypto_exit_proc
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/char/misc.c:misc_init
  - drivers/connector/connector.c:cn_fini
  - drivers/scsi/scsi_devinfo.c:scsi_init_devinfo
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_host_rm
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_proc_exit
  - drivers/input/input.c:input_proc_exit
  - drivers/input/input.c:input_proc_exit
  - drivers/rtc/rtc-proc.c:rtc_proc_del_device
  - drivers/md/md.c:md_exit
  - net/core/sock.c:proto_exit_net
  - net/core/neighbour.c:neigh_table_clear
  - net/core/net-procfs.c:dev_mc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/sched/sch_api.c:psched_net_exit
  - net/netlink/af_netlink.c:netlink_net_exit
  - net/netfilter/core.c:netfilter_net_exit
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net
  - net/ipv4/raw.c:raw_exit_net
  - net/ipv4/udp.c:udp4_proc_exit_net
  - net/ipv4/udplite.c:udplite4_proc_exit_net
  - net/ipv4/arp.c:arp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/ping.c:ping_v4_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/xfrm/xfrm_proc.c:xfrm_proc_fini
  - net/unix/af_unix.c:unix_net_exit
  - net/ipv6/anycast.c:ac6_proc_exit
  - net/ipv6/addrconf.c:if6_proc_net_exit
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/udp.c:udp6_proc_exit
  - net/ipv6/udplite.c:udplite6_proc_exit_net
  - net/ipv6/raw.c:raw6_exit_net
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcp6_proc_exit
  - net/ipv6/ping.c:ping_v6_proc_exit_net
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_init
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/wireless/wext-proc.c:wext_proc_exit
```
**Symbols:**

```
ffffffff81320d40-ffffffff81320ea6: remove_proc_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void remove_proc_entry(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81337e40)
Location: fs/proc/generic.c:654
Inline: False
Direct callers:
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - fs/proc/proc_tty.c:proc_tty_unregister_driver
  - fs/proc/proc_net.c:proc_net_ns_exit
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/jbd2/journal.c:jbd2_remove_jbd_stats_proc_entry
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - crypto/proc.c:crypto_exit_proc
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/char/misc.c:misc_init
  - drivers/connector/connector.c:cn_fini
  - drivers/scsi/scsi_devinfo.c:scsi_init_devinfo
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_host_rm
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_proc_exit
  - drivers/input/input.c:input_proc_exit
  - drivers/input/input.c:input_proc_exit
  - drivers/rtc/proc.c:rtc_proc_del_device
  - drivers/md/md.c:md_exit
  - net/core/sock.c:proto_exit_net
  - net/core/neighbour.c:neigh_table_clear
  - net/core/net-procfs.c:dev_mc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/sched/sch_api.c:psched_net_exit
  - net/netlink/af_netlink.c:netlink_net_exit
  - net/netfilter/core.c:netfilter_net_exit
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net
  - net/ipv4/raw.c:raw_exit_net
  - net/ipv4/udp.c:udp4_proc_exit_net
  - net/ipv4/udplite.c:udplite4_proc_exit_net
  - net/ipv4/arp.c:arp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/ping.c:ping_v4_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/xfrm/xfrm_proc.c:xfrm_proc_fini
  - net/unix/af_unix.c:unix_net_exit
  - net/ipv6/anycast.c:ac6_proc_exit
  - net/ipv6/addrconf.c:if6_proc_net_exit
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/udp.c:udp6_proc_exit
  - net/ipv6/udplite.c:udplite6_proc_exit_net
  - net/ipv6/raw.c:raw6_exit_net
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcp6_proc_exit
  - net/ipv6/ping.c:ping_v6_proc_exit_net
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_init
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/wireless/wext-proc.c:wext_proc_exit
```
**Symbols:**

```
ffffffff81337e40-ffffffff81337faa: remove_proc_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void remove_proc_entry(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8135ffb0)
Location: fs/proc/generic.c:655
Inline: False
Direct callers:
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - fs/proc/proc_tty.c:proc_tty_unregister_driver
  - fs/proc/proc_net.c:proc_net_ns_exit
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/jbd2/journal.c:jbd2_remove_jbd_stats_proc_entry
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - crypto/proc.c:crypto_exit_proc
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/char/misc.c:misc_init
  - drivers/connector/connector.c:cn_fini
  - drivers/scsi/scsi_devinfo.c:scsi_init_devinfo
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_host_rm
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_proc_exit
  - drivers/input/input.c:input_proc_exit
  - drivers/input/input.c:input_proc_exit
  - drivers/rtc/proc.c:rtc_proc_del_device
  - drivers/md/md.c:md_exit
  - net/core/sock.c:proto_exit_net
  - net/core/neighbour.c:neigh_table_clear
  - net/core/net-procfs.c:dev_mc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/sched/sch_api.c:psched_net_exit
  - net/netlink/af_netlink.c:netlink_net_exit
  - net/netfilter/core.c:netfilter_net_exit
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net
  - net/ipv4/raw.c:raw_exit_net
  - net/ipv4/udp.c:udp4_proc_exit_net
  - net/ipv4/udplite.c:udplite4_proc_exit_net
  - net/ipv4/arp.c:arp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/ping.c:ping_v4_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/xfrm/xfrm_proc.c:xfrm_proc_fini
  - net/unix/af_unix.c:unix_net_exit
  - net/ipv6/anycast.c:ac6_proc_exit
  - net/ipv6/addrconf.c:if6_proc_net_exit
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/udp.c:udp6_proc_exit
  - net/ipv6/udplite.c:udplite6_proc_exit_net
  - net/ipv6/raw.c:raw6_exit_net
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcp6_proc_exit
  - net/ipv6/ping.c:ping_v6_proc_exit_net
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_init
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/wireless/wext-proc.c:wext_proc_exit
```
**Symbols:**

```
ffffffff8135ffb0-ffffffff81360122: remove_proc_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void remove_proc_entry(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81378210)
Location: fs/proc/generic.c:655
Inline: False
Direct callers:
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - fs/proc/proc_tty.c:proc_tty_unregister_driver
  - fs/proc/proc_net.c:proc_net_ns_exit
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/jbd2/journal.c:jbd2_remove_jbd_stats_proc_entry
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - crypto/proc.c:crypto_exit_proc
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/char/misc.c:misc_init
  - drivers/connector/connector.c:cn_fini
  - drivers/scsi/scsi_devinfo.c:scsi_init_devinfo
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_host_rm
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_proc_exit
  - drivers/input/input.c:input_proc_exit
  - drivers/input/input.c:input_proc_exit
  - drivers/rtc/proc.c:rtc_proc_del_device
  - drivers/md/md.c:md_exit
  - net/core/sock.c:proto_exit_net
  - net/core/neighbour.c:neigh_table_clear
  - net/core/net-procfs.c:dev_mc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/sched/sch_api.c:psched_net_exit
  - net/netlink/af_netlink.c:netlink_net_exit
  - net/netfilter/core.c:netfilter_net_exit
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net
  - net/ipv4/raw.c:raw_exit_net
  - net/ipv4/udp.c:udp4_proc_exit_net
  - net/ipv4/udplite.c:udplite4_proc_exit_net
  - net/ipv4/arp.c:arp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/ping.c:ping_v4_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/xfrm/xfrm_proc.c:xfrm_proc_fini
  - net/unix/af_unix.c:unix_net_exit
  - net/ipv6/anycast.c:ac6_proc_exit
  - net/ipv6/addrconf.c:if6_proc_net_exit
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/udp.c:udp6_proc_exit
  - net/ipv6/udplite.c:udplite6_proc_exit_net
  - net/ipv6/raw.c:raw6_exit_net
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcp6_proc_exit
  - net/ipv6/ping.c:ping_v6_proc_exit_net
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_init
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/wireless/wext-proc.c:wext_proc_exit
```
**Symbols:**

```
ffffffff81378210-ffffffff81378382: remove_proc_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void remove_proc_entry(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813c1280)
Location: fs/proc/generic.c:668
Inline: False
Direct callers:
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - fs/proc/proc_tty.c:proc_tty_unregister_driver
  - fs/proc/proc_net.c:proc_net_ns_exit
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/jbd2/journal.c:jbd2_remove_jbd_stats_proc_entry
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - crypto/proc.c:crypto_exit_proc
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/acpi/button.c:acpi_button_add_fs
  - drivers/acpi/button.c:acpi_button_add_fs
  - drivers/acpi/button.c:acpi_button_add_fs
  - drivers/char/misc.c:misc_init
  - drivers/connector/connector.c:cn_fini
  - drivers/scsi/scsi_devinfo.c:scsi_exit_devinfo
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_host_rm
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_proc_exit
  - drivers/input/input.c:input_proc_exit
  - drivers/input/input.c:input_proc_exit
  - drivers/rtc/proc.c:rtc_proc_del_device
  - drivers/md/md.c:md_exit
  - net/core/sock.c:proto_exit_net
  - net/core/neighbour.c:neigh_table_clear
  - net/core/net-procfs.c:dev_mc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/sched/sch_api.c:psched_net_exit
  - net/netlink/af_netlink.c:netlink_net_exit
  - net/netfilter/core.c:netfilter_net_exit
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_init
  - net/ipv4/route.c:ip_rt_do_proc_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net
  - net/ipv4/raw.c:raw_exit_net
  - net/ipv4/udp.c:udp4_proc_exit_net
  - net/ipv4/udplite.c:udplite4_proc_exit_net
  - net/ipv4/arp.c:arp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/ping.c:ping_v4_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_init_net
  - net/ipv4/proc.c:ip_proc_init_net
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/xfrm/xfrm_proc.c:xfrm_proc_fini
  - net/unix/af_unix.c:unix_net_exit
  - net/ipv6/anycast.c:ac6_proc_exit
  - net/ipv6/addrconf.c:if6_proc_net_exit
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/udp.c:udp6_proc_exit
  - net/ipv6/udplite.c:udplite6_proc_exit_net
  - net/ipv6/raw.c:raw6_exit_net
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcp6_proc_exit
  - net/ipv6/ping.c:ping_v6_proc_exit_net
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_init_net
  - net/ipv6/proc.c:ipv6_proc_init_net
  - net/wireless/wext-proc.c:wext_proc_exit
```
**Symbols:**

```
ffffffff813c1280-ffffffff813c1407: remove_proc_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void remove_proc_entry(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813d3170)
Location: fs/proc/generic.c:688
Inline: False
Direct callers:
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - fs/proc/proc_tty.c:proc_tty_unregister_driver
  - fs/proc/proc_net.c:proc_net_ns_exit
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/jbd2/journal.c:jbd2_remove_jbd_stats_proc_entry
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - crypto/proc.c:crypto_exit_proc
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/acpi/button.c:acpi_button_add_fs
  - drivers/acpi/button.c:acpi_button_add_fs
  - drivers/acpi/button.c:acpi_button_add_fs
  - drivers/char/misc.c:misc_init
  - drivers/connector/connector.c:cn_fini
  - drivers/scsi/scsi_devinfo.c:scsi_exit_devinfo
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_host_rm
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_proc_exit
  - drivers/input/input.c:input_proc_exit
  - drivers/input/input.c:input_proc_exit
  - drivers/rtc/proc.c:rtc_proc_del_device
  - drivers/md/md.c:md_exit
  - net/core/sock.c:proto_exit_net
  - net/core/neighbour.c:neigh_table_clear
  - net/core/net-procfs.c:dev_mc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/sched/sch_api.c:psched_net_exit
  - net/netlink/af_netlink.c:netlink_net_exit
  - net/netfilter/core.c:netfilter_net_exit
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_init
  - net/ipv4/route.c:ip_rt_do_proc_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net
  - net/ipv4/raw.c:raw_exit_net
  - net/ipv4/udp.c:udp4_proc_exit_net
  - net/ipv4/udplite.c:udplite4_proc_exit_net
  - net/ipv4/arp.c:arp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/ping.c:ping_v4_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_init_net
  - net/ipv4/proc.c:ip_proc_init_net
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/xfrm/xfrm_proc.c:xfrm_proc_fini
  - net/unix/af_unix.c:unix_net_exit
  - net/ipv6/anycast.c:ac6_proc_exit
  - net/ipv6/addrconf.c:if6_proc_net_exit
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/udp.c:udp6_proc_exit
  - net/ipv6/udplite.c:udplite6_proc_exit_net
  - net/ipv6/raw.c:raw6_exit_net
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcp6_proc_exit
  - net/ipv6/ping.c:ping_v6_proc_exit_net
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_init_net
  - net/ipv6/proc.c:ipv6_proc_init_net
  - net/wireless/wext-proc.c:wext_proc_exit
```
**Symbols:**

```
ffffffff813d3170-ffffffff813d32f7: remove_proc_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void remove_proc_entry(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813d9fc0)
Location: fs/proc/generic.c:683
Inline: False
Direct callers:
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - fs/proc/proc_tty.c:proc_tty_unregister_driver
  - fs/proc/proc_net.c:proc_net_ns_exit
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/jbd2/journal.c:jbd2_remove_jbd_stats_proc_entry
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - crypto/proc.c:crypto_exit_proc
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/char/misc.c:misc_init
  - drivers/connector/connector.c:cn_fini
  - drivers/scsi/scsi_devinfo.c:scsi_exit_devinfo
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_host_rm
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_proc_exit
  - drivers/input/input.c:input_proc_exit
  - drivers/input/input.c:input_proc_exit
  - drivers/rtc/proc.c:rtc_proc_del_device
  - drivers/md/md.c:md_exit
  - net/core/sock.c:proto_exit_net
  - net/core/neighbour.c:neigh_table_clear
  - net/core/net-procfs.c:dev_mc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/sched/sch_api.c:psched_net_exit
  - net/netlink/af_netlink.c:netlink_net_exit
  - net/netfilter/core.c:netfilter_net_exit
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_init
  - net/ipv4/route.c:ip_rt_do_proc_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net
  - net/ipv4/raw.c:raw_exit_net
  - net/ipv4/udp.c:udp4_proc_exit_net
  - net/ipv4/udplite.c:udplite4_proc_exit_net
  - net/ipv4/arp.c:arp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/ping.c:ping_v4_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_init_net
  - net/ipv4/proc.c:ip_proc_init_net
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/xfrm/xfrm_proc.c:xfrm_proc_fini
  - net/unix/af_unix.c:unix_net_exit
  - net/ipv6/anycast.c:ac6_proc_exit
  - net/ipv6/addrconf.c:if6_proc_net_exit
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/udp.c:udp6_proc_exit
  - net/ipv6/udplite.c:udplite6_proc_exit_net
  - net/ipv6/raw.c:raw6_exit_net
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcp6_proc_exit
  - net/ipv6/ping.c:ping_v6_proc_exit_net
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_init_net
  - net/ipv6/proc.c:ipv6_proc_init_net
  - net/wireless/wext-proc.c:wext_proc_exit
```
**Symbols:**

```
ffffffff813d9fc0-ffffffff813da13e: remove_proc_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void remove_proc_entry(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8142b6f0)
Location: fs/proc/generic.c:683
Inline: False
Direct callers:
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - fs/proc/proc_tty.c:proc_tty_unregister_driver
  - fs/proc/proc_net.c:proc_net_ns_exit
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/jbd2/journal.c:jbd2_remove_jbd_stats_proc_entry
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - crypto/proc.c:crypto_exit_proc
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/char/misc.c:misc_init
  - drivers/connector/connector.c:cn_fini
  - drivers/scsi/scsi_devinfo.c:scsi_exit_devinfo
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_host_rm
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_proc_exit
  - drivers/input/input.c:input_proc_exit
  - drivers/input/input.c:input_proc_exit
  - drivers/rtc/proc.c:rtc_proc_del_device
  - drivers/md/md.c:md_exit
  - net/core/sock.c:proto_exit_net
  - net/core/neighbour.c:neigh_table_clear
  - net/core/net-procfs.c:dev_mc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/sched/sch_api.c:psched_net_exit
  - net/netlink/af_netlink.c:netlink_net_exit
  - net/netfilter/core.c:netfilter_net_exit
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_init
  - net/ipv4/route.c:ip_rt_do_proc_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net
  - net/ipv4/raw.c:raw_exit_net
  - net/ipv4/udp.c:udp4_proc_exit_net
  - net/ipv4/udplite.c:udplite4_proc_exit_net
  - net/ipv4/arp.c:arp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/ping.c:ping_v4_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_init_net
  - net/ipv4/proc.c:ip_proc_init_net
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/xfrm/xfrm_proc.c:xfrm_proc_fini
  - net/unix/af_unix.c:unix_net_exit
  - net/ipv6/anycast.c:ac6_proc_exit
  - net/ipv6/addrconf.c:if6_proc_net_exit
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/udp.c:udp6_proc_exit
  - net/ipv6/udplite.c:udplite6_proc_exit_net
  - net/ipv6/raw.c:raw6_exit_net
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcp6_proc_exit
  - net/ipv6/ping.c:ping_v6_proc_exit_net
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_init_net
  - net/ipv6/proc.c:ipv6_proc_init_net
  - net/packet/af_packet.c:packet_net_exit
  - net/wireless/wext-proc.c:wext_proc_exit
```
**Symbols:**

```
ffffffff8142b6f0-ffffffff8142b86e: remove_proc_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void remove_proc_entry(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff814a4e40)
Location: fs/proc/generic.c:686
Inline: False
Direct callers:
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - fs/proc/proc_tty.c:proc_tty_unregister_driver
  - fs/proc/proc_net.c:proc_net_ns_exit
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/jbd2/journal.c:jbd2_remove_jbd_stats_proc_entry
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - crypto/proc.c:crypto_exit_proc
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/char/misc.c:misc_init
  - drivers/connector/connector.c:cn_fini
  - drivers/scsi/scsi_devinfo.c:scsi_exit_devinfo
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_host_rm
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_proc_exit
  - drivers/input/input.c:input_proc_exit
  - drivers/input/input.c:input_proc_exit
  - drivers/rtc/proc.c:rtc_proc_del_device
  - drivers/md/md.c:md_exit
  - net/core/sock.c:proto_exit_net
  - net/core/neighbour.c:neigh_table_clear
  - net/core/net-procfs.c:dev_mc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/sched/sch_api.c:psched_net_exit
  - net/netlink/af_netlink.c:netlink_net_exit
  - net/netfilter/core.c:netfilter_net_exit
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_init
  - net/ipv4/route.c:ip_rt_do_proc_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net
  - net/ipv4/raw.c:raw_exit_net
  - net/ipv4/udp.c:udp4_proc_exit_net
  - net/ipv4/udplite.c:udplite4_proc_exit_net
  - net/ipv4/arp.c:arp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/ping.c:ping_v4_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_init_net
  - net/ipv4/proc.c:ip_proc_init_net
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/xfrm/xfrm_proc.c:xfrm_proc_fini
  - net/unix/af_unix.c:unix_net_exit
  - net/ipv6/anycast.c:ac6_proc_exit
  - net/ipv6/addrconf.c:if6_proc_net_exit
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/udp.c:udp6_proc_exit
  - net/ipv6/udplite.c:udplite6_proc_exit_net
  - net/ipv6/raw.c:raw6_exit_net
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcp6_proc_exit
  - net/ipv6/ping.c:ping_v6_proc_exit_net
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_init_net
  - net/ipv6/proc.c:ipv6_proc_init_net
  - net/packet/af_packet.c:packet_net_exit
  - net/wireless/wext-proc.c:wext_proc_exit
```
**Symbols:**

```
ffffffff814a4e40-ffffffff814a4ff3: remove_proc_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void remove_proc_entry(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8153a390)
Location: fs/proc/generic.c:686
Inline: False
Direct callers:
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - fs/proc/proc_tty.c:proc_tty_unregister_driver
  - fs/proc/proc_net.c:proc_net_ns_exit
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/jbd2/journal.c:journal_exit
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - crypto/proc.c:crypto_exit_proc
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/char/misc.c:misc_init
  - drivers/connector/connector.c:cn_fini
  - drivers/scsi/scsi_devinfo.c:scsi_init_devinfo
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_host_rm
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm
  - drivers/input/input.c:input_exit
  - drivers/input/input.c:input_exit
  - drivers/input/input.c:input_exit
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_init
  - drivers/rtc/proc.c:rtc_proc_del_device
  - drivers/md/md.c:md_exit
  - net/core/sock.c:proto_exit_net
  - net/core/neighbour.c:neigh_table_clear
  - net/core/net-procfs.c:dev_mc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/sched/sch_api.c:psched_net_exit
  - net/netlink/af_netlink.c:netlink_net_exit
  - net/netfilter/core.c:netfilter_net_exit
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_init
  - net/ipv4/route.c:ip_rt_do_proc_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net
  - net/ipv4/raw.c:raw_exit_net
  - net/ipv4/udp.c:udp4_proc_exit_net
  - net/ipv4/udplite.c:udplite4_proc_exit_net
  - net/ipv4/arp.c:arp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/ping.c:ping_v4_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_init_net
  - net/ipv4/proc.c:ip_proc_init_net
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/xfrm/xfrm_proc.c:xfrm_proc_fini
  - net/unix/af_unix.c:unix_net_exit
  - net/unix/af_unix.c:unix_net_init
  - net/ipv6/anycast.c:ac6_proc_exit
  - net/ipv6/addrconf.c:if6_proc_net_exit
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/route.c:ip6_route_net_init_late
  - net/ipv6/udp.c:udp6_proc_exit
  - net/ipv6/udplite.c:udplite6_proc_exit_net
  - net/ipv6/raw.c:raw6_exit_net
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcp6_proc_exit
  - net/ipv6/ping.c:ping_v6_proc_exit_net
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_init_net
  - net/ipv6/proc.c:ipv6_proc_init_net
  - net/packet/af_packet.c:packet_net_exit
  - net/wireless/wext-proc.c:wext_proc_exit
```
**Symbols:**

```
ffffffff8153a390-ffffffff8153a543: remove_proc_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void remove_proc_entry(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81572630)
Location: fs/proc/generic.c:685
Inline: False
Direct callers:
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - fs/proc/proc_tty.c:proc_tty_unregister_driver
  - fs/proc/proc_net.c:proc_net_ns_exit
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/jbd2/journal.c:journal_exit
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - crypto/proc.c:crypto_exit_proc
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/char/misc.c:misc_init
  - drivers/connector/connector.c:cn_fini
  - drivers/scsi/scsi_devinfo.c:scsi_init_devinfo
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_host_rm
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm
  - drivers/input/input.c:input_exit
  - drivers/input/input.c:input_exit
  - drivers/input/input.c:input_exit
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_init
  - drivers/rtc/proc.c:rtc_proc_del_device
  - drivers/md/md.c:md_exit
  - net/core/sock.c:proto_exit_net
  - net/core/neighbour.c:neigh_table_clear
  - net/core/net-procfs.c:dev_mc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/sched/sch_api.c:psched_net_exit
  - net/netlink/af_netlink.c:netlink_net_exit
  - net/netfilter/core.c:netfilter_net_exit
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_init
  - net/ipv4/route.c:ip_rt_do_proc_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net
  - net/ipv4/raw.c:raw_exit_net
  - net/ipv4/udp.c:udp4_proc_exit_net
  - net/ipv4/udplite.c:udplite4_proc_exit_net
  - net/ipv4/arp.c:arp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/ping.c:ping_v4_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_init_net
  - net/ipv4/proc.c:ip_proc_init_net
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/xfrm/xfrm_proc.c:xfrm_proc_fini
  - net/unix/af_unix.c:unix_net_exit
  - net/unix/af_unix.c:unix_net_init
  - net/ipv6/anycast.c:ac6_proc_exit
  - net/ipv6/addrconf.c:if6_proc_net_exit
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/route.c:ip6_route_net_init_late
  - net/ipv6/udp.c:udp6_proc_exit
  - net/ipv6/udplite.c:udplite6_proc_exit_net
  - net/ipv6/raw.c:raw6_exit_net
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcp6_proc_exit
  - net/ipv6/ping.c:ping_v6_proc_exit_net
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_init_net
  - net/ipv6/proc.c:ipv6_proc_init_net
  - net/packet/af_packet.c:packet_net_exit
  - net/wireless/wext-proc.c:wext_proc_exit
```
**Symbols:**

```
ffffffff81572630-ffffffff81572807: remove_proc_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void remove_proc_entry(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff815aafe0)
Location: fs/proc/generic.c:685
Inline: False
Direct callers:
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - fs/proc/proc_tty.c:proc_tty_unregister_driver
  - fs/proc/proc_net.c:proc_net_ns_exit
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/jbd2/journal.c:journal_exit
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - crypto/proc.c:crypto_exit_proc
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/char/misc.c:misc_init
  - drivers/connector/connector.c:cn_fini
  - drivers/scsi/scsi_devinfo.c:scsi_init_devinfo
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_host_rm
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm
  - drivers/input/input.c:input_exit
  - drivers/input/input.c:input_exit
  - drivers/input/input.c:input_exit
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_init
  - drivers/rtc/proc.c:rtc_proc_del_device
  - drivers/md/md.c:md_exit
  - net/core/sock.c:proto_exit_net
  - net/core/neighbour.c:neigh_table_clear
  - net/core/net-procfs.c:dev_mc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/sched/sch_api.c:psched_net_exit
  - net/netlink/af_netlink.c:netlink_net_exit
  - net/netfilter/core.c:netfilter_net_exit
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_init
  - net/ipv4/route.c:ip_rt_do_proc_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net
  - net/ipv4/raw.c:raw_exit_net
  - net/ipv4/udp.c:udp4_proc_exit_net
  - net/ipv4/udplite.c:udplite4_proc_exit_net
  - net/ipv4/arp.c:arp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/ping.c:ping_v4_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_init_net
  - net/ipv4/proc.c:ip_proc_init_net
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/xfrm/xfrm_proc.c:xfrm_proc_fini
  - net/unix/af_unix.c:unix_net_exit
  - net/unix/af_unix.c:unix_net_init
  - net/ipv6/anycast.c:ac6_proc_exit
  - net/ipv6/addrconf.c:if6_proc_net_exit
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/route.c:ip6_route_net_init_late
  - net/ipv6/udp.c:udp6_proc_exit
  - net/ipv6/udplite.c:udplite6_proc_exit_net
  - net/ipv6/raw.c:raw6_exit_net
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcp6_proc_exit
  - net/ipv6/ping.c:ping_v6_proc_exit_net
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_init_net
  - net/ipv6/proc.c:ipv6_proc_init_net
  - net/packet/af_packet.c:packet_net_exit
  - net/wireless/wext-proc.c:wext_proc_exit
```
**Symbols:**

```
ffffffff815aafe0-ffffffff815ab1b7: remove_proc_entry (STB_GLOBAL)
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
void remove_proc_entry(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffff8000104442d0)
Location: fs/proc/generic.c:655
Inline: False
Direct callers:
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - fs/proc/proc_tty.c:proc_tty_unregister_driver
  - fs/proc/proc_net.c:proc_net_ns_exit
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/jbd2/journal.c:jbd2_remove_jbd_stats_proc_entry
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - crypto/proc.c:crypto_exit_proc
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/char/misc.c:misc_init
  - drivers/connector/connector.c:cn_fini
  - drivers/scsi/scsi_devinfo.c:scsi_init_devinfo
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_host_rm
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_proc_exit
  - drivers/input/input.c:input_proc_exit
  - drivers/input/input.c:input_proc_exit
  - drivers/rtc/proc.c:rtc_proc_del_device
  - drivers/md/md.c:md_exit
  - net/core/sock.c:proto_exit_net
  - net/core/neighbour.c:neigh_table_clear
  - net/core/net-procfs.c:dev_mc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/sched/sch_api.c:psched_net_exit
  - net/netlink/af_netlink.c:netlink_net_exit
  - net/netfilter/core.c:netfilter_net_exit
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net
  - net/ipv4/raw.c:raw_exit_net
  - net/ipv4/udp.c:udp4_proc_exit_net
  - net/ipv4/udplite.c:udplite4_proc_exit_net
  - net/ipv4/arp.c:arp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/ping.c:ping_v4_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/xfrm/xfrm_proc.c:xfrm_proc_fini
  - net/unix/af_unix.c:unix_net_exit
  - net/ipv6/anycast.c:ac6_proc_exit
  - net/ipv6/addrconf.c:if6_proc_net_exit
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/udp.c:udp6_proc_exit
  - net/ipv6/udplite.c:udplite6_proc_exit_net
  - net/ipv6/raw.c:raw6_exit_net
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcp6_proc_exit
  - net/ipv6/ping.c:ping_v6_proc_exit_net
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_init
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/wireless/wext-proc.c:wext_proc_exit
```
**Symbols:**

```
ffff8000104442d0-ffff8000104444cc: remove_proc_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void remove_proc_entry(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (c06093b8)
Location: fs/proc/generic.c:655
Inline: False
Direct callers:
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - fs/proc/proc_tty.c:proc_tty_unregister_driver
  - fs/proc/proc_net.c:proc_net_ns_exit
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/jbd2/journal.c:jbd2_remove_jbd_stats_proc_entry
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - crypto/proc.c:crypto_exit_proc
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/char/misc.c:misc_init
  - drivers/connector/connector.c:cn_fini
  - drivers/scsi/scsi_devinfo.c:scsi_init_devinfo
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_host_rm
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm
  - drivers/mtd/mtdcore.c:cleanup_mtd
  - drivers/mtd/mtdcore.c:init_mtd
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_proc_exit
  - drivers/input/input.c:input_proc_exit
  - drivers/input/input.c:input_proc_exit
  - drivers/rtc/proc.c:rtc_proc_del_device
  - drivers/md/md.c:md_exit
  - net/core/sock.c:proto_exit_net
  - net/core/neighbour.c:neigh_table_clear
  - net/core/net-procfs.c:dev_mc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/sched/sch_api.c:psched_net_exit
  - net/netlink/af_netlink.c:netlink_net_exit
  - net/netfilter/core.c:netfilter_net_exit
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net
  - net/ipv4/raw.c:raw_exit_net
  - net/ipv4/udp.c:udp4_proc_exit_net
  - net/ipv4/udplite.c:udplite4_proc_exit_net
  - net/ipv4/arp.c:arp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/ping.c:ping_v4_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/xfrm/xfrm_proc.c:xfrm_proc_fini
  - net/unix/af_unix.c:unix_net_exit
  - net/ipv6/anycast.c:ac6_proc_exit
  - net/ipv6/addrconf.c:if6_proc_net_exit
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/udp.c:udp6_proc_exit
  - net/ipv6/udplite.c:udplite6_proc_exit_net
  - net/ipv6/raw.c:raw6_exit_net
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcp6_proc_exit
  - net/ipv6/ping.c:ping_v6_proc_exit_net
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_init
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/wireless/wext-proc.c:wext_proc_exit
```
**Symbols:**

```
c06093b8-c0609570: remove_proc_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void remove_proc_entry(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (c000000000559a50)
Location: fs/proc/generic.c:655
Inline: False
Direct callers:
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - fs/proc/proc_tty.c:proc_tty_unregister_driver
  - fs/proc/proc_net.c:proc_net_ns_exit
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/jbd2/journal.c:jbd2_remove_jbd_stats_proc_entry
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - crypto/proc.c:crypto_exit_proc
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/char/misc.c:misc_init
  - drivers/connector/connector.c:cn_fini
  - drivers/scsi/scsi_devinfo.c:scsi_init_devinfo
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_host_rm
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_proc_exit
  - drivers/input/input.c:input_proc_exit
  - drivers/input/input.c:input_proc_exit
  - drivers/rtc/proc.c:rtc_proc_del_device
  - drivers/md/md.c:md_exit
  - net/core/sock.c:proto_exit_net
  - net/core/neighbour.c:neigh_table_clear
  - net/core/net-procfs.c:dev_mc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/sched/sch_api.c:psched_net_exit
  - net/netlink/af_netlink.c:netlink_net_exit
  - net/netfilter/core.c:netfilter_net_exit
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net
  - net/ipv4/raw.c:raw_exit_net
  - net/ipv4/udp.c:udp4_proc_exit_net
  - net/ipv4/udplite.c:udplite4_proc_exit_net
  - net/ipv4/arp.c:arp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/ping.c:ping_v4_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/xfrm/xfrm_proc.c:xfrm_proc_fini
  - net/unix/af_unix.c:unix_net_exit
  - net/ipv6/anycast.c:ac6_proc_exit
  - net/ipv6/addrconf.c:if6_proc_net_exit
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/udp.c:udp6_proc_exit
  - net/ipv6/udplite.c:udplite6_proc_exit_net
  - net/ipv6/raw.c:raw6_exit_net
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcp6_proc_exit
  - net/ipv6/ping.c:ping_v6_proc_exit_net
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_init
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/wireless/wext-proc.c:wext_proc_exit
```
**Symbols:**

```
c000000000559a50-c000000000559c8c: remove_proc_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void remove_proc_entry(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffe0002d9d18)
Location: fs/proc/generic.c:655
Inline: False
Direct callers:
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - fs/proc/proc_tty.c:proc_tty_unregister_driver
  - fs/proc/proc_net.c:proc_net_ns_exit
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/jbd2/journal.c:jbd2_remove_jbd_stats_proc_entry
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - crypto/proc.c:crypto_exit_proc
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/char/misc.c:misc_init
  - drivers/connector/connector.c:cn_fini
  - drivers/scsi/scsi_devinfo.c:scsi_init_devinfo
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_host_rm
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_proc_exit
  - drivers/input/input.c:input_proc_exit
  - drivers/input/input.c:input_proc_exit
  - drivers/rtc/proc.c:rtc_proc_del_device
  - drivers/md/md.c:md_exit
  - net/core/sock.c:proto_exit_net
  - net/core/neighbour.c:neigh_table_clear
  - net/core/net-procfs.c:dev_mc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/sched/sch_api.c:psched_net_exit
  - net/netlink/af_netlink.c:netlink_net_exit
  - net/netfilter/core.c:netfilter_net_exit
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net
  - net/ipv4/raw.c:raw_exit_net
  - net/ipv4/udp.c:udp4_proc_exit_net
  - net/ipv4/udplite.c:udplite4_proc_exit_net
  - net/ipv4/arp.c:arp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/ping.c:ping_v4_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/xfrm/xfrm_proc.c:xfrm_proc_fini
  - net/unix/af_unix.c:unix_net_exit
  - net/ipv6/anycast.c:ac6_proc_exit
  - net/ipv6/addrconf.c:if6_proc_net_exit
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/udp.c:udp6_proc_exit
  - net/ipv6/udplite.c:udplite6_proc_exit_net
  - net/ipv6/raw.c:raw6_exit_net
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcp6_proc_exit
  - net/ipv6/ping.c:ping_v6_proc_exit_net
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_init
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/wireless/wext-proc.c:wext_proc_exit
```
**Symbols:**

```
ffffffe0002d9d18-ffffffe0002d9e68: remove_proc_entry (STB_GLOBAL)
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
void remove_proc_entry(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813707f0)
Location: fs/proc/generic.c:655
Inline: False
Direct callers:
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - fs/proc/proc_tty.c:proc_tty_unregister_driver
  - fs/proc/proc_net.c:proc_net_ns_exit
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/jbd2/journal.c:jbd2_remove_jbd_stats_proc_entry
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - crypto/proc.c:crypto_exit_proc
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/char/misc.c:misc_init
  - drivers/connector/connector.c:cn_fini
  - drivers/scsi/scsi_devinfo.c:scsi_init_devinfo
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_host_rm
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_proc_exit
  - drivers/input/input.c:input_proc_exit
  - drivers/input/input.c:input_proc_exit
  - drivers/rtc/proc.c:rtc_proc_del_device
  - drivers/md/md.c:md_exit
  - net/core/sock.c:proto_exit_net
  - net/core/neighbour.c:neigh_table_clear
  - net/core/net-procfs.c:dev_mc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/sched/sch_api.c:psched_net_exit
  - net/netlink/af_netlink.c:netlink_net_exit
  - net/netfilter/core.c:netfilter_net_exit
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net
  - net/ipv4/raw.c:raw_exit_net
  - net/ipv4/udp.c:udp4_proc_exit_net
  - net/ipv4/udplite.c:udplite4_proc_exit_net
  - net/ipv4/arp.c:arp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/ping.c:ping_v4_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/xfrm/xfrm_proc.c:xfrm_proc_fini
  - net/unix/af_unix.c:unix_net_exit
  - net/ipv6/anycast.c:ac6_proc_exit
  - net/ipv6/addrconf.c:if6_proc_net_exit
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/udp.c:udp6_proc_exit
  - net/ipv6/udplite.c:udplite6_proc_exit_net
  - net/ipv6/raw.c:raw6_exit_net
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcp6_proc_exit
  - net/ipv6/ping.c:ping_v6_proc_exit_net
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_init
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/wireless/wext-proc.c:wext_proc_exit
```
**Symbols:**

```
ffffffff813707f0-ffffffff81370962: remove_proc_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void remove_proc_entry(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81361280)
Location: fs/proc/generic.c:655
Inline: False
Direct callers:
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - fs/proc/proc_tty.c:proc_tty_unregister_driver
  - fs/proc/proc_net.c:proc_net_ns_exit
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/jbd2/journal.c:jbd2_remove_jbd_stats_proc_entry
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - crypto/proc.c:crypto_exit_proc
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/char/misc.c:misc_init
  - drivers/connector/connector.c:cn_fini
  - drivers/scsi/scsi_devinfo.c:scsi_init_devinfo
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_host_rm
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_proc_exit
  - drivers/input/input.c:input_proc_exit
  - drivers/input/input.c:input_proc_exit
  - drivers/rtc/proc.c:rtc_proc_del_device
  - drivers/md/md.c:md_exit
  - net/core/sock.c:proto_exit_net
  - net/core/neighbour.c:neigh_table_clear
  - net/core/net-procfs.c:dev_mc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/sched/sch_api.c:psched_net_exit
  - net/netlink/af_netlink.c:netlink_net_exit
  - net/netfilter/core.c:netfilter_net_exit
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net
  - net/ipv4/raw.c:raw_exit_net
  - net/ipv4/udp.c:udp4_proc_exit_net
  - net/ipv4/udplite.c:udplite4_proc_exit_net
  - net/ipv4/arp.c:arp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/ping.c:ping_v4_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/xfrm/xfrm_proc.c:xfrm_proc_fini
  - net/unix/af_unix.c:unix_net_exit
  - net/ipv6/anycast.c:ac6_proc_exit
  - net/ipv6/addrconf.c:if6_proc_net_exit
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/udp.c:udp6_proc_exit
  - net/ipv6/udplite.c:udplite6_proc_exit_net
  - net/ipv6/raw.c:raw6_exit_net
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcp6_proc_exit
  - net/ipv6/ping.c:ping_v6_proc_exit_net
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_init
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/wireless/wext-proc.c:wext_proc_exit
```
**Symbols:**

```
ffffffff81361280-ffffffff813613f2: remove_proc_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void remove_proc_entry(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8136e2c0)
Location: fs/proc/generic.c:655
Inline: False
Direct callers:
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - fs/proc/proc_tty.c:proc_tty_unregister_driver
  - fs/proc/proc_net.c:proc_net_ns_exit
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/jbd2/journal.c:jbd2_remove_jbd_stats_proc_entry
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - crypto/proc.c:crypto_exit_proc
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/char/misc.c:misc_init
  - drivers/connector/connector.c:cn_fini
  - drivers/scsi/scsi_devinfo.c:scsi_init_devinfo
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_host_rm
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_proc_exit
  - drivers/input/input.c:input_proc_exit
  - drivers/input/input.c:input_proc_exit
  - drivers/rtc/proc.c:rtc_proc_del_device
  - drivers/md/md.c:md_exit
  - net/core/sock.c:proto_exit_net
  - net/core/neighbour.c:neigh_table_clear
  - net/core/net-procfs.c:dev_mc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/sched/sch_api.c:psched_net_exit
  - net/netlink/af_netlink.c:netlink_net_exit
  - net/netfilter/core.c:netfilter_net_exit
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/netfilter/nfnetlink_queue.c:nfnl_queue_net_exit
  - net/netfilter/nfnetlink_log.c:nfnl_log_net_exit
  - net/netfilter/nf_conntrack_standalone.c:nf_conntrack_pernet_exit
  - net/netfilter/nf_conntrack_standalone.c:nf_conntrack_pernet_exit
  - net/netfilter/nf_conntrack_expect.c:nf_conntrack_expect_pernet_fini
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net
  - net/ipv4/raw.c:raw_exit_net
  - net/ipv4/udp.c:udp4_proc_exit_net
  - net/ipv4/udplite.c:udplite4_proc_exit_net
  - net/ipv4/arp.c:arp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/ping.c:ping_v4_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/xfrm/xfrm_proc.c:xfrm_proc_fini
  - net/unix/af_unix.c:unix_net_exit
  - net/ipv6/anycast.c:ac6_proc_exit
  - net/ipv6/addrconf.c:if6_proc_net_exit
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/udp.c:udp6_proc_exit
  - net/ipv6/udplite.c:udplite6_proc_exit_net
  - net/ipv6/raw.c:raw6_exit_net
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcp6_proc_exit
  - net/ipv6/ping.c:ping_v6_proc_exit_net
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_init
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/wireless/wext-proc.c:wext_proc_exit
```
**Symbols:**

```
ffffffff8136e2c0-ffffffff8136e432: remove_proc_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void remove_proc_entry(const char *name, struct proc_dir_entry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81381bf0)
Location: fs/proc/generic.c:655
Inline: False
Direct callers:
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - kernel/irq/proc.c:unregister_irq_proc
  - fs/proc/proc_tty.c:proc_tty_unregister_driver
  - fs/proc/proc_net.c:proc_net_ns_exit
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/jbd2/journal.c:jbd2_remove_jbd_stats_proc_entry
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - crypto/proc.c:crypto_exit_proc
  - drivers/video/fbdev/core/fbmem.c:fbmem_init
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/char/misc.c:misc_init
  - drivers/connector/connector.c:cn_fini
  - drivers/scsi/scsi_devinfo.c:scsi_init_devinfo
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/scsi_proc.c:scsi_exit_procfs
  - drivers/scsi/scsi_proc.c:scsi_init_procfs
  - drivers/scsi/scsi_proc.c:scsi_proc_host_rm
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_rm
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_init
  - drivers/input/input.c:input_proc_exit
  - drivers/input/input.c:input_proc_exit
  - drivers/input/input.c:input_proc_exit
  - drivers/rtc/proc.c:rtc_proc_del_device
  - drivers/md/md.c:md_exit
  - net/core/sock.c:proto_exit_net
  - net/core/neighbour.c:neigh_table_clear
  - net/core/net-procfs.c:dev_mc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_exit
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/sched/sch_api.c:psched_net_exit
  - net/netlink/af_netlink.c:netlink_net_exit
  - net/netfilter/core.c:netfilter_net_exit
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/route.c:ip_rt_do_proc_exit
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net
  - net/ipv4/raw.c:raw_exit_net
  - net/ipv4/udp.c:udp4_proc_exit_net
  - net/ipv4/udplite.c:udplite4_proc_exit_net
  - net/ipv4/arp.c:arp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/igmp.c:igmp_net_exit
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_exit
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/ping.c:ping_v4_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/proc.c:ip_proc_exit_net
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/xfrm/xfrm_proc.c:xfrm_proc_fini
  - net/unix/af_unix.c:unix_net_exit
  - net/ipv6/anycast.c:ac6_proc_exit
  - net/ipv6/addrconf.c:if6_proc_net_exit
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/route.c:ip6_route_net_exit_late
  - net/ipv6/udp.c:udp6_proc_exit
  - net/ipv6/udplite.c:udplite6_proc_exit_net
  - net/ipv6/raw.c:raw6_exit_net
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_exit
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcp6_proc_exit
  - net/ipv6/ping.c:ping_v6_proc_exit_net
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_exit
  - net/ipv6/ip6mr.c:ip6mr_net_init
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/ipv6/proc.c:ipv6_proc_exit_net
  - net/wireless/wext-proc.c:wext_proc_exit
```
**Symbols:**

```
ffffffff81381bf0-ffffffff81381d77: remove_proc_entry (STB_GLOBAL)
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
