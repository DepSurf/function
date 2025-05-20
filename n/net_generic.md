# Function: <code>net_generic</code>

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
In kernel/audit.c (ffffffff81120a56)
Location: include/net/netns/generic.h:34
Inline: True
Inline callers:
  - kernel/audit.c:audit_net_exit
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_net_init
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:audit_send_list
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff815f502c)
Location: include/net/netns/generic.h:34
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/net_namespace.c (ffffffff81710201)
Location: include/net/netns/generic.h:34
Inline: True
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
In kernel/audit.c (ffffffff81129065)
Location: include/net/netns/generic.h:34
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:audit_net_exit
  - kernel/audit.c:audit_net_init
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8165650e)
Location: include/net/netns/generic.h:34
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/net_namespace.c (ffffffff81777b51)
Location: include/net/netns/generic.h:34
Inline: True
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
In kernel/audit.c (ffffffff81132a36)
Location: include/net/netns/generic.h:38
Inline: True
Inline callers:
  - kernel/audit.c:audit_net_exit
  - kernel/audit.c:audit_net_init
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff816841ee)
Location: include/net/netns/generic.h:38
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/net_namespace.c (ffffffff817a4b21)
Location: include/net/netns/generic.h:38
Inline: True
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
In kernel/audit.c (ffffffff81133d85)
Location: include/net/netns/generic.h:38
Inline: True
Inline callers:
  - kernel/audit.c:audit_net_exit
  - kernel/audit.c:audit_net_init
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_multicast_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8169963e)
Location: include/net/netns/generic.h:38
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/net_namespace.c (ffffffff817c2d51)
Location: include/net/netns/generic.h:38
Inline: True
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
In kernel/audit.c (ffffffff81140b45)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - kernel/audit.c:audit_net_exit
  - kernel/audit.c:audit_net_init
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_multicast_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8170648e)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/net_namespace.c (ffffffff8183c481)
Location: include/net/netns/generic.h:39
Inline: True
```
```
In net/sched/act_api.c (ffffffff81881c65)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_net_exit
  - net/sched/act_api.c:tcf_action_net_init
  - net/sched/act_api.c:tc_setup_cb_egdev_register
  - net/sched/act_api.c:tcf_action_egdev_lookup
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
In kernel/audit.c (ffffffff8114f485)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - kernel/audit.c:audit_net_exit
  - kernel/audit.c:audit_net_init
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_multicast_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81743cfe)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/net_namespace.c (ffffffff818869f1)
Location: include/net/netns/generic.h:39
Inline: True
```
```
In net/sched/cls_api.c (ffffffff818d2b75)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_net_exit
  - net/sched/cls_api.c:tcf_net_init
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/sched/act_api.c (ffffffff818d54b5)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_net_exit
  - net/sched/act_api.c:tcf_action_net_init
  - net/sched/act_api.c:tc_setup_cb_egdev_register
  - net/sched/act_api.c:tcf_action_egdev_lookup
```
```
In net/netlink/af_netlink.c (ffffffff818dc7e5)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/netlink/af_netlink.c:netlink_tap_init_net
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netlink/af_netlink.c:netlink_add_tap
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
In kernel/audit.c (ffffffff8115c165)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - kernel/audit.c:audit_net_exit
  - kernel/audit.c:audit_net_init
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_multicast_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81766dbe)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/net_namespace.c (ffffffff818a70e1)
Location: include/net/netns/generic.h:39
Inline: True
```
```
In net/sched/cls_api.c (ffffffff818fdff5)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_net_exit
  - net/sched/cls_api.c:tcf_net_init
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/netlink/af_netlink.c (ffffffff819091c2)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/netlink/af_netlink.c:netlink_tap_init_net
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netlink/af_netlink.c:netlink_add_tap
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
In kernel/audit.c (ffffffff8116882c)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - kernel/audit.c:audit_net_exit
  - kernel/audit.c:audit_net_init
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_multicast_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817a5c19)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/net_namespace.c (ffffffff818f27e3)
Location: include/net/netns/generic.h:39
Inline: True
```
```
In net/sched/cls_api.c (ffffffff8195d98c)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_net_exit
  - net/sched/cls_api.c:tcf_net_init
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/netlink/af_netlink.c (ffffffff819675bc)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/netlink/af_netlink.c:netlink_tap_init_net
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netlink/af_netlink.c:netlink_add_tap
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
In kernel/audit.c (ffffffff811746cc)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - kernel/audit.c:audit_net_exit
  - kernel/audit.c:audit_net_init
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_multicast_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817c8669)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/net_namespace.c (ffffffff81924743)
Location: include/net/netns/generic.h:39
Inline: True
```
```
In net/core/fib_notifier.c (ffffffff81961aac)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_net_init
  - net/core/fib_notifier.c:fib_notifier_ops_register
  - net/core/fib_notifier.c:register_fib_notifier
  - net/core/fib_notifier.c:fib_seq_sum
```
```
In net/sched/cls_api.c (ffffffff8199407c)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_net_exit
  - net/sched/cls_api.c:tcf_net_init
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/netlink/af_netlink.c (ffffffff8199e04c)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/netlink/af_netlink.c:netlink_tap_init_net
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netlink/af_netlink.c:netlink_add_tap
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
In kernel/audit.c (ffffffff811864cc)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - kernel/audit.c:audit_net_exit
  - kernel/audit.c:audit_net_init
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_multicast_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81892839)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_connect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
```
```
In net/core/net_namespace.c (ffffffff819f7f13)
Location: include/net/netns/generic.h:39
Inline: True
```
```
In net/core/fib_notifier.c (ffffffff81a3509c)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_net_init
  - net/core/fib_notifier.c:fib_notifier_ops_register
  - net/core/fib_notifier.c:unregister_fib_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/fib_notifier.c:call_fib_notifiers
```
```
In net/sched/cls_api.c (ffffffff81a6bc7c)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_net_exit
  - net/sched/cls_api.c:tcf_net_init
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/netlink/af_netlink.c (ffffffff81a76e6c)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/netlink/af_netlink.c:netlink_tap_init_net
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/mptcp/ctrl.c (ffffffff81bb21ec)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/mptcp/ctrl.c:mptcp_net_exit
  - net/mptcp/ctrl.c:mptcp_net_init
  - net/mptcp/ctrl.c:mptcp_is_enabled
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb3745)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:pm_nl_exit_net
  - net/mptcp/pm_netlink.c:pm_nl_init_net
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_data_init
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_local_id
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
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
In kernel/audit.c (ffffffff811835ac)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - kernel/audit.c:audit_net_exit
  - kernel/audit.c:audit_net_init
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_multicast_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818a2139)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_connect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/net_namespace.c (ffffffff819f7965)
Location: include/net/netns/generic.h:39
Inline: True
```
```
In net/core/fib_notifier.c (ffffffff81a3743c)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_net_init
  - net/core/fib_notifier.c:fib_notifier_ops_register
  - net/core/fib_notifier.c:unregister_fib_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/fib_notifier.c:call_fib_notifiers
```
```
In net/sched/cls_api.c (ffffffff81a7450c)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_net_exit
  - net/sched/cls_api.c:tcf_net_init
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/netlink/af_netlink.c (ffffffff81a7fbec)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/netlink/af_netlink.c:netlink_tap_init_net
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/mptcp/ctrl.c (ffffffff81bc64ec)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/mptcp/ctrl.c:mptcp_net_exit
  - net/mptcp/ctrl.c:mptcp_net_init
  - net/mptcp/ctrl.c:mptcp_get_add_addr_timeout
  - net/mptcp/ctrl.c:mptcp_is_enabled
```
```
In net/mptcp/pm_netlink.c (ffffffff81bc8bc6)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:pm_nl_exit_net
  - net/mptcp/pm_netlink.c:pm_nl_init_net
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_data_init
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_local_id
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
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
In kernel/audit.c (ffffffff811846dc)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - kernel/audit.c:audit_net_exit
  - kernel/audit.c:audit_net_init
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_multicast_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81883640)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/net_namespace.c (ffffffff819ddae5)
Location: include/net/netns/generic.h:39
Inline: True
```
```
In net/core/fib_notifier.c (ffffffff81a1e59c)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_net_init
  - net/core/fib_notifier.c:fib_notifier_ops_register
  - net/core/fib_notifier.c:unregister_fib_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/fib_notifier.c:call_fib_notifiers
```
```
In net/sched/cls_api.c (ffffffff81a5d08c)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_net_exit
  - net/sched/cls_api.c:tcf_net_init
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/netlink/af_netlink.c (ffffffff81a6c7d3)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/netlink/af_netlink.c:netlink_tap_init_net
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/mptcp/ctrl.c (ffffffff81bb704c)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/mptcp/ctrl.c:mptcp_net_exit
  - net/mptcp/ctrl.c:mptcp_net_init
  - net/mptcp/ctrl.c:mptcp_get_add_addr_timeout
  - net/mptcp/ctrl.c:mptcp_is_enabled
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb8f16)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:pm_nl_exit_net
  - net/mptcp/pm_netlink.c:pm_nl_init_net
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_data_init
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_data_init
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_data_init
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_data_init
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_local_id
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
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
In kernel/audit.c (ffffffff811ac9ec)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - kernel/audit.c:audit_net_exit
  - kernel/audit.c:audit_net_init
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_multicast_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81914fe0)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/net_namespace.c (ffffffff81a8ee2c)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/core/net_namespace.c:unregister_pernet_operations
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:setup_net
```
```
In net/core/fib_notifier.c (ffffffff81ad295c)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_net_exit
  - net/core/fib_notifier.c:fib_notifier_net_init
  - net/core/fib_notifier.c:fib_notifier_ops_register
  - net/core/fib_notifier.c:unregister_fib_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/fib_notifier.c:call_fib_notifiers
```
```
In net/sched/cls_api.c (ffffffff81b1622c)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_net_exit
  - net/sched/cls_api.c:tcf_net_init
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/netlink/af_netlink.c (ffffffff81b25e23)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/netlink/af_netlink.c:netlink_tap_init_net
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/mptcp/ctrl.c (ffffffff81c862dc)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/mptcp/ctrl.c:mptcp_net_exit
  - net/mptcp/ctrl.c:mptcp_net_init
  - net/mptcp/ctrl.c:mptcp_stale_loss_cnt
  - net/mptcp/ctrl.c:mptcp_allow_join_id0
  - net/mptcp/ctrl.c:mptcp_is_checksum_enabled
  - net/mptcp/ctrl.c:mptcp_get_add_addr_timeout
  - net/mptcp/ctrl.c:mptcp_is_enabled
```
```
In net/mptcp/pm_netlink.c (ffffffff81c885e6)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:pm_nl_exit_net
  - net/mptcp/pm_netlink.c:pm_nl_init_net
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_get_flags_and_ifindex_by_id
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_data_init
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_data_init
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_data_init
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_data_init
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_local_id
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:fill_remote_addresses_vec
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
In kernel/audit.c (ffffffff811de545)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - kernel/audit.c:audit_net_exit
  - kernel/audit.c:audit_net_init
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_multicast_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a6a60c)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/net_namespace.c (ffffffff81c0492d)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/fib_notifier.c (ffffffff81c503b5)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_net_exit
  - net/core/fib_notifier.c:fib_notifier_net_init
  - net/core/fib_notifier.c:fib_notifier_ops_register
  - net/core/fib_notifier.c:unregister_fib_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/fib_notifier.c:call_fib_notifiers
```
```
In net/sched/cls_api.c (ffffffff81c9d975)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_net_exit
  - net/sched/cls_api.c:tcf_net_init
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/sched/act_api.c (ffffffff81ca816d)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_reoffload_cb
```
```
In net/netlink/af_netlink.c (ffffffff81cae9f6)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/netlink/af_netlink.c:netlink_tap_init_net
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/mptcp/ctrl.c (ffffffff81e2c675)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/mptcp/ctrl.c:mptcp_net_exit
  - net/mptcp/ctrl.c:mptcp_net_init
  - net/mptcp/ctrl.c:mptcp_get_pm_type
  - net/mptcp/ctrl.c:mptcp_stale_loss_cnt
  - net/mptcp/ctrl.c:mptcp_allow_join_id0
  - net/mptcp/ctrl.c:mptcp_is_checksum_enabled
  - net/mptcp/ctrl.c:mptcp_get_add_addr_timeout
  - net/mptcp/ctrl.c:mptcp_is_enabled
```
```
In net/mptcp/pm_netlink.c (ffffffff81e2ed06)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:pm_nl_exit_net
  - net/mptcp/pm_netlink.c:pm_nl_init_net
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_get_flags_and_ifindex_by_id
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_local_id
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_check_work_pending
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_check_work_pending
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
In kernel/audit.c (ffffffff812240b5)
Location: include/net/netns/generic.h:40
Inline: True
Inline callers:
  - kernel/audit.c:audit_net_exit
  - kernel/audit.c:audit_net_init
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_multicast_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfd39c)
Location: include/net/netns/generic.h:40
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/net_namespace.c (ffffffff81db3e4d)
Location: include/net/netns/generic.h:40
Inline: True
Inline callers:
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/fib_notifier.c (ffffffff81e05775)
Location: include/net/netns/generic.h:40
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_net_exit
  - net/core/fib_notifier.c:fib_notifier_net_init
  - net/core/fib_notifier.c:fib_notifier_ops_register
  - net/core/fib_notifier.c:unregister_fib_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/fib_notifier.c:call_fib_notifiers
```
```
In net/sched/cls_api.c (ffffffff81e59fa5)
Location: include/net/netns/generic.h:40
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_net_exit
  - net/sched/cls_api.c:tcf_net_init
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/sched/act_api.c (ffffffff81e645f6)
Location: include/net/netns/generic.h:40
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_reoffload_cb
  - net/sched/act_api.c:__tcf_generic_walker
```
```
In net/netlink/af_netlink.c (ffffffff81e6c036)
Location: include/net/netns/generic.h:40
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/netlink/af_netlink.c:netlink_tap_init_net
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/mptcp/ctrl.c (ffffffff82004905)
Location: include/net/netns/generic.h:40
Inline: True
Inline callers:
  - net/mptcp/ctrl.c:mptcp_net_exit
  - net/mptcp/ctrl.c:mptcp_net_init
  - net/mptcp/ctrl.c:mptcp_get_pm_type
  - net/mptcp/ctrl.c:mptcp_stale_loss_cnt
  - net/mptcp/ctrl.c:mptcp_allow_join_id0
  - net/mptcp/ctrl.c:mptcp_is_checksum_enabled
  - net/mptcp/ctrl.c:mptcp_get_add_addr_timeout
  - net/mptcp/ctrl.c:mptcp_is_enabled
```
```
In net/mptcp/pm_netlink.c (ffffffff82007386)
Location: include/net/netns/generic.h:40
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:pm_nl_exit_net
  - net/mptcp/pm_netlink.c:pm_nl_init_net
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_get_flags_and_ifindex_by_id
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_local_id
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_check_work_pending
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_check_work_pending
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
In kernel/audit.c (ffffffff8123a695)
Location: include/net/netns/generic.h:40
Inline: True
Inline callers:
  - kernel/audit.c:audit_net_exit
  - kernel/audit.c:audit_net_init
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_multicast_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c62a1c)
Location: include/net/netns/generic.h:40
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/net_namespace.c (ffffffff81e244fd)
Location: include/net/netns/generic.h:40
Inline: True
Inline callers:
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/fib_notifier.c (ffffffff81e77fc5)
Location: include/net/netns/generic.h:40
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_net_exit
  - net/core/fib_notifier.c:fib_notifier_net_init
  - net/core/fib_notifier.c:fib_notifier_ops_register
  - net/core/fib_notifier.c:unregister_fib_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/fib_notifier.c:call_fib_notifiers
```
```
In net/sched/cls_api.c (ffffffff81eb59e5)
Location: include/net/netns/generic.h:40
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_net_exit
  - net/sched/cls_api.c:tcf_net_init
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/sched/act_api.c (ffffffff81ec0467)
Location: include/net/netns/generic.h:40
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_reoffload_cb
  - net/sched/act_api.c:__tcf_generic_walker
```
```
In net/netlink/af_netlink.c (ffffffff81ec8096)
Location: include/net/netns/generic.h:40
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/netlink/af_netlink.c:netlink_tap_init_net
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/mptcp/ctrl.c (ffffffff82080aa5)
Location: include/net/netns/generic.h:40
Inline: True
Inline callers:
  - net/mptcp/ctrl.c:mptcp_net_exit
  - net/mptcp/ctrl.c:mptcp_net_init
  - net/mptcp/ctrl.c:mptcp_get_pm_type
  - net/mptcp/ctrl.c:mptcp_stale_loss_cnt
  - net/mptcp/ctrl.c:mptcp_allow_join_id0
  - net/mptcp/ctrl.c:mptcp_is_checksum_enabled
  - net/mptcp/ctrl.c:mptcp_get_add_addr_timeout
  - net/mptcp/ctrl.c:mptcp_is_enabled
```
```
In net/mptcp/pm_netlink.c (ffffffff82083726)
Location: include/net/netns/generic.h:40
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:pm_nl_exit_net
  - net/mptcp/pm_netlink.c:pm_nl_init_net
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_flags_and_ifindex_by_id
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_local_id
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_check_work_pending
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_check_work_pending
```
```
In net/handshake/netlink.c (ffffffff8209225a)
Location: include/net/netns/generic.h:40
Inline: True
Inline callers:
  - net/handshake/netlink.c:handshake_net_exit
  - net/handshake/netlink.c:handshake_net_init
  - net/handshake/netlink.c:handshake_nl_accept_doit
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
In kernel/audit.c (ffffffff81254365)
Location: include/net/netns/generic.h:40
Inline: True
Inline callers:
  - kernel/audit.c:audit_net_exit
  - kernel/audit.c:audit_net_init
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_multicast_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d1943c)
Location: include/net/netns/generic.h:40
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_unit_register
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/net_namespace.c (ffffffff81ee270d)
Location: include/net/netns/generic.h:40
Inline: True
Inline callers:
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/fib_notifier.c (ffffffff81f37f85)
Location: include/net/netns/generic.h:40
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_net_exit
  - net/core/fib_notifier.c:fib_notifier_net_init
  - net/core/fib_notifier.c:fib_notifier_ops_register
  - net/core/fib_notifier.c:unregister_fib_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/core/fib_notifier.c:register_fib_notifier
  - net/core/fib_notifier.c:fib_seq_sum
  - net/core/fib_notifier.c:call_fib_notifiers
```
```
In net/sched/cls_api.c (ffffffff81f786f5)
Location: include/net/netns/generic.h:40
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_net_exit
  - net/sched/cls_api.c:tcf_net_init
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/sched/act_api.c (ffffffff81f8386d)
Location: include/net/netns/generic.h:40
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_reoffload_cb
  - net/sched/act_api.c:__tcf_generic_walker
```
```
In net/netlink/af_netlink.c (ffffffff81f8b4ac)
Location: include/net/netns/generic.h:40
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/netlink/af_netlink.c:netlink_tap_init_net
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/mptcp/ctrl.c (ffffffff82156005)
Location: include/net/netns/generic.h:40
Inline: True
Inline callers:
  - net/mptcp/ctrl.c:mptcp_net_exit
  - net/mptcp/ctrl.c:mptcp_net_init
  - net/mptcp/ctrl.c:mptcp_get_scheduler
  - net/mptcp/ctrl.c:mptcp_get_pm_type
  - net/mptcp/ctrl.c:mptcp_close_timeout
  - net/mptcp/ctrl.c:mptcp_stale_loss_cnt
  - net/mptcp/ctrl.c:mptcp_allow_join_id0
  - net/mptcp/ctrl.c:mptcp_is_checksum_enabled
  - net/mptcp/ctrl.c:mptcp_get_add_addr_timeout
  - net/mptcp/ctrl.c:mptcp_is_enabled
```
```
In net/mptcp/pm_netlink.c (ffffffff82158eb6)
Location: include/net/netns/generic.h:40
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:pm_nl_exit_net
  - net/mptcp/pm_netlink.c:pm_nl_init_net
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_set_flags
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_limits_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_set_limits_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_addr_dumpit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_addr_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_flush_addrs_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_del_addr_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_flags_and_ifindex_by_id
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_local_id
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:fill_remote_addresses_vec
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_check_work_pending
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_check_work_pending
```
```
In net/handshake/netlink.c (ffffffff82168b3a)
Location: include/net/netns/generic.h:40
Inline: True
Inline callers:
  - net/handshake/netlink.c:handshake_net_exit
  - net/handshake/netlink.c:handshake_net_init
  - net/handshake/netlink.c:handshake_nl_accept_doit
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
In kernel/audit.c (ffff8000101e90e8)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - kernel/audit.c:audit_net_exit
  - kernel/audit.c:audit_net_init
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_multicast_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffff800010a00584)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/net_namespace.c (ffff800010bc0180)
Location: include/net/netns/generic.h:39
Inline: True
```
```
In net/core/fib_notifier.c (ffff800010c05768)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_net_init
  - net/core/fib_notifier.c:fib_notifier_ops_register
  - net/core/fib_notifier.c:register_fib_notifier
  - net/core/fib_notifier.c:fib_seq_sum
```
```
In net/sched/cls_api.c (ffff800010c40568)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_net_exit
  - net/sched/cls_api.c:tcf_net_init
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/netlink/af_netlink.c (ffff800010c4b54c)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/netlink/af_netlink.c:netlink_tap_init_net
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netlink/af_netlink.c:netlink_add_tap
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
In kernel/audit.c (c04290cc)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - kernel/audit.c:audit_net_exit
  - kernel/audit.c:audit_net_init
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_multicast_skb
```
```
In drivers/net/ppp/ppp_generic.c (c0add8ac)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/net_namespace.c (c0cdbc74)
Location: include/net/netns/generic.h:39
Inline: True
```
```
In net/core/fib_notifier.c (c0d1e868)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_net_init
  - net/core/fib_notifier.c:fib_notifier_ops_register
  - net/core/fib_notifier.c:register_fib_notifier
  - net/core/fib_notifier.c:fib_seq_sum
```
```
In net/sched/cls_api.c (c0d52a40)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_net_exit
  - net/sched/cls_api.c:tcf_net_init
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/netlink/af_netlink.c (c0d5bf4c)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/netlink/af_netlink.c:netlink_tap_init_net
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netlink/af_netlink.c:netlink_add_tap
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
In kernel/audit.c (c000000000259d74)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - kernel/audit.c:audit_net_exit
  - kernel/audit.c:audit_net_init
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_multicast_skb
```
```
In drivers/net/ppp/ppp_generic.c (c000000000aa87e4)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/net_namespace.c (c000000000c9983c)
Location: include/net/netns/generic.h:39
Inline: True
```
```
In net/core/fib_notifier.c (c000000000cef8e8)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_net_init
  - net/core/fib_notifier.c:fib_notifier_ops_register
  - net/core/fib_notifier.c:register_fib_notifier
  - net/core/fib_notifier.c:fib_seq_sum
```
```
In net/sched/cls_api.c (c000000000d3b5e4)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_net_exit
  - net/sched/cls_api.c:tcf_net_init
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/netlink/af_netlink.c (c000000000d49700)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/netlink/af_netlink.c:netlink_tap_init_net
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netlink/af_netlink.c:netlink_add_tap
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
In kernel/audit.c (ffffffe00015e014)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - kernel/audit.c:audit_net_exit
  - kernel/audit.c:audit_net_init
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_multicast_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffe00062cfbe)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/net_namespace.c (ffffffe00074da4e)
Location: include/net/netns/generic.h:39
Inline: True
```
```
In net/core/fib_notifier.c (ffffffe000783f64)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_net_init
  - net/core/fib_notifier.c:fib_notifier_ops_register
  - net/core/fib_notifier.c:register_fib_notifier
  - net/core/fib_notifier.c:fib_seq_sum
```
```
In net/sched/cls_api.c (ffffffe0007b0018)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_net_exit
  - net/sched/cls_api.c:tcf_net_init
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/netlink/af_netlink.c (ffffffe0007b8c9c)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/netlink/af_netlink.c:netlink_tap_init_net
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netlink/af_netlink.c:netlink_add_tap
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
In kernel/audit.c (ffffffff8116ccec)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - kernel/audit.c:audit_net_exit
  - kernel/audit.c:audit_net_init
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_multicast_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8178d149)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/net_namespace.c (ffffffff818c4743)
Location: include/net/netns/generic.h:39
Inline: True
```
```
In net/core/fib_notifier.c (ffffffff81901a7c)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_net_init
  - net/core/fib_notifier.c:fib_notifier_ops_register
  - net/core/fib_notifier.c:register_fib_notifier
  - net/core/fib_notifier.c:fib_seq_sum
```
```
In net/sched/cls_api.c (ffffffff81933eec)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_net_exit
  - net/sched/cls_api.c:tcf_net_init
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/netlink/af_netlink.c (ffffffff8193debc)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/netlink/af_netlink.c:netlink_tap_init_net
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netlink/af_netlink.c:netlink_add_tap
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
In kernel/audit.c (ffffffff8115fe8c)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - kernel/audit.c:audit_net_exit
  - kernel/audit.c:audit_net_init
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_multicast_skb
```
```
In drivers/net/vxlan.c (ffffffff8176c2a0)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_exit_batch_net
  - drivers/net/vxlan.c:vxlan_init_net
  - drivers/net/vxlan.c:vxlan_netdevice_event
  - drivers/net/vxlan.c:__vxlan_dev_create
  - drivers/net/vxlan.c:vxlan_config_validate
  - drivers/net/vxlan.c:__vxlan_sock_add
  - drivers/net/vxlan.c:__vxlan_sock_add
  - drivers/net/vxlan.c:__vxlan_sock_add
  - drivers/net/vxlan.c:__vxlan_sock_add
  - drivers/net/vxlan.c:vxlan_offload_rx_ports
  - drivers/net/vxlan.c:vxlan_stop
  - drivers/net/vxlan.c:vxlan_sock_release
  - drivers/net/vxlan.c:vxlan_find_sock
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81775f19)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/net_namespace.c (ffffffff8187e683)
Location: include/net/netns/generic.h:39
Inline: True
```
```
In net/core/fib_notifier.c (ffffffff818bb8ac)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_net_init
  - net/core/fib_notifier.c:fib_notifier_ops_register
  - net/core/fib_notifier.c:register_fib_notifier
  - net/core/fib_notifier.c:fib_seq_sum
```
```
In net/sched/cls_api.c (ffffffff818ed9ec)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_net_exit
  - net/sched/cls_api.c:tcf_net_init
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/netlink/af_netlink.c (ffffffff818f79bc)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/netlink/af_netlink.c:netlink_tap_init_net
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/ipv4/ip_tunnel.c (ffffffff819669b2)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:ip_tunnel_uninit
  - net/ipv4/ip_tunnel.c:ip_tunnel_changelink
  - net/ipv4/ip_tunnel.c:ip_tunnel_newlink
  - net/ipv4/ip_tunnel.c:ip_tunnel_delete_nets
  - net/ipv4/ip_tunnel.c:ip_tunnel_init_net
  - net/ipv4/ip_tunnel.c:ip_tunnel_init_net
  - net/ipv4/ip_tunnel.c:ip_tunnel_dellink
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
In kernel/audit.c (ffffffff8116aabc)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - kernel/audit.c:audit_net_exit
  - kernel/audit.c:audit_net_init
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_multicast_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817bd4e9)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/net_namespace.c (ffffffff81915743)
Location: include/net/netns/generic.h:39
Inline: True
```
```
In net/core/fib_notifier.c (ffffffff81952aac)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_net_init
  - net/core/fib_notifier.c:fib_notifier_ops_register
  - net/core/fib_notifier.c:register_fib_notifier
  - net/core/fib_notifier.c:fib_seq_sum
```
```
In net/sched/cls_api.c (ffffffff8198507c)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_net_exit
  - net/sched/cls_api.c:tcf_net_init
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/netlink/af_netlink.c (ffffffff8198f04c)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/netlink/af_netlink.c:netlink_tap_init_net
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netlink/af_netlink.c:netlink_add_tap
```
```
In net/netfilter/nfnetlink_queue.c (ffffffff8199919c)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_queue.c:nfnl_queue_net_exit
  - net/netfilter/nfnetlink_queue.c:nfnl_queue_net_init
  - net/netfilter/nfnetlink_queue.c:seq_stop
  - net/netfilter/nfnetlink_queue.c:seq_next
  - net/netfilter/nfnetlink_queue.c:seq_start
  - net/netfilter/nfnetlink_queue.c:seq_start
  - net/netfilter/nfnetlink_queue.c:seq_start
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_config
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_verdict
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_verdict_batch
  - net/netfilter/nfnetlink_queue.c:nfqnl_rcv_nl_event
  - net/netfilter/nfnetlink_queue.c:nfqnl_nf_hook_drop
  - net/netfilter/nfnetlink_queue.c:nfqnl_rcv_dev_event
  - net/netfilter/nfnetlink_queue.c:nfqnl_enqueue_packet
```
```
In net/netfilter/nfnetlink_log.c (ffffffff8199b4dc)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_log.c:nfnl_log_net_exit
  - net/netfilter/nfnetlink_log.c:nfnl_log_net_init
  - net/netfilter/nfnetlink_log.c:seq_next
  - net/netfilter/nfnetlink_log.c:seq_start
  - net/netfilter/nfnetlink_log.c:seq_start
  - net/netfilter/nfnetlink_log.c:nfulnl_recv_config
  - net/netfilter/nfnetlink_log.c:nfulnl_recv_config
  - net/netfilter/nfnetlink_log.c:nfulnl_rcv_nl_event
  - net/netfilter/nfnetlink_log.c:nfulnl_log_packet
```
```
In net/netfilter/nf_conntrack_proto.c (ffffffff819a415c)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto.c:nf_ct_netns_do_put
  - net/netfilter/nf_conntrack_proto.c:nf_ct_netns_do_get
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
In kernel/audit.c (ffffffff81178285)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - kernel/audit.c:audit_net_exit
  - kernel/audit.c:audit_net_init
  - kernel/audit.c:kauditd_send_multicast_skb
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817d7d0a)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_exit_net
  - drivers/net/ppp/ppp_generic.c:ppp_init_net
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In net/core/net_namespace.c (ffffffff81936926)
Location: include/net/netns/generic.h:39
Inline: True
```
```
In net/core/fib_notifier.c (ffffffff81974565)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/core/fib_notifier.c:fib_notifier_net_init
  - net/core/fib_notifier.c:fib_notifier_ops_register
  - net/core/fib_notifier.c:register_fib_notifier
  - net/core/fib_notifier.c:fib_seq_sum
```
```
In net/sched/cls_api.c (ffffffff819a7de5)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_net_exit
  - net/sched/cls_api.c:tcf_net_init
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/netlink/af_netlink.c (ffffffff819b1922)
Location: include/net/netns/generic.h:39
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
  - net/netlink/af_netlink.c:netlink_tap_init_net
  - net/netlink/af_netlink.c:netlink_remove_tap
  - net/netlink/af_netlink.c:netlink_add_tap
```
</details>
</li>
</ul>

## Differences
