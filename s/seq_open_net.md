# Function: <code>seq_open_net</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int seq_open_net(struct inode *ino, struct file *f, const struct seq_operations *ops, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff812864e0)
Location: fs/proc/proc_net.c:39
Inline: True
Direct callers:
  - net/core/sock.c:proto_seq_open
  - net/core/net-procfs.c:dev_mc_seq_open
  - net/core/net-procfs.c:ptype_seq_open
  - net/core/net-procfs.c:dev_seq_open
  - net/netlink/af_netlink.c:netlink_seq_open
  - net/netfilter/nf_log.c:nflog_open
  - net/ipv4/tcp_ipv4.c:tcp_seq_open
  - net/ipv4/raw.c:raw_v4_seq_open
  - net/ipv4/udp.c:udp_seq_open
  - net/ipv4/arp.c:arp_seq_open
  - net/ipv4/igmp.c:igmp_mcf_seq_open
  - net/ipv4/igmp.c:igmp_mc_seq_open
  - net/ipv4/fib_trie.c:fib_route_seq_open
  - net/ipv4/fib_trie.c:fib_trie_seq_open
  - net/ipv4/ping.c:ping_seq_open
  - net/ipv4/ipmr.c:ipmr_mfc_open
  - net/ipv4/ipmr.c:ipmr_vif_open
  - net/unix/af_unix.c:unix_seq_open
  - net/ipv6/anycast.c:ac6_seq_open
  - net/ipv6/addrconf.c:if6_seq_open
  - net/ipv6/ip6_fib.c:ipv6_route_open
  - net/ipv6/mcast.c:igmp6_mcf_seq_open
  - net/ipv6/mcast.c:igmp6_mc_seq_open
  - net/ipv6/ip6mr.c:ipmr_mfc_open
  - net/ipv6/ip6mr.c:ip6mr_vif_open
  - net/packet/af_packet.c:packet_seq_open
  - net/wireless/wext-proc.c:seq_open_wireless
```
**Symbols:**

```
ffffffff812864e0-ffffffff81286552: seq_open_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int seq_open_net(struct inode *ino, struct file *f, const struct seq_operations *ops, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff812b3680)
Location: fs/proc/proc_net.c:39
Inline: True
Direct callers:
  - net/core/sock.c:proto_seq_open
  - net/core/net-procfs.c:dev_mc_seq_open
  - net/core/net-procfs.c:ptype_seq_open
  - net/core/net-procfs.c:dev_seq_open
  - net/netlink/af_netlink.c:netlink_seq_open
  - net/netfilter/nf_log.c:nflog_open
  - net/ipv4/tcp_ipv4.c:tcp_seq_open
  - net/ipv4/raw.c:raw_v4_seq_open
  - net/ipv4/udp.c:udp_seq_open
  - net/ipv4/arp.c:arp_seq_open
  - net/ipv4/igmp.c:igmp_mcf_seq_open
  - net/ipv4/igmp.c:igmp_mc_seq_open
  - net/ipv4/fib_trie.c:fib_route_seq_open
  - net/ipv4/fib_trie.c:fib_trie_seq_open
  - net/ipv4/ping.c:ping_seq_open
  - net/ipv4/ipmr.c:ipmr_mfc_open
  - net/ipv4/ipmr.c:ipmr_vif_open
  - net/unix/af_unix.c:unix_seq_open
  - net/ipv6/anycast.c:ac6_seq_open
  - net/ipv6/addrconf.c:if6_seq_open
  - net/ipv6/ip6_fib.c:ipv6_route_open
  - net/ipv6/mcast.c:igmp6_mcf_seq_open
  - net/ipv6/mcast.c:igmp6_mc_seq_open
  - net/ipv6/ip6mr.c:ipmr_mfc_open
  - net/ipv6/ip6mr.c:ip6mr_vif_open
  - net/packet/af_packet.c:packet_seq_open
  - net/wireless/wext-proc.c:seq_open_wireless
```
**Symbols:**

```
ffffffff812b3680-ffffffff812b36f9: seq_open_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int seq_open_net(struct inode *ino, struct file *f, const struct seq_operations *ops, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff812c8ed0)
Location: fs/proc/proc_net.c:40
Inline: True
Direct callers:
  - net/core/sock.c:proto_seq_open
  - net/core/net-procfs.c:dev_mc_seq_open
  - net/core/net-procfs.c:ptype_seq_open
  - net/core/net-procfs.c:dev_seq_open
  - net/netlink/af_netlink.c:netlink_seq_open
  - net/netfilter/nf_log.c:nflog_open
  - net/ipv4/tcp_ipv4.c:tcp_seq_open
  - net/ipv4/raw.c:raw_v4_seq_open
  - net/ipv4/udp.c:udp_seq_open
  - net/ipv4/arp.c:arp_seq_open
  - net/ipv4/igmp.c:igmp_mcf_seq_open
  - net/ipv4/igmp.c:igmp_mc_seq_open
  - net/ipv4/fib_trie.c:fib_route_seq_open
  - net/ipv4/fib_trie.c:fib_trie_seq_open
  - net/ipv4/ping.c:ping_seq_open
  - net/ipv4/ipmr.c:ipmr_mfc_open
  - net/ipv4/ipmr.c:ipmr_vif_open
  - net/unix/af_unix.c:unix_seq_open
  - net/ipv6/anycast.c:ac6_seq_open
  - net/ipv6/addrconf.c:if6_seq_open
  - net/ipv6/ip6_fib.c:ipv6_route_open
  - net/ipv6/mcast.c:igmp6_mcf_seq_open
  - net/ipv6/mcast.c:igmp6_mc_seq_open
  - net/ipv6/ip6mr.c:ipmr_mfc_open
  - net/ipv6/ip6mr.c:ip6mr_vif_open
  - net/packet/af_packet.c:packet_seq_open
  - net/wireless/wext-proc.c:seq_open_wireless
```
**Symbols:**

```
ffffffff812c8ed0-ffffffff812c8f49: seq_open_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int seq_open_net(struct inode *ino, struct file *f, const struct seq_operations *ops, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff812d61d0)
Location: fs/proc/proc_net.c:41
Inline: True
Direct callers:
  - net/core/sock.c:proto_seq_open
  - net/core/net-procfs.c:dev_mc_seq_open
  - net/core/net-procfs.c:ptype_seq_open
  - net/core/net-procfs.c:dev_seq_open
  - net/netlink/af_netlink.c:netlink_seq_open
  - net/netfilter/nf_log.c:nflog_open
  - net/ipv4/tcp_ipv4.c:tcp_seq_open
  - net/ipv4/raw.c:raw_v4_seq_open
  - net/ipv4/udp.c:udp_seq_open
  - net/ipv4/arp.c:arp_seq_open
  - net/ipv4/igmp.c:igmp_mcf_seq_open
  - net/ipv4/igmp.c:igmp_mc_seq_open
  - net/ipv4/fib_trie.c:fib_route_seq_open
  - net/ipv4/fib_trie.c:fib_trie_seq_open
  - net/ipv4/ping.c:ping_seq_open
  - net/ipv4/ipmr.c:ipmr_mfc_open
  - net/ipv4/ipmr.c:ipmr_vif_open
  - net/unix/af_unix.c:unix_seq_open
  - net/ipv6/anycast.c:ac6_seq_open
  - net/ipv6/addrconf.c:if6_seq_open
  - net/ipv6/ip6_fib.c:ipv6_route_open
  - net/ipv6/mcast.c:igmp6_mcf_seq_open
  - net/ipv6/mcast.c:igmp6_mc_seq_open
  - net/ipv6/ip6mr.c:ipmr_mfc_open
  - net/ipv6/ip6mr.c:ip6mr_vif_open
  - net/packet/af_packet.c:packet_seq_open
  - net/wireless/wext-proc.c:seq_open_wireless
```
**Symbols:**

```
ffffffff812d61d0-ffffffff812d6262: seq_open_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int seq_open_net(struct inode *ino, struct file *f, const struct seq_operations *ops, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff812faa10)
Location: fs/proc/proc_net.c:41
Inline: True
Direct callers:
  - net/core/sock.c:proto_seq_open
  - net/core/net-procfs.c:dev_mc_seq_open
  - net/core/net-procfs.c:ptype_seq_open
  - net/core/net-procfs.c:dev_seq_open
  - net/netlink/af_netlink.c:netlink_seq_open
  - net/netfilter/nf_log.c:nflog_open
  - net/ipv4/tcp_ipv4.c:tcp_seq_open
  - net/ipv4/raw.c:raw_v4_seq_open
  - net/ipv4/udp.c:udp_seq_open
  - net/ipv4/arp.c:arp_seq_open
  - net/ipv4/igmp.c:igmp_mcf_seq_open
  - net/ipv4/igmp.c:igmp_mc_seq_open
  - net/ipv4/fib_trie.c:fib_route_seq_open
  - net/ipv4/fib_trie.c:fib_trie_seq_open
  - net/ipv4/ping.c:ping_seq_open
  - net/ipv4/ipmr.c:ipmr_mfc_open
  - net/ipv4/ipmr.c:ipmr_vif_open
  - net/unix/af_unix.c:unix_seq_open
  - net/ipv6/anycast.c:ac6_seq_open
  - net/ipv6/addrconf.c:if6_seq_open
  - net/ipv6/ip6_fib.c:ipv6_route_open
  - net/ipv6/mcast.c:igmp6_mcf_seq_open
  - net/ipv6/mcast.c:igmp6_mc_seq_open
  - net/ipv6/ip6mr.c:ipmr_mfc_open
  - net/ipv6/ip6mr.c:ip6mr_vif_open
  - net/packet/af_packet.c:packet_seq_open
  - net/wireless/wext-proc.c:seq_open_wireless
```
**Symbols:**

```
ffffffff812faa10-ffffffff812faaa2: seq_open_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int seq_open_net(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff81327e50)
Location: fs/proc/proc_net.c:41
Inline: False
```
**Symbols:**

```
ffffffff81327e50-ffffffff81327f45: seq_open_net (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int seq_open_net(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff8133f040)
Location: fs/proc/proc_net.c:57
Inline: False
```
**Symbols:**

```
ffffffff8133f040-ffffffff8133f135: seq_open_net (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int seq_open_net(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff813673a0)
Location: fs/proc/proc_net.c:58
Inline: False
```
**Symbols:**

```
ffffffff813673a0-ffffffff81367462: seq_open_net (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int seq_open_net(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff8137f620)
Location: fs/proc/proc_net.c:58
Inline: False
```
**Symbols:**

```
ffffffff8137f620-ffffffff8137f6e2: seq_open_net (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int seq_open_net(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff813c9ab0)
Location: fs/proc/proc_net.c:58
Inline: False
```
**Symbols:**

```
ffffffff813c9ab0-ffffffff813c9b71: seq_open_net (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int seq_open_net(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff813db6d0)
Location: fs/proc/proc_net.c:42
Inline: False
```
**Symbols:**

```
ffffffff813db6d0-ffffffff813db7da: seq_open_net (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int seq_open_net(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff813e2600)
Location: fs/proc/proc_net.c:42
Inline: False
```
**Symbols:**

```
ffffffff813e2600-ffffffff813e26fe: seq_open_net (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int seq_open_net(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff81434110)
Location: fs/proc/proc_net.c:42
Inline: False
```
**Symbols:**

```
ffffffff81434110-ffffffff8143420e: seq_open_net (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int seq_open_net(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff814ae190)
Location: fs/proc/proc_net.c:42
Inline: False
```
**Symbols:**

```
ffffffff814ae190-ffffffff814ae2a4: seq_open_net (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int seq_open_net(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff81544770)
Location: fs/proc/proc_net.c:39
Inline: False
```
**Symbols:**

```
ffffffff81544770-ffffffff81544884: seq_open_net (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int seq_open_net(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff8157c370)
Location: fs/proc/proc_net.c:39
Inline: False
```
**Symbols:**

```
ffffffff8157c370-ffffffff8157c480: seq_open_net (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int seq_open_net(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff815b4c80)
Location: fs/proc/proc_net.c:39
Inline: False
```
**Symbols:**

```
ffffffff815b4c80-ffffffff815b4d90: seq_open_net (STB_LOCAL)
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
int seq_open_net(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffff80001044cde8)
Location: fs/proc/proc_net.c:58
Inline: False
```
**Symbols:**

```
ffff80001044cde8-ffff80001044cee4: seq_open_net (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int seq_open_net(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (c06114e4)
Location: fs/proc/proc_net.c:58
Inline: False
```
**Symbols:**

```
c06114e4-c06115e8: seq_open_net (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int seq_open_net(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (c000000000564420)
Location: fs/proc/proc_net.c:58
Inline: False
```
**Symbols:**

```
c000000000564420-c00000000056459c: seq_open_net (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int seq_open_net(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffe0002e1b8e)
Location: fs/proc/proc_net.c:58
Inline: False
```
**Symbols:**

```
ffffffe0002e1b8e-ffffffe0002e1c3e: seq_open_net (STB_LOCAL)
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
int seq_open_net(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff81377c00)
Location: fs/proc/proc_net.c:58
Inline: False
```
**Symbols:**

```
ffffffff81377c00-ffffffff81377cc2: seq_open_net (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int seq_open_net(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff813686d0)
Location: fs/proc/proc_net.c:58
Inline: False
```
**Symbols:**

```
ffffffff813686d0-ffffffff81368792: seq_open_net (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int seq_open_net(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff813756d0)
Location: fs/proc/proc_net.c:58
Inline: False
```
**Symbols:**

```
ffffffff813756d0-ffffffff81375792: seq_open_net (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int seq_open_net(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff81389170)
Location: fs/proc/proc_net.c:58
Inline: False
```
**Symbols:**

```
ffffffff81389170-ffffffff81389232: seq_open_net (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct inode *inode</code>
</li>
<li>
<b>Param added. </b>
<code>struct file *file</code>
</li>
<li>
<b>Param removed. </b>
<code>struct inode *ino</code>
</li>
<li>
<b>Param removed. </b>
<code>struct file *f</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct seq_operations *ops</code>
</li>
<li>
<b>Param removed. </b>
<code>int size</code>
</li>
</ul>
</details>
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
