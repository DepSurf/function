# Function: <code>skb_queue_purge_reason</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void skb_queue_purge_reason(struct sk_buff_head *list, enum skb_drop_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ed93a0)
Location: net/core/skbuff.c:3761
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_list_rules_send
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/tun.c:tun_queue_purge
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - net/core/stream.c:sk_stream_kill_queues
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
  - net/mctp/af_mctp.c:mctp_sk_destruct
```
**Symbols:**

```
ffffffff81ed93a0-ffffffff81ed94d0: skb_queue_purge_reason (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
