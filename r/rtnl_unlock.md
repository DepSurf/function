# Function: <code>rtnl_unlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81729c60)
Location: net/core/rtnetlink.c:79
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_link_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnetlink_rcv
Direct callers:
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_set_bools
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/virtio_net.c:virtnet_config_changed_work
  - drivers/net/virtio_net.c:virtnet_restore
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:netback_changed
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
  - net/core/dev.c:netdev_notify_peers
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:unregister_netdev
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:default_device_exit
  - net/core/dev.c:register_netdev
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/link_watch.c:linkwatch_event
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/net-sysfs.c:set_tx_maxrate
  - net/core/net-sysfs.c:set_tx_maxrate
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_async_cleanup
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:cgrp_css_online
  - net/sched/sch_api.c:qdisc_create
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/sched/act_api.c:tcf_action_init_1
  - net/netfilter/core.c:nf_unregister_hook
  - net/netfilter/core.c:netfilter_net_exit
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_verify_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/fib6_rules.c:fib6_rules_net_exit
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/wireless/wext-core.c:wireless_nlevent_process
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-proc.c:wireless_dev_seq_stop
```
**Symbols:**

```
ffffffff81729c60-ffffffff81729c70: rtnl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81794cd8)
Location: net/core/rtnetlink.c:101
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnl_link_register
Direct callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/virtio_net.c:virtnet_restore
  - drivers/net/virtio_net.c:virtnet_config_changed_work
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:default_device_exit
  - net/core/dev.c:unregister_netdev
  - net/core/dev.c:register_netdev
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:netdev_notify_peers
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/link_watch.c:linkwatch_event
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/net-sysfs.c:set_tx_maxrate
  - net/core/net-sysfs.c:set_tx_maxrate
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_async_cleanup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:cgrp_css_online
  - net/sched/sch_api.c:qdisc_create
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/sched/act_api.c:tcf_action_init_1
  - net/netfilter/core.c:netfilter_net_exit
  - net/netfilter/core.c:nf_unregister_hook
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_verify_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
  - net/ipv6/fib6_rules.c:fib6_rules_net_exit
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:wireless_nlevent_process
  - net/wireless/wext-proc.c:wireless_dev_seq_stop
  - net/switchdev/switchdev.c:unregister_switchdev_notifier
  - net/switchdev/switchdev.c:register_switchdev_notifier
  - net/switchdev/switchdev.c:switchdev_deferred_process_work
```
**Symbols:**

```
ffffffff817937a0-ffffffff817937b0: rtnl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817c2558)
Location: net/core/rtnetlink.c:101
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnl_link_register
Direct callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_connect
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:default_device_exit
  - net/core/dev.c:unregister_netdev
  - net/core/dev.c:register_netdev
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:netdev_notify_peers
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/link_watch.c:linkwatch_event
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/net-sysfs.c:set_tx_maxrate
  - net/core/net-sysfs.c:set_tx_maxrate
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_async_cleanup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:cgrp_css_online
  - net/sched/sch_api.c:qdisc_create
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/sched/act_api.c:tcf_action_init_1
  - net/netfilter/core.c:netfilter_net_exit
  - net/netfilter/core.c:nf_unregister_hooks
  - net/netfilter/core.c:nf_register_hooks
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_trie.c:fib_seq_sum
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_verify_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
  - net/ipv6/fib6_rules.c:fib6_rules_net_exit
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:wireless_nlevent_process
  - net/wireless/wext-proc.c:wireless_dev_seq_stop
  - net/switchdev/switchdev.c:unregister_switchdev_notifier
  - net/switchdev/switchdev.c:register_switchdev_notifier
  - net/switchdev/switchdev.c:switchdev_deferred_process_work
```
**Symbols:**

```
ffffffff817c1070-ffffffff817c1080: rtnl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817e0cf8)
Location: net/core/rtnetlink.c:103
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnl_link_register
Direct callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:default_device_exit
  - net/core/dev.c:unregister_netdev
  - net/core/dev.c:register_netdev
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:netdev_notify_peers
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/link_watch.c:linkwatch_event
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/net-sysfs.c:set_tx_maxrate
  - net/core/net-sysfs.c:set_tx_maxrate
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_async_cleanup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:cgrp_css_online
  - net/sched/sch_api.c:qdisc_create
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/raw.c:raw_close
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_notifier.c:fib_seq_sum
  - net/ipv4/fib_notifier.c:fib_seq_sum
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_verify_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
  - net/ipv6/fib6_rules.c:fib6_rules_net_exit
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:wireless_nlevent_process
  - net/wireless/wext-proc.c:wireless_dev_seq_stop
  - net/switchdev/switchdev.c:switchdev_deferred_process_work
```
**Symbols:**

```
ffffffff817df830-ffffffff817df840: rtnl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8185bc56)
Location: net/core/rtnetlink.c:103
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnl_link_register
Direct callers:
  - kernel/bpf/offload.c:bpf_prog_offload_compile
  - kernel/bpf/offload.c:bpf_prog_offload_destroy
  - kernel/bpf/offload.c:bpf_prog_offload_verifier_prep
  - kernel/bpf/offload.c:bpf_prog_offload_init
  - kernel/bpf/offload.c:bpf_prog_offload_init
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:default_device_exit
  - net/core/dev.c:unregister_netdev
  - net/core/dev.c:register_netdev
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:netdev_notify_peers
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/link_watch.c:linkwatch_event
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_async_cleanup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:cgrp_css_online
  - net/sched/sch_api.c:qdisc_create
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/sched/act_api.c:tc_setup_cb_egdev_unregister
  - net/sched/act_api.c:tc_setup_cb_egdev_unregister
  - net/sched/act_api.c:tc_setup_cb_egdev_register
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/raw.c:raw_close
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_verify_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
  - net/ipv6/fib6_rules.c:fib6_rules_net_exit
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:wireless_nlevent_process
  - net/wireless/wext-proc.c:wireless_dev_seq_stop
  - net/switchdev/switchdev.c:switchdev_deferred_process_work
```
**Symbols:**

```
ffffffff8185a0e0-ffffffff8185a0f0: rtnl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818a75d6)
Location: net/core/rtnetlink.c:114
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnl_link_register
  - net/core/rtnetlink.c:rtnl_register_internal
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_map_offload_map_free
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_compile
  - kernel/bpf/offload.c:bpf_prog_offload_destroy
  - kernel/bpf/offload.c:bpf_prog_offload_verifier_prep
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_unregister_upstream
  - drivers/net/phy/sfp-bus.c:sfp_register_upstream
  - drivers/net/phy/sfp-bus.c:sfp_register_upstream
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:sock_do_ioctl
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:default_device_exit
  - net/core/dev.c:unregister_netdev
  - net/core/dev.c:register_netdev
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:netdev_notify_peers
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/link_watch.c:linkwatch_event
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_async_cleanup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:cgrp_css_online
  - net/sched/sch_api.c:qdisc_create
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/act_api.c:tc_setup_cb_egdev_unregister
  - net/sched/act_api.c:tc_setup_cb_egdev_unregister
  - net/sched/act_api.c:tc_setup_cb_egdev_register
  - net/sched/act_api.c:tcf_action_init_1
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_verify_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
  - net/ipv6/fib6_rules.c:fib6_rules_net_exit
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-proc.c:wireless_dev_seq_stop
  - net/switchdev/switchdev.c:switchdev_deferred_process_work
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
```
**Symbols:**

```
ffffffff818a5960-ffffffff818a5970: rtnl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818cb416)
Location: net/core/rtnetlink.c:114
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnl_link_register
  - net/core/rtnetlink.c:rtnl_register_internal
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_map_offload_map_free
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_unregister_upstream
  - drivers/net/phy/sfp-bus.c:sfp_register_upstream
  - drivers/net/phy/sfp-bus.c:sfp_register_upstream
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:sock_do_ioctl
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:default_device_exit
  - net/core/dev.c:unregister_netdev
  - net/core/dev.c:register_netdev
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:netdev_notify_peers
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/link_watch.c:linkwatch_event
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:cgrp_css_online
  - net/sched/sch_generic.c:qdisc_put_unlocked
  - net/sched/sch_api.c:qdisc_create
  - net/sched/cls_api.c:tc_indr_block_cb_unregister
  - net/sched/cls_api.c:tc_indr_block_cb_register
  - net/sched/act_api.c:tcf_action_init_1
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_verify_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
  - net/ipv6/fib6_rules.c:fib6_rules_net_exit
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-proc.c:wireless_dev_seq_stop
  - net/switchdev/switchdev.c:switchdev_deferred_process_work
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
```
**Symbols:**

```
ffffffff818c8ef0-ffffffff818c8f00: rtnl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81917f03)
Location: net/core/rtnetlink.c:109
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnl_link_register
  - net/core/rtnetlink.c:rtnl_register_internal
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_map_offload_map_free
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_unregister_upstream
  - drivers/net/phy/sfp-bus.c:sfp_register_upstream
  - drivers/net/phy/sfp-bus.c:sfp_register_upstream
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:sock_do_ioctl
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:default_device_exit
  - net/core/dev.c:unregister_netdev
  - net/core/dev.c:register_netdev
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:netdev_notify_peers
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/link_watch.c:linkwatch_event
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:cgrp_css_online
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_running_version
  - net/sched/sch_generic.c:qdisc_put_unlocked
  - net/sched/sch_api.c:qdisc_create
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_indr_block_cb_unregister
  - net/sched/cls_api.c:tc_indr_block_cb_register
  - net/sched/act_api.c:tcf_action_init_1
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_verify_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
  - net/ipv6/fib6_rules.c:fib6_rules_net_exit
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-proc.c:wireless_dev_seq_stop
  - net/switchdev/switchdev.c:switchdev_deferred_process_work
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff81915ec0-ffffffff81915ed0: rtnl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8194a523)
Location: net/core/rtnetlink.c:109
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnl_link_register
  - net/core/rtnetlink.c:rtnl_register_internal
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_map_offload_map_free
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_unregister_upstream
  - drivers/net/phy/sfp-bus.c:sfp_register_upstream
  - drivers/net/phy/sfp-bus.c:sfp_register_upstream
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:sock_do_ioctl
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:default_device_exit
  - net/core/dev.c:unregister_netdev
  - net/core/dev.c:register_netdev
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:netdev_notify_peers
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/link_watch.c:linkwatch_event
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/flow_offload.c:flow_indr_block_cb_unregister
  - net/core/flow_offload.c:flow_indr_block_cb_register
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:cgrp_css_online
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_running_version
  - net/sched/sch_generic.c:qdisc_put_unlocked
  - net/sched/sch_api.c:qdisc_create
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/cls_api.c:tc_setup_cb_destroy
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_setup_cb_add
  - net/sched/cls_api.c:tc_setup_cb_call
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/act_api.c:tcf_action_init_1
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:ipmr_rules_exit
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_verify_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
  - net/ipv6/fib6_rules.c:fib6_rules_net_exit
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-proc.c:wireless_dev_seq_stop
  - net/switchdev/switchdev.c:switchdev_deferred_process_work
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff819484d0-ffffffff819484e0: rtnl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a1ab24)
Location: net/core/rtnetlink.c:109
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnl_link_register
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/rtnetlink.c:rtnl_unregister
  - net/core/rtnetlink.c:rtnl_unregister
  - net/core/rtnetlink.c:rtnl_register_internal
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_map_offload_map_free
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:sock_do_ioctl
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:default_device_exit
  - net/core/dev.c:unregister_netdev
  - net/core/dev.c:register_netdev
  - net/core/dev.c:unregister_netdevice_notifier_dev_net
  - net/core/dev.c:register_netdevice_notifier_dev_net
  - net/core/dev.c:unregister_netdevice_notifier_net
  - net/core/dev.c:register_netdevice_notifier_net
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:netdev_notify_peers
  - net/core/link_watch.c:linkwatch_event
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/core/net-sysfs.c:phys_port_id_show
  - net/core/net-sysfs.c:proto_down_store
  - net/core/net-sysfs.c:group_store
  - net/core/net-sysfs.c:ifalias_store
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
  - net/core/net-sysfs.c:gro_flush_timeout_store
  - net/core/net-sysfs.c:flags_store
  - net/core/net-sysfs.c:mtu_store
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:carrier_store
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:cgrp_css_online
  - net/core/netprio_cgroup.c:cgrp_css_online
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_running_version
  - net/sched/sch_generic.c:qdisc_put_unlocked
  - net/sched/sch_api.c:qdisc_create
  - net/sched/cls_api.c:tc_setup_cb_destroy
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_setup_cb_add
  - net/sched/cls_api.c:tc_setup_cb_call
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_block_indr_cleanup
  - net/sched/act_api.c:tcf_action_init_1
  - net/ethtool/ioctl.c:ethtool_phys_id
  - net/ethtool/ioctl.c:ethtool_phys_id
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
  - net/ethtool/debug.c:ethnl_set_debug
  - net/ethtool/wol.c:ethnl_set_wol
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/privflags.c:ethnl_set_privflags
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/pause.c:ethnl_set_pause
  - net/ethtool/eee.c:ethnl_set_eee
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr
  - net/ethtool/cabletest.c:ethnl_act_cable_test
  - net/ipv4/ip_sockglue.c:compat_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:compat_ip_setsockopt
  - net/ipv4/ip_sockglue.c:compat_ip_setsockopt
  - net/ipv4/ip_sockglue.c:compat_ip_setsockopt
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:ipmr_rules_exit
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_verify_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_fixup_linkdown
  - net/ipv6/addrconf.c:addrconf_fixup_linkdown
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_setsockopt
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
  - net/ipv6/fib6_rules.c:fib6_rules_net_exit
  - net/packet/af_packet.c:packet_mc_drop
  - net/packet/af_packet.c:packet_mc_add
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:init_prb_bdqc
  - net/packet/af_packet.c:init_prb_bdqc
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-proc.c:wireless_dev_seq_stop
  - net/switchdev/switchdev.c:switchdev_deferred_process_work
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff81a18310-ffffffff81a18320: rtnl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a1abcf)
Location: net/core/rtnetlink.c:109
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnl_link_register
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/rtnetlink.c:rtnl_unregister
  - net/core/rtnetlink.c:rtnl_unregister
  - net/core/rtnetlink.c:rtnl_register_internal
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_map_offload_map_free
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:sock_do_ioctl
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:default_device_exit
  - net/core/dev.c:unregister_netdev
  - net/core/dev.c:register_netdev
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:bpf_xdp_link_update
  - net/core/dev.c:bpf_xdp_link_fill_link_info
  - net/core/dev.c:bpf_xdp_link_show_fdinfo
  - net/core/dev.c:bpf_xdp_link_release
  - net/core/dev.c:unregister_netdevice_notifier_dev_net
  - net/core/dev.c:register_netdevice_notifier_dev_net
  - net/core/dev.c:unregister_netdevice_notifier_net
  - net/core/dev.c:register_netdevice_notifier_net
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:netdev_notify_peers
  - net/core/link_watch.c:linkwatch_event
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/core/net-sysfs.c:phys_port_id_show
  - net/core/net-sysfs.c:proto_down_store
  - net/core/net-sysfs.c:group_store
  - net/core/net-sysfs.c:ifalias_store
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
  - net/core/net-sysfs.c:gro_flush_timeout_store
  - net/core/net-sysfs.c:flags_store
  - net/core/net-sysfs.c:mtu_store
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:carrier_store
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:cgrp_css_online
  - net/core/netprio_cgroup.c:cgrp_css_online
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/sched/sch_generic.c:qdisc_put_unlocked
  - net/sched/sch_api.c:qdisc_create
  - net/sched/cls_api.c:tc_setup_cb_destroy
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_setup_cb_add
  - net/sched/cls_api.c:tc_setup_cb_call
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_block_indr_cleanup
  - net/sched/act_api.c:tc_action_load_ops
  - net/ethtool/ioctl.c:ethtool_phys_id
  - net/ethtool/ioctl.c:ethtool_phys_id
  - net/ethtool/common.c:ethtool_set_ethtool_phy_ops
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
  - net/ethtool/debug.c:ethnl_set_debug
  - net/ethtool/debug.c:ethnl_set_debug
  - net/ethtool/wol.c:ethnl_set_wol
  - net/ethtool/wol.c:ethnl_set_wol
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/privflags.c:ethnl_set_privflags
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/pause.c:ethnl_set_pause
  - net/ethtool/pause.c:ethnl_set_pause
  - net/ethtool/eee.c:ethnl_set_eee
  - net/ethtool/eee.c:ethnl_set_eee
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr
  - net/ethtool/cabletest.c:ethnl_act_cable_test
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:register_nexthop_notifier
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:ipmr_rules_exit
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_verify_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_fixup_linkdown
  - net/ipv6/addrconf.c:addrconf_fixup_linkdown
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
  - net/ipv6/fib6_rules.c:fib6_rules_net_exit
  - net/packet/af_packet.c:packet_mc_drop
  - net/packet/af_packet.c:packet_mc_add
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:init_prb_bdqc
  - net/packet/af_packet.c:init_prb_bdqc
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-proc.c:wireless_dev_seq_stop
  - net/switchdev/switchdev.c:switchdev_deferred_process_work
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
```
**Symbols:**

```
ffffffff81a183e0-ffffffff81a183f0: rtnl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a01b0c)
Location: net/core/rtnetlink.c:109
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnl_link_register
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/rtnetlink.c:rtnl_unregister
  - net/core/rtnetlink.c:rtnl_unregister
  - net/core/rtnetlink.c:rtnl_register_internal
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_map_offload_map_free
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:sock_do_ioctl
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:default_device_exit
  - net/core/dev.c:unregister_netdev
  - net/core/dev.c:register_netdev
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:bpf_xdp_link_update
  - net/core/dev.c:bpf_xdp_link_fill_link_info
  - net/core/dev.c:bpf_xdp_link_show_fdinfo
  - net/core/dev.c:bpf_xdp_link_release
  - net/core/dev.c:unregister_netdevice_notifier_dev_net
  - net/core/dev.c:register_netdevice_notifier_dev_net
  - net/core/dev.c:unregister_netdevice_notifier_net
  - net/core/dev.c:register_netdevice_notifier_net
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:netdev_notify_peers
  - net/core/link_watch.c:linkwatch_event
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:traffic_class_show
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/core/net-sysfs.c:phys_port_id_show
  - net/core/net-sysfs.c:ifalias_store
  - net/core/net-sysfs.c:duplex_show
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:cgrp_css_online
  - net/core/netprio_cgroup.c:cgrp_css_online
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/sched/sch_generic.c:qdisc_put_unlocked
  - net/sched/sch_api.c:qdisc_create
  - net/sched/cls_api.c:tc_setup_cb_destroy
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_setup_cb_add
  - net/sched/cls_api.c:tc_setup_cb_call
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_block_indr_cleanup
  - net/sched/act_api.c:tc_action_load_ops
  - net/ethtool/ioctl.c:ethtool_phys_id
  - net/ethtool/ioctl.c:ethtool_phys_id
  - net/ethtool/common.c:ethtool_set_ethtool_phy_ops
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
  - net/ethtool/debug.c:ethnl_set_debug
  - net/ethtool/debug.c:ethnl_set_debug
  - net/ethtool/wol.c:ethnl_set_wol
  - net/ethtool/wol.c:ethnl_set_wol
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/privflags.c:ethnl_set_privflags
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/pause.c:ethnl_set_pause
  - net/ethtool/pause.c:ethnl_set_pause
  - net/ethtool/eee.c:ethnl_set_eee
  - net/ethtool/eee.c:ethnl_set_eee
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr
  - net/ethtool/cabletest.c:ethnl_act_cable_test
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:register_nexthop_notifier
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:ipmr_rules_exit
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_verify_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
  - net/ipv6/fib6_rules.c:fib6_rules_net_exit
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_mc_add
  - net/packet/af_packet.c:packet_release
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-proc.c:wireless_dev_seq_stop
  - net/switchdev/switchdev.c:switchdev_deferred_process_work
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
```
**Symbols:**

```
ffffffff819ff2b0-ffffffff819ff2c0: rtnl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81ab3f30)
Location: net/core/rtnetlink.c:109
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnl_link_register
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/rtnetlink.c:rtnl_unregister
  - net/core/rtnetlink.c:rtnl_unregister
  - net/core/rtnetlink.c:rtnl_register_internal
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_map_offload_map_free
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - drivers/net/wwan/wwan_core.c:wwan_unregister_ops
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:default_device_exit
  - net/core/dev.c:unregister_netdev
  - net/core/dev.c:register_netdev
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:bpf_xdp_link_update
  - net/core/dev.c:bpf_xdp_link_fill_link_info
  - net/core/dev.c:bpf_xdp_link_show_fdinfo
  - net/core/dev.c:bpf_xdp_link_release
  - net/core/dev.c:unregister_netdevice_notifier_dev_net
  - net/core/dev.c:register_netdevice_notifier_dev_net
  - net/core/dev.c:unregister_netdevice_notifier_net
  - net/core/dev.c:register_netdevice_notifier_net
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:netdev_notify_peers
  - net/core/link_watch.c:linkwatch_event
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifconf
  - net/core/dev_ioctl.c:dev_ifconf
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:traffic_class_show
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/core/net-sysfs.c:phys_port_name_show
  - net/core/net-sysfs.c:phys_port_id_show
  - net/core/net-sysfs.c:ifalias_store
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:speed_show
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:cgrp_css_online
  - net/core/netprio_cgroup.c:cgrp_css_online
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_compat_running_version
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/sched/sch_generic.c:qdisc_put_unlocked
  - net/sched/sch_api.c:qdisc_create
  - net/sched/cls_api.c:tc_setup_cb_destroy
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_setup_cb_add
  - net/sched/cls_api.c:tc_setup_cb_call
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_block_indr_cleanup
  - net/sched/act_api.c:tc_action_load_ops
  - net/ethtool/ioctl.c:ethtool_phys_id
  - net/ethtool/ioctl.c:ethtool_phys_id
  - net/ethtool/common.c:ethtool_set_ethtool_phy_ops
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
  - net/ethtool/debug.c:ethnl_set_debug
  - net/ethtool/wol.c:ethnl_set_wol
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/privflags.c:ethnl_set_privflags
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/pause.c:ethnl_set_pause
  - net/ethtool/eee.c:ethnl_set_eee
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr
  - net/ethtool/cabletest.c:ethnl_act_cable_test
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:unregister_nexthop_notifier
  - net/ipv4/nexthop.c:register_nexthop_notifier
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:ipmr_rules_exit
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_verify_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
  - net/ipv6/fib6_rules.c:fib6_rules_net_exit
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_mc_add
  - net/packet/af_packet.c:packet_release
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-proc.c:wireless_dev_seq_stop
  - net/switchdev/switchdev.c:switchdev_deferred_process_work
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
```
**Symbols:**

```
ffffffff81ab14a0-ffffffff81ab14b0: rtnl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81c2d613)
Location: net/core/rtnetlink.c:144
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnl_link_register
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/rtnetlink.c:rtnl_unregister
  - net/core/rtnetlink.c:rtnl_unregister
  - net/core/rtnetlink.c:rtnl_register_internal
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_map_offload_map_free
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream
  - drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - drivers/net/wwan/wwan_core.c:wwan_unregister_ops
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:unregister_netdev
  - net/core/dev.c:register_netdev
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:bpf_xdp_link_update
  - net/core/dev.c:bpf_xdp_link_fill_link_info
  - net/core/dev.c:bpf_xdp_link_show_fdinfo
  - net/core/dev.c:bpf_xdp_link_release
  - net/core/dev.c:unregister_netdevice_notifier_dev_net
  - net/core/dev.c:register_netdevice_notifier_dev_net
  - net/core/dev.c:unregister_netdevice_notifier_net
  - net/core/dev.c:register_netdevice_notifier_net
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:netdev_notify_peers
  - net/core/link_watch.c:linkwatch_event
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifconf
  - net/core/dev_ioctl.c:dev_ifconf
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:traffic_class_show
  - net/core/net-sysfs.c:threaded_store
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/core/net-sysfs.c:phys_port_name_show
  - net/core/net-sysfs.c:phys_port_id_show
  - net/core/net-sysfs.c:proto_down_store
  - net/core/net-sysfs.c:group_store
  - net/core/net-sysfs.c:ifalias_store
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
  - net/core/net-sysfs.c:gro_flush_timeout_store
  - net/core/net-sysfs.c:tx_queue_len_store
  - net/core/net-sysfs.c:flags_store
  - net/core/net-sysfs.c:mtu_store
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:speed_show
  - net/core/net-sysfs.c:carrier_store
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:cgrp_css_online
  - net/core/netprio_cgroup.c:cgrp_css_online
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/sched/cls_api.c:tc_setup_cb_destroy
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_setup_cb_add
  - net/sched/cls_api.c:tc_setup_cb_call
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_block_indr_cleanup
  - net/sched/act_api.c:tc_action_load_ops
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:ethtool_phys_id
  - net/ethtool/ioctl.c:ethtool_phys_id
  - net/ethtool/common.c:ethtool_set_ethtool_phy_ops
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
  - net/ethtool/debug.c:ethnl_set_debug
  - net/ethtool/wol.c:ethnl_set_wol
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/privflags.c:ethnl_set_privflags
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/pause.c:ethnl_set_pause
  - net/ethtool/eee.c:ethnl_set_eee
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr
  - net/ethtool/cabletest.c:ethnl_act_cable_test
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/module.c:ethnl_set_module
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/fib_frontend.c:fib_net_exit_batch
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/nexthop.c:nexthop_net_exit_batch
  - net/ipv4/nexthop.c:unregister_nexthop_notifier
  - net/ipv4/nexthop.c:register_nexthop_notifier
  - net/ipv4/ipmr.c:ipmr_net_exit_batch
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_verify_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_net_exit_batch
  - net/ipv6/fib6_rules.c:fib6_rules_net_exit_batch
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_mc_add
  - net/packet/af_packet.c:packet_release
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-proc.c:wireless_dev_seq_stop
  - net/switchdev/switchdev.c:switchdev_deferred_process_work
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/mctp/device.c:mctp_register_netdev
```
**Symbols:**

```
ffffffff81c2a630-ffffffff81c2a644: rtnl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81de07a3)
Location: net/core/rtnetlink.c:145
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnl_link_register
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/rtnetlink.c:rtnl_unregister
  - net/core/rtnetlink.c:rtnl_unregister
  - net/core/rtnetlink.c:rtnl_register_internal
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_map_offload_map_free
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream
  - drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - drivers/net/wwan/wwan_core.c:wwan_unregister_ops
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:netfront_resume
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:unregister_netdev
  - net/core/dev.c:register_netdev
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:bpf_xdp_link_update
  - net/core/dev.c:bpf_xdp_link_fill_link_info
  - net/core/dev.c:bpf_xdp_link_show_fdinfo
  - net/core/dev.c:bpf_xdp_link_release
  - net/core/dev.c:unregister_netdevice_notifier_dev_net
  - net/core/dev.c:register_netdevice_notifier_dev_net
  - net/core/dev.c:unregister_netdevice_notifier_net
  - net/core/dev.c:register_netdevice_notifier_net
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:netdev_notify_peers
  - net/core/link_watch.c:linkwatch_event
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifconf
  - net/core/dev_ioctl.c:dev_ifconf
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:traffic_class_show
  - net/core/net-sysfs.c:threaded_store
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/core/net-sysfs.c:phys_port_name_show
  - net/core/net-sysfs.c:phys_port_id_show
  - net/core/net-sysfs.c:proto_down_store
  - net/core/net-sysfs.c:group_store
  - net/core/net-sysfs.c:ifalias_store
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
  - net/core/net-sysfs.c:gro_flush_timeout_store
  - net/core/net-sysfs.c:tx_queue_len_store
  - net/core/net-sysfs.c:flags_store
  - net/core/net-sysfs.c:mtu_store
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:speed_show
  - net/core/net-sysfs.c:carrier_store
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:cgrp_css_online
  - net/core/netprio_cgroup.c:cgrp_css_online
  - net/sched/sch_api.c:qdisc_create
  - net/sched/cls_api.c:tc_setup_cb_destroy
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_setup_cb_add
  - net/sched/cls_api.c:tc_setup_cb_call
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_block_indr_cleanup
  - net/sched/act_api.c:tc_action_load_ops
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:ethtool_phys_id
  - net/ethtool/ioctl.c:ethtool_phys_id
  - net/ethtool/common.c:ethtool_set_ethtool_phy_ops
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
  - net/ethtool/debug.c:ethnl_set_debug
  - net/ethtool/wol.c:ethnl_set_wol
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/privflags.c:ethnl_set_privflags
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/pause.c:ethnl_set_pause
  - net/ethtool/eee.c:ethnl_set_eee
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr
  - net/ethtool/cabletest.c:ethnl_act_cable_test
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/module.c:ethnl_set_module
  - net/ethtool/pse-pd.c:ethnl_set_pse
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/fib_frontend.c:fib_net_exit_batch
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/nexthop.c:nexthop_net_exit_batch
  - net/ipv4/nexthop.c:unregister_nexthop_notifier
  - net/ipv4/nexthop.c:register_nexthop_notifier
  - net/ipv4/ipmr.c:ipmr_net_exit_batch
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_verify_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_net_exit_batch
  - net/ipv6/fib6_rules.c:fib6_rules_net_exit_batch
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_mc_add
  - net/packet/af_packet.c:packet_release
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-proc.c:wireless_dev_seq_stop
  - net/switchdev/switchdev.c:switchdev_deferred_process_work
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/mctp/device.c:mctp_register_netdev
```
**Symbols:**

```
ffffffff81ddd390-ffffffff81ddd3a4: rtnl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81e51f33)
Location: net/core/rtnetlink.c:148
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnl_link_register
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/rtnetlink.c:rtnl_unregister
  - net/core/rtnetlink.c:rtnl_unregister
  - net/core/rtnetlink.c:rtnl_register_internal
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_map_offload_map_free
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_dev_bound_destroy
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream
  - drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/virtio_net.c:virtnet_restore
  - drivers/net/virtio_net.c:remove_vq_common
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_config_changed_work
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - drivers/net/wwan/wwan_core.c:wwan_unregister_ops
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:netfront_resume
  - net/core/sysctl_net_core.c:rps_default_mask_sysctl
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:unregister_netdev
  - net/core/dev.c:register_netdev
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:bpf_xdp_link_update
  - net/core/dev.c:bpf_xdp_link_fill_link_info
  - net/core/dev.c:bpf_xdp_link_show_fdinfo
  - net/core/dev.c:bpf_xdp_link_release
  - net/core/dev.c:unregister_netdevice_notifier_dev_net
  - net/core/dev.c:register_netdevice_notifier_dev_net
  - net/core/dev.c:unregister_netdevice_notifier_net
  - net/core/dev.c:register_netdevice_notifier_net
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:netdev_notify_peers
  - net/core/link_watch.c:linkwatch_event
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifconf
  - net/core/dev_ioctl.c:dev_ifconf
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/netdev-genl.c:netdev_nl_dev_get_dumpit
  - net/core/netdev-genl.c:netdev_nl_dev_get_doit
  - net/core/netdev-genl.c:netdev_nl_dev_get_doit
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:traffic_class_show
  - net/core/net-sysfs.c:threaded_store
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/core/net-sysfs.c:phys_port_name_show
  - net/core/net-sysfs.c:phys_port_id_show
  - net/core/net-sysfs.c:proto_down_store
  - net/core/net-sysfs.c:group_store
  - net/core/net-sysfs.c:ifalias_store
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
  - net/core/net-sysfs.c:gro_flush_timeout_store
  - net/core/net-sysfs.c:tx_queue_len_store
  - net/core/net-sysfs.c:flags_store
  - net/core/net-sysfs.c:mtu_store
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:speed_show
  - net/core/net-sysfs.c:carrier_store
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:cgrp_css_online
  - net/core/netprio_cgroup.c:cgrp_css_online
  - net/sched/sch_api.c:qdisc_create
  - net/sched/cls_api.c:tc_setup_cb_destroy
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_setup_cb_add
  - net/sched/cls_api.c:tc_setup_cb_call
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_block_indr_cleanup
  - net/sched/act_api.c:tc_action_load_ops
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:ethtool_phys_id
  - net/ethtool/ioctl.c:ethtool_phys_id
  - net/ethtool/common.c:ethtool_set_ethtool_phy_ops
  - net/ethtool/netlink.c:ethnl_default_set_doit
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr
  - net/ethtool/cabletest.c:ethnl_act_cable_test
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/fib_frontend.c:fib_net_exit_batch
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/nexthop.c:nexthop_net_exit_batch
  - net/ipv4/nexthop.c:unregister_nexthop_notifier
  - net/ipv4/nexthop.c:register_nexthop_notifier
  - net/ipv4/ipmr.c:ipmr_net_exit_batch
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_verify_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_net_exit_batch
  - net/ipv6/fib6_rules.c:fib6_rules_net_exit_batch
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_mc_add
  - net/packet/af_packet.c:packet_release
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-proc.c:wireless_dev_seq_stop
  - net/switchdev/switchdev.c:switchdev_deferred_process_work
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/mctp/device.c:mctp_register_netdev
```
**Symbols:**

```
ffffffff81e4e0e0-ffffffff81e4e0f4: rtnl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81f11013)
Location: net/core/rtnetlink.c:149
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnl_link_register
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/rtnetlink.c:rtnl_unregister
  - net/core/rtnetlink.c:rtnl_unregister
  - net/core/rtnetlink.c:rtnl_register_internal
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_map_offload_map_free
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_dev_bound_destroy
  - kernel/bpf/tcx.c:tcx_link_attach
  - kernel/bpf/tcx.c:tcx_link_fill_info
  - kernel/bpf/tcx.c:tcx_link_fdinfo
  - kernel/bpf/tcx.c:tcx_link_update
  - kernel/bpf/tcx.c:tcx_link_release
  - kernel/bpf/tcx.c:tcx_prog_query
  - kernel/bpf/tcx.c:tcx_prog_detach
  - kernel/bpf/tcx.c:tcx_prog_attach
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/netkit.c:netkit_link_attach
  - drivers/net/netkit.c:netkit_link_fill_info
  - drivers/net/netkit.c:netkit_link_fdinfo
  - drivers/net/netkit.c:netkit_link_update
  - drivers/net/netkit.c:netkit_link_release
  - drivers/net/netkit.c:netkit_prog_query
  - drivers/net/netkit.c:netkit_prog_query
  - drivers/net/netkit.c:netkit_prog_detach
  - drivers/net/netkit.c:netkit_prog_attach
  - drivers/net/phy/phy_device.c:phy_exit
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream
  - drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/virtio_net.c:virtnet_restore
  - drivers/net/virtio_net.c:remove_vq_common
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_config_changed_work
  - drivers/net/virtio_net.c:virtnet_rx_dim_work
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:netfront_resume
  - drivers/dpll/dpll_core.c:dpll_netdev_pin_clear
  - drivers/dpll/dpll_core.c:dpll_netdev_pin_set
  - net/core/sysctl_net_core.c:rps_default_mask_sysctl
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:unregister_netdev
  - net/core/dev.c:register_netdev
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:bpf_xdp_link_update
  - net/core/dev.c:bpf_xdp_link_fill_link_info
  - net/core/dev.c:bpf_xdp_link_show_fdinfo
  - net/core/dev.c:bpf_xdp_link_release
  - net/core/dev.c:unregister_netdevice_notifier_dev_net
  - net/core/dev.c:register_netdevice_notifier_dev_net
  - net/core/dev.c:unregister_netdevice_notifier_net
  - net/core/dev.c:register_netdevice_notifier_net
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:netdev_notify_peers
  - net/core/link_watch.c:linkwatch_event
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifconf
  - net/core/dev_ioctl.c:dev_ifconf
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/netdev-genl.c:netdev_nl_queue_get_dumpit
  - net/core/netdev-genl.c:netdev_nl_queue_get_dumpit
  - net/core/netdev-genl.c:netdev_nl_queue_get_dumpit
  - net/core/netdev-genl.c:netdev_nl_queue_get_dumpit
  - net/core/netdev-genl.c:netdev_nl_queue_get_dumpit
  - net/core/netdev-genl.c:netdev_nl_queue_get_doit
  - net/core/netdev-genl.c:netdev_nl_queue_get_doit
  - net/core/netdev-genl.c:netdev_nl_queue_get_doit
  - net/core/netdev-genl.c:netdev_nl_queue_get_doit
  - net/core/netdev-genl.c:netdev_nl_napi_get_dumpit
  - net/core/netdev-genl.c:netdev_nl_napi_get_dumpit
  - net/core/netdev-genl.c:netdev_nl_napi_get_dumpit
  - net/core/netdev-genl.c:netdev_nl_napi_get_dumpit
  - net/core/netdev-genl.c:netdev_nl_napi_get_dumpit
  - net/core/netdev-genl.c:netdev_nl_napi_get_doit
  - net/core/netdev-genl.c:netdev_nl_napi_get_doit
  - net/core/netdev-genl.c:netdev_nl_dev_get_dumpit
  - net/core/netdev-genl.c:netdev_nl_dev_get_dumpit
  - net/core/netdev-genl.c:netdev_nl_dev_get_dumpit
  - net/core/netdev-genl.c:netdev_nl_dev_get_doit
  - net/core/netdev-genl.c:netdev_nl_dev_get_doit
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:xps_rxqs_show
  - net/core/net-sysfs.c:xps_cpus_store
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:traffic_class_show
  - net/core/net-sysfs.c:threaded_store
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/core/net-sysfs.c:phys_port_name_show
  - net/core/net-sysfs.c:phys_port_id_show
  - net/core/net-sysfs.c:proto_down_store
  - net/core/net-sysfs.c:group_store
  - net/core/net-sysfs.c:ifalias_store
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
  - net/core/net-sysfs.c:gro_flush_timeout_store
  - net/core/net-sysfs.c:tx_queue_len_store
  - net/core/net-sysfs.c:flags_store
  - net/core/net-sysfs.c:mtu_store
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:speed_show
  - net/core/net-sysfs.c:carrier_show
  - net/core/net-sysfs.c:carrier_store
  - net/core/page_pool_user.c:netdev_nl_page_pool_get_dump
  - net/core/page_pool_user.c:netdev_nl_page_pool_get_dump
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:cgrp_css_online
  - net/core/netprio_cgroup.c:cgrp_css_online
  - net/sched/sch_api.c:qdisc_create
  - net/sched/cls_api.c:tc_setup_cb_destroy
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_setup_cb_add
  - net/sched/cls_api.c:tc_setup_cb_call
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_block_indr_cleanup
  - net/sched/act_api.c:tc_action_load_ops
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:ethtool_phys_id
  - net/ethtool/ioctl.c:ethtool_phys_id
  - net/ethtool/netlink.c:ethnl_default_set_doit
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr
  - net/ethtool/cabletest.c:ethnl_act_cable_test
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/fib_frontend.c:fib_net_exit_batch
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/nexthop.c:nexthop_net_exit_batch
  - net/ipv4/nexthop.c:unregister_nexthop_notifier
  - net/ipv4/nexthop.c:register_nexthop_notifier
  - net/ipv4/ipmr.c:ipmr_net_exit_batch
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_verify_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/addrconf.c:addrconf_fixup_forwarding
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_net_exit_batch
  - net/ipv6/fib6_rules.c:fib6_rules_net_exit_batch
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_mc_add
  - net/packet/af_packet.c:packet_release
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-proc.c:wireless_dev_seq_stop
  - net/switchdev/switchdev.c:switchdev_deferred_process_work
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/mctp/device.c:mctp_register_netdev
```
**Symbols:**

```
ffffffff81f0ce40-ffffffff81f0ce54: rtnl_unlock (STB_GLOBAL)
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
void rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffff800010bec754)
Location: net/core/rtnetlink.c:109
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnl_link_register
  - net/core/rtnetlink.c:rtnl_register_internal
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_map_offload_map_free
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_unregister_upstream
  - drivers/net/phy/sfp-bus.c:sfp_register_upstream
  - drivers/net/phy/sfp-bus.c:sfp_register_upstream
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ethernet/freescale/fec_main.c:fec_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_suspend
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:sock_do_ioctl
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:default_device_exit
  - net/core/dev.c:unregister_netdev
  - net/core/dev.c:register_netdev
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:netdev_notify_peers
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/link_watch.c:linkwatch_event
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/flow_offload.c:flow_indr_block_cb_unregister
  - net/core/flow_offload.c:flow_indr_block_cb_register
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:cgrp_css_online
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_running_version
  - net/sched/sch_generic.c:qdisc_put_unlocked
  - net/sched/sch_api.c:qdisc_create
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/cls_api.c:tc_setup_cb_destroy
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_setup_cb_add
  - net/sched/cls_api.c:tc_setup_cb_call
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/act_api.c:tcf_action_init_1
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:ipmr_rules_exit
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_verify_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
  - net/ipv6/fib6_rules.c:fib6_rules_net_exit
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-proc.c:wireless_dev_seq_stop
  - net/switchdev/switchdev.c:switchdev_deferred_process_work
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffff800010bea070-ffff800010bea08c: rtnl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c0d04e44)
Location: net/core/rtnetlink.c:109
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnl_link_register
  - net/core/rtnetlink.c:rtnl_register_internal
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_map_offload_map_free
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_unregister_upstream
  - drivers/net/phy/sfp-bus.c:sfp_register_upstream
  - drivers/net/phy/sfp-bus.c:sfp_register_upstream
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/ethernet/freescale/fec_main.c:fec_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_suspend
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work
  - drivers/net/ethernet/ti/cpsw.c:cpsw_resume
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - net/socket.c:sock_ioctl
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:default_device_exit
  - net/core/dev.c:unregister_netdev
  - net/core/dev.c:register_netdev
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:netdev_notify_peers
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/link_watch.c:linkwatch_event
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/flow_offload.c:flow_indr_block_cb_unregister
  - net/core/flow_offload.c:flow_indr_block_cb_register
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:cgrp_css_online
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_running_version
  - net/sched/sch_generic.c:qdisc_put_unlocked
  - net/sched/sch_api.c:qdisc_create
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/cls_api.c:tc_setup_cb_destroy
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_setup_cb_add
  - net/sched/cls_api.c:tc_setup_cb_call
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/act_api.c:tcf_action_init_1
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:ipmr_rules_exit
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_verify_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
  - net/ipv6/fib6_rules.c:fib6_rules_net_exit
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-proc.c:wireless_dev_seq_stop
  - net/switchdev/switchdev.c:switchdev_deferred_process_work
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
c0d029e4-c0d02a00: rtnl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c000000000ccf974)
Location: net/core/rtnetlink.c:109
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnl_link_register
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/rtnetlink.c:rtnl_unregister
  - net/core/rtnetlink.c:rtnl_unregister
  - net/core/rtnetlink.c:rtnl_register_internal
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_map_offload_map_free
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_unregister_upstream
  - drivers/net/phy/sfp-bus.c:sfp_register_upstream
  - drivers/net/phy/sfp-bus.c:sfp_register_upstream
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:sock_do_ioctl
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:default_device_exit
  - net/core/dev.c:unregister_netdev
  - net/core/dev.c:register_netdev
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:netdev_notify_peers
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/link_watch.c:linkwatch_event
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/flow_offload.c:flow_indr_block_cb_unregister
  - net/core/flow_offload.c:flow_indr_block_cb_register
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:cgrp_css_online
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_running_version
  - net/sched/sch_generic.c:qdisc_put_unlocked
  - net/sched/sch_api.c:qdisc_create
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/cls_api.c:tc_setup_cb_destroy
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_setup_cb_add
  - net/sched/cls_api.c:tc_setup_cb_call
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/act_api.c:tcf_action_init_1
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:ipmr_rules_exit
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_verify_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
  - net/ipv6/fib6_rules.c:fib6_rules_net_exit
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-proc.c:wireless_dev_seq_stop
  - net/switchdev/switchdev.c:switchdev_deferred_process_work
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
c000000000ccc440-c000000000ccc474: rtnl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffe000770064)
Location: net/core/rtnetlink.c:109
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnl_link_register
  - net/core/rtnetlink.c:rtnl_register_internal
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_map_offload_map_free
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_unregister_upstream
  - drivers/net/phy/sfp-bus.c:sfp_register_upstream
  - drivers/net/phy/sfp-bus.c:sfp_register_upstream
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - net/socket.c:sock_ioctl
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:default_device_exit
  - net/core/dev.c:unregister_netdev
  - net/core/dev.c:register_netdev
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:netdev_notify_peers
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/link_watch.c:linkwatch_event
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/flow_offload.c:flow_indr_block_cb_unregister
  - net/core/flow_offload.c:flow_indr_block_cb_register
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:phys_switch_id_show
  - net/core/net-sysfs.c:phys_port_name_show
  - net/core/net-sysfs.c:phys_port_id_show
  - net/core/net-sysfs.c:ifalias_store
  - net/core/net-sysfs.c:duplex_show
  - net/core/net-sysfs.c:speed_show
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:cgrp_css_online
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_running_version
  - net/sched/sch_generic.c:qdisc_put_unlocked
  - net/sched/sch_api.c:qdisc_create
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/cls_api.c:tc_setup_cb_destroy
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_setup_cb_add
  - net/sched/cls_api.c:tc_setup_cb_call
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/act_api.c:tcf_action_init_1
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:ipmr_rules_exit
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_verify_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
  - net/ipv6/fib6_rules.c:fib6_rules_net_exit
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-proc.c:wireless_dev_seq_stop
  - net/switchdev/switchdev.c:switchdev_deferred_process_work
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffe00076d910-ffffffe00076d932: rtnl_unlock (STB_GLOBAL)
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
void rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818ea4f3)
Location: net/core/rtnetlink.c:109
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnl_link_register
  - net/core/rtnetlink.c:rtnl_register_internal
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_map_offload_map_free
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_unregister_upstream
  - drivers/net/phy/sfp-bus.c:sfp_register_upstream
  - drivers/net/phy/sfp-bus.c:sfp_register_upstream
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:sock_do_ioctl
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:default_device_exit
  - net/core/dev.c:unregister_netdev
  - net/core/dev.c:register_netdev
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:netdev_notify_peers
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/link_watch.c:linkwatch_event
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/flow_offload.c:flow_indr_block_cb_unregister
  - net/core/flow_offload.c:flow_indr_block_cb_register
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:cgrp_css_online
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_running_version
  - net/sched/sch_generic.c:qdisc_put_unlocked
  - net/sched/sch_api.c:qdisc_create
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/cls_api.c:tc_setup_cb_destroy
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_setup_cb_add
  - net/sched/cls_api.c:tc_setup_cb_call
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/act_api.c:tcf_action_init_1
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_verify_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
  - net/ipv6/fib6_rules.c:fib6_rules_net_exit
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-proc.c:wireless_dev_seq_stop
  - net/switchdev/switchdev.c:switchdev_deferred_process_work
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff818e84a0-ffffffff818e84b0: rtnl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818a4333)
Location: net/core/rtnetlink.c:109
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnl_link_register
  - net/core/rtnetlink.c:rtnl_register_internal
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_map_offload_map_free
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_unregister_upstream
  - drivers/net/phy/sfp-bus.c:sfp_register_upstream
  - drivers/net/phy/sfp-bus.c:sfp_register_upstream
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/vxlan.c:vxlan_exit_batch_net
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:sock_do_ioctl
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:default_device_exit
  - net/core/dev.c:unregister_netdev
  - net/core/dev.c:register_netdev
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:netdev_notify_peers
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/link_watch.c:linkwatch_event
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/flow_offload.c:flow_indr_block_cb_unregister
  - net/core/flow_offload.c:flow_indr_block_cb_register
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:cgrp_css_online
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_running_version
  - net/sched/sch_generic.c:qdisc_put_unlocked
  - net/sched/sch_api.c:qdisc_create
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/cls_api.c:tc_setup_cb_destroy
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_setup_cb_add
  - net/sched/cls_api.c:tc_setup_cb_call
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/act_api.c:tcf_action_init_1
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/ip_tunnel.c:ip_tunnel_delete_nets
  - net/ipv4/ip_tunnel.c:ip_tunnel_init_net
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_verify_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
  - net/ipv6/fib6_rules.c:fib6_rules_net_exit
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-proc.c:wireless_dev_seq_stop
  - net/switchdev/switchdev.c:switchdev_deferred_process_work
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff818a22e0-ffffffff818a22f0: rtnl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8193b523)
Location: net/core/rtnetlink.c:109
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnl_link_register
  - net/core/rtnetlink.c:rtnl_register_internal
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_map_offload_map_free
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_unregister_upstream
  - drivers/net/phy/sfp-bus.c:sfp_register_upstream
  - drivers/net/phy/sfp-bus.c:sfp_register_upstream
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:sock_do_ioctl
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:default_device_exit
  - net/core/dev.c:unregister_netdev
  - net/core/dev.c:register_netdev
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:netdev_notify_peers
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/link_watch.c:linkwatch_event
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/flow_offload.c:flow_indr_block_cb_unregister
  - net/core/flow_offload.c:flow_indr_block_cb_register
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:cgrp_css_online
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_running_version
  - net/sched/sch_generic.c:qdisc_put_unlocked
  - net/sched/sch_api.c:qdisc_create
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/cls_api.c:tc_setup_cb_destroy
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_setup_cb_add
  - net/sched/cls_api.c:tc_setup_cb_call
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/act_api.c:tcf_action_init_1
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_verify_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
  - net/ipv6/fib6_rules.c:fib6_rules_net_exit
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-proc.c:wireless_dev_seq_stop
  - net/switchdev/switchdev.c:switchdev_deferred_process_work
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff819394d0-ffffffff819394e0: rtnl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8195cbd7)
Location: net/core/rtnetlink.c:109
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnl_link_register
  - net/core/rtnetlink.c:rtnl_register_internal
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_map_offload_map_free
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
  - drivers/net/loopback.c:blackhole_netdev_init
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_unregister_upstream
  - drivers/net/phy/sfp-bus.c:sfp_register_upstream
  - drivers/net/phy/sfp-bus.c:sfp_register_upstream
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:tun_chr_close
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:sock_do_ioctl
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:default_device_exit
  - net/core/dev.c:unregister_netdev
  - net/core/dev.c:register_netdev
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:netdev_notify_peers
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/link_watch.c:linkwatch_event
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/flow_offload.c:flow_indr_block_cb_unregister
  - net/core/flow_offload.c:flow_indr_block_cb_register
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/net-sysfs.c:tx_maxrate_store
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/core/netprio_cgroup.c:write_priomap
  - net/core/netprio_cgroup.c:cgrp_css_online
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_running_version
  - net/sched/sch_generic.c:qdisc_put_unlocked
  - net/sched/sch_api.c:qdisc_create
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/cls_api.c:tc_setup_flow_action
  - net/sched/cls_api.c:tc_setup_cb_destroy
  - net/sched/cls_api.c:tc_setup_cb_replace
  - net/sched/cls_api.c:tc_setup_cb_add
  - net/sched/cls_api.c:tc_setup_cb_call
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/act_api.c:tcf_action_init_1
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:ipmr_rules_exit
  - net/ipv6/anycast.c:ipv6_sock_ac_close
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:addrconf_verify_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
  - net/ipv6/fib6_rules.c:fib6_rules_net_exit
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-proc.c:wireless_dev_seq_stop
  - net/switchdev/switchdev.c:switchdev_deferred_process_work
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff8195abb0-ffffffff8195abc0: rtnl_unlock (STB_GLOBAL)
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
