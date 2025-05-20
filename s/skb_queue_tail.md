# Function: <code>skb_queue_tail</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void skb_queue_tail(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81704fe0)
Location: net/core/skbuff.c:2481
Inline: False
Direct callers:
  - kernel/audit.c:audit_hold_skb
  - kernel/audit.c:audit_log_end
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/auditfilter.c:audit_list_rules_send
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff81704fe0-ffffffff8170502a: skb_queue_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void skb_queue_tail(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8176bbb0)
Location: net/core/skbuff.c:2479
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:audit_hold_skb
  - kernel/auditfilter.c:audit_list_rules
  - kernel/auditfilter.c:audit_list_rules
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff8176bbb0-ffffffff8176bbfa: skb_queue_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void skb_queue_tail(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81798c80)
Location: net/core/skbuff.c:2474
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:kauditd_thread
  - kernel/auditfilter.c:audit_list_rules
  - kernel/auditfilter.c:audit_list_rules
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff81798c80-ffffffff81798cca: skb_queue_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void skb_queue_tail(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817b7230)
Location: net/core/skbuff.c:2514
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:kauditd_retry_skb
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/auditfilter.c:audit_list_rules_send
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_start_xmit
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff817b7230-ffffffff817b727a: skb_queue_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void skb_queue_tail(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8182f830)
Location: net/core/skbuff.c:2893
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:kauditd_retry_skb
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/bpf/sockmap.c:smap_read_sock_strparser
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff8182f830-ffffffff8182f87a: skb_queue_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void skb_queue_tail(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81879d50)
Location: net/core/skbuff.c:2909
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:kauditd_retry_skb
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/bpf/sockmap.c:smap_read_sock_strparser
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff81879d50-ffffffff81879d9a: skb_queue_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void skb_queue_tail(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189a9c0)
Location: net/core/skbuff.c:2968
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:kauditd_retry_skb
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/auditfilter.c:audit_list_rules_send
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff8189a9c0-ffffffff8189aa0a: skb_queue_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void skb_queue_tail(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818e4fe0)
Location: net/core/skbuff.c:3134
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:kauditd_retry_skb
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/auditfilter.c:audit_list_rules_send
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff818e4fe0-ffffffff818e502a: skb_queue_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void skb_queue_tail(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81917170)
Location: net/core/skbuff.c:3140
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:kauditd_retry_skb
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/auditfilter.c:audit_list_rules_send
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff81917170-ffffffff819171ba: skb_queue_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void skb_queue_tail(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819eb73f)
Location: net/core/skbuff.c:3139
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
Direct callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:kauditd_retry_skb
  - kernel/auditfilter.c:audit_list_rules
  - kernel/auditfilter.c:audit_list_rules
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/core/netpoll.c:__netpoll_send_skb
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
  - net/xfrm/espintcp.c:handle_nonesp
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff819e9af0-ffffffff819e9b3a: skb_queue_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void skb_queue_tail(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819eb45f)
Location: net/core/skbuff.c:3157
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
Direct callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:kauditd_retry_skb
  - kernel/auditfilter.c:audit_list_rules
  - kernel/auditfilter.c:audit_list_rules
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/core/netpoll.c:__netpoll_send_skb
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:netlink_dump
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
  - net/xfrm/espintcp.c:handle_nonesp
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff819e9890-ffffffff819e98da: skb_queue_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void skb_queue_tail(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d196f)
Location: net/core/skbuff.c:3243
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
Direct callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:kauditd_retry_skb
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/auditfilter.c:audit_list_rules_send
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - drivers/net/wwan/wwan_core.c:wwan_port_rx
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
  - net/xfrm/espintcp.c:handle_nonesp
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff819cf9b0-ffffffff819cf9fa: skb_queue_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void skb_queue_tail(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a81563)
Location: net/core/skbuff.c:3315
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
Direct callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:kauditd_hold_skb
  - kernel/audit.c:kauditd_hold_skb
  - kernel/audit.c:kauditd_rehold_skb
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/auditfilter.c:audit_list_rules_send
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - drivers/net/wwan/wwan_core.c:wwan_port_rx
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
  - net/xfrm/espintcp.c:espintcp_rcv
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff81a7f500-ffffffff81a7f54f: skb_queue_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void skb_queue_tail(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bf51f3)
Location: net/core/skbuff.c:3364
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
Direct callers:
  - kernel/audit.c:audit_buffer_aux_new
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:kauditd_hold_skb
  - kernel/audit.c:kauditd_hold_skb
  - kernel/audit.c:kauditd_rehold_skb
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/auditfilter.c:audit_list_rules_send
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - drivers/net/wwan/wwan_core.c:wwan_port_rx
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
  - net/xfrm/espintcp.c:handle_nonesp
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff81bf3850-ffffffff81bf38a9: skb_queue_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void skb_queue_tail(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da3713)
Location: net/core/skbuff.c:3568
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
Direct callers:
  - kernel/audit.c:audit_buffer_aux_new
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:kauditd_hold_skb
  - kernel/audit.c:kauditd_hold_skb
  - kernel/audit.c:kauditd_rehold_skb
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/auditfilter.c:audit_list_rules_send
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - drivers/net/wwan/wwan_core.c:wwan_port_rx
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
  - net/xfrm/espintcp.c:handle_nonesp
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:queue_oob
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/garbage.c:unix_gc
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff81da15f0-ffffffff81da1649: skb_queue_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void skb_queue_tail(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e12308)
Location: net/core/skbuff.c:3738
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
Direct callers:
  - kernel/audit.c:audit_buffer_aux_new
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:kauditd_hold_skb
  - kernel/audit.c:kauditd_hold_skb
  - kernel/audit.c:kauditd_rehold_skb
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/auditfilter.c:audit_list_rules_send
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - drivers/net/wwan/wwan_core.c:wwan_port_rx
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
  - net/xfrm/espintcp.c:handle_nonesp
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:queue_oob
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/garbage.c:unix_gc
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff81e0fee0-ffffffff81e0ff39: skb_queue_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void skb_queue_tail(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ecf4c8)
Location: net/core/skbuff.c:3859
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
Direct callers:
  - kernel/audit.c:audit_buffer_aux_new
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:kauditd_hold_skb
  - kernel/audit.c:kauditd_hold_skb
  - kernel/audit.c:kauditd_rehold_skb
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/auditfilter.c:audit_list_rules_send
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
  - net/xfrm/espintcp.c:handle_nonesp
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:queue_oob
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/garbage.c:unix_gc
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff81ecc990-ffffffff81ecc9e9: skb_queue_tail (STB_GLOBAL)
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
void skb_queue_tail(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb3868)
Location: net/core/skbuff.c:3140
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:kauditd_retry_skb
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/auditfilter.c:audit_list_rules_send
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffff800010bb3868-ffff800010bb3930: skb_queue_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void skb_queue_tail(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0ccdb68)
Location: net/core/skbuff.c:3140
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:kauditd_retry_skb
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/auditfilter.c:audit_list_rules_send
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_mp_explode
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
c0ccdb68-c0ccdbc0: skb_queue_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void skb_queue_tail(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c86300)
Location: net/core/skbuff.c:3140
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:kauditd_retry_skb
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/auditfilter.c:audit_list_rules_send
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
c000000000c86300-c000000000c8638c: skb_queue_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void skb_queue_tail(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe0007415d0)
Location: net/core/skbuff.c:3140
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:kauditd_retry_skb
  - kernel/auditfilter.c:audit_list_rules
  - kernel/auditfilter.c:audit_list_rules
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffe0007415d0-ffffffe00074162c: skb_queue_tail (STB_GLOBAL)
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
void skb_queue_tail(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818b7170)
Location: net/core/skbuff.c:3140
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:kauditd_retry_skb
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/auditfilter.c:audit_list_rules_send
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff818b7170-ffffffff818b71ba: skb_queue_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void skb_queue_tail(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818710c0)
Location: net/core/skbuff.c:3140
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:kauditd_retry_skb
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/auditfilter.c:audit_list_rules_send
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff818710c0-ffffffff8187110a: skb_queue_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void skb_queue_tail(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81908170)
Location: net/core/skbuff.c:3140
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:kauditd_retry_skb
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/auditfilter.c:audit_list_rules_send
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff81908170-ffffffff819081ba: skb_queue_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void skb_queue_tail(struct sk_buff_head *list, struct sk_buff *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819291b0)
Location: net/core/skbuff.c:3140
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_end
  - kernel/audit.c:kauditd_retry_skb
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/auditfilter.c:audit_list_rules_send
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff819291b0-ffffffff819291fa: skb_queue_tail (STB_GLOBAL)
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
