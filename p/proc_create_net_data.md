# Function: <code>proc_create_net_data</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_data(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct seq_operations *ops, unsigned int state_size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff81327ce0)
Location: fs/proc/proc_net.c:84
Inline: False
Direct callers:
  - net/core/sock.c:proto_init_net
  - net/core/net-procfs.c:dev_mc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/netlink/af_netlink.c:netlink_net_init
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_init_net
  - net/ipv4/raw.c:raw_init_net
  - net/ipv4/udp.c:udp4_proc_init_net
  - net/ipv4/udplite.c:udplite4_proc_init_net
  - net/ipv4/arp.c:arp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/ping.c:ping_v4_proc_init_net
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/unix/af_unix.c:unix_net_init
  - net/ipv6/anycast.c:ac6_proc_init
  - net/ipv6/addrconf.c:if6_proc_net_init
  - net/ipv6/route.c:ip6_route_net_init_late
  - net/ipv6/udp.c:udp6_proc_init
  - net/ipv6/udplite.c:udplite6_proc_init_net
  - net/ipv6/raw.c:raw6_init_net
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcp6_proc_init
  - net/ipv6/ping.c:ping_v6_proc_init_net
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init
  - net/ipv6/ip6mr.c:ip6mr_net_init
  - net/ipv6/ip6mr.c:ip6mr_net_init
  - net/packet/af_packet.c:packet_net_init
  - net/wireless/wext-proc.c:wext_proc_init
```
**Symbols:**

```
ffffffff81327ce0-ffffffff81327d33: proc_create_net_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_data(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct seq_operations *ops, unsigned int state_size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff8133eec0)
Location: fs/proc/proc_net.c:100
Inline: False
Direct callers:
  - net/core/sock.c:proto_init_net
  - net/core/net-procfs.c:dev_mc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/netlink/af_netlink.c:netlink_net_init
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_init_net
  - net/ipv4/raw.c:raw_init_net
  - net/ipv4/udp.c:udp4_proc_init_net
  - net/ipv4/udplite.c:udplite4_proc_init_net
  - net/ipv4/arp.c:arp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/ping.c:ping_v4_proc_init_net
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/unix/af_unix.c:unix_net_init
  - net/ipv6/anycast.c:ac6_proc_init
  - net/ipv6/addrconf.c:if6_proc_net_init
  - net/ipv6/route.c:ip6_route_net_init_late
  - net/ipv6/udp.c:udp6_proc_init
  - net/ipv6/udplite.c:udplite6_proc_init_net
  - net/ipv6/raw.c:raw6_init_net
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcp6_proc_init
  - net/ipv6/ping.c:ping_v6_proc_init_net
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init
  - net/ipv6/ip6mr.c:ip6mr_net_init
  - net/ipv6/ip6mr.c:ip6mr_net_init
  - net/packet/af_packet.c:packet_net_init
  - net/wireless/wext-proc.c:wext_proc_init
```
**Symbols:**

```
ffffffff8133eec0-ffffffff8133ef1b: proc_create_net_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_data(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct seq_operations *ops, unsigned int state_size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff81367220)
Location: fs/proc/proc_net.c:101
Inline: False
Direct callers:
  - net/core/sock.c:proto_init_net
  - net/core/net-procfs.c:dev_mc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/netlink/af_netlink.c:netlink_net_init
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_init_net
  - net/ipv4/raw.c:raw_init_net
  - net/ipv4/udp.c:udp4_proc_init_net
  - net/ipv4/udplite.c:udplite4_proc_init_net
  - net/ipv4/arp.c:arp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/ping.c:ping_v4_proc_init_net
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/unix/af_unix.c:unix_net_init
  - net/ipv6/anycast.c:ac6_proc_init
  - net/ipv6/addrconf.c:if6_proc_net_init
  - net/ipv6/route.c:ip6_route_net_init_late
  - net/ipv6/udp.c:udp6_proc_init
  - net/ipv6/udplite.c:udplite6_proc_init_net
  - net/ipv6/raw.c:raw6_init_net
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcp6_proc_init
  - net/ipv6/ping.c:ping_v6_proc_init_net
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init
  - net/ipv6/ip6mr.c:ip6mr_net_init
  - net/ipv6/ip6mr.c:ip6mr_net_init
  - net/packet/af_packet.c:packet_net_init
  - net/wireless/wext-proc.c:wext_proc_init
```
**Symbols:**

```
ffffffff81367220-ffffffff8136727a: proc_create_net_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_data(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct seq_operations *ops, unsigned int state_size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff8137f4a0)
Location: fs/proc/proc_net.c:101
Inline: False
Direct callers:
  - net/core/sock.c:proto_init_net
  - net/core/net-procfs.c:dev_mc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/netlink/af_netlink.c:netlink_net_init
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_init_net
  - net/ipv4/raw.c:raw_init_net
  - net/ipv4/udp.c:udp4_proc_init_net
  - net/ipv4/udplite.c:udplite4_proc_init_net
  - net/ipv4/arp.c:arp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/ping.c:ping_v4_proc_init_net
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/unix/af_unix.c:unix_net_init
  - net/ipv6/anycast.c:ac6_proc_init
  - net/ipv6/addrconf.c:if6_proc_net_init
  - net/ipv6/route.c:ip6_route_net_init_late
  - net/ipv6/udp.c:udp6_proc_init
  - net/ipv6/udplite.c:udplite6_proc_init_net
  - net/ipv6/raw.c:raw6_init_net
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcp6_proc_init
  - net/ipv6/ping.c:ping_v6_proc_init_net
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init
  - net/ipv6/ip6mr.c:ip6mr_net_init
  - net/ipv6/ip6mr.c:ip6mr_net_init
  - net/packet/af_packet.c:packet_net_init
  - net/wireless/wext-proc.c:wext_proc_init
```
**Symbols:**

```
ffffffff8137f4a0-ffffffff8137f4fa: proc_create_net_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_data(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct seq_operations *ops, unsigned int state_size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff813c9710)
Location: fs/proc/proc_net.c:120
Inline: False
Direct callers:
  - net/core/sock.c:proto_init_net
  - net/core/net-procfs.c:dev_mc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/netlink/af_netlink.c:netlink_net_init
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_init_net
  - net/ipv4/raw.c:raw_init_net
  - net/ipv4/udp.c:udp4_proc_init_net
  - net/ipv4/udplite.c:udplite4_proc_init_net
  - net/ipv4/arp.c:arp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/ping.c:ping_v4_proc_init_net
  - net/unix/af_unix.c:unix_net_init
  - net/ipv6/anycast.c:ac6_proc_init
  - net/ipv6/addrconf.c:if6_proc_net_init
  - net/ipv6/route.c:ip6_route_net_init_late
  - net/ipv6/udp.c:udp6_proc_init
  - net/ipv6/udplite.c:udplite6_proc_init_net
  - net/ipv6/raw.c:raw6_init_net
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcp6_proc_init
  - net/ipv6/ping.c:ping_v6_proc_init_net
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init
  - net/packet/af_packet.c:packet_net_init
  - net/wireless/wext-proc.c:wext_proc_init
```
**Symbols:**

```
ffffffff813c9710-ffffffff813c976a: proc_create_net_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_data(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct seq_operations *ops, unsigned int state_size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff813db380)
Location: fs/proc/proc_net.c:104
Inline: False
Direct callers:
  - net/core/sock.c:proto_init_net
  - net/core/net-procfs.c:dev_mc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/netlink/af_netlink.c:netlink_net_init
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_init_net
  - net/ipv4/raw.c:raw_init_net
  - net/ipv4/udp.c:udp4_proc_init_net
  - net/ipv4/udplite.c:udplite4_proc_init_net
  - net/ipv4/arp.c:arp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/ping.c:ping_v4_proc_init_net
  - net/unix/af_unix.c:unix_net_init
  - net/ipv6/anycast.c:ac6_proc_init
  - net/ipv6/addrconf.c:if6_proc_net_init
  - net/ipv6/route.c:ip6_route_net_init_late
  - net/ipv6/udp.c:udp6_proc_init
  - net/ipv6/udplite.c:udplite6_proc_init_net
  - net/ipv6/raw.c:raw6_init_net
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcp6_proc_init
  - net/ipv6/ping.c:ping_v6_proc_init_net
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init
  - net/packet/af_packet.c:packet_net_init
  - net/wireless/wext-proc.c:wext_proc_init
```
**Symbols:**

```
ffffffff813db380-ffffffff813db3da: proc_create_net_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_data(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct seq_operations *ops, unsigned int state_size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff813e22b0)
Location: fs/proc/proc_net.c:104
Inline: False
Direct callers:
  - net/core/sock.c:proto_init_net
  - net/core/net-procfs.c:dev_mc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/netlink/af_netlink.c:netlink_net_init
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_init_net
  - net/ipv4/raw.c:raw_init_net
  - net/ipv4/udp.c:udp4_proc_init_net
  - net/ipv4/udplite.c:udplite4_proc_init_net
  - net/ipv4/arp.c:arp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/ping.c:ping_v4_proc_init_net
  - net/unix/af_unix.c:unix_net_init
  - net/ipv6/anycast.c:ac6_proc_init
  - net/ipv6/addrconf.c:if6_proc_net_init
  - net/ipv6/route.c:ip6_route_net_init_late
  - net/ipv6/udp.c:udp6_proc_init
  - net/ipv6/udplite.c:udplite6_proc_init_net
  - net/ipv6/raw.c:raw6_init_net
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcp6_proc_init
  - net/ipv6/ping.c:ping_v6_proc_init_net
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init
  - net/packet/af_packet.c:packet_net_init
  - net/wireless/wext-proc.c:wext_proc_init
```
**Symbols:**

```
ffffffff813e22b0-ffffffff813e230a: proc_create_net_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_data(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct seq_operations *ops, unsigned int state_size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff81433dc0)
Location: fs/proc/proc_net.c:104
Inline: False
Direct callers:
  - net/core/sock.c:proto_init_net
  - net/core/net-procfs.c:dev_mc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/netlink/af_netlink.c:netlink_net_init
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_init_net
  - net/ipv4/raw.c:raw_init_net
  - net/ipv4/udp.c:udp4_proc_init_net
  - net/ipv4/udplite.c:udplite4_proc_init_net
  - net/ipv4/arp.c:arp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/ping.c:ping_v4_proc_init_net
  - net/unix/af_unix.c:unix_net_init
  - net/ipv6/anycast.c:ac6_proc_init
  - net/ipv6/addrconf.c:if6_proc_net_init
  - net/ipv6/route.c:ip6_route_net_init_late
  - net/ipv6/udp.c:udp6_proc_init
  - net/ipv6/udplite.c:udplite6_proc_init_net
  - net/ipv6/raw.c:raw6_init_net
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcp6_proc_init
  - net/ipv6/ping.c:ping_v6_proc_init_net
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init
  - net/packet/af_packet.c:packet_net_init
  - net/wireless/wext-proc.c:wext_proc_init
```
**Symbols:**

```
ffffffff81433dc0-ffffffff81433e1a: proc_create_net_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_data(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct seq_operations *ops, unsigned int state_size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff814adde0)
Location: fs/proc/proc_net.c:117
Inline: False
Direct callers:
  - net/core/sock.c:proto_init_net
  - net/core/net-procfs.c:dev_mc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/netlink/af_netlink.c:netlink_net_init
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_init_net
  - net/ipv4/raw.c:raw_init_net
  - net/ipv4/udp.c:udp4_proc_init_net
  - net/ipv4/udplite.c:udplite4_proc_init_net
  - net/ipv4/arp.c:arp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/ping.c:ping_v4_proc_init_net
  - net/unix/af_unix.c:unix_net_init
  - net/ipv6/anycast.c:ac6_proc_init
  - net/ipv6/addrconf.c:if6_proc_net_init
  - net/ipv6/route.c:ip6_route_net_init_late
  - net/ipv6/udp.c:udp6_proc_init
  - net/ipv6/udplite.c:udplite6_proc_init_net
  - net/ipv6/raw.c:raw6_init_net
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcp6_proc_init
  - net/ipv6/ping.c:ping_v6_proc_init_net
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init
  - net/packet/af_packet.c:packet_net_init
  - net/wireless/wext-proc.c:wext_proc_init
```
**Symbols:**

```
ffffffff814adde0-ffffffff814ade4c: proc_create_net_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_data(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct seq_operations *ops, unsigned int state_size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff81544350)
Location: fs/proc/proc_net.c:114
Inline: False
Direct callers:
  - net/core/sock.c:proto_init_net
  - net/core/net-procfs.c:dev_mc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/netlink/af_netlink.c:netlink_net_init
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_init_net
  - net/ipv4/raw.c:raw_init_net
  - net/ipv4/udp.c:udp4_proc_init_net
  - net/ipv4/udplite.c:udplite4_proc_init_net
  - net/ipv4/arp.c:arp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/ping.c:ping_v4_proc_init_net
  - net/unix/af_unix.c:unix_net_init
  - net/ipv6/anycast.c:ac6_proc_init
  - net/ipv6/addrconf.c:if6_proc_net_init
  - net/ipv6/route.c:ip6_route_net_init_late
  - net/ipv6/udp.c:udp6_proc_init
  - net/ipv6/udplite.c:udplite6_proc_init_net
  - net/ipv6/raw.c:raw6_init_net
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcp6_proc_init
  - net/ipv6/ping.c:ping_v6_proc_init_net
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init
  - net/packet/af_packet.c:packet_net_init
  - net/wireless/wext-proc.c:wext_proc_init
```
**Symbols:**

```
ffffffff81544350-ffffffff815443bc: proc_create_net_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_data(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct seq_operations *ops, unsigned int state_size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff8157bf50)
Location: fs/proc/proc_net.c:114
Inline: False
Direct callers:
  - net/core/sock.c:proto_init_net
  - net/core/net-procfs.c:dev_mc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/netlink/af_netlink.c:netlink_net_init
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_init_net
  - net/ipv4/raw.c:raw_init_net
  - net/ipv4/udp.c:udp4_proc_init_net
  - net/ipv4/udplite.c:udplite4_proc_init_net
  - net/ipv4/arp.c:arp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/ping.c:ping_v4_proc_init_net
  - net/unix/af_unix.c:unix_net_init
  - net/ipv6/anycast.c:ac6_proc_init
  - net/ipv6/addrconf.c:if6_proc_net_init
  - net/ipv6/route.c:ip6_route_net_init_late
  - net/ipv6/udp.c:udp6_proc_init
  - net/ipv6/udplite.c:udplite6_proc_init_net
  - net/ipv6/raw.c:raw6_init_net
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcp6_proc_init
  - net/ipv6/ping.c:ping_v6_proc_init_net
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init
  - net/packet/af_packet.c:packet_net_init
  - net/wireless/wext-proc.c:wext_proc_init
```
**Symbols:**

```
ffffffff8157bf50-ffffffff8157bfbc: proc_create_net_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_data(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct seq_operations *ops, unsigned int state_size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff815b4860)
Location: fs/proc/proc_net.c:114
Inline: False
Direct callers:
  - net/core/sock.c:proto_init_net
  - net/core/net-procfs.c:dev_mc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/netlink/af_netlink.c:netlink_net_init
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_init_net
  - net/ipv4/raw.c:raw_init_net
  - net/ipv4/udp.c:udp4_proc_init_net
  - net/ipv4/udplite.c:udplite4_proc_init_net
  - net/ipv4/arp.c:arp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/ping.c:ping_v4_proc_init_net
  - net/unix/af_unix.c:unix_net_init
  - net/ipv6/anycast.c:ac6_proc_init
  - net/ipv6/addrconf.c:if6_proc_net_init
  - net/ipv6/route.c:ip6_route_net_init_late
  - net/ipv6/udp.c:udp6_proc_init
  - net/ipv6/udplite.c:udplite6_proc_init_net
  - net/ipv6/raw.c:raw6_init_net
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcp6_proc_init
  - net/ipv6/ping.c:ping_v6_proc_init_net
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init
  - net/packet/af_packet.c:packet_net_init
  - net/wireless/wext-proc.c:wext_proc_init
```
**Symbols:**

```
ffffffff815b4860-ffffffff815b48cc: proc_create_net_data (STB_GLOBAL)
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
struct proc_dir_entry *proc_create_net_data(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct seq_operations *ops, unsigned int state_size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffff80001044cbb0)
Location: fs/proc/proc_net.c:101
Inline: False
Direct callers:
  - net/core/sock.c:proto_init_net
  - net/core/net-procfs.c:dev_mc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/netlink/af_netlink.c:netlink_net_init
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_init_net
  - net/ipv4/raw.c:raw_init_net
  - net/ipv4/udp.c:udp4_proc_init_net
  - net/ipv4/udplite.c:udplite4_proc_init_net
  - net/ipv4/arp.c:arp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/ping.c:ping_v4_proc_init_net
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/unix/af_unix.c:unix_net_init
  - net/ipv6/anycast.c:ac6_proc_init
  - net/ipv6/addrconf.c:if6_proc_net_init
  - net/ipv6/route.c:ip6_route_net_init_late
  - net/ipv6/udp.c:udp6_proc_init
  - net/ipv6/udplite.c:udplite6_proc_init_net
  - net/ipv6/raw.c:raw6_init_net
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcp6_proc_init
  - net/ipv6/ping.c:ping_v6_proc_init_net
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init
  - net/ipv6/ip6mr.c:ip6mr_net_init
  - net/ipv6/ip6mr.c:ip6mr_net_init
  - net/packet/af_packet.c:packet_net_init
  - net/wireless/wext-proc.c:wext_proc_init
```
**Symbols:**

```
ffff80001044cbb0-ffff80001044cc3c: proc_create_net_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_data(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct seq_operations *ops, unsigned int state_size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (c0611344)
Location: fs/proc/proc_net.c:101
Inline: False
Direct callers:
  - net/core/sock.c:proto_init_net
  - net/core/net-procfs.c:dev_mc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/netlink/af_netlink.c:netlink_net_init
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_init_net
  - net/ipv4/raw.c:raw_init_net
  - net/ipv4/udp.c:udp4_proc_init_net
  - net/ipv4/udplite.c:udplite4_proc_init_net
  - net/ipv4/arp.c:arp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/ping.c:ping_v4_proc_init_net
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/unix/af_unix.c:unix_net_init
  - net/ipv6/anycast.c:ac6_proc_init
  - net/ipv6/addrconf.c:if6_proc_net_init
  - net/ipv6/route.c:ip6_route_net_init_late
  - net/ipv6/udp.c:udp6_proc_init
  - net/ipv6/udplite.c:udplite6_proc_init_net
  - net/ipv6/raw.c:raw6_init_net
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcp6_proc_init
  - net/ipv6/ping.c:ping_v6_proc_init_net
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init
  - net/ipv6/ip6mr.c:ip6mr_net_init
  - net/ipv6/ip6mr.c:ip6mr_net_init
  - net/packet/af_packet.c:packet_net_init
  - net/wireless/wext-proc.c:wext_proc_init
```
**Symbols:**

```
c0611344-c06113ac: proc_create_net_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_data(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct seq_operations *ops, unsigned int state_size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (c0000000005641e0)
Location: fs/proc/proc_net.c:101
Inline: False
Direct callers:
  - net/core/sock.c:proto_init_net
  - net/core/net-procfs.c:dev_mc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/netlink/af_netlink.c:netlink_net_init
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_init_net
  - net/ipv4/raw.c:raw_init_net
  - net/ipv4/udp.c:udp4_proc_init_net
  - net/ipv4/udplite.c:udplite4_proc_init_net
  - net/ipv4/arp.c:arp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/ping.c:ping_v4_proc_init_net
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/unix/af_unix.c:unix_net_init
  - net/ipv6/anycast.c:ac6_proc_init
  - net/ipv6/addrconf.c:if6_proc_net_init
  - net/ipv6/route.c:ip6_route_net_init_late
  - net/ipv6/udp.c:udp6_proc_init
  - net/ipv6/udplite.c:udplite6_proc_init_net
  - net/ipv6/raw.c:raw6_init_net
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcp6_proc_init
  - net/ipv6/ping.c:ping_v6_proc_init_net
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init
  - net/ipv6/ip6mr.c:ip6mr_net_init
  - net/ipv6/ip6mr.c:ip6mr_net_init
  - net/packet/af_packet.c:packet_net_init
  - net/wireless/wext-proc.c:wext_proc_init
```
**Symbols:**

```
c0000000005641e0-c000000000564270: proc_create_net_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_data(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct seq_operations *ops, unsigned int state_size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffe0002e1940)
Location: fs/proc/proc_net.c:101
Inline: False
Direct callers:
  - net/core/sock.c:proto_init_net
  - net/core/net-procfs.c:dev_mc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/netlink/af_netlink.c:netlink_net_init
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_init_net
  - net/ipv4/raw.c:raw_init_net
  - net/ipv4/udp.c:udp4_proc_init_net
  - net/ipv4/udplite.c:udplite4_proc_init_net
  - net/ipv4/arp.c:arp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/ping.c:ping_v4_proc_init_net
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/unix/af_unix.c:unix_net_init
  - net/ipv6/anycast.c:ac6_proc_init
  - net/ipv6/addrconf.c:if6_proc_net_init
  - net/ipv6/route.c:ip6_route_net_init_late
  - net/ipv6/udp.c:udp6_proc_init
  - net/ipv6/udplite.c:udplite6_proc_init_net
  - net/ipv6/raw.c:raw6_init_net
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcp6_proc_init
  - net/ipv6/ping.c:ping_v6_proc_init_net
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init
  - net/ipv6/ip6mr.c:ip6mr_net_init
  - net/ipv6/ip6mr.c:ip6mr_net_init
  - net/packet/af_packet.c:packet_net_init
  - net/wireless/wext-proc.c:wext_proc_init
```
**Symbols:**

```
ffffffe0002e1940-ffffffe0002e19be: proc_create_net_data (STB_GLOBAL)
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
struct proc_dir_entry *proc_create_net_data(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct seq_operations *ops, unsigned int state_size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff81377a80)
Location: fs/proc/proc_net.c:101
Inline: False
Direct callers:
  - net/core/sock.c:proto_init_net
  - net/core/net-procfs.c:dev_mc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/netlink/af_netlink.c:netlink_net_init
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_init_net
  - net/ipv4/raw.c:raw_init_net
  - net/ipv4/udp.c:udp4_proc_init_net
  - net/ipv4/udplite.c:udplite4_proc_init_net
  - net/ipv4/arp.c:arp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/ping.c:ping_v4_proc_init_net
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/unix/af_unix.c:unix_net_init
  - net/ipv6/anycast.c:ac6_proc_init
  - net/ipv6/addrconf.c:if6_proc_net_init
  - net/ipv6/route.c:ip6_route_net_init_late
  - net/ipv6/udp.c:udp6_proc_init
  - net/ipv6/udplite.c:udplite6_proc_init_net
  - net/ipv6/raw.c:raw6_init_net
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcp6_proc_init
  - net/ipv6/ping.c:ping_v6_proc_init_net
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init
  - net/ipv6/ip6mr.c:ip6mr_net_init
  - net/ipv6/ip6mr.c:ip6mr_net_init
  - net/packet/af_packet.c:packet_net_init
  - net/wireless/wext-proc.c:wext_proc_init
```
**Symbols:**

```
ffffffff81377a80-ffffffff81377ada: proc_create_net_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_data(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct seq_operations *ops, unsigned int state_size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff81368550)
Location: fs/proc/proc_net.c:101
Inline: False
Direct callers:
  - net/core/sock.c:proto_init_net
  - net/core/net-procfs.c:dev_mc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/netlink/af_netlink.c:netlink_net_init
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_init_net
  - net/ipv4/raw.c:raw_init_net
  - net/ipv4/udp.c:udp4_proc_init_net
  - net/ipv4/udplite.c:udplite4_proc_init_net
  - net/ipv4/arp.c:arp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/ping.c:ping_v4_proc_init_net
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/unix/af_unix.c:unix_net_init
  - net/ipv6/anycast.c:ac6_proc_init
  - net/ipv6/addrconf.c:if6_proc_net_init
  - net/ipv6/route.c:ip6_route_net_init_late
  - net/ipv6/udp.c:udp6_proc_init
  - net/ipv6/udplite.c:udplite6_proc_init_net
  - net/ipv6/raw.c:raw6_init_net
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcp6_proc_init
  - net/ipv6/ping.c:ping_v6_proc_init_net
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init
  - net/ipv6/ip6mr.c:ip6mr_net_init
  - net/ipv6/ip6mr.c:ip6mr_net_init
  - net/packet/af_packet.c:packet_net_init
  - net/wireless/wext-proc.c:wext_proc_init
```
**Symbols:**

```
ffffffff81368550-ffffffff813685aa: proc_create_net_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_data(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct seq_operations *ops, unsigned int state_size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff81375550)
Location: fs/proc/proc_net.c:101
Inline: False
Direct callers:
  - net/core/sock.c:proto_init_net
  - net/core/net-procfs.c:dev_mc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/netlink/af_netlink.c:netlink_net_init
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/netfilter/nfnetlink_queue.c:nfnl_queue_net_init
  - net/netfilter/nfnetlink_log.c:nfnl_log_net_init
  - net/netfilter/nf_conntrack_expect.c:nf_conntrack_expect_pernet_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_init_net
  - net/ipv4/raw.c:raw_init_net
  - net/ipv4/udp.c:udp4_proc_init_net
  - net/ipv4/udplite.c:udplite4_proc_init_net
  - net/ipv4/arp.c:arp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/ping.c:ping_v4_proc_init_net
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/unix/af_unix.c:unix_net_init
  - net/ipv6/anycast.c:ac6_proc_init
  - net/ipv6/addrconf.c:if6_proc_net_init
  - net/ipv6/route.c:ip6_route_net_init_late
  - net/ipv6/udp.c:udp6_proc_init
  - net/ipv6/udplite.c:udplite6_proc_init_net
  - net/ipv6/raw.c:raw6_init_net
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcp6_proc_init
  - net/ipv6/ping.c:ping_v6_proc_init_net
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init
  - net/ipv6/ip6mr.c:ip6mr_net_init
  - net/ipv6/ip6mr.c:ip6mr_net_init
  - net/packet/af_packet.c:packet_net_init
  - net/wireless/wext-proc.c:wext_proc_init
```
**Symbols:**

```
ffffffff81375550-ffffffff813755aa: proc_create_net_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct proc_dir_entry *proc_create_net_data(const char *name, umode_t mode, struct proc_dir_entry *parent, const struct seq_operations *ops, unsigned int state_size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff81388ff0)
Location: fs/proc/proc_net.c:101
Inline: False
Direct callers:
  - net/core/sock.c:proto_init_net
  - net/core/net-procfs.c:dev_mc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/core/net-procfs.c:dev_proc_net_init
  - net/netlink/af_netlink.c:netlink_net_init
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_init_net
  - net/ipv4/raw.c:raw_init_net
  - net/ipv4/udp.c:udp4_proc_init_net
  - net/ipv4/udplite.c:udplite4_proc_init_net
  - net/ipv4/arp.c:arp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/igmp.c:igmp_net_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/fib_trie.c:fib_proc_init
  - net/ipv4/ping.c:ping_v4_proc_init_net
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/ipv4/ipmr.c:ipmr_net_init
  - net/unix/af_unix.c:unix_net_init
  - net/ipv6/anycast.c:ac6_proc_init
  - net/ipv6/addrconf.c:if6_proc_net_init
  - net/ipv6/route.c:ip6_route_net_init_late
  - net/ipv6/udp.c:udp6_proc_init
  - net/ipv6/udplite.c:udplite6_proc_init_net
  - net/ipv6/raw.c:raw6_init_net
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/mcast.c:igmp6_net_init
  - net/ipv6/tcp_ipv6.c:tcp6_proc_init
  - net/ipv6/ping.c:ping_v6_proc_init_net
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_proc_init
  - net/ipv6/ip6mr.c:ip6mr_net_init
  - net/ipv6/ip6mr.c:ip6mr_net_init
  - net/packet/af_packet.c:packet_net_init
  - net/wireless/wext-proc.c:wext_proc_init
```
**Symbols:**

```
ffffffff81388ff0-ffffffff8138904a: proc_create_net_data (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
