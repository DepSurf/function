# Function: <code>ip_fast_csum</code>

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
In drivers/net/slip/slhc.c (ffffffff815f973d)
Location: arch/x86/include/asm/checksum_64.h:45
Inline: True
```
```
In net/core/netpoll.c (ffffffff817394d2)
Location: arch/x86/include/asm/checksum_64.h:45
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/ip_input.c (ffffffff81758ff2)
Location: arch/x86/include/asm/checksum_64.h:45
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_output.c (ffffffff8175c278)
Location: arch/x86/include/asm/checksum_64.h:45
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_check
```
```
In net/ipv4/raw.c (ffffffff81785530)
Location: arch/x86/include/asm/checksum_64.h:45
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81793bfc)
Location: arch/x86/include/asm/checksum_64.h:45
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (ffffffff81797e49)
Location: arch/x86/include/asm/checksum_64.h:45
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
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
In drivers/net/slip/slhc.c (ffffffff8165962d)
Location: arch/x86/include/asm/checksum_64.h:45
Inline: True
```
```
In net/core/netpoll.c (ffffffff817a5786)
Location: arch/x86/include/asm/checksum_64.h:45
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/ip_input.c (ffffffff817c5392)
Location: arch/x86/include/asm/checksum_64.h:45
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_output.c (ffffffff817c8518)
Location: arch/x86/include/asm/checksum_64.h:45
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_check
```
```
In net/ipv4/raw.c (ffffffff817f2aee)
Location: arch/x86/include/asm/checksum_64.h:45
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff8180132c)
Location: arch/x86/include/asm/checksum_64.h:45
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (ffffffff818057ed)
Location: arch/x86/include/asm/checksum_64.h:45
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
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
In drivers/net/slip/slhc.c (ffffffff816873bd)
Location: arch/x86/include/asm/checksum_64.h:45
Inline: True
```
```
In net/core/netpoll.c (ffffffff817d41f6)
Location: arch/x86/include/asm/checksum_64.h:45
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/ip_input.c (ffffffff817f4ea2)
Location: arch/x86/include/asm/checksum_64.h:45
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_output.c (ffffffff817f8008)
Location: arch/x86/include/asm/checksum_64.h:45
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_check
```
```
In net/ipv4/raw.c (ffffffff818238ed)
Location: arch/x86/include/asm/checksum_64.h:45
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff8183213c)
Location: arch/x86/include/asm/checksum_64.h:45
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (ffffffff81836c3d)
Location: arch/x86/include/asm/checksum_64.h:45
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
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
In drivers/net/slip/slhc.c (ffffffff8169c76d)
Location: arch/x86/include/asm/checksum_64.h:45
Inline: True
```
```
In net/core/netpoll.c (ffffffff817f3544)
Location: arch/x86/include/asm/checksum_64.h:45
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/ip_input.c (ffffffff81815304)
Location: arch/x86/include/asm/checksum_64.h:45
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_output.c (ffffffff818183f8)
Location: arch/x86/include/asm/checksum_64.h:45
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_check
```
```
In net/ipv4/raw.c (ffffffff81844381)
Location: arch/x86/include/asm/checksum_64.h:45
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81854c13)
Location: arch/x86/include/asm/checksum_64.h:45
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (ffffffff81857c9a)
Location: arch/x86/include/asm/checksum_64.h:45
Inline: True
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
In drivers/net/slip/slhc.c (ffffffff817077bd)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
```
```
In net/core/netpoll.c (ffffffff8186e934)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/ip_input.c (ffffffff818944d4)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_output.c (ffffffff81897558)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_check
```
```
In net/ipv4/raw.c (ffffffff818c3cbf)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff818d4ab3)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (ffffffff818d745a)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
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
In drivers/net/slip/slhc.c (ffffffff81746498)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
```
```
In net/core/netpoll.c (ffffffff818bfacd)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/ip_input.c (ffffffff818e8720)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_output.c (ffffffff818eb83f)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_check
```
```
In net/ipv4/raw.c (ffffffff819198c3)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff8192afc7)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (ffffffff8192ddaa)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
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
In drivers/net/slip/slhc.c (ffffffff8176a5a8)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
```
```
In net/core/netpoll.c (ffffffff818e88ed)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ipv4/ip_input.c (ffffffff819151ca)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81918d5f)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_check
```
```
In net/ipv4/raw.c (ffffffff8194819e)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/af_inet.c (ffffffff81958c47)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (ffffffff8195d66e)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
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
In drivers/net/slip/slhc.c (ffffffff817a831c)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
```
```
In net/core/netpoll.c (ffffffff819380ff)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffffffff819438ad)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/ip_input.c (ffffffff819776e8)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff8197ac9f)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_check
```
```
In net/ipv4/raw.c (ffffffff819ac4ad)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff819bd710)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (ffffffff819c22e0)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/xfrm/xfrm_input.c (ffffffff819f4d44)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
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
In drivers/net/slip/slhc.c (ffffffff817cbd8c)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
```
```
In net/core/netpoll.c (ffffffff8196afbf)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffffffff819788ab)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/ip_input.c (ffffffff819ae078)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff819b160f)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_check
```
```
In net/ipv4/raw.c (ffffffff819e2f0a)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff819f4320)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (ffffffff819f8e80)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2b9f4)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
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
In drivers/net/slip/slhc.c (ffffffff818963cf)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
```
```
In net/core/netpoll.c (ffffffff81a3ed29)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffffffff81a4d7e1)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/ip_input.c (ffffffff81a97f20)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_output.c (ffffffff81a9b5af)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_check
```
```
In net/ipv4/raw.c (ffffffff81ad07ed)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/af_inet.c (ffffffff81ae2be8)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (ffffffff81ae6888)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_iphdr
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1dbbe)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
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
In drivers/net/slip/slhc.c (ffffffff818a479f)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
```
```
In net/core/netpoll.c (ffffffff81a41ac9)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffffffff81a534a4)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/ip_input.c (ffffffff81aa1e80)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_output.c (ffffffff81aa541f)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_check
```
```
In net/ipv4/raw.c (ffffffff81adc7fd)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/af_inet.c (ffffffff81aefab5)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (ffffffff81af3758)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_iphdr
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2c48e)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
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
In drivers/net/slip/slhc.c (ffffffff81887205)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
```
```
In net/core/netpoll.c (ffffffff81a2658c)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffffffff81a38d34)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/ip_input.c (ffffffff81a8cdab)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_output.c (ffffffff81a904df)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_check
```
```
In net/ipv4/raw.c (ffffffff81ac783f)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/af_inet.c (ffffffff81adb205)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (ffffffff81adf2bc)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1a0ee)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
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
In drivers/net/slip/slhc.c (ffffffff81918bf5)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
```
```
In net/core/netpoll.c (ffffffff81adb307)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffffffff81aeec24)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/ip_input.c (ffffffff81b47efb)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_output.c (ffffffff81b4b74f)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_check
```
```
In net/ipv4/raw.c (ffffffff81b86093)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/af_inet.c (ffffffff81b9a5b5)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (ffffffff81b9e79c)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/xfrm/xfrm_input.c (ffffffff81bde70e)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
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
In drivers/net/slip/slhc.c (ffffffff81a6dc18)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - drivers/net/slip/slhc.c:slhc_remember
  - drivers/net/slip/slhc.c:slhc_uncompress
```
```
In net/core/netpoll.c (ffffffff81c5c809)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffffffff81c71bb2)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/ip_input.c (ffffffff81cd51a0)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_output.c (ffffffff81cd8c8f)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_check
```
```
In net/ipv4/raw.c (ffffffff81d169d8)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/af_inet.c (ffffffff81d2c95e)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (ffffffff81d30b0b)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/xfrm/xfrm_input.c (ffffffff81d7554e)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
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
In drivers/net/slip/slhc.c (ffffffff81c00bf8)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - drivers/net/slip/slhc.c:slhc_remember
  - drivers/net/slip/slhc.c:slhc_uncompress
```
```
In net/core/netpoll.c (ffffffff81e12ef9)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffffffff81e29ca2)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/ip_input.c (ffffffff81e95670)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_output.c (ffffffff81e9938f)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_check
```
```
In net/ipv4/raw.c (ffffffff81edd187)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/af_inet.c (ffffffff81ef4227)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (ffffffff81ef8c1b)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/xfrm/xfrm_input.c (ffffffff81f41b5e)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
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
In drivers/net/slip/slhc.c (ffffffff81c661db)
Location: arch/x86/include/asm/checksum_64.h:45
Inline: True
Inline callers:
  - drivers/net/slip/slhc.c:slhc_remember
  - drivers/net/slip/slhc.c:slhc_uncompress
```
```
In net/core/netpoll.c (ffffffff81e86823)
Location: arch/x86/include/asm/checksum_64.h:45
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffffffff81e9f2a8)
Location: arch/x86/include/asm/checksum_64.h:45
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/ip_input.c (ffffffff81ef3e70)
Location: arch/x86/include/asm/checksum_64.h:45
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_output.c (ffffffff81ef7c7f)
Location: arch/x86/include/asm/checksum_64.h:45
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_check
```
```
In net/ipv4/raw.c (ffffffff81f3c3d7)
Location: arch/x86/include/asm/checksum_64.h:45
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/af_inet.c (ffffffff81f53b1a)
Location: arch/x86/include/asm/checksum_64.h:45
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (ffffffff81f5868b)
Location: arch/x86/include/asm/checksum_64.h:45
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa13fa)
Location: arch/x86/include/asm/checksum_64.h:45
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
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
In drivers/net/slip/slhc.c (ffffffff81d1cc0b)
Location: arch/x86/include/asm/checksum_64.h:45
Inline: True
Inline callers:
  - drivers/net/slip/slhc.c:slhc_remember
  - drivers/net/slip/slhc.c:slhc_uncompress
```
```
In net/core/netpoll.c (ffffffff81f48830)
Location: arch/x86/include/asm/checksum_64.h:45
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffffffff81f61a15)
Location: arch/x86/include/asm/checksum_64.h:45
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/ip_input.c (ffffffff81fb7e03)
Location: arch/x86/include/asm/checksum_64.h:45
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_output.c (ffffffff81fbbb9f)
Location: arch/x86/include/asm/checksum_64.h:45
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_check
```
```
In net/ipv4/raw.c (ffffffff82002501)
Location: arch/x86/include/asm/checksum_64.h:45
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/af_inet.c (ffffffff82019eda)
Location: arch/x86/include/asm/checksum_64.h:45
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (ffffffff8201eb4b)
Location: arch/x86/include/asm/checksum_64.h:45
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/xfrm/xfrm_input.c (ffffffff8206e71a)
Location: arch/x86/include/asm/checksum_64.h:45
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
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
In drivers/net/slip/slhc.c (ffff800010a05b20)
Location: arch/arm64/include/asm/checksum.h:18
Inline: True
```
```
In net/core/netpoll.c (ffff800010c11774)
Location: arch/arm64/include/asm/checksum.h:18
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffff800010c1f378)
Location: arch/arm64/include/asm/checksum.h:18
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/ip_input.c (ffff800010c5e0c0)
Location: arch/arm64/include/asm/checksum.h:18
Inline: True
```
```
In net/ipv4/ip_output.c (ffff800010c62660)
Location: arch/arm64/include/asm/checksum.h:18
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:__ip_local_out
```
```
In net/ipv4/raw.c (ffff800010c97cac)
Location: arch/arm64/include/asm/checksum.h:18
Inline: True
```
```
In net/ipv4/af_inet.c (ffff800010caa2b0)
Location: arch/arm64/include/asm/checksum.h:18
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (ffff800010cae644)
Location: arch/arm64/include/asm/checksum.h:18
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/xfrm/xfrm_input.c (ffff800010cea498)
Location: arch/arm64/include/asm/checksum.h:18
Inline: True
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
In drivers/net/slip/slhc.c (c0ae0e18)
Location: arch/arm/include/asm/checksum.h:61
Inline: True
```
```
In net/core/netpoll.c (c0d294d8)
Location: arch/arm/include/asm/checksum.h:61
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (c0d36f30)
Location: arch/arm/include/asm/checksum.h:61
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/ip_input.c (c0d6d9c8)
Location: arch/arm/include/asm/checksum.h:61
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_output.c (c0d71518)
Location: arch/arm/include/asm/checksum.h:61
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_check
```
```
In net/ipv4/raw.c (c0da5ac0)
Location: arch/arm/include/asm/checksum.h:61
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/af_inet.c (c0db6a48)
Location: arch/arm/include/asm/checksum.h:61
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (c0dbc954)
Location: arch/arm/include/asm/checksum.h:61
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/xfrm/xfrm_input.c (c0df25b4)
Location: arch/arm/include/asm/checksum.h:61
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
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
In drivers/net/slip/slhc.c (c000000000aacd04)
Location: arch/powerpc/include/asm/checksum.h:148
Inline: True
```
```
In net/core/netpoll.c (c000000000cfe4ec)
Location: arch/powerpc/include/asm/checksum.h:148
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (c000000000d11244)
Location: arch/powerpc/include/asm/checksum.h:148
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/ip_input.c (c000000000d60cf4)
Location: arch/powerpc/include/asm/checksum.h:148
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_output.c (c000000000d6519c)
Location: arch/powerpc/include/asm/checksum.h:148
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_check
```
```
In net/ipv4/raw.c (c000000000da8c2c)
Location: arch/powerpc/include/asm/checksum.h:148
Inline: True
```
```
In net/ipv4/af_inet.c (c000000000dc030c)
Location: arch/powerpc/include/asm/checksum.h:148
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (c000000000dc6a38)
Location: arch/powerpc/include/asm/checksum.h:148
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/xfrm/xfrm_input.c (c000000000e0e03c)
Location: arch/powerpc/include/asm/checksum.h:148
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
__sum16 ip_fast_csum(const void *iph, unsigned int ihl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/checksum.c (ffffffe00048eb3e)
Location: lib/checksum.c:106
Inline: False
Direct callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:ip_fraglist_init
  - net/ipv4/ip_output.c:__ip_local_out
  - net/ipv4/af_inet.c:inet_gro_receive
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
**Symbols:**

```
ffffffe00048eb3e-ffffffe00048eb62: ip_fast_csum (STB_GLOBAL)
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
In drivers/net/slip/slhc.c (ffffffff8179086c)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
```
```
In net/core/netpoll.c (ffffffff8190af8f)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffffffff8191871b)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/ip_input.c (ffffffff8194dee8)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff8195147f)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_check
```
```
In net/ipv4/raw.c (ffffffff81982d7a)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff819940c0)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (ffffffff81998c20)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/xfrm/xfrm_input.c (ffffffff819cb084)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
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
In drivers/net/slip/slhc.c (ffffffff8177963c)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
```
```
In net/core/netpoll.c (ffffffff818c4d2a)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffffffff818d24cb)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/ip_input.c (ffffffff819079d8)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff8190af6f)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_check
```
```
In net/ipv4/raw.c (ffffffff8193c83a)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff8194db80)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (ffffffff819526e0)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/xfrm/xfrm_input.c (ffffffff81987e74)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
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
In drivers/net/slip/slhc.c (ffffffff817c0c0c)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
```
```
In net/core/netpoll.c (ffffffff8195bfbf)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffffffff819698ab)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/ip_input.c (ffffffff819b86b8)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff819bbc4f)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_check
```
```
In net/ipv4/raw.c (ffffffff819ed54a)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff819fe960)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (ffffffff81a034c0)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/xfrm/xfrm_input.c (ffffffff81a35b04)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
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
In drivers/net/slip/slhc.c (ffffffff817daecc)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
```
```
In net/core/netpoll.c (ffffffff8197e39f)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (ffffffff8198bc8b)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/ip_input.c (ffffffff819c1f18)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff819c555f)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_check
```
```
In net/ipv4/raw.c (ffffffff819f742a)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff81a0a739)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (ffffffff81a0da10)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/xfrm/xfrm_input.c (ffffffff81a41474)
Location: arch/x86/include/asm/checksum_64.h:46
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
