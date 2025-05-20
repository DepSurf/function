# Function: <code>sk_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sock *sk_alloc(struct net *net, int family, gfp_t priority, struct proto *prot, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81701320)
Location: net/core/sock.c:1414
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
ffffffff81701320-ffffffff81701456: sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sock *sk_alloc(struct net *net, int family, gfp_t priority, struct proto *prot, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81767580)
Location: net/core/sock.c:1404
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
ffffffff81767580-ffffffff8176772c: sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sock *sk_alloc(struct net *net, int family, gfp_t priority, struct proto *prot, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81794580)
Location: net/core/sock.c:1391
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
ffffffff81794580-ffffffff81794734: sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sock *sk_alloc(struct net *net, int family, gfp_t priority, struct proto *prot, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817b47b0)
Location: net/core/sock.c:1512
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_chr_open
  - net/netlink/af_netlink.c:__netlink_create
  - net/unix/af_unix.c:unix_create1
  - net/packet/af_packet.c:packet_create
```
**Symbols:**

```
ffffffff817b47b0-ffffffff817b49d8: sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sock *sk_alloc(struct net *net, int family, gfp_t priority, struct proto *prot, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8182ca10)
Location: net/core/sock.c:1518
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_chr_open
  - net/netlink/af_netlink.c:__netlink_create
  - net/unix/af_unix.c:unix_create1
  - net/packet/af_packet.c:packet_create
```
**Symbols:**

```
ffffffff8182ca10-ffffffff8182cc38: sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sock *sk_alloc(struct net *net, int family, gfp_t priority, struct proto *prot, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81877520)
Location: net/core/sock.c:1530
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
ffffffff81877520-ffffffff8187772f: sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sock *sk_alloc(struct net *net, int family, gfp_t priority, struct proto *prot, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81897970)
Location: net/core/sock.c:1526
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
ffffffff81897970-ffffffff81897b7f: sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sock *sk_alloc(struct net *net, int family, gfp_t priority, struct proto *prot, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818e1e80)
Location: net/core/sock.c:1652
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
ffffffff818e1e80-ffffffff818e20a7: sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sock *sk_alloc(struct net *net, int family, gfp_t priority, struct proto *prot, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81914050)
Location: net/core/sock.c:1654
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
ffffffff81914050-ffffffff81914277: sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sock *sk_alloc(struct net *net, int family, gfp_t priority, struct proto *prot, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e6850)
Location: net/core/sock.c:1742
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
ffffffff819e6850-ffffffff819e6ab4: sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sock *sk_alloc(struct net *net, int family, gfp_t priority, struct proto *prot, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e6070)
Location: net/core/sock.c:1734
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
ffffffff819e6070-ffffffff819e62ed: sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sock *sk_alloc(struct net *net, int family, gfp_t priority, struct proto *prot, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819cc130)
Location: net/core/sock.c:1766
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
ffffffff819cc130-ffffffff819cc395: sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sock *sk_alloc(struct net *net, int family, gfp_t priority, struct proto *prot, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81a7b790)
Location: net/core/sock.c:1889
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
ffffffff81a7b790-ffffffff81a7b9e2: sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sock *sk_alloc(struct net *net, int family, gfp_t priority, struct proto *prot, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81beef40)
Location: net/core/sock.c:2023
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
ffffffff81beef40-ffffffff81bef19c: sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sock *sk_alloc(struct net *net, int family, gfp_t priority, struct proto *prot, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81d9b780)
Location: net/core/sock.c:2088
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
ffffffff81d9b780-ffffffff81d9b9dc: sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sock *sk_alloc(struct net *net, int family, gfp_t priority, struct proto *prot, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81e09e20)
Location: net/core/sock.c:2146
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
ffffffff81e09e20-ffffffff81e0a07c: sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sock *sk_alloc(struct net *net, int family, gfp_t priority, struct proto *prot, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81ec6810)
Location: net/core/sock.c:2126
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
ffffffff81ec6810-ffffffff81ec6a6c: sk_alloc (STB_GLOBAL)
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
struct sock *sk_alloc(struct net *net, int family, gfp_t priority, struct proto *prot, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffff800010bab078)
Location: net/core/sock.c:1654
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
ffff800010bab078-ffff800010bab204: sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sock *sk_alloc(struct net *net, int family, gfp_t priority, struct proto *prot, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c0cc9b00)
Location: net/core/sock.c:1654
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
c0cc9b00-c0cc9d24: sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sock *sk_alloc(struct net *net, int family, gfp_t priority, struct proto *prot, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c000000000c81830)
Location: net/core/sock.c:1654
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
c000000000c81830-c000000000c81a30: sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sock *sk_alloc(struct net *net, int family, gfp_t priority, struct proto *prot, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffe00073ea40)
Location: net/core/sock.c:1654
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
ffffffe00073ea40-ffffffe00073ebf0: sk_alloc (STB_GLOBAL)
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
struct sock *sk_alloc(struct net *net, int family, gfp_t priority, struct proto *prot, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818b4050)
Location: net/core/sock.c:1654
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
ffffffff818b4050-ffffffff818b4277: sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sock *sk_alloc(struct net *net, int family, gfp_t priority, struct proto *prot, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8186dfa0)
Location: net/core/sock.c:1654
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
ffffffff8186dfa0-ffffffff8186e1c7: sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sock *sk_alloc(struct net *net, int family, gfp_t priority, struct proto *prot, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81905050)
Location: net/core/sock.c:1654
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
ffffffff81905050-ffffffff81905277: sk_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sock *sk_alloc(struct net *net, int family, gfp_t priority, struct proto *prot, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81926120)
Location: net/core/sock.c:1654
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
ffffffff81926120-ffffffff81926364: sk_alloc (STB_GLOBAL)
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
