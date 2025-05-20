# Function: <code>seq_file_net</code>

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
In fs/proc/proc_net.c (ffffffff81286618)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - fs/proc/proc_net.c:seq_release_net
```
```
In net/core/sock.c (ffffffff81701e1d)
Location: include/linux/seq_file_net.h:21
Inline: True
```
```
In net/core/neighbour.c (ffffffff81725288)
Location: include/linux/seq_file_net.h:21
Inline: True
```
```
In net/core/net-procfs.c (ffffffff81737d3f)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/core/net-procfs.c:dev_seq_start
  - net/core/net-procfs.c:dev_seq_next
```
```
In net/netlink/af_netlink.c (ffffffff8174ace3)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_seq_next
```
```
In net/netfilter/nf_log.c (ffffffff81751a03)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:seq_show
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177b8fc)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv4/raw.c (ffffffff8178419c)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_first
```
```
In net/ipv4/udp.c (ffffffff8178743a)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
```
```
In net/ipv4/igmp.c (ffffffff817950c5)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
  - net/ipv4/igmp.c:igmp_mcf_seq_start
```
```
In net/ipv4/fib_trie.c (ffffffff8179e955)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_trie_seq_next
  - net/ipv4/fib_trie.c:fib_trie_seq_start
```
```
In net/ipv4/ping.c (ffffffff817a37f9)
Location: include/linux/seq_file_net.h:21
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/seq_file_net.h:21
Inline: True
```
```
In net/unix/af_unix.c (ffffffff817be3b5)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/anycast.c (ffffffff817c3b03)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_seq_start
```
```
In net/ipv6/addrconf.c (ffffffff817ca2cf)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:if6_seq_start
  - net/ipv6/addrconf.c:if6_seq_next
```
```
In net/ipv6/ip6_fib.c (ffffffff817d9b20)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/mcast.c (ffffffff817e9418)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff817f5caa)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_next
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_next
```
```
In net/ipv6/ip6mr.c (ffffffff817f7b23)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_start
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_start
```
```
In net/packet/af_packet.c (ffffffff81802c46)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_next
  - net/packet/af_packet.c:packet_seq_start
```
```
In net/wireless/wext-proc.c (ffffffff8180a805)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/wireless/wext-proc.c:wireless_dev_seq_next
  - net/wireless/wext-proc.c:wireless_dev_seq_start
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
In fs/proc/proc_net.c (ffffffff812b37b1)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - fs/proc/proc_net.c:seq_release_net
```
```
In net/core/sock.c (ffffffff817690c1)
Location: include/linux/seq_file_net.h:21
Inline: True
```
```
In net/core/neighbour.c (ffffffff8178ed48)
Location: include/linux/seq_file_net.h:21
Inline: True
```
```
In net/core/net-procfs.c (ffffffff817a4213)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/core/net-procfs.c:dev_seq_next
  - net/core/net-procfs.c:dev_seq_start
```
```
In net/netlink/af_netlink.c (ffffffff817b7923)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_seq_next
```
```
In net/netfilter/nf_log.c (ffffffff817bda55)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:seq_show
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817e931f)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv4/raw.c (ffffffff817f1734)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_first
```
```
In net/ipv4/udp.c (ffffffff817f46b6)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
```
```
In net/ipv4/igmp.c (ffffffff81803578)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
```
```
In net/ipv4/fib_trie.c (ffffffff8180c545)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_trie_seq_next
  - net/ipv4/fib_trie.c:fib_trie_seq_start
```
```
In net/ipv4/ping.c (ffffffff81810e49)
Location: include/linux/seq_file_net.h:21
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/seq_file_net.h:21
Inline: True
```
```
In net/unix/af_unix.c (ffffffff8182b345)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/anycast.c (ffffffff81830bd3)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_seq_start
```
```
In net/ipv6/addrconf.c (ffffffff818374ca)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_start
```
```
In net/ipv6/ip6_fib.c (ffffffff81847df6)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
```
```
In net/ipv6/mcast.c (ffffffff81857c68)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_start
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81864e5c)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_next
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_next
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
```
```
In net/ipv6/ip6mr.c (ffffffff81868123)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_start
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_start
```
```
In net/packet/af_packet.c (ffffffff81873fd6)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_next
  - net/packet/af_packet.c:packet_seq_start
```
```
In net/wireless/wext-proc.c (ffffffff8187c365)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/wireless/wext-proc.c:wireless_dev_seq_next
  - net/wireless/wext-proc.c:wireless_dev_seq_start
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
In fs/proc/proc_net.c (ffffffff812c9051)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - fs/proc/proc_net.c:seq_release_net
```
```
In net/core/sock.c (ffffffff81795fd1)
Location: include/linux/seq_file_net.h:21
Inline: True
```
```
In net/core/neighbour.c (ffffffff817bc618)
Location: include/linux/seq_file_net.h:21
Inline: True
```
```
In net/core/net-procfs.c (ffffffff817d2c93)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/core/net-procfs.c:dev_seq_next
  - net/core/net-procfs.c:dev_seq_start
```
```
In net/netlink/af_netlink.c (ffffffff817e73a0)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_seq_next
```
```
In net/netfilter/nf_log.c (ffffffff817ed335)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:seq_show
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181952c)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv4/raw.c (ffffffff818224c1)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_first
```
```
In net/ipv4/udp.c (ffffffff81825783)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
```
```
In net/ipv4/igmp.c (ffffffff81834512)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
```
```
In net/ipv4/fib_trie.c (ffffffff8183d7c2)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_trie_seq_next
  - net/ipv4/fib_trie.c:fib_trie_seq_start
```
```
In net/ipv4/ping.c (ffffffff81842359)
Location: include/linux/seq_file_net.h:21
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/seq_file_net.h:21
Inline: True
```
```
In net/unix/af_unix.c (ffffffff8185cd75)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/anycast.c (ffffffff81862640)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_seq_start
```
```
In net/ipv6/addrconf.c (ffffffff81868fb7)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_start
```
```
In net/ipv6/ip6_fib.c (ffffffff81879c33)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
```
```
In net/ipv6/mcast.c (ffffffff81889a52)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_start
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81897539)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_next
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_next
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
```
```
In net/ipv6/ip6mr.c (ffffffff8189af80)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_start
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_start
```
```
In net/packet/af_packet.c (ffffffff818a8566)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_next
  - net/packet/af_packet.c:packet_seq_start
```
```
In net/wireless/wext-proc.c (ffffffff818b0c25)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/wireless/wext-proc.c:wireless_dev_seq_next
  - net/wireless/wext-proc.c:wireless_dev_seq_start
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
In fs/proc/proc_net.c (ffffffff812d6361)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - fs/proc/proc_net.c:seq_release_net
```
```
In net/core/sock.c (ffffffff817b422e)
Location: include/linux/seq_file_net.h:21
Inline: True
```
```
In net/core/neighbour.c (ffffffff817dacc8)
Location: include/linux/seq_file_net.h:21
Inline: True
```
```
In net/core/net-procfs.c (ffffffff817f1ff3)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/core/net-procfs.c:dev_seq_next
  - net/core/net-procfs.c:dev_seq_start
```
```
In net/netlink/af_netlink.c (ffffffff818070b2)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_seq_next
```
```
In net/netfilter/nf_log.c (ffffffff8180dc75)
Location: include/linux/seq_file_net.h:21
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183a6ec)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv4/raw.c (ffffffff81843130)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_first
```
```
In net/ipv4/udp.c (ffffffff818477b3)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
```
```
In net/ipv4/igmp.c (ffffffff81855fe2)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
```
```
In net/ipv4/fib_trie.c (ffffffff8185efc2)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_trie_seq_next
  - net/ipv4/fib_trie.c:fib_trie_seq_start
```
```
In net/ipv4/ping.c (ffffffff81863c29)
Location: include/linux/seq_file_net.h:21
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/seq_file_net.h:21
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81881529)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/anycast.c (ffffffff81886e10)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_seq_start
```
```
In net/ipv6/addrconf.c (ffffffff8188d8c7)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_start
```
```
In net/ipv6/ip6_fib.c (ffffffff8189f693)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
```
```
In net/ipv6/mcast.c (ffffffff818b0282)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_start
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff818bd87f)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
```
```
In net/ipv6/ip6mr.c (ffffffff818c0ff0)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_start
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_start
```
```
In net/packet/af_packet.c (ffffffff818ceda6)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_next
  - net/packet/af_packet.c:packet_seq_start
```
```
In net/wireless/wext-proc.c (ffffffff818d75b5)
Location: include/linux/seq_file_net.h:21
Inline: True
Inline callers:
  - net/wireless/wext-proc.c:wireless_dev_seq_next
  - net/wireless/wext-proc.c:wireless_dev_seq_start
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
In fs/proc/proc_net.c (ffffffff812fabb8)
Location: include/linux/seq_file_net.h:22
Inline: True
Inline callers:
  - fs/proc/proc_net.c:seq_release_net
```
```
In net/core/sock.c (ffffffff8182c471)
Location: include/linux/seq_file_net.h:22
Inline: True
```
```
In net/core/neighbour.c (ffffffff81855468)
Location: include/linux/seq_file_net.h:22
Inline: True
```
```
In net/core/net-procfs.c (ffffffff8186d5b3)
Location: include/linux/seq_file_net.h:22
Inline: True
Inline callers:
  - net/core/net-procfs.c:dev_seq_next
  - net/core/net-procfs.c:dev_seq_start
```
```
In net/netlink/af_netlink.c (ffffffff81885e62)
Location: include/linux/seq_file_net.h:22
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_seq_next
```
```
In net/netfilter/nf_log.c (ffffffff8188d155)
Location: include/linux/seq_file_net.h:22
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818ba1ec)
Location: include/linux/seq_file_net.h:22
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv4/raw.c (ffffffff818c2af0)
Location: include/linux/seq_file_net.h:22
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_first
```
```
In net/ipv4/udp.c (ffffffff818c7213)
Location: include/linux/seq_file_net.h:22
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
```
```
In net/ipv4/igmp.c (ffffffff818d5e72)
Location: include/linux/seq_file_net.h:22
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
```
```
In net/ipv4/fib_trie.c (ffffffff818df022)
Location: include/linux/seq_file_net.h:22
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_trie_seq_next
  - net/ipv4/fib_trie.c:fib_trie_seq_start
```
```
In net/ipv4/ping.c (ffffffff818e3d69)
Location: include/linux/seq_file_net.h:22
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/seq_file_net.h:22
Inline: True
```
```
In net/unix/af_unix.c (ffffffff819026c9)
Location: include/linux/seq_file_net.h:22
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/anycast.c (ffffffff81908030)
Location: include/linux/seq_file_net.h:22
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_seq_start
```
```
In net/ipv6/addrconf.c (ffffffff8190e967)
Location: include/linux/seq_file_net.h:22
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_start
```
```
In net/ipv6/ip6_fib.c (ffffffff81921c93)
Location: include/linux/seq_file_net.h:22
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
```
```
In net/ipv6/mcast.c (ffffffff81933092)
Location: include/linux/seq_file_net.h:22
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_start
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff8194091f)
Location: include/linux/seq_file_net.h:22
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
```
```
In net/ipv6/ip6mr.c (ffffffff81944210)
Location: include/linux/seq_file_net.h:22
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_start
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_start
```
```
In net/packet/af_packet.c (ffffffff81953c96)
Location: include/linux/seq_file_net.h:22
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_next
  - net/packet/af_packet.c:packet_seq_start
```
```
In net/wireless/wext-proc.c (ffffffff8195d195)
Location: include/linux/seq_file_net.h:22
Inline: True
Inline callers:
  - net/wireless/wext-proc.c:wireless_dev_seq_next
  - net/wireless/wext-proc.c:wireless_dev_seq_start
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
In fs/proc/proc_net.c (ffffffff813280e5)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - fs/proc/proc_net.c:seq_release_net
```
```
In net/core/sock.c (ffffffff81876684)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/core/neighbour.c (ffffffff818a09f2)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/core/net-procfs.c (ffffffff818be7e3)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/core/net-procfs.c:dev_seq_next
  - net/core/net-procfs.c:dev_seq_start
```
```
In net/netlink/af_netlink.c (ffffffff818d97d3)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_seq_next
```
```
In net/netfilter/nf_log.c (ffffffff818e0b85)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8190eec6)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv4/raw.c (ffffffff81918d96)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_get_first
```
```
In net/ipv4/udp.c (ffffffff8191c676)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
```
```
In net/ipv4/igmp.c (ffffffff8192dc52)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
```
```
In net/ipv4/fib_trie.c (ffffffff8193604a)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_start
  - net/ipv4/fib_trie.c:fib_trie_seq_next
  - net/ipv4/fib_trie.c:fib_trie_seq_start
```
```
In net/ipv4/ping.c (ffffffff8193a615)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8193f569)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_seq_start
  - net/ipv4/ipmr.c:ipmr_mfc_seq_start
  - net/ipv4/ipmr.c:ipmr_vif_seq_start
  - net/ipv4/ipmr.c:ipmr_vif_seq_start
```
```
In net/ipv4/ipmr_base.c (ffffffff819446ee)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/unix/af_unix.c (ffffffff81958be5)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/anycast.c (ffffffff8195f1b0)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_seq_start
```
```
In net/ipv6/addrconf.c (ffffffff81965a8a)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_start
```
```
In net/ipv6/ip6_fib.c (ffffffff8197a10a)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
```
```
In net/ipv6/mcast.c (ffffffff8198d002)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_start
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff819997f6)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
```
```
In net/ipv6/ip6mr.c (ffffffff8199d019)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_start
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_start
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_start
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_start
```
```
In net/packet/af_packet.c (ffffffff819ad6a5)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_next
  - net/packet/af_packet.c:packet_seq_start
```
```
In net/wireless/wext-proc.c (ffffffff819b69f5)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/wireless/wext-proc.c:wireless_dev_seq_next
  - net/wireless/wext-proc.c:wireless_dev_seq_start
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
In fs/proc/proc_net.c (ffffffff8133f2c5)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - fs/proc/proc_net.c:seq_release_net
```
```
In net/core/sock.c (ffffffff81896f14)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/core/neighbour.c (ffffffff818c3372)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/core/net-procfs.c (ffffffff818e5bc3)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/core/net-procfs.c:dev_seq_next
  - net/core/net-procfs.c:dev_seq_start
```
```
In net/netlink/af_netlink.c (ffffffff81905fc3)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_seq_next
```
```
In net/netfilter/nf_log.c (ffffffff8190d6f5)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193d2f6)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv4/raw.c (ffffffff819475e6)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_get_first
```
```
In net/ipv4/udp.c (ffffffff8194ac16)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
```
```
In net/ipv4/igmp.c (ffffffff8195b6e2)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
```
```
In net/ipv4/fib_trie.c (ffffffff81965a4a)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_start
  - net/ipv4/fib_trie.c:fib_trie_seq_next
  - net/ipv4/fib_trie.c:fib_trie_seq_start
```
```
In net/ipv4/ping.c (ffffffff81969aa5)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8196f309)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_seq_start
  - net/ipv4/ipmr.c:ipmr_mfc_seq_start
  - net/ipv4/ipmr.c:ipmr_vif_seq_start
  - net/ipv4/ipmr.c:ipmr_vif_seq_start
```
```
In net/ipv4/ipmr_base.c (ffffffff8197498e)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/unix/af_unix.c (ffffffff8198d795)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/anycast.c (ffffffff81993d40)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_seq_start
```
```
In net/ipv6/addrconf.c (ffffffff8199ae7a)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_start
```
```
In net/ipv6/ip6_fib.c (ffffffff819afcfa)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
```
```
In net/ipv6/mcast.c (ffffffff819c21d2)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_start
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff819d0146)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
```
```
In net/ipv6/ip6mr.c (ffffffff819d3b79)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_start
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_start
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_start
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_start
```
```
In net/packet/af_packet.c (ffffffff819e4015)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_next
  - net/packet/af_packet.c:packet_seq_start
```
```
In net/wireless/wext-proc.c (ffffffff819edcb5)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/wireless/wext-proc.c:wireless_dev_seq_next
  - net/wireless/wext-proc.c:wireless_dev_seq_start
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
In fs/proc/proc_net.c (ffffffff813675f5)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - fs/proc/proc_net.c:seq_release_net
```
```
In net/core/sock.c (ffffffff818e11d0)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/core/neighbour.c (ffffffff8190f502)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/core/net-procfs.c (ffffffff81935493)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/core/net-procfs.c:dev_seq_next
  - net/core/net-procfs.c:dev_seq_start
```
```
In net/netlink/af_netlink.c (ffffffff81967243)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_seq_next
```
```
In net/netfilter/nf_log.c (ffffffff8196f325)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a1726)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv4/raw.c (ffffffff819abc79)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_get_first
```
```
In net/ipv4/udp.c (ffffffff819af25d)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
```
```
In net/ipv4/igmp.c (ffffffff819c03b1)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
```
```
In net/ipv4/fib_trie.c (ffffffff819cbab5)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_start
  - net/ipv4/fib_trie.c:fib_trie_seq_next
  - net/ipv4/fib_trie.c:fib_trie_seq_start
```
```
In net/ipv4/ping.c (ffffffff819d0775)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819d89f9)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_seq_start
  - net/ipv4/ipmr.c:ipmr_mfc_seq_start
  - net/ipv4/ipmr.c:ipmr_vif_seq_start
  - net/ipv4/ipmr.c:ipmr_vif_seq_start
```
```
In net/ipv4/ipmr_base.c (ffffffff819de4be)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/unix/af_unix.c (ffffffff819f8eb8)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/anycast.c (ffffffff819ff7ed)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_seq_start
```
```
In net/ipv6/addrconf.c (ffffffff81a06dca)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_start
```
```
In net/ipv6/ip6_fib.c (ffffffff81a1de5a)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
```
```
In net/ipv6/mcast.c (ffffffff81a30fd1)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_start
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a3ee66)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
```
```
In net/ipv6/ip6mr.c (ffffffff81a42bf9)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_start
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_start
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_start
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_start
```
```
In net/packet/af_packet.c (ffffffff81a52f05)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_next
  - net/packet/af_packet.c:packet_seq_start
```
```
In net/wireless/wext-proc.c (ffffffff81a5cef5)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/wireless/wext-proc.c:wireless_dev_seq_next
  - net/wireless/wext-proc.c:wireless_dev_seq_start
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
In fs/proc/proc_net.c (ffffffff8137f875)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - fs/proc/proc_net.c:seq_release_net
```
```
In net/core/sock.c (ffffffff81913390)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/core/neighbour.c (ffffffff81941b72)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/core/net-procfs.c (ffffffff81968253)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/core/net-procfs.c:dev_seq_next
  - net/core/net-procfs.c:dev_seq_start
```
```
In net/netlink/af_netlink.c (ffffffff8199dcd3)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_seq_next
```
```
In net/netfilter/nf_log.c (ffffffff819a5d55)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819d83d6)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv4/raw.c (ffffffff819e2929)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_get_first
```
```
In net/ipv4/udp.c (ffffffff819e5f6d)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
```
```
In net/ipv4/igmp.c (ffffffff819f6f51)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
```
```
In net/ipv4/fib_trie.c (ffffffff81a02605)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_start
  - net/ipv4/fib_trie.c:fib_trie_seq_next
  - net/ipv4/fib_trie.c:fib_trie_seq_start
```
```
In net/ipv4/ping.c (ffffffff81a072c5)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a0f839)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_seq_start
  - net/ipv4/ipmr.c:ipmr_mfc_seq_start
  - net/ipv4/ipmr.c:ipmr_vif_seq_start
  - net/ipv4/ipmr.c:ipmr_vif_seq_start
```
```
In net/ipv4/ipmr_base.c (ffffffff81a1555e)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/unix/af_unix.c (ffffffff81a2fb08)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/anycast.c (ffffffff81a363cd)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_seq_start
```
```
In net/ipv6/addrconf.c (ffffffff81a3d93a)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_start
```
```
In net/ipv6/ip6_fib.c (ffffffff81a54aba)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
```
```
In net/ipv6/mcast.c (ffffffff81a67b21)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_start
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a75ad6)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
```
```
In net/ipv6/ip6mr.c (ffffffff81a79859)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_start
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_start
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_start
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_start
```
```
In net/packet/af_packet.c (ffffffff81a89ae5)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_next
  - net/packet/af_packet.c:packet_seq_start
```
```
In net/wireless/wext-proc.c (ffffffff81a93b05)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/wireless/wext-proc.c:wireless_dev_seq_next
  - net/wireless/wext-proc.c:wireless_dev_seq_start
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
In fs/proc/proc_net.c (ffffffff813c9b85)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - fs/proc/proc_net.c:seq_release_net
```
```
In net/core/sock.c (ffffffff819e55f7)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/core/sock.c:proto_seq_printf
```
```
In net/core/neighbour.c (ffffffff81a11bb5)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/core/net-procfs.c (ffffffff81a3ba36)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/core/net-procfs.c:dev_seq_next
  - net/core/net-procfs.c:dev_seq_start
```
```
In net/netlink/af_netlink.c (ffffffff81a76ba3)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_seq_next
```
```
In net/netfilter/nf_log.c (ffffffff81a8e785)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:seq_show
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac4389)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_first
  - net/ipv4/tcp_ipv4.c:listening_get_next
```
```
In net/ipv4/raw.c (ffffffff81acff29)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_get_first
```
```
In net/ipv4/udp.c (ffffffff81ad25e9)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_get_first
```
```
In net/ipv4/igmp.c (ffffffff81ae69b1)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
```
```
In net/ipv4/fib_trie.c (ffffffff81af0c55)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_start
  - net/ipv4/fib_trie.c:fib_trie_seq_next
  - net/ipv4/fib_trie.c:fib_trie_seq_start
```
```
In net/ipv4/ping.c (ffffffff81af6c35)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81b00815)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_seq_start
  - net/ipv4/ipmr.c:ipmr_mfc_seq_start
  - net/ipv4/ipmr.c:ipmr_vif_seq_start
  - net/ipv4/ipmr.c:ipmr_vif_seq_start
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81b23b8b)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/anycast.c (ffffffff81b2b490)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_get_idx
```
```
In net/ipv6/addrconf.c (ffffffff81b33a10)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:if6_seq_start
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4c07f)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
```
```
In net/ipv6/mcast.c (ffffffff81b61ca1)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_get_idx
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b70859)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_next
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
```
```
In net/ipv6/ip6mr.c (ffffffff81b73a85)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_start
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_start
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_start
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_start
```
```
In net/packet/af_packet.c (ffffffff81b85065)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_next
  - net/packet/af_packet.c:packet_seq_start
```
```
In net/wireless/wext-proc.c (ffffffff81b8f065)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/wireless/wext-proc.c:wireless_dev_seq_next
  - net/wireless/wext-proc.c:wireless_dev_seq_start
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
In fs/proc/proc_net.c (ffffffff813db855)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - fs/proc/proc_net.c:seq_release_net
```
```
In net/core/sock.c (ffffffff819e4ef1)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/core/sock.c:proto_seq_printf
```
```
In net/core/neighbour.c (ffffffff81a11f15)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/core/net-procfs.c (ffffffff81a3e136)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/core/net-procfs.c:dev_seq_next
  - net/core/net-procfs.c:dev_seq_start
```
```
In net/netlink/af_netlink.c (ffffffff81a7f923)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_seq_next
```
```
In net/netfilter/nf_log.c (ffffffff81a987f5)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:seq_show
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad0d15)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81adbea9)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_get_first
```
```
In net/ipv4/udp.c (ffffffff81adecb5)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81af3881)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
```
```
In net/ipv4/fib_trie.c (ffffffff81afdc05)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_start
  - net/ipv4/fib_trie.c:fib_trie_seq_next
  - net/ipv4/fib_trie.c:fib_trie_seq_start
```
```
In net/ipv4/ping.c (ffffffff81b03ac5)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81b0e8f5)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_seq_start
  - net/ipv4/ipmr.c:ipmr_mfc_seq_start
  - net/ipv4/ipmr.c:ipmr_vif_seq_start
  - net/ipv4/ipmr.c:ipmr_vif_seq_start
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81b3255b)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/anycast.c (ffffffff81b39eb0)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_get_idx
```
```
In net/ipv6/addrconf.c (ffffffff81b42350)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:if6_seq_start
```
```
In net/ipv6/ip6_fib.c (ffffffff81b5acbf)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
```
```
In net/ipv6/mcast.c (ffffffff81b70441)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_get_idx
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b7f4a9)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_next
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
```
```
In net/ipv6/ip6mr.c (ffffffff81b827f5)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_start
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_start
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_start
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_start
```
```
In net/packet/af_packet.c (ffffffff81b949b8)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_next
  - net/packet/af_packet.c:packet_seq_start
```
```
In net/wireless/wext-proc.c (ffffffff81b9ecc5)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/wireless/wext-proc.c:wireless_dev_seq_next
  - net/wireless/wext-proc.c:wireless_dev_seq_start
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
In fs/proc/proc_net.c (ffffffff813e2705)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - fs/proc/proc_net.c:seq_release_net
```
```
In net/core/sock.c (ffffffff819cb174)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/core/sock.c:proto_seq_printf
```
```
In net/core/neighbour.c (ffffffff819f8b75)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/core/net-procfs.c (ffffffff81a25206)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/core/net-procfs.c:dev_seq_next
  - net/core/net-procfs.c:dev_seq_start
```
```
In net/netlink/af_netlink.c (ffffffff81a688e3)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_seq_next
```
```
In net/netfilter/nf_log.c (ffffffff81a83b35)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:seq_show
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abbe0a)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv4/raw.c (ffffffff81ac6d49)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_get_first
```
```
In net/ipv4/udp.c (ffffffff81ac9d8a)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
```
```
In net/ipv4/igmp.c (ffffffff81adeee1)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
```
```
In net/ipv4/fib_trie.c (ffffffff81ae9415)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_start
  - net/ipv4/fib_trie.c:fib_trie_seq_next
  - net/ipv4/fib_trie.c:fib_trie_seq_start
```
```
In net/ipv4/ping.c (ffffffff81aef2e5)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81afc5e5)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_seq_start
  - net/ipv4/ipmr.c:ipmr_mfc_seq_start
  - net/ipv4/ipmr.c:ipmr_vif_seq_start
  - net/ipv4/ipmr.c:ipmr_vif_seq_start
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81b2008b)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/anycast.c (ffffffff81b27bbd)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_seq_start
```
```
In net/ipv6/addrconf.c (ffffffff81b30201)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_start
```
```
In net/ipv6/ip6_fib.c (ffffffff81b48f3f)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
```
```
In net/ipv6/mcast.c (ffffffff81b5d659)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_start
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b6dfc9)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_next
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
```
```
In net/ipv6/ip6mr.c (ffffffff81b71455)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_start
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_start
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_start
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_start
```
```
In net/packet/af_packet.c (ffffffff81b83a98)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_next
  - net/packet/af_packet.c:packet_seq_start
```
```
In net/wireless/wext-proc.c (ffffffff81b8ddc5)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/wireless/wext-proc.c:wireless_dev_seq_next
  - net/wireless/wext-proc.c:wireless_dev_seq_start
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
In fs/proc/proc_net.c (ffffffff81434215)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - fs/proc/proc_net.c:seq_release_net
```
```
In net/core/sock.c (ffffffff81a7a797)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/core/sock.c:proto_seq_printf
```
```
In net/core/neighbour.c (ffffffff81aaa755)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/core/net-procfs.c (ffffffff81ad9de7)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/core/net-procfs.c:ptype_seq_next
  - net/core/net-procfs.c:dev_seq_next
  - net/core/net-procfs.c:dev_seq_start
```
```
In net/netlink/af_netlink.c (ffffffff81b21d33)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_seq_next
```
```
In net/netfilter/nf_log.c (ffffffff81b3d8f5)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:seq_show
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7b9d3)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_first
  - net/ipv4/tcp_ipv4.c:listening_get_next
  - net/ipv4/tcp_ipv4.c:listening_get_first
```
```
In net/ipv4/raw.c (ffffffff81b85569)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_get_first
```
```
In net/ipv4/udp.c (ffffffff81b8861a)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
```
```
In net/ipv4/igmp.c (ffffffff81b9e3c1)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
```
```
In net/ipv4/fib_trie.c (ffffffff81baa295)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_start
  - net/ipv4/fib_trie.c:fib_trie_seq_next
  - net/ipv4/fib_trie.c:fib_trie_seq_start
```
```
In net/ipv4/ping.c (ffffffff81baf6c5)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81bbdcd5)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_seq_start
  - net/ipv4/ipmr.c:ipmr_mfc_seq_start
  - net/ipv4/ipmr.c:ipmr_vif_seq_start
  - net/ipv4/ipmr.c:ipmr_vif_seq_start
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81be4f15)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/anycast.c (ffffffff81bedafd)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_seq_start
```
```
In net/ipv6/addrconf.c (ffffffff81bf6629)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_start
```
```
In net/ipv6/ip6_fib.c (ffffffff81c1024f)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
```
```
In net/ipv6/mcast.c (ffffffff81c24906)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_start
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81c35ee7)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_next
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
```
```
In net/ipv6/ip6mr.c (ffffffff81c3b8a5)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_start
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_start
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_start
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_start
```
```
In net/packet/af_packet.c (ffffffff81c4fba8)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_next
  - net/packet/af_packet.c:packet_seq_start
```
```
In net/wireless/wext-proc.c (ffffffff81c5a235)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/wireless/wext-proc.c:wireless_dev_seq_next
  - net/wireless/wext-proc.c:wireless_dev_seq_start
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
In net/core/sock.c (ffffffff81bee319)
Location: include/linux/seq_file_net.h:17
Inline: True
Inline callers:
  - net/core/sock.c:proto_seq_printf
```
```
In net/core/neighbour.c (ffffffff81c23595)
Location: include/linux/seq_file_net.h:17
Inline: True
```
```
In net/core/net-procfs.c (ffffffff81c5b183)
Location: include/linux/seq_file_net.h:17
Inline: True
Inline callers:
  - net/core/net-procfs.c:ptype_seq_next
  - net/core/net-procfs.c:dev_seq_next
  - net/core/net-procfs.c:dev_seq_start
```
```
In net/netlink/af_netlink.c (ffffffff81caa5e3)
Location: include/linux/seq_file_net.h:17
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_seq_next
```
```
In net/netfilter/nf_log.c (ffffffff81cc9f05)
Location: include/linux/seq_file_net.h:17
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:seq_show
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0abd4)
Location: include/linux/seq_file_net.h:17
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_first
  - net/ipv4/tcp_ipv4.c:listening_get_next
  - net/ipv4/tcp_ipv4.c:listening_get_first
```
```
In net/ipv4/raw.c (ffffffff81d15afb)
Location: include/linux/seq_file_net.h:17
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_get_first
```
```
In net/ipv4/udp.c (ffffffff81d19a53)
Location: include/linux/seq_file_net.h:17
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
```
```
In net/ipv4/igmp.c (ffffffff81d306db)
Location: include/linux/seq_file_net.h:17
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
```
```
In net/ipv4/fib_trie.c (ffffffff81d3cecd)
Location: include/linux/seq_file_net.h:17
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_start
  - net/ipv4/fib_trie.c:fib_trie_seq_next
  - net/ipv4/fib_trie.c:fib_trie_seq_start
```
```
In net/ipv4/ping.c (ffffffff81d42ba5)
Location: include/linux/seq_file_net.h:17
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81d525e5)
Location: include/linux/seq_file_net.h:17
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_seq_start
  - net/ipv4/ipmr.c:ipmr_mfc_seq_start
  - net/ipv4/ipmr.c:ipmr_vif_seq_start
  - net/ipv4/ipmr.c:ipmr_vif_seq_start
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/linux/seq_file_net.h:17
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81d7ddc8)
Location: include/linux/seq_file_net.h:17
Inline: True
Inline callers:
  - net/unix/af_unix.c:bpf_iter_unix_batch
  - net/unix/af_unix.c:unix_seq_next
  - net/unix/af_unix.c:unix_get_first
```
```
In net/ipv6/anycast.c (ffffffff81d86008)
Location: include/linux/seq_file_net.h:17
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_seq_start
```
```
In net/ipv6/addrconf.c (ffffffff81d8f90a)
Location: include/linux/seq_file_net.h:17
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_start
```
```
In net/ipv6/ip6_fib.c (ffffffff81dab457)
Location: include/linux/seq_file_net.h:17
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
```
```
In net/ipv6/mcast.c (ffffffff81dc1b75)
Location: include/linux/seq_file_net.h:17
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_start
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81dd3981)
Location: include/linux/seq_file_net.h:17
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_next
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
```
```
In net/ipv6/ip6mr.c (ffffffff81dd9a15)
Location: include/linux/seq_file_net.h:17
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_start
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_start
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_start
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_start
```
```
In net/packet/af_packet.c (ffffffff81df0688)
Location: include/linux/seq_file_net.h:17
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_next
  - net/packet/af_packet.c:packet_seq_start
```
```
In net/wireless/wext-proc.c (ffffffff81dfbb35)
Location: include/linux/seq_file_net.h:17
Inline: True
Inline callers:
  - net/wireless/wext-proc.c:wireless_dev_seq_next
  - net/wireless/wext-proc.c:wireless_dev_seq_start
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
In net/core/sock.c (ffffffff81d99c83)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/core/sock.c:proto_seq_printf
```
```
In net/core/neighbour.c (ffffffff81dd5585)
Location: include/linux/seq_file_net.h:18
Inline: True
```
```
In net/core/net-procfs.c (ffffffff81e113f3)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/core/net-procfs.c:ptype_seq_next
  - net/core/net-procfs.c:dev_seq_next
  - net/core/net-procfs.c:dev_seq_start
```
```
In net/netlink/af_netlink.c (ffffffff81e67763)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_seq_next
```
```
In net/netfilter/nf_log.c (ffffffff81e89b75)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:seq_show
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed0385)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:tcp_seek_last_pos
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_first
  - net/ipv4/tcp_ipv4.c:established_get_first
  - net/ipv4/tcp_ipv4.c:listening_get_next
  - net/ipv4/tcp_ipv4.c:listening_get_first
  - net/ipv4/tcp_ipv4.c:listening_get_first
```
```
In net/ipv4/raw.c (ffffffff81edbecb)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_get_first
```
```
In net/ipv4/udp.c (ffffffff81ee252a)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/ipv4/udp.c:bpf_iter_udp_seq_stop
  - net/ipv4/udp.c:udp_get_next
```
```
In net/ipv4/igmp.c (ffffffff81ef883b)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
```
```
In net/ipv4/fib_trie.c (ffffffff81f05b4d)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_start
  - net/ipv4/fib_trie.c:fib_trie_seq_next
  - net/ipv4/fib_trie.c:fib_trie_seq_start
```
```
In net/ipv4/ping.c (ffffffff81f0bb65)
Location: include/linux/seq_file_net.h:18
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f1c8d5)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_seq_start
  - net/ipv4/ipmr.c:ipmr_mfc_seq_start
  - net/ipv4/ipmr.c:ipmr_vif_seq_start
  - net/ipv4/ipmr.c:ipmr_vif_seq_start
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/linux/seq_file_net.h:18
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81f4b1cf)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/unix/af_unix.c:bpf_iter_unix_batch
  - net/unix/af_unix.c:unix_seq_next
  - net/unix/af_unix.c:unix_get_first
  - net/unix/af_unix.c:unix_get_first
```
```
In net/ipv6/anycast.c (ffffffff81f53b28)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_seq_start
```
```
In net/ipv6/addrconf.c (ffffffff81f5db4a)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_start
```
```
In net/ipv6/ip6_fib.c (ffffffff81f7ad97)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
```
```
In net/ipv6/mcast.c (ffffffff81f924b5)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_start
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81fa4f71)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_next
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
```
```
In net/ipv6/ip6mr.c (ffffffff81fab685)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_start
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_start
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_start
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_start
```
```
In net/packet/af_packet.c (ffffffff81fc4818)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_next
  - net/packet/af_packet.c:packet_seq_start
```
```
In net/wireless/wext-proc.c (ffffffff81fd0405)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/wireless/wext-proc.c:wireless_dev_seq_next
  - net/wireless/wext-proc.c:wireless_dev_seq_start
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
In net/core/sock.c (ffffffff81e07fb2)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/core/sock.c:proto_seq_printf
```
```
In net/core/neighbour.c (ffffffff81e463a5)
Location: include/linux/seq_file_net.h:18
Inline: True
```
```
In net/core/net-procfs.c (ffffffff81e84d03)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/core/net-procfs.c:ptype_seq_next
  - net/core/net-procfs.c:dev_seq_next
  - net/core/net-procfs.c:dev_seq_start
```
```
In net/netlink/af_netlink.c (ffffffff81ec3543)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_seq_next
```
```
In net/netfilter/nf_log.c (ffffffff81ee7b75)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:seq_show
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2f035)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:tcp_seek_last_pos
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_first
  - net/ipv4/tcp_ipv4.c:established_get_first
  - net/ipv4/tcp_ipv4.c:listening_get_next
  - net/ipv4/tcp_ipv4.c:listening_get_first
  - net/ipv4/tcp_ipv4.c:listening_get_first
```
```
In net/ipv4/raw.c (ffffffff81f3af1b)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_get_first
```
```
In net/ipv4/udp.c (ffffffff81f4031d)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/ipv4/udp.c:bpf_iter_udp_batch
  - net/ipv4/udp.c:bpf_iter_udp_batch
  - net/ipv4/udp.c:udp_seq_stop
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_get_first
  - net/ipv4/udp.c:udp_get_first
```
```
In net/ipv4/igmp.c (ffffffff81f582ab)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
```
```
In net/ipv4/fib_trie.c (ffffffff81f6559d)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_start
  - net/ipv4/fib_trie.c:fib_trie_seq_next
  - net/ipv4/fib_trie.c:fib_trie_seq_start
```
```
In net/ipv4/ping.c (ffffffff81f6b819)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_next
```
```
In net/ipv4/ipmr.c (ffffffff81f7c3b5)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_seq_start
  - net/ipv4/ipmr.c:ipmr_mfc_seq_start
  - net/ipv4/ipmr.c:ipmr_vif_seq_start
  - net/ipv4/ipmr.c:ipmr_vif_seq_start
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/linux/seq_file_net.h:18
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81faaf6f)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/unix/af_unix.c:bpf_iter_unix_batch
  - net/unix/af_unix.c:unix_seq_next
  - net/unix/af_unix.c:unix_get_first
  - net/unix/af_unix.c:unix_get_first
```
```
In net/ipv6/anycast.c (ffffffff81fb3518)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_seq_start
```
```
In net/ipv6/addrconf.c (ffffffff81fbd84a)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_start
```
```
In net/ipv6/ip6_fib.c (ffffffff81fdafa7)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
```
```
In net/ipv6/mcast.c (ffffffff81ff2e25)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_start
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff82005901)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_next
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
```
```
In net/ipv6/ip6mr.c (ffffffff8200be25)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_start
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_start
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_start
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_start
```
```
In net/packet/af_packet.c (ffffffff82025738)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_next
  - net/packet/af_packet.c:packet_seq_start
```
```
In net/wireless/wext-proc.c (ffffffff8204bec5)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/wireless/wext-proc.c:wireless_dev_seq_next
  - net/wireless/wext-proc.c:wireless_dev_seq_start
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
In net/core/sock.c (ffffffff81ec49f2)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/core/sock.c:proto_seq_printf
```
```
In net/core/neighbour.c (ffffffff81f05045)
Location: include/linux/seq_file_net.h:18
Inline: True
```
```
In net/core/net-procfs.c (ffffffff81f46ced)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/core/net-procfs.c:ptype_seq_next
  - net/core/net-procfs.c:dev_seq_next
  - net/core/net-procfs.c:dev_seq_start
```
```
In net/netlink/af_netlink.c (ffffffff81f86963)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_seq_next
```
```
In net/netfilter/nf_log.c (ffffffff81fab985)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:seq_show
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff4585)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:tcp_seek_last_pos
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_first
  - net/ipv4/tcp_ipv4.c:established_get_first
  - net/ipv4/tcp_ipv4.c:listening_get_next
  - net/ipv4/tcp_ipv4.c:listening_get_first
  - net/ipv4/tcp_ipv4.c:listening_get_first
```
```
In net/ipv4/raw.c (ffffffff8200102b)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_get_first
```
```
In net/ipv4/udp.c (ffffffff82005ca0)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/ipv4/udp.c:bpf_iter_udp_batch
  - net/ipv4/udp.c:bpf_iter_udp_batch
  - net/ipv4/udp.c:udp_seq_stop
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_get_first
  - net/ipv4/udp.c:udp_get_first
```
```
In net/ipv4/igmp.c (ffffffff8201e76b)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
```
```
In net/ipv4/fib_trie.c (ffffffff8202bb6d)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_start
  - net/ipv4/fib_trie.c:fib_trie_seq_next
  - net/ipv4/fib_trie.c:fib_trie_seq_start
```
```
In net/ipv4/ping.c (ffffffff82031b19)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_next
```
```
In net/ipv4/ipmr.c (ffffffff82042aa5)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_seq_start
  - net/ipv4/ipmr.c:ipmr_mfc_seq_start
  - net/ipv4/ipmr.c:ipmr_vif_seq_start
  - net/ipv4/ipmr.c:ipmr_vif_seq_start
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/linux/seq_file_net.h:18
Inline: True
```
```
In net/unix/af_unix.c (ffffffff8207835f)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/unix/af_unix.c:bpf_iter_unix_batch
  - net/unix/af_unix.c:unix_seq_next
  - net/unix/af_unix.c:unix_get_first
  - net/unix/af_unix.c:unix_get_first
```
```
In net/ipv6/anycast.c (ffffffff82080d78)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_seq_start
```
```
In net/ipv6/addrconf.c (ffffffff8208ac9a)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_start
```
```
In net/ipv6/ip6_fib.c (ffffffff820a89f7)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
```
```
In net/ipv6/mcast.c (ffffffff820c0ac5)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_start
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff820d4711)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_next
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
```
```
In net/ipv6/ip6mr.c (ffffffff820dadf5)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_start
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_start
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_start
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_start
```
```
In net/packet/af_packet.c (ffffffff820f50a8)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_next
  - net/packet/af_packet.c:packet_seq_start
```
```
In net/wireless/wext-proc.c (ffffffff8211e345)
Location: include/linux/seq_file_net.h:18
Inline: True
Inline callers:
  - net/wireless/wext-proc.c:wireless_dev_seq_next
  - net/wireless/wext-proc.c:wireless_dev_seq_start
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
In fs/proc/proc_net.c (ffff80001044d0e8)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - fs/proc/proc_net.c:seq_release_net
```
```
In net/core/sock.c (ffff800010baa658)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/core/neighbour.c (ffff800010be1774)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/core/net-procfs.c (ffff800010c0e0f8)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/core/net-procfs.c:dev_seq_next
  - net/core/net-procfs.c:dev_seq_start
```
```
In net/netlink/af_netlink.c (ffff800010c4b1f8)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_seq_next
```
```
In net/netfilter/nf_log.c (ffff800010c55420)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8ba24)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv4/raw.c (ffff800010c9683c)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_get_first
```
```
In net/ipv4/udp.c (ffff800010c9ad44)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
```
```
In net/ipv4/igmp.c (ffff800010cb0344)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
```
```
In net/ipv4/fib_trie.c (ffff800010cbaf9c)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_start
  - net/ipv4/fib_trie.c:fib_trie_seq_next
  - net/ipv4/fib_trie.c:fib_trie_seq_start
```
```
In net/ipv4/ping.c (ffff800010cc01c4)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/ipv4/ipmr.c (ffff800010cc9730)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_seq_start
  - net/ipv4/ipmr.c:ipmr_mfc_seq_start
  - net/ipv4/ipmr.c:ipmr_vif_seq_start
  - net/ipv4/ipmr.c:ipmr_vif_seq_start
```
```
In net/ipv4/ipmr_base.c (ffff800010cd1348)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/unix/af_unix.c (ffff800010ceefec)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/anycast.c (ffff800010cf6ec4)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_seq_start
```
```
In net/ipv6/addrconf.c (ffff800010cfecf0)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_start
```
```
In net/ipv6/ip6_fib.c (ffff800010d19ccc)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
```
```
In net/ipv6/mcast.c (ffff800010d30834)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_start
```
```
In net/ipv6/ip6_flowlabel.c (ffff800010d3e488)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
```
```
In net/ipv6/ip6mr.c (ffff800010d42c58)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_start
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_start
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_start
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_start
```
```
In net/packet/af_packet.c (ffff800010d568dc)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_next
  - net/packet/af_packet.c:packet_seq_start
```
```
In net/wireless/wext-proc.c (ffff800010d61d84)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/wireless/wext-proc.c:wireless_dev_seq_next
  - net/wireless/wext-proc.c:wireless_dev_seq_start
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
In fs/proc/proc_net.c (c06117e0)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - fs/proc/proc_net.c:seq_release_net
```
```
In net/core/sock.c (c0cc9470)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/core/neighbour.c (c0cfb5cc)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_get_first
  - net/core/neighbour.c:neigh_get_next
  - net/core/neighbour.c:neigh_get_first
```
```
In net/core/net-procfs.c (c0d26124)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/core/net-procfs.c:dev_seq_next
  - net/core/net-procfs.c:dev_seq_start
```
```
In net/netlink/af_netlink.c (c0d5bd34)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_seq_next
```
```
In net/netfilter/nf_log.c (c0d64eb8)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (c0d9a0e0)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_first
  - net/ipv4/tcp_ipv4.c:listening_get_next
```
```
In net/ipv4/raw.c (c0da4ed0)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_get_first
```
```
In net/ipv4/udp.c (c0da7e70)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_get_first
```
```
In net/ipv4/igmp.c (c0db95bc)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
```
```
In net/ipv4/fib_trie.c (c0dc6898)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_start
  - net/ipv4/fib_trie.c:fib_trie_seq_next
  - net/ipv4/fib_trie.c:fib_trie_seq_start
```
```
In net/ipv4/ping.c (c0dcb3b4)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_next
  - net/ipv4/ping.c:ping_get_first
```
```
In net/ipv4/ipmr.c (c0dd4e54)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_seq_start
  - net/ipv4/ipmr.c:ipmr_mfc_seq_start
  - net/ipv4/ipmr.c:ipmr_vif_seq_start
  - net/ipv4/ipmr.c:ipmr_vif_seq_start
```
```
In net/ipv4/ipmr_base.c (c0ddb0ac)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/unix/af_unix.c (c0df69d0)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/anycast.c (c0dfd650)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_seq_start
```
```
In net/ipv6/addrconf.c (c0e05b80)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_start
```
```
In net/ipv6/ip6_fib.c (c0e1ef1c)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
```
```
In net/ipv6/mcast.c (c0e31404)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_start
```
```
In net/ipv6/ip6_flowlabel.c (c0e4192c)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_next
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ip6fl_get_next
```
```
In net/ipv6/ip6mr.c (c0e45a08)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_start
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_start
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_start
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_start
```
```
In net/packet/af_packet.c (c0e57064)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_next
  - net/packet/af_packet.c:packet_seq_start
```
```
In net/wireless/wext-proc.c (c0e61158)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/wireless/wext-proc.c:wireless_dev_seq_next
  - net/wireless/wext-proc.c:wireless_dev_seq_start
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
In fs/proc/proc_net.c (c000000000564850)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - fs/proc/proc_net.c:seq_release_net
```
```
In net/core/sock.c (c000000000c8104c)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/core/neighbour.c (c000000000cc252c)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_get_next
  - net/core/neighbour.c:pneigh_get_first
  - net/core/neighbour.c:neigh_get_next
  - net/core/neighbour.c:neigh_get_first
```
```
In net/core/net-procfs.c (c000000000cf9940)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/core/net-procfs.c:dev_seq_next
  - net/core/net-procfs.c:dev_seq_start
```
```
In net/netlink/af_netlink.c (c000000000d494bc)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_seq_next
```
```
In net/netfilter/nf_log.c (c000000000d55884)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (c000000000d98354)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_first
  - net/ipv4/tcp_ipv4.c:listening_get_next
```
```
In net/ipv4/raw.c (c000000000da8298)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_get_first
```
```
In net/ipv4/udp.c (c000000000daba88)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_get_first
```
```
In net/ipv4/igmp.c (c000000000dc42c0)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
```
```
In net/ipv4/fib_trie.c (c000000000dd469c)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_start
  - net/ipv4/fib_trie.c:fib_trie_seq_next
  - net/ipv4/fib_trie.c:fib_trie_seq_start
```
```
In net/ipv4/ping.c (c000000000dda894)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_next
  - net/ipv4/ping.c:ping_get_first
```
```
In net/ipv4/ipmr.c (c000000000de7540)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_seq_start
  - net/ipv4/ipmr.c:ipmr_mfc_seq_start
  - net/ipv4/ipmr.c:ipmr_vif_seq_start
  - net/ipv4/ipmr.c:ipmr_vif_seq_start
```
```
In net/ipv4/ipmr_base.c (c000000000def050)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/unix/af_unix.c (c000000000e14b74)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/anycast.c (c000000000e1d65c)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_seq_start
```
```
In net/ipv6/addrconf.c (c000000000e263f4)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_start
```
```
In net/ipv6/ip6_fib.c (c000000000e46f9c)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
```
```
In net/ipv6/mcast.c (c000000000e60260)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_start
```
```
In net/ipv6/ip6_flowlabel.c (c000000000e72e24)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_next
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ip6fl_get_next
```
```
In net/ipv6/ip6mr.c (c000000000e78220)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_start
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_start
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_start
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_start
```
```
In net/packet/af_packet.c (c000000000e8fc9c)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_next
  - net/packet/af_packet.c:packet_seq_start
```
```
In net/wireless/wext-proc.c (c000000000e9d168)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/wireless/wext-proc.c:wireless_dev_seq_next
  - net/wireless/wext-proc.c:wireless_dev_seq_start
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
In fs/proc/proc_net.c (ffffffe0002e1b52)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - fs/proc/proc_net.c:seq_release_net
```
```
In net/core/sock.c (ffffffe00073e278)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/core/neighbour.c (ffffffe000767662)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_get_next
  - net/core/neighbour.c:pneigh_get_first
  - net/core/neighbour.c:neigh_get_next
  - net/core/neighbour.c:neigh_get_first
```
```
In net/core/net-procfs.c (ffffffe00078abb8)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/core/net-procfs.c:dev_seq_next
  - net/core/net-procfs.c:dev_seq_start
```
```
In net/netlink/af_netlink.c (ffffffe0007b84ac)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_seq_next
```
```
In net/netfilter/nf_log.c (ffffffe0007bf8a6)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007eb568)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_first
  - net/ipv4/tcp_ipv4.c:listening_get_next
```
```
In net/ipv4/raw.c (ffffffe0007f5a62)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_get_first
```
```
In net/ipv4/udp.c (ffffffe0007f752a)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_get_first
```
```
In net/ipv4/igmp.c (ffffffe000807f38)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
```
```
In net/ipv4/fib_trie.c (ffffffe00081177e)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_start
  - net/ipv4/fib_trie.c:fib_trie_seq_next
  - net/ipv4/fib_trie.c:fib_trie_seq_start
```
```
In net/ipv4/ping.c (ffffffe000815686)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_next
  - net/ipv4/ping.c:ping_get_first
```
```
In net/ipv4/ipmr.c (ffffffe00081e21a)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_seq_start
  - net/ipv4/ipmr.c:ipmr_mfc_seq_start
  - net/ipv4/ipmr.c:ipmr_vif_seq_start
  - net/ipv4/ipmr.c:ipmr_vif_seq_start
```
```
In net/ipv4/ipmr_base.c (ffffffe0008227c4)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/unix/af_unix.c (ffffffe00083c0b8)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/anycast.c (ffffffe000842458)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_seq_start
```
```
In net/ipv6/addrconf.c (ffffffe0008484c8)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_start
```
```
In net/ipv6/ip6_fib.c (ffffffe00085dcbe)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
```
```
In net/ipv6/mcast.c (ffffffe00086e27e)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_start
```
```
In net/ipv6/ip6_flowlabel.c (ffffffe00087ab58)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_next
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ip6fl_get_next
```
```
In net/ipv6/ip6mr.c (ffffffe00087e70c)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_start
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_start
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_start
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_start
```
```
In net/packet/af_packet.c (ffffffe00088e256)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_next
  - net/packet/af_packet.c:packet_seq_start
```
```
In net/wireless/wext-proc.c (ffffffe000896708)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/wireless/wext-proc.c:wireless_dev_seq_next
  - net/wireless/wext-proc.c:wireless_dev_seq_start
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
In fs/proc/proc_net.c (ffffffff81377e55)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - fs/proc/proc_net.c:seq_release_net
```
```
In net/core/sock.c (ffffffff818b3390)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/core/neighbour.c (ffffffff818e1b42)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/core/net-procfs.c (ffffffff81908223)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/core/net-procfs.c:dev_seq_next
  - net/core/net-procfs.c:dev_seq_start
```
```
In net/netlink/af_netlink.c (ffffffff8193db43)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_seq_next
```
```
In net/netfilter/nf_log.c (ffffffff81945bc5)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81978246)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv4/raw.c (ffffffff81982799)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_get_first
```
```
In net/ipv4/udp.c (ffffffff81985ddd)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
```
```
In net/ipv4/igmp.c (ffffffff81996cf1)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
```
```
In net/ipv4/fib_trie.c (ffffffff819a23a5)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_start
  - net/ipv4/fib_trie.c:fib_trie_seq_next
  - net/ipv4/fib_trie.c:fib_trie_seq_start
```
```
In net/ipv4/ping.c (ffffffff819a7065)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819af289)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_seq_start
  - net/ipv4/ipmr.c:ipmr_mfc_seq_start
  - net/ipv4/ipmr.c:ipmr_vif_seq_start
  - net/ipv4/ipmr.c:ipmr_vif_seq_start
```
```
In net/ipv4/ipmr_base.c (ffffffff819b4bee)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/unix/af_unix.c (ffffffff819cf198)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/anycast.c (ffffffff819d5a5d)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_seq_start
```
```
In net/ipv6/addrconf.c (ffffffff819dcfca)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_start
```
```
In net/ipv6/ip6_fib.c (ffffffff819f414a)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
```
```
In net/ipv6/mcast.c (ffffffff81a071b1)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_start
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a15166)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
```
```
In net/ipv6/ip6mr.c (ffffffff81a18ee9)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_start
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_start
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_start
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_start
```
```
In net/packet/af_packet.c (ffffffff81a29175)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_next
  - net/packet/af_packet.c:packet_seq_start
```
```
In net/wireless/wext-proc.c (ffffffff81a33195)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/wireless/wext-proc.c:wireless_dev_seq_next
  - net/wireless/wext-proc.c:wireless_dev_seq_start
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
In fs/proc/proc_net.c (ffffffff81368925)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - fs/proc/proc_net.c:seq_release_net
```
```
In net/core/sock.c (ffffffff8186d2e0)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/core/neighbour.c (ffffffff8189b982)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/core/net-procfs.c (ffffffff818c2033)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/core/net-procfs.c:dev_seq_next
  - net/core/net-procfs.c:dev_seq_start
```
```
In net/netlink/af_netlink.c (ffffffff818f7643)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_seq_next
```
```
In net/netfilter/nf_log.c (ffffffff818ff6b5)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81931d06)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv4/raw.c (ffffffff8193c259)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_get_first
```
```
In net/ipv4/udp.c (ffffffff8193f89d)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
```
```
In net/ipv4/igmp.c (ffffffff819507b1)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
```
```
In net/ipv4/fib_trie.c (ffffffff8195be65)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_start
  - net/ipv4/fib_trie.c:fib_trie_seq_next
  - net/ipv4/fib_trie.c:fib_trie_seq_start
```
```
In net/ipv4/ping.c (ffffffff81960b25)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8196b8b9)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_seq_start
  - net/ipv4/ipmr.c:ipmr_mfc_seq_start
  - net/ipv4/ipmr.c:ipmr_vif_seq_start
  - net/ipv4/ipmr.c:ipmr_vif_seq_start
```
```
In net/ipv4/ipmr_base.c (ffffffff8197121e)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/unix/af_unix.c (ffffffff8198bf58)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/anycast.c (ffffffff8199281d)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_seq_start
```
```
In net/ipv6/addrconf.c (ffffffff81999d8a)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_start
```
```
In net/ipv6/ip6_fib.c (ffffffff819b0f0a)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
```
```
In net/ipv6/mcast.c (ffffffff819c3f71)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_start
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff819d1f26)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
```
```
In net/ipv6/ip6mr.c (ffffffff819d5ca9)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_start
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_start
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_start
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_start
```
```
In net/packet/af_packet.c (ffffffff819e6365)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_next
  - net/packet/af_packet.c:packet_seq_start
```
```
In net/wireless/wext-proc.c (ffffffff819f0275)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/wireless/wext-proc.c:wireless_dev_seq_next
  - net/wireless/wext-proc.c:wireless_dev_seq_start
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
In fs/proc/proc_net.c (ffffffff81375925)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - fs/proc/proc_net.c:seq_release_net
```
```
In net/core/sock.c (ffffffff81904390)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/core/neighbour.c (ffffffff81932b72)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/core/net-procfs.c (ffffffff81959253)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/core/net-procfs.c:dev_seq_next
  - net/core/net-procfs.c:dev_seq_start
```
```
In net/netlink/af_netlink.c (ffffffff8198ecd3)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_seq_next
```
```
In net/netfilter/nf_log.c (ffffffff81996d55)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/netfilter/nfnetlink_queue.c (ffffffff8199ac05)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_queue.c:seq_stop
  - net/netfilter/nfnetlink_queue.c:seq_next
  - net/netfilter/nfnetlink_queue.c:seq_start
  - net/netfilter/nfnetlink_queue.c:seq_start
  - net/netfilter/nfnetlink_queue.c:seq_start
```
```
In net/netfilter/nfnetlink_log.c (ffffffff8199b2ce)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_log.c:seq_next
  - net/netfilter/nfnetlink_log.c:seq_start
```
```
In net/netfilter/nf_conntrack_standalone.c (ffffffff819a1055)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_standalone.c:ct_cpu_seq_show
  - net/netfilter/nf_conntrack_standalone.c:ct_cpu_seq_next
  - net/netfilter/nf_conntrack_standalone.c:ct_cpu_seq_start
  - net/netfilter/nf_conntrack_standalone.c:ct_seq_show
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e2a16)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv4/raw.c (ffffffff819ecf69)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_get_first
```
```
In net/ipv4/udp.c (ffffffff819f05ad)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
```
```
In net/ipv4/igmp.c (ffffffff81a01591)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
```
```
In net/ipv4/fib_trie.c (ffffffff81a0cc45)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_start
  - net/ipv4/fib_trie.c:fib_trie_seq_next
  - net/ipv4/fib_trie.c:fib_trie_seq_start
```
```
In net/ipv4/ping.c (ffffffff81a11905)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a19b29)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_seq_start
  - net/ipv4/ipmr.c:ipmr_mfc_seq_start
  - net/ipv4/ipmr.c:ipmr_vif_seq_start
  - net/ipv4/ipmr.c:ipmr_vif_seq_start
```
```
In net/ipv4/ipmr_base.c (ffffffff81a1f48e)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/unix/af_unix.c (ffffffff81a39c18)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/anycast.c (ffffffff81a404dd)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_seq_start
```
```
In net/ipv6/addrconf.c (ffffffff81a47a4a)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_start
```
```
In net/ipv6/ip6_fib.c (ffffffff81a5ebca)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
```
```
In net/ipv6/mcast.c (ffffffff81a71c31)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_start
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a7fbe6)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
```
```
In net/ipv6/ip6mr.c (ffffffff81a83969)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_start
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_start
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_start
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_start
```
```
In net/packet/af_packet.c (ffffffff81a94d25)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_next
  - net/packet/af_packet.c:packet_seq_start
```
```
In net/wireless/wext-proc.c (ffffffff81a9ed45)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/wireless/wext-proc.c:wireless_dev_seq_next
  - net/wireless/wext-proc.c:wireless_dev_seq_start
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
In fs/proc/proc_net.c (ffffffff813893d5)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - fs/proc/proc_net.c:seq_release_net
```
```
In net/core/sock.c (ffffffff81925410)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/core/neighbour.c (ffffffff819544a2)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/core/net-procfs.c (ffffffff8197b3c3)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/core/net-procfs.c:dev_seq_next
  - net/core/net-procfs.c:dev_seq_start
```
```
In net/netlink/af_netlink.c (ffffffff819b1593)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_seq_next
```
```
In net/netfilter/nf_log.c (ffffffff819b9a15)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ec886)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv4/raw.c (ffffffff819f6e59)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_get_next
  - net/ipv4/raw.c:raw_get_first
```
```
In net/ipv4/udp.c (ffffffff819fb62d)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_next
```
```
In net/ipv4/igmp.c (ffffffff81a0ba81)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_mc_seq_next
  - net/ipv4/igmp.c:igmp_mc_seq_start
```
```
In net/ipv4/fib_trie.c (ffffffff81a1743d)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_start
  - net/ipv4/fib_trie.c:fib_trie_seq_next
  - net/ipv4/fib_trie.c:fib_trie_seq_start
```
```
In net/ipv4/ping.c (ffffffff81a1c275)
Location: include/linux/seq_file_net.h:16
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a24919)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_seq_start
  - net/ipv4/ipmr.c:ipmr_mfc_seq_start
  - net/ipv4/ipmr.c:ipmr_vif_seq_start
  - net/ipv4/ipmr.c:ipmr_vif_seq_start
```
```
In net/ipv4/ipmr_base.c (ffffffff81a2a980)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/unix/af_unix.c (ffffffff81a46258)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_next_socket
  - net/unix/af_unix.c:unix_next_socket
```
```
In net/ipv6/anycast.c (ffffffff81a4c139)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_seq_start
```
```
In net/ipv6/addrconf.c (ffffffff81a5395a)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:if6_seq_next
  - net/ipv6/addrconf.c:if6_seq_start
```
```
In net/ipv6/ip6_fib.c (ffffffff81a6b04a)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
```
```
In net/ipv6/mcast.c (ffffffff81a7e251)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_start
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a8c4a6)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
```
```
In net/ipv6/ip6mr.c (ffffffff81a902e9)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_start
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_start
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_start
  - net/ipv6/ip6mr.c:ip6mr_vif_seq_start
```
```
In net/packet/af_packet.c (ffffffff81aa0e75)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_next
  - net/packet/af_packet.c:packet_seq_start
```
```
In net/wireless/wext-proc.c (ffffffff81aaaf45)
Location: include/linux/seq_file_net.h:16
Inline: True
Inline callers:
  - net/wireless/wext-proc.c:wireless_dev_seq_next
  - net/wireless/wext-proc.c:wireless_dev_seq_start
```
</details>
</li>
</ul>

## Differences
