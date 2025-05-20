# Function: <code>jiffies_to_clock_t</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
clock_t jiffies_to_clock_t(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810eae90)
Location: kernel/time/time.c:629
Inline: False
Direct callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:do_notify_parent
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/mcast.c:igmp6_mc_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
**Symbols:**

```
ffffffff810eae90-ffffffff810eaeb9: jiffies_to_clock_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
clock_t jiffies_to_clock_t(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810f1b30)
Location: kernel/time/time.c:636
Inline: False
Direct callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:do_notify_parent
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/mcast.c:igmp6_mc_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
**Symbols:**

```
ffffffff810f1b30-ffffffff810f1b59: jiffies_to_clock_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
clock_t jiffies_to_clock_t(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810f8cb0)
Location: kernel/time/time.c:636
Inline: False
Direct callers:
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:do_notify_parent
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - kernel/sys.c:do_sys_times
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/mcast.c:igmp6_mc_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
**Symbols:**

```
ffffffff810f8cb0-ffffffff810f8cd9: jiffies_to_clock_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
clock_t jiffies_to_clock_t(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810facd0)
Location: kernel/time/time.c:726
Inline: False
Direct callers:
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/ipmr.c:__ipmr_fill_mroute
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/mcast.c:igmp6_mc_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/ip6mr.c:__ip6mr_fill_mroute
```
**Symbols:**

```
ffffffff810facd0-ffffffff810facf9: jiffies_to_clock_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
clock_t jiffies_to_clock_t(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81105660)
Location: kernel/time/time.c:693
Inline: False
Direct callers:
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/ipmr.c:__ipmr_fill_mroute
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/mcast.c:igmp6_mc_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/ip6mr.c:__ip6mr_fill_mroute
```
**Symbols:**

```
ffffffff81105660-ffffffff81105689: jiffies_to_clock_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
clock_t jiffies_to_clock_t(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811104c0)
Location: kernel/time/time.c:705
Inline: False
Direct callers:
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/mcast.c:igmp6_mc_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
**Symbols:**

```
ffffffff811104c0-ffffffff811104e9: jiffies_to_clock_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
clock_t jiffies_to_clock_t(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111bab0)
Location: kernel/time/time.c:643
Inline: False
Direct callers:
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/mcast.c:igmp6_mc_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
**Symbols:**

```
ffffffff8111bab0-ffffffff8111bad9: jiffies_to_clock_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
clock_t jiffies_to_clock_t(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811264d0)
Location: kernel/time/time.c:711
Inline: False
Direct callers:
  - kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv
  - kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/mcast.c:igmp6_mc_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
**Symbols:**

```
ffffffff811264d0-ffffffff811264f9: jiffies_to_clock_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
clock_t jiffies_to_clock_t(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81132470)
Location: kernel/time/time.c:711
Inline: False
Direct callers:
  - kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv
  - kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/mcast.c:igmp6_mc_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
**Symbols:**

```
ffffffff81132470-ffffffff81132499: jiffies_to_clock_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
clock_t jiffies_to_clock_t(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81141820)
Location: kernel/time/time.c:621
Inline: False
Direct callers:
  - kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv
  - kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
  - net/ipv4/tcp_ipv4.c:get_openreq4
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/mcast.c:igmp6_mc_seq_show
  - net/ipv6/tcp_ipv6.c:get_timewait6_sock
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
  - net/ipv6/tcp_ipv6.c:get_openreq6
```
**Symbols:**

```
ffffffff81141820-ffffffff81141849: jiffies_to_clock_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
clock_t jiffies_to_clock_t(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8113da30)
Location: kernel/time/time.c:621
Inline: False
Direct callers:
  - kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv
  - kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
  - net/ipv4/tcp_ipv4.c:get_openreq4
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/mcast.c:igmp6_mc_seq_show
  - net/ipv6/tcp_ipv6.c:get_timewait6_sock
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
  - net/ipv6/tcp_ipv6.c:get_openreq6
```
**Symbols:**

```
ffffffff8113da30-ffffffff8113da59: jiffies_to_clock_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
clock_t jiffies_to_clock_t(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8113ec80)
Location: kernel/time/time.c:621
Inline: False
Direct callers:
  - kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv
  - kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/nexthop.c:nla_put_nh_group_res
  - net/ipv4/nexthop.c:nla_put_nh_group_res
  - net/ipv4/nexthop.c:nla_put_nh_group_res
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/mcast.c:igmp6_mc_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
```
**Symbols:**

```
ffffffff8113ec80-ffffffff8113eca9: jiffies_to_clock_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
clock_t jiffies_to_clock_t(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81162110)
Location: kernel/time/time.c:621
Inline: False
Direct callers:
  - kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv
  - kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv
  - block/bsg.c:bsg_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/nexthop.c:nla_put_nh_group_res
  - net/ipv4/nexthop.c:nla_put_nh_group_res
  - net/ipv4/nexthop.c:nla_put_nh_group_res
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/mcast.c:igmp6_mc_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
```
**Symbols:**

```
ffffffff81162110-ffffffff81162139: jiffies_to_clock_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
clock_t jiffies_to_clock_t(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81195080)
Location: kernel/time/time.c:621
Inline: False
Direct callers:
  - kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv
  - kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv
  - block/bsg.c:bsg_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/nexthop.c:nla_put_nh_group_res
  - net/ipv4/nexthop.c:nla_put_nh_group_res
  - net/ipv4/nexthop.c:nla_put_nh_group_res
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/mcast.c:igmp6_mc_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
```
**Symbols:**

```
ffffffff81195080-ffffffff811950b0: jiffies_to_clock_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
clock_t jiffies_to_clock_t(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811d2e20)
Location: kernel/time/time.c:621
Inline: False
Direct callers:
  - kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv
  - kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv
  - block/bsg.c:bsg_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/nexthop.c:nla_put_nh_group_res
  - net/ipv4/nexthop.c:nla_put_nh_group_res
  - net/ipv4/nexthop.c:nla_put_nh_group_res
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/mcast.c:igmp6_mc_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
```
**Symbols:**

```
ffffffff811d2e20-ffffffff811d2e50: jiffies_to_clock_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
clock_t jiffies_to_clock_t(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811e7110)
Location: kernel/time/time.c:621
Inline: False
Direct callers:
  - kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv
  - kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv
  - block/bsg.c:bsg_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/nexthop.c:nla_put_nh_group_res
  - net/ipv4/nexthop.c:nla_put_nh_group_res
  - net/ipv4/nexthop.c:nla_put_nh_group_res
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/mcast.c:igmp6_mc_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
```
**Symbols:**

```
ffffffff811e7110-ffffffff811e7140: jiffies_to_clock_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
clock_t jiffies_to_clock_t(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811fce60)
Location: kernel/time/time.c:662
Inline: False
Direct callers:
  - kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv
  - kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv
  - block/bsg.c:bsg_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/nexthop.c:nla_put_nh_group_res
  - net/ipv4/nexthop.c:nla_put_nh_group_res
  - net/ipv4/nexthop.c:nla_put_nh_group_res
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/mcast.c:igmp6_mc_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
```
**Symbols:**

```
ffffffff811fce60-ffffffff811fce90: jiffies_to_clock_t (STB_GLOBAL)
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
clock_t jiffies_to_clock_t(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffff800010199f60)
Location: kernel/time/time.c:711
Inline: False
Direct callers:
  - kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv
  - kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/mcast.c:igmp6_mc_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
**Symbols:**

```
ffff800010199f60-ffff800010199fa8: jiffies_to_clock_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
clock_t jiffies_to_clock_t(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c03e53d0)
Location: kernel/time/time.c:711
Inline: False
Direct callers:
  - kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/mcast.c:igmp6_mc_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
**Symbols:**

```
c03e53d0-c03e5430: jiffies_to_clock_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
clock_t jiffies_to_clock_t(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c0000000001fa1e0)
Location: kernel/time/time.c:711
Inline: False
Direct callers:
  - kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv
  - kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/mcast.c:igmp6_mc_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
**Symbols:**

```
c0000000001fa1e0-c0000000001fa214: jiffies_to_clock_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
clock_t jiffies_to_clock_t(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffe00012a3fc)
Location: kernel/time/time.c:711
Inline: False
Direct callers:
  - kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/mcast.c:igmp6_mc_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
**Symbols:**

```
ffffffe00012a3fc-ffffffe00012a434: jiffies_to_clock_t (STB_GLOBAL)
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
clock_t jiffies_to_clock_t(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8112ac20)
Location: kernel/time/time.c:711
Inline: False
Direct callers:
  - kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv
  - kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/mcast.c:igmp6_mc_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
**Symbols:**

```
ffffffff8112ac20-ffffffff8112ac49: jiffies_to_clock_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
clock_t jiffies_to_clock_t(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111d490)
Location: kernel/time/time.c:711
Inline: False
Direct callers:
  - kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv
  - kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - drivers/net/vxlan.c:vxlan_fdb_info
  - drivers/net/vxlan.c:vxlan_fdb_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/mcast.c:igmp6_mc_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
**Symbols:**

```
ffffffff8111d490-ffffffff8111d4b9: jiffies_to_clock_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
clock_t jiffies_to_clock_t(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81128940)
Location: kernel/time/time.c:711
Inline: False
Direct callers:
  - kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv
  - kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/mcast.c:igmp6_mc_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
**Symbols:**

```
ffffffff81128940-ffffffff81128969: jiffies_to_clock_t (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
clock_t jiffies_to_clock_t(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81134fc0)
Location: kernel/time/time.c:711
Inline: False
Direct callers:
  - kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv
  - kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/core/rtnetlink.c:rtnl_put_cacheinfo
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
  - net/ipv4/igmp.c:igmp_mc_seq_show
  - net/ipv4/ipmr_base.c:mr_fill_mroute
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/mcast.c:igmp6_mc_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
**Symbols:**

```
ffffffff81134fc0-ffffffff81134fe9: jiffies_to_clock_t (STB_GLOBAL)
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
