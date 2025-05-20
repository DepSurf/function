# Function: <code>skb_dequeue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sk_buff *skb_dequeue(struct sk_buff_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81704eb0)
Location: net/core/skbuff.c:2401
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - net/core/skbuff.c:skb_queue_purge
  - net/core/dev.c:dev_cpu_callback
  - net/core/neighbour.c:pneigh_queue_purge
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:netpoll_send_udp
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/wireless/wext-core.c:wireless_nlevent_flush
```
**Symbols:**

```
ffffffff81704eb0-ffffffff81704f17: skb_dequeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sk_buff *skb_dequeue(struct sk_buff_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8176ba80)
Location: net/core/skbuff.c:2399
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - net/core/skbuff.c:skb_queue_purge
  - net/core/dev.c:dev_cpu_callback
  - net/core/neighbour.c:pneigh_queue_purge
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/wireless/wext-core.c:wireless_nlevent_flush
```
**Symbols:**

```
ffffffff8176ba80-ffffffff8176bae7: skb_dequeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sk_buff *skb_dequeue(struct sk_buff_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81798b50)
Location: net/core/skbuff.c:2375
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_reset
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - net/core/skbuff.c:skb_queue_purge
  - net/core/dev.c:dev_cpu_dead
  - net/core/neighbour.c:pneigh_queue_purge
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/wireless/wext-core.c:wireless_nlevent_flush
```
**Symbols:**

```
ffffffff81798b50-ffffffff81798bb7: skb_dequeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sk_buff *skb_dequeue(struct sk_buff_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817b7100)
Location: net/core/skbuff.c:2415
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - kernel/audit.c:kauditd_send_queue
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - net/core/skbuff.c:skb_queue_purge
  - net/core/dev.c:dev_cpu_dead
  - net/core/neighbour.c:pneigh_queue_purge
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/wireless/wext-core.c:wireless_nlevent_flush
```
**Symbols:**

```
ffffffff817b7100-ffffffff817b7167: skb_dequeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sk_buff *skb_dequeue(struct sk_buff_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8182f700)
Location: net/core/skbuff.c:2791
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - kernel/audit.c:kauditd_send_queue
  - kernel/bpf/sockmap.c:smap_tx_work
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - net/core/skbuff.c:skb_queue_purge
  - net/core/dev.c:dev_cpu_dead
  - net/core/neighbour.c:pneigh_queue_purge
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/wireless/wext-core.c:wireless_nlevent_flush
```
**Symbols:**

```
ffffffff8182f700-ffffffff8182f767: skb_dequeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sk_buff *skb_dequeue(struct sk_buff_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81879c20)
Location: net/core/skbuff.c:2807
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - kernel/audit.c:kauditd_send_queue
  - kernel/bpf/sockmap.c:smap_tx_work
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - net/core/skbuff.c:skb_queue_purge
  - net/core/dev.c:dev_cpu_dead
  - net/core/neighbour.c:pneigh_queue_purge
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/wireless/wext-core.c:wireless_nlevent_flush
```
**Symbols:**

```
ffffffff81879c20-ffffffff81879c87: skb_dequeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sk_buff *skb_dequeue(struct sk_buff_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189a890)
Location: net/core/skbuff.c:2862
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - kernel/audit.c:kauditd_send_queue
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - net/core/skbuff.c:skb_queue_purge
  - net/core/dev.c:dev_cpu_dead
  - net/core/neighbour.c:pneigh_queue_purge
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/wireless/wext-core.c:wireless_nlevent_flush
```
**Symbols:**

```
ffffffff8189a890-ffffffff8189a8f7: skb_dequeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sk_buff *skb_dequeue(struct sk_buff_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818e4eb0)
Location: net/core/skbuff.c:3028
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - kernel/audit.c:kauditd_send_queue
  - fs/io_uring.c:io_sqe_files_unregister
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - net/core/skbuff.c:skb_queue_purge
  - net/core/dev.c:dev_cpu_dead
  - net/core/neighbour.c:pneigh_queue_purge
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/wireless/wext-core.c:wireless_nlevent_flush
```
**Symbols:**

```
ffffffff818e4eb0-ffffffff818e4f19: skb_dequeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sk_buff *skb_dequeue(struct sk_buff_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81917040)
Location: net/core/skbuff.c:3034
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - kernel/audit.c:kauditd_send_queue
  - fs/io_uring.c:io_sqe_files_unregister
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - net/core/skbuff.c:skb_queue_purge
  - net/core/dev.c:dev_cpu_dead
  - net/core/neighbour.c:pneigh_queue_purge
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/wireless/wext-core.c:wireless_nlevent_flush
```
**Symbols:**

```
ffffffff81917040-ffffffff819170a9: skb_dequeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *skb_dequeue(struct sk_buff_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ea660)
Location: net/core/skbuff.c:3033
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - kernel/audit.c:kauditd_send_queue
  - fs/io_uring.c:io_sqe_files_unregister
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - net/core/skbuff.c:skb_queue_purge
  - net/core/dev.c:dev_cpu_dead
  - net/core/neighbour.c:neigh_table_clear
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/wireless/wext-core.c:wireless_nlevent_flush
```
**Symbols:**

```
ffffffff819ea660-ffffffff819ea6ce: skb_dequeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *skb_dequeue(struct sk_buff_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ea3a0)
Location: net/core/skbuff.c:3051
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - kernel/audit.c:kauditd_send_queue
  - fs/io_uring.c:io_sqe_files_unregister
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - net/core/skbuff.c:skb_queue_purge
  - net/core/dev.c:dev_cpu_dead
  - net/core/neighbour.c:neigh_table_clear
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/wireless/wext-core.c:wireless_nlevent_flush
```
**Symbols:**

```
ffffffff819ea3a0-ffffffff819ea40e: skb_dequeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *skb_dequeue(struct sk_buff_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d0960)
Location: net/core/skbuff.c:3137
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - kernel/audit.c:kauditd_send_queue
  - fs/io_uring.c:io_rsrc_file_put
  - fs/io_uring.c:io_rsrc_file_put
  - fs/io_uring.c:__io_sqe_files_unregister
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
  - net/core/skbuff.c:skb_queue_purge
  - net/core/dev.c:dev_cpu_dead
  - net/core/neighbour.c:neigh_table_clear
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
  - net/core/skmsg.c:sk_psock_stop
  - net/core/skmsg.c:sk_psock_backlog
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/wireless/wext-core.c:wireless_nlevent_flush
```
**Symbols:**

```
ffffffff819d0960-ffffffff819d09ce: skb_dequeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sk_buff *skb_dequeue(struct sk_buff_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a80560)
Location: net/core/skbuff.c:3209
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - fs/io_uring.c:io_rsrc_file_put
  - fs/io_uring.c:io_rsrc_file_put
  - fs/io_uring.c:__io_sqe_files_unregister
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
  - net/core/skbuff.c:skb_queue_purge
  - net/core/dev.c:dev_cpu_dead
  - net/core/neighbour.c:neigh_table_clear
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
  - net/core/skmsg.c:sk_psock_stop
  - net/core/skmsg.c:sk_psock_backlog
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/wireless/wext-core.c:wireless_nlevent_flush
```
**Symbols:**

```
ffffffff81a80560-ffffffff81a805ce: skb_dequeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sk_buff *skb_dequeue(struct sk_buff_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bf4c30)
Location: net/core/skbuff.c:3258
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:kauditd_send_queue
  - io_uring/io_uring.c:io_rsrc_file_put
  - io_uring/io_uring.c:__io_sqe_files_unregister
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
  - net/core/skbuff.c:skb_queue_purge
  - net/core/dev.c:dev_cpu_dead
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
  - net/core/skmsg.c:sk_psock_stop
  - net/core/skmsg.c:sk_psock_backlog
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/wireless/wext-core.c:wireless_nlevent_flush
```
**Symbols:**

```
ffffffff81bf4c30-ffffffff81bf4ca8: skb_dequeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *skb_dequeue(struct sk_buff_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da2c40)
Location: net/core/skbuff.c:3462
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:kauditd_send_queue
  - io_uring/rsrc.c:io_rsrc_file_put
  - io_uring/rsrc.c:__io_sqe_files_unregister
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
  - net/core/skbuff.c:skb_queue_purge
  - net/core/dev.c:dev_cpu_dead
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
  - net/core/skmsg.c:sk_psock_stop
  - net/core/skmsg.c:sk_psock_backlog
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/wireless/wext-core.c:wireless_nlevent_flush
```
**Symbols:**

```
ffffffff81da2c40-ffffffff81da2cb8: skb_dequeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *skb_dequeue(struct sk_buff_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e117e0)
Location: net/core/skbuff.c:3632
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:kauditd_send_queue
  - io_uring/rsrc.c:io_rsrc_file_scm_put
  - io_uring/rsrc.c:io_rsrc_file_scm_put
  - io_uring/rsrc.c:__io_sqe_files_unregister
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
  - net/core/skbuff.c:skb_queue_purge
  - net/core/dev.c:dev_cpu_dead
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_backlog
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/wireless/wext-core.c:wireless_nlevent_flush
```
**Symbols:**

```
ffffffff81e117e0-ffffffff81e11858: skb_dequeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *skb_dequeue(struct sk_buff_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ecea80)
Location: net/core/skbuff.c:3720
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:kauditd_send_queue
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - net/core/dev.c:dev_cpu_dead
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_backlog
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/wireless/wext-core.c:wireless_nlevent_flush
```
**Symbols:**

```
ffffffff81ecea80-ffffffff81eceaf8: skb_dequeue (STB_GLOBAL)
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
struct sk_buff *skb_dequeue(struct sk_buff_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb3b90)
Location: net/core/skbuff.c:3034
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - kernel/audit.c:kauditd_send_queue
  - fs/io_uring.c:io_sqe_files_unregister
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - net/core/skbuff.c:skb_queue_purge
  - net/core/dev.c:dev_cpu_dead
  - net/core/neighbour.c:pneigh_queue_purge
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/wireless/wext-core.c:wireless_nlevent_flush
```
**Symbols:**

```
ffff800010bb3b90-ffff800010bb3c6c: skb_dequeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sk_buff *skb_dequeue(struct sk_buff_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0ccda20)
Location: net/core/skbuff.c:3034
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - kernel/audit.c:kauditd_send_queue
  - fs/io_uring.c:io_sqe_files_unregister
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - net/core/skbuff.c:skb_queue_purge
  - net/core/dev.c:dev_cpu_dead
  - net/core/neighbour.c:pneigh_queue_purge
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/wireless/wext-core.c:wireless_nlevent_flush
```
**Symbols:**

```
c0ccda20-c0ccda98: skb_dequeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sk_buff *skb_dequeue(struct sk_buff_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c860b0)
Location: net/core/skbuff.c:3034
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - kernel/audit.c:kauditd_send_queue
  - fs/io_uring.c:io_sqe_files_unregister
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - net/core/skbuff.c:skb_queue_purge
  - net/core/dev.c:dev_cpu_dead
  - net/core/neighbour.c:pneigh_queue_purge
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/wireless/wext-core.c:wireless_nlevent_flush
```
**Symbols:**

```
c000000000c860b0-c000000000c86190: skb_dequeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sk_buff *skb_dequeue(struct sk_buff_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000741498)
Location: net/core/skbuff.c:3034
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - kernel/audit.c:kauditd_send_queue
  - fs/io_uring.c:io_sqe_files_unregister
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - net/core/skbuff.c:skb_queue_purge
  - net/core/dev.c:dev_cpu_dead
  - net/core/neighbour.c:pneigh_queue_purge
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/wireless/wext-core.c:wireless_nlevent_flush
```
**Symbols:**

```
ffffffe000741498-ffffffe000741506: skb_dequeue (STB_GLOBAL)
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
struct sk_buff *skb_dequeue(struct sk_buff_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818b7040)
Location: net/core/skbuff.c:3034
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - kernel/audit.c:kauditd_send_queue
  - fs/io_uring.c:io_sqe_files_unregister
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - net/core/skbuff.c:skb_queue_purge
  - net/core/dev.c:dev_cpu_dead
  - net/core/neighbour.c:pneigh_queue_purge
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/wireless/wext-core.c:wireless_nlevent_flush
```
**Symbols:**

```
ffffffff818b7040-ffffffff818b70a9: skb_dequeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sk_buff *skb_dequeue(struct sk_buff_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81870f90)
Location: net/core/skbuff.c:3034
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - kernel/audit.c:kauditd_send_queue
  - fs/io_uring.c:io_sqe_files_unregister
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - net/core/skbuff.c:skb_queue_purge
  - net/core/dev.c:dev_cpu_dead
  - net/core/neighbour.c:pneigh_queue_purge
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/wireless/wext-core.c:wireless_nlevent_flush
```
**Symbols:**

```
ffffffff81870f90-ffffffff81870ff9: skb_dequeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sk_buff *skb_dequeue(struct sk_buff_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81908040)
Location: net/core/skbuff.c:3034
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - kernel/audit.c:kauditd_send_queue
  - fs/io_uring.c:io_sqe_files_unregister
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - net/core/skbuff.c:skb_queue_purge
  - net/core/dev.c:dev_cpu_dead
  - net/core/neighbour.c:pneigh_queue_purge
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/wireless/wext-core.c:wireless_nlevent_flush
```
**Symbols:**

```
ffffffff81908040-ffffffff819080a9: skb_dequeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sk_buff *skb_dequeue(struct sk_buff_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81929080)
Location: net/core/skbuff.c:3034
Inline: False
Direct callers:
  - kernel/audit.c:kauditd_send_queue
  - kernel/audit.c:kauditd_send_queue
  - fs/io_uring.c:io_sqe_files_unregister
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - net/core/skbuff.c:skb_queue_purge
  - net/core/dev.c:dev_cpu_dead
  - net/core/neighbour.c:pneigh_queue_purge
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:queue_process
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/wireless/wext-core.c:wireless_nlevent_flush
```
**Symbols:**

```
ffffffff81929080-ffffffff819290e9: skb_dequeue (STB_GLOBAL)
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
