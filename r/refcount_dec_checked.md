# Function: <code>refcount_dec_checked</code>

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
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void refcount_dec_checked(refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff814e2260)
Location: lib/refcount.c:226
Inline: True
```
**Symbols:**

```
ffffffff814e2260-ffffffff814e2297: refcount_dec_checked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void refcount_dec_checked(refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff8150e0f0)
Location: lib/refcount.c:234
Inline: True
```
**Symbols:**

```
ffffffff8150e0f0-ffffffff8150e127: refcount_dec_checked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void refcount_dec_checked(refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff8152bf40)
Location: lib/refcount.c:234
Inline: True
```
**Symbols:**

```
ffffffff8152bf40-ffffffff8152bf77: refcount_dec_checked (STB_GLOBAL)
```
</details>
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
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void refcount_dec_checked(refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffff800010637948)
Location: lib/refcount.c:234
Inline: True
Direct callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
  - fs/fuse/dev.c:request_wait_answer
  - net/core/sock.c:sk_stop_timer
  - net/core/datagram.c:__sk_queue_drop_skb
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/netlink/af_netlink.c:netlink_remove
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/arp.c:arp_constructor
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_stop_timer
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:addrconf_del_dad_work
  - net/ipv6/ndisc.c:ndisc_constructor
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:mld_ifc_stop_timer
  - net/ipv6/mcast.c:mld_gq_stop_timer
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/packet/af_packet.c:packet_release
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffff800010637948-ffff800010637998: refcount_dec_checked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void refcount_dec_checked(refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (c07dd73c)
Location: lib/refcount.c:234
Inline: True
Direct callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
  - fs/fuse/dev.c:fuse_simple_request
  - sound/core/pcm_native.c:snd_pcm_unlink
  - sound/core/pcm_native.c:snd_pcm_unlink
  - net/core/sock.c:sk_stop_timer
  - net/core/datagram.c:__sk_queue_drop_skb
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit
  - net/netlink/af_netlink.c:netlink_remove
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_output.c:tcp_release_cb
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/arp.c:arp_constructor
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_stop_timer
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:addrconf_del_dad_work
  - net/ipv6/ndisc.c:ndisc_constructor
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:mld_ifc_stop_timer
  - net/ipv6/mcast.c:mld_gq_stop_timer
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/packet/af_packet.c:packet_release
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
c07dd73c-c07dd798: refcount_dec_checked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void refcount_dec_checked(refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (c0000000007ddbb0)
Location: lib/refcount.c:234
Inline: True
```
**Symbols:**

```
c0000000007ddbb0-c0000000007ddc24: refcount_dec_checked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void refcount_dec_checked(refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffe000464c24)
Location: lib/refcount.c:234
Inline: True
```
**Symbols:**

```
ffffffe000464c24-ffffffe000464c6a: refcount_dec_checked (STB_GLOBAL)
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
void refcount_dec_checked(refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff81524520)
Location: lib/refcount.c:234
Inline: True
```
**Symbols:**

```
ffffffff81524520-ffffffff81524557: refcount_dec_checked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void refcount_dec_checked(refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff81514800)
Location: lib/refcount.c:234
Inline: True
```
**Symbols:**

```
ffffffff81514800-ffffffff81514837: refcount_dec_checked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void refcount_dec_checked(refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff815205b0)
Location: lib/refcount.c:234
Inline: True
```
**Symbols:**

```
ffffffff815205b0-ffffffff815205e7: refcount_dec_checked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void refcount_dec_checked(refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff81539f30)
Location: lib/refcount.c:234
Inline: True
```
**Symbols:**

```
ffffffff81539f30-ffffffff81539f67: refcount_dec_checked (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
