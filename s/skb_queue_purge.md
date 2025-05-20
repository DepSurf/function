# Function: <code>skb_queue_purge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void skb_queue_purge(struct sk_buff_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817060d0)
Location: net/core/skbuff.c:2441
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_list_rules_send
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/netlink/af_netlink.c:netlink_sock_destruct
  - net/netlink/af_netlink.c:netlink_release
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/unix/af_unix.c:unix_sock_destructor
  - net/packet/af_packet.c:packet_sock_destruct
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
  - net/wireless/wext-core.c:wext_pernet_exit
```
**Symbols:**

```
ffffffff817060d0-ffffffff817060f7: skb_queue_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void skb_queue_purge(struct sk_buff_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8176e140)
Location: net/core/skbuff.c:2439
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_list_rules_send
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_sock_destruct
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/unix/af_unix.c:unix_sock_destructor
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_sock_destruct
  - net/wireless/wext-core.c:wext_pernet_exit
```
**Symbols:**

```
ffffffff8176e140-ffffffff8176e167: skb_queue_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void skb_queue_purge(struct sk_buff_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8179b580)
Location: net/core/skbuff.c:2415
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_list_rules_send
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_sock_destruct
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/unix/af_unix.c:unix_sock_destructor
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_sock_destruct
  - net/wireless/wext-core.c:wext_pernet_exit
```
**Symbols:**

```
ffffffff8179b580-ffffffff8179b5a7: skb_queue_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void skb_queue_purge(struct sk_buff_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817bc9a0)
Location: net/core/skbuff.c:2455
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_list_rules_send
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_sock_destruct
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/unix/af_unix.c:unix_sock_destructor
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_sock_destruct
  - net/wireless/wext-core.c:wext_pernet_exit
```
**Symbols:**

```
ffffffff817bc9a0-ffffffff817bc9c7: skb_queue_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void skb_queue_purge(struct sk_buff_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81833810)
Location: net/core/skbuff.c:2831
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_list_rules_send
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_sock_destruct
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/unix/af_unix.c:unix_sock_destructor
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_sock_destruct
  - net/wireless/wext-core.c:wext_pernet_exit
```
**Symbols:**

```
ffffffff81833810-ffffffff81833837: skb_queue_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void skb_queue_purge(struct sk_buff_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187dc70)
Location: net/core/skbuff.c:2847
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_list_rules_send
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_sock_destruct
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/unix/af_unix.c:unix_sock_destructor
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_sock_destruct
  - net/wireless/wext-core.c:wext_pernet_exit
```
**Symbols:**

```
ffffffff8187dc70-ffffffff8187dc97: skb_queue_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void skb_queue_purge(struct sk_buff_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189e840)
Location: net/core/skbuff.c:2902
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_list_rules_send
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_sock_destruct
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/unix/af_unix.c:unix_sock_destructor
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_sock_destruct
  - net/wireless/wext-core.c:wext_pernet_exit
```
**Symbols:**

```
ffffffff8189e840-ffffffff8189e867: skb_queue_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void skb_queue_purge(struct sk_buff_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818e90d0)
Location: net/core/skbuff.c:3068
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_list_rules_send
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_sock_destruct
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/unix/af_unix.c:unix_sock_destructor
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_sock_destruct
  - net/wireless/wext-core.c:wext_pernet_exit
```
**Symbols:**

```
ffffffff818e90d0-ffffffff818e90f7: skb_queue_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void skb_queue_purge(struct sk_buff_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8191b230)
Location: net/core/skbuff.c:3074
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_list_rules_send
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_sock_destruct
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/unix/af_unix.c:unix_sock_destructor
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_sock_destruct
  - net/wireless/wext-core.c:wext_pernet_exit
```
**Symbols:**

```
ffffffff8191b230-ffffffff8191b257: skb_queue_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void skb_queue_purge(struct sk_buff_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ee000)
Location: net/core/skbuff.c:3073
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_list_rules_send
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_sock_destruct
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/espintcp.c:espintcp_close
  - net/xfrm/espintcp.c:espintcp_close
  - net/unix/af_unix.c:unix_sock_destructor
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_sock_destruct
  - net/wireless/wext-core.c:wext_pernet_exit
```
**Symbols:**

```
ffffffff819ee000-ffffffff819ee02a: skb_queue_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void skb_queue_purge(struct sk_buff_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819edca0)
Location: net/core/skbuff.c:3091
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_list_rules_send
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_sock_destruct
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/espintcp.c:espintcp_close
  - net/xfrm/espintcp.c:espintcp_close
  - net/unix/af_unix.c:unix_sock_destructor
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_sock_destruct
  - net/wireless/wext-core.c:wext_pernet_exit
```
**Symbols:**

```
ffffffff819edca0-ffffffff819edcca: skb_queue_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void skb_queue_purge(struct sk_buff_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d6f40)
Location: net/core/skbuff.c:3177
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_list_rules_send
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - drivers/net/wwan/wwan_core.c:wwan_remove_port
  - drivers/net/wwan/wwan_core.c:wwan_port_destroy
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_sock_destruct
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/espintcp.c:espintcp_close
  - net/xfrm/espintcp.c:espintcp_close
  - net/unix/af_unix.c:unix_sock_destructor
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_sock_destruct
  - net/wireless/wext-core.c:wext_pernet_exit
```
**Symbols:**

```
ffffffff819d6f40-ffffffff819d6f6a: skb_queue_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void skb_queue_purge(struct sk_buff_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a85a70)
Location: net/core/skbuff.c:3249
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_list_rules_send
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_release
  - drivers/net/wwan/wwan_core.c:wwan_remove_port
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_sock_destruct
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/espintcp.c:espintcp_close
  - net/xfrm/espintcp.c:espintcp_close
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:unix_dgram_disconnected
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_sock_destruct
  - net/wireless/wext-core.c:wext_pernet_exit
```
**Symbols:**

```
ffffffff81a85a70-ffffffff81a85a9a: skb_queue_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void skb_queue_purge(struct sk_buff_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bf84c0)
Location: net/core/skbuff.c:3298
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_list_rules_send
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_release
  - drivers/net/wwan/wwan_core.c:wwan_remove_port
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_sock_destruct
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/espintcp.c:espintcp_close
  - net/xfrm/espintcp.c:espintcp_close
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:unix_dgram_disconnected
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
  - net/wireless/wext-core.c:wext_pernet_exit
```
**Symbols:**

```
ffffffff81bf84c0-ffffffff81bf84f9: skb_queue_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void skb_queue_purge(struct sk_buff_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da7310)
Location: net/core/skbuff.c:3502
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_list_rules_send
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_release
  - drivers/net/wwan/wwan_core.c:wwan_remove_port
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_sock_destruct
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/espintcp.c:espintcp_close
  - net/xfrm/espintcp.c:espintcp_close
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:unix_dgram_disconnected
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
  - net/wireless/wext-core.c:wext_pernet_exit
  - net/mctp/af_mctp.c:mctp_sk_destruct
```
**Symbols:**

```
ffffffff81da7310-ffffffff81da7349: skb_queue_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void skb_queue_purge(struct sk_buff_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e193c0)
Location: net/core/skbuff.c:3672
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_list_rules_send
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_release
  - drivers/net/wwan/wwan_core.c:wwan_remove_port
  - net/core/stream.c:sk_stream_kill_queues
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_sock_destruct
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/espintcp.c:espintcp_close
  - net/xfrm/espintcp.c:espintcp_close
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:unix_dgram_disconnected
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
  - net/wireless/wext-core.c:wext_pernet_exit
  - net/mctp/af_mctp.c:mctp_sk_destruct
```
**Symbols:**

```
ffffffff81e193c0-ffffffff81e193f9: skb_queue_purge (STB_GLOBAL)
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
In kernel/auditfilter.c (ffffffff8125b32c)
Location: include/linux/skbuff.h:3187
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In drivers/net/tun.c (ffffffff81cfb26c)
Location: include/linux/skbuff.h:3187
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/tun.c:tun_queue_purge
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d1a531)
Location: include/linux/skbuff.h:3187
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
```
```
In net/core/stream.c (ffffffff81edee0e)
Location: include/linux/skbuff.h:3187
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/core/netpoll.c (ffffffff81f47a27)
Location: include/linux/skbuff.h:3187
Inline: True
Inline callers:
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
```
```
In net/netlink/af_netlink.c (ffffffff81f8aaf3)
Location: include/linux/skbuff.h:3187
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_sock_destruct
```
```
In net/xfrm/xfrm_policy.c (ffffffff82063c0c)
Location: include/linux/skbuff.h:3187
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
```
```
In net/xfrm/espintcp.c (ffffffff82074b60)
Location: include/linux/skbuff.h:3187
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_close
  - net/xfrm/espintcp.c:espintcp_close
```
```
In net/unix/af_unix.c (ffffffff82077435)
Location: include/linux/skbuff.h:3187
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:unix_dgram_disconnected
```
```
In net/packet/af_packet.c (ffffffff820f81fb)
Location: include/linux/skbuff.h:3187
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
```
```
In net/wireless/wext-core.c (ffffffff8211cc45)
Location: include/linux/skbuff.h:3187
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_exit
```
```
In net/mctp/af_mctp.c (ffffffff82162e05)
Location: include/linux/skbuff.h:3187
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_destruct
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
void skb_queue_purge(struct sk_buff_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb5708)
Location: net/core/skbuff.c:3074
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_list_rules_send
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_sock_destruct
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/unix/af_unix.c:unix_sock_destructor
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_sock_destruct
  - net/wireless/wext-core.c:wext_pernet_exit
```
**Symbols:**

```
ffff800010bb5708-ffff800010bb5740: skb_queue_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void skb_queue_purge(struct sk_buff_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cd27b4)
Location: net/core/skbuff.c:3074
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_list_rules_send
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/ethernet/ti/cpts.c:cpts_unregister
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_sock_destruct
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/unix/af_unix.c:unix_sock_destructor
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_sock_destruct
  - net/wireless/wext-core.c:wext_pernet_exit
```
**Symbols:**

```
c0cd27b4-c0cd27e4: skb_queue_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void skb_queue_purge(struct sk_buff_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c8c8f0)
Location: net/core/skbuff.c:3074
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_list_rules_send
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_sock_destruct
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/unix/af_unix.c:unix_sock_destructor
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_sock_destruct
  - net/wireless/wext-core.c:wext_pernet_exit
```
**Symbols:**

```
c000000000c8c8f0-c000000000c8c948: skb_queue_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void skb_queue_purge(struct sk_buff_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe0007456a4)
Location: net/core/skbuff.c:3074
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_list_rules_send
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_sock_destruct
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/unix/af_unix.c:unix_sock_destructor
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_sock_destruct
  - net/wireless/wext-core.c:wext_pernet_exit
```
**Symbols:**

```
ffffffe0007456a4-ffffffe0007456da: skb_queue_purge (STB_GLOBAL)
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
void skb_queue_purge(struct sk_buff_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818bb230)
Location: net/core/skbuff.c:3074
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_list_rules_send
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_sock_destruct
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/unix/af_unix.c:unix_sock_destructor
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_sock_destruct
  - net/wireless/wext-core.c:wext_pernet_exit
```
**Symbols:**

```
ffffffff818bb230-ffffffff818bb257: skb_queue_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void skb_queue_purge(struct sk_buff_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81875170)
Location: net/core/skbuff.c:3074
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_list_rules_send
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_sock_destruct
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/unix/af_unix.c:unix_sock_destructor
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_sock_destruct
  - net/wireless/wext-core.c:wext_pernet_exit
```
**Symbols:**

```
ffffffff81875170-ffffffff81875197: skb_queue_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void skb_queue_purge(struct sk_buff_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8190c230)
Location: net/core/skbuff.c:3074
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_list_rules_send
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_sock_destruct
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/unix/af_unix.c:unix_sock_destructor
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_sock_destruct
  - net/wireless/wext-core.c:wext_pernet_exit
```
**Symbols:**

```
ffffffff8190c230-ffffffff8190c257: skb_queue_purge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void skb_queue_purge(struct sk_buff_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8192d360)
Location: net/core/skbuff.c:3074
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_list_rules_send
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - net/core/netpoll.c:rcu_cleanup_netpoll_info
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_sock_destruct
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/unix/af_unix.c:unix_sock_destructor
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_sock_destruct
  - net/wireless/wext-core.c:wext_pernet_exit
```
**Symbols:**

```
ffffffff8192d360-ffffffff8192d387: skb_queue_purge (STB_GLOBAL)
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
