# Function: <code>sock_init_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void sock_init_data(struct socket *sock, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81700cc0)
Location: net/core/sock.c:2364
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_chr_open
  - net/netlink/af_netlink.c:__netlink_create
  - net/unix/af_unix.c:unix_create1
  - net/ipv6/af_inet6.c:inet6_create
  - net/packet/af_packet.c:packet_create
```
**Symbols:**

```
ffffffff81700cc0-ffffffff81700edb: sock_init_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void sock_init_data(struct socket *sock, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81767840)
Location: net/core/sock.c:2437
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_chr_open
  - net/netlink/af_netlink.c:__netlink_create
  - net/unix/af_unix.c:unix_create1
  - net/ipv6/af_inet6.c:inet6_create
  - net/packet/af_packet.c:packet_create
```
**Symbols:**

```
ffffffff81767840-ffffffff81767a5b: sock_init_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sock_init_data(struct socket *sock, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81794840)
Location: net/core/sock.c:2461
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_chr_open
  - net/netlink/af_netlink.c:__netlink_create
  - net/unix/af_unix.c:unix_create1
  - net/ipv6/af_inet6.c:inet6_create
  - net/packet/af_packet.c:packet_create
```
**Symbols:**

```
ffffffff81794840-ffffffff81794a7b: sock_init_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sock_init_data(struct socket *sock, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817b2a60)
Location: net/core/sock.c:2621
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_chr_open
  - net/netlink/af_netlink.c:__netlink_create
  - net/unix/af_unix.c:unix_create1
  - net/packet/af_packet.c:packet_create
```
**Symbols:**

```
ffffffff817b2a60-ffffffff817b2c70: sock_init_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sock_init_data(struct socket *sock, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8182ad30)
Location: net/core/sock.c:2680
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_chr_open
  - net/netlink/af_netlink.c:__netlink_create
  - net/unix/af_unix.c:unix_create1
  - net/packet/af_packet.c:packet_create
```
**Symbols:**

```
ffffffff8182ad30-ffffffff8182af54: sock_init_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sock_init_data(struct socket *sock, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81874e20)
Location: net/core/sock.c:2755
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_chr_open
  - net/netlink/af_netlink.c:__netlink_create
  - net/unix/af_unix.c:unix_create1
  - net/packet/af_packet.c:packet_create
  - net/xdp/xsk.c:xsk_create
```
**Symbols:**

```
ffffffff81874e20-ffffffff81875045: sock_init_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sock_init_data(struct socket *sock, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818956e0)
Location: net/core/sock.c:2699
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_chr_open
  - net/netlink/af_netlink.c:__netlink_create
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/unix/af_unix.c:unix_create1
  - net/packet/af_packet.c:packet_create
  - net/xdp/xsk.c:xsk_create
```
**Symbols:**

```
ffffffff818956e0-ffffffff81895912: sock_init_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sock_init_data(struct socket *sock, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818dfc00)
Location: net/core/sock.c:2842
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_chr_open
  - net/netlink/af_netlink.c:__netlink_create
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/unix/af_unix.c:unix_create1
  - net/packet/af_packet.c:packet_create
  - net/xdp/xsk.c:xsk_create
```
**Symbols:**

```
ffffffff818dfc00-ffffffff818dfe3f: sock_init_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sock_init_data(struct socket *sock, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81911db0)
Location: net/core/sock.c:2857
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_chr_open
  - net/netlink/af_netlink.c:__netlink_create
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/unix/af_unix.c:unix_create1
  - net/packet/af_packet.c:packet_create
  - net/xdp/xsk.c:xsk_create
```
**Symbols:**

```
ffffffff81911db0-ffffffff81911fef: sock_init_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sock_init_data(struct socket *sock, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e3d60)
Location: net/core/sock.c:2986
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_chr_open
  - net/netlink/af_netlink.c:__netlink_create
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/unix/af_unix.c:unix_create1
  - net/packet/af_packet.c:packet_create
  - net/xdp/xsk.c:xsk_create
```
**Symbols:**

```
ffffffff819e3d60-ffffffff819e3f96: sock_init_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sock_init_data(struct socket *sock, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e36a0)
Location: net/core/sock.c:2965
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_chr_open
  - net/netlink/af_netlink.c:__netlink_create
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/unix/af_unix.c:unix_create1
  - net/packet/af_packet.c:packet_create
  - net/xdp/xsk.c:xsk_create
```
**Symbols:**

```
ffffffff819e36a0-ffffffff819e38d6: sock_init_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sock_init_data(struct socket *sock, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819c9720)
Location: net/core/sock.c:2988
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_chr_open
  - net/netlink/af_netlink.c:__netlink_create
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/unix/af_unix.c:unix_create1
  - net/packet/af_packet.c:packet_create
  - net/xdp/xsk.c:xsk_create
```
**Symbols:**

```
ffffffff819c9720-ffffffff819c9956: sock_init_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sock_init_data(struct socket *sock, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81a78aa0)
Location: net/core/sock.c:3119
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_chr_open
  - net/netlink/af_netlink.c:__netlink_create
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/unix/af_unix.c:unix_create1
  - net/packet/af_packet.c:packet_create
  - net/xdp/xsk.c:xsk_create
```
**Symbols:**

```
ffffffff81a78aa0-ffffffff81a78d9c: sock_init_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sock_init_data(struct socket *sock, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81bec510)
Location: net/core/sock.c:3304
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_chr_open
  - net/netlink/af_netlink.c:__netlink_create
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/unix/af_unix.c:unix_create1
  - net/packet/af_packet.c:packet_create
  - net/xdp/xsk.c:xsk_create
  - net/mctp/af_mctp.c:mctp_pf_create
```
**Symbols:**

```
ffffffff81bec510-ffffffff81bec824: sock_init_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sock_init_data(struct socket *sock, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81d9a6a0)
Location: net/core/sock.c:3467
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_create
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/unix/af_unix.c:unix_create1
  - net/packet/af_packet.c:packet_create
  - net/xdp/xsk.c:xsk_create
  - net/mctp/af_mctp.c:mctp_pf_create
```
**Symbols:**

```
ffffffff81d9a6a0-ffffffff81d9a706: sock_init_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sock_init_data(struct socket *sock, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81e08f00)
Location: net/core/sock.c:3500
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_create
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/unix/af_unix.c:unix_create1
  - net/packet/af_packet.c:packet_create
  - net/xdp/xsk.c:xsk_create
  - net/mctp/af_mctp.c:mctp_pf_create
```
**Symbols:**

```
ffffffff81e08f00-ffffffff81e08f66: sock_init_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sock_init_data(struct socket *sock, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81ec5970)
Location: net/core/sock.c:3510
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_create
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/unix/af_unix.c:unix_create1
  - net/packet/af_packet.c:packet_create
  - net/xdp/xsk.c:xsk_create
  - net/mctp/af_mctp.c:mctp_pf_create
```
**Symbols:**

```
ffffffff81ec5970-ffffffff81ec59d6: sock_init_data (STB_GLOBAL)
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
void sock_init_data(struct socket *sock, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffff800010ba9938)
Location: net/core/sock.c:2857
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_chr_open
  - net/netlink/af_netlink.c:__netlink_create
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/unix/af_unix.c:unix_create1
  - net/packet/af_packet.c:packet_create
  - net/xdp/xsk.c:xsk_create
```
**Symbols:**

```
ffff800010ba9938-ffff800010ba9ad4: sock_init_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sock_init_data(struct socket *sock, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c0cc7ec8)
Location: net/core/sock.c:2857
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_chr_open
  - net/netlink/af_netlink.c:__netlink_create
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/unix/af_unix.c:unix_create1
  - net/packet/af_packet.c:packet_create
  - net/xdp/xsk.c:xsk_create
```
**Symbols:**

```
c0cc7ec8-c0cc80a8: sock_init_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sock_init_data(struct socket *sock, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c000000000c7edf0)
Location: net/core/sock.c:2857
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_chr_open
  - net/netlink/af_netlink.c:__netlink_create
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/unix/af_unix.c:unix_create1
  - net/packet/af_packet.c:packet_create
  - net/xdp/xsk.c:xsk_create
```
**Symbols:**

```
c000000000c7edf0-c000000000c7eff0: sock_init_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sock_init_data(struct socket *sock, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffe00073ce6a)
Location: net/core/sock.c:2857
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_chr_open
  - net/netlink/af_netlink.c:__netlink_create
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/unix/af_unix.c:unix_create1
  - net/packet/af_packet.c:packet_create
  - net/xdp/xsk.c:xsk_create
```
**Symbols:**

```
ffffffe00073ce6a-ffffffe00073cffe: sock_init_data (STB_GLOBAL)
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
void sock_init_data(struct socket *sock, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818b1db0)
Location: net/core/sock.c:2857
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_chr_open
  - net/netlink/af_netlink.c:__netlink_create
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/unix/af_unix.c:unix_create1
  - net/packet/af_packet.c:packet_create
  - net/xdp/xsk.c:xsk_create
```
**Symbols:**

```
ffffffff818b1db0-ffffffff818b1fef: sock_init_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sock_init_data(struct socket *sock, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8186bd00)
Location: net/core/sock.c:2857
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_chr_open
  - net/netlink/af_netlink.c:__netlink_create
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/unix/af_unix.c:unix_create1
  - net/packet/af_packet.c:packet_create
  - net/xdp/xsk.c:xsk_create
```
**Symbols:**

```
ffffffff8186bd00-ffffffff8186bf3f: sock_init_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sock_init_data(struct socket *sock, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81902db0)
Location: net/core/sock.c:2857
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_chr_open
  - net/netlink/af_netlink.c:__netlink_create
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/unix/af_unix.c:unix_create1
  - net/packet/af_packet.c:packet_create
  - net/xdp/xsk.c:xsk_create
```
**Symbols:**

```
ffffffff81902db0-ffffffff81902fef: sock_init_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sock_init_data(struct socket *sock, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81923d20)
Location: net/core/sock.c:2857
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_chr_open
  - net/netlink/af_netlink.c:__netlink_create
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/unix/af_unix.c:unix_create1
  - net/packet/af_packet.c:packet_create
  - net/xdp/xsk.c:xsk_create
```
**Symbols:**

```
ffffffff81923d20-ffffffff81923f5f: sock_init_data (STB_GLOBAL)
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
