# Function: <code>skb_set_mac_header</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_iptunnel.c (ffffffff818a41d9)
Location: include/linux/skbuff.h:2191
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
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
In net/ipv4/xfrm4_input.c (ffffffff818721fa)
Location: include/linux/skbuff.h:2240
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv6/xfrm6_input.c (ffffffff818c5b93)
Location: include/linux/skbuff.h:2240
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818ca824)
Location: include/linux/skbuff.h:2240
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
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
In net/ipv4/xfrm4_input.c (ffffffff818f2c1e)
Location: include/linux/skbuff.h:2327
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv6/xfrm6_input.c (ffffffff81948ec7)
Location: include/linux/skbuff.h:2327
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8194e4bb)
Location: include/linux/skbuff.h:2327
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/ipv4/xfrm4_input.c (ffffffff8194954e)
Location: include/linux/skbuff.h:2338
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv6/xfrm6_input.c (ffffffff819a1fb7)
Location: include/linux/skbuff.h:2338
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819a782a)
Location: include/linux/skbuff.h:2338
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/ipv4/xfrm4_input.c (ffffffff8197b21b)
Location: include/linux/skbuff.h:2416
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv6/xfrm6_input.c (ffffffff819d8c18)
Location: include/linux/skbuff.h:2416
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819de391)
Location: include/linux/skbuff.h:2416
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/ipv4/xfrm4_input.c (ffffffff819e4742)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff819f4b82)
Location: include/linux/skbuff.h:2504
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff819f5f79)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a47487)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a4cef1)
Location: include/linux/skbuff.h:2504
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/ipv4/xfrm4_input.c (ffffffff81a1b752)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2b832)
Location: include/linux/skbuff.h:2518
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2cbf9)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a7e037)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a83ac1)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/ipv4/xfrm4_input.c (ffffffff81b0c7ef)
Location: include/linux/skbuff.h:2541
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1d6c5)
Location: include/linux/skbuff.h:2541
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1f80e)
Location: include/linux/skbuff.h:2541
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_ro_output
  - net/xfrm/xfrm_output.c:xfrm6_transport_output
```
```
In net/ipv6/exthdrs.c (ffffffff81b6cd92)
Location: include/linux/skbuff.h:2541
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b78b91)
Location: include/linux/skbuff.h:2541
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7e89a)
Location: include/linux/skbuff.h:2541
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/ipv4/xfrm4_input.c (ffffffff81b1ab08)
Location: include/linux/skbuff.h:2567
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2bee7)
Location: include/linux/skbuff.h:2567
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2e0de)
Location: include/linux/skbuff.h:2567
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_ro_output
  - net/xfrm/xfrm_output.c:xfrm6_transport_output
```
```
In net/ipv6/exthdrs.c (ffffffff81b7b81e)
Location: include/linux/skbuff.h:2567
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b87afa)
Location: include/linux/skbuff.h:2567
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b8d8aa)
Location: include/linux/skbuff.h:2567
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/ipv4/xfrm4_input.c (ffffffff81b087b8)
Location: include/linux/skbuff.h:2583
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81b19b55)
Location: include/linux/skbuff.h:2583
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1c04c)
Location: include/linux/skbuff.h:2583
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/exthdrs.c (ffffffff81b6a2e6)
Location: include/linux/skbuff.h:2583
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b767aa)
Location: include/linux/skbuff.h:2583
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7c75a)
Location: include/linux/skbuff.h:2583
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/ipv4/xfrm4_input.c (ffffffff81bcb6c3)
Location: include/linux/skbuff.h:2612
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81bdde25)
Location: include/linux/skbuff.h:2612
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81be09d8)
Location: include/linux/skbuff.h:2612
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/exthdrs.c (ffffffff81c32146)
Location: include/linux/skbuff.h:2612
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81c41235)
Location: include/linux/skbuff.h:2612
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81c475f0)
Location: include/linux/skbuff.h:2612
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81c4beaa)
Location: include/linux/skbuff.h:2612
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
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
In net/ipv4/xfrm4_input.c (ffffffff81d6118e)
Location: include/linux/skbuff.h:2981
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81d74f89)
Location: include/linux/skbuff.h:2981
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81d777d4)
Location: include/linux/skbuff.h:2981
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/exthdrs.c (ffffffff81dcf944)
Location: include/linux/skbuff.h:2981
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81ddf9d7)
Location: include/linux/skbuff.h:2981
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81de69d1)
Location: include/linux/skbuff.h:2981
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81debe7e)
Location: include/linux/skbuff.h:2981
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
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
In net/ipv4/xfrm4_input.c (ffffffff81f2ba80)
Location: include/linux/skbuff.h:2875
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81f421c3)
Location: include/linux/skbuff.h:2875
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81f44064)
Location: include/linux/skbuff.h:2875
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/exthdrs.c (ffffffff81fa0cc8)
Location: include/linux/skbuff.h:2875
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81fb1ca1)
Location: include/linux/skbuff.h:2875
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81fb97d5)
Location: include/linux/skbuff.h:2875
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81fbfade)
Location: include/linux/skbuff.h:2875
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
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
In net/ipv4/xfrm4_input.c (ffffffff81f8b8d8)
Location: include/linux/skbuff.h:2929
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa19ab)
Location: include/linux/skbuff.h:2929
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa387b)
Location: include/linux/skbuff.h:2929
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/exthdrs.c (ffffffff8200166f)
Location: include/linux/skbuff.h:2929
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff82012389)
Location: include/linux/skbuff.h:2929
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff82019fca)
Location: include/linux/skbuff.h:2929
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff8201d182)
Location: include/linux/skbuff.h:2929
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_pop_srh
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff82020a6e)
Location: include/linux/skbuff.h:2929
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
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
In net/ipv4/xfrm4_input.c (ffffffff820531d8)
Location: include/linux/skbuff.h:2936
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff8206eccb)
Location: include/linux/skbuff.h:2936
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
  - net/xfrm/xfrm_input.c:xfrm4_remove_beet_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff82070bab)
Location: include/linux/skbuff.h:2936
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/exthdrs.c (ffffffff820d04af)
Location: include/linux/skbuff.h:2936
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff820e14f9)
Location: include/linux/skbuff.h:2936
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820e8f9a)
Location: include/linux/skbuff.h:2936
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff820ec162)
Location: include/linux/skbuff.h:2936
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_pop_srh
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff820efb9e)
Location: include/linux/skbuff.h:2936
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_encap
  - net/ipv6/ioam6_iptunnel.c:ioam6_do_inline
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
In net/ipv4/xfrm4_input.c (ffff800010cd79b4)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffff800010cea2bc)
Location: include/linux/skbuff.h:2518
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffff800010ceb85c)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/xfrm6_input.c (ffff800010d493dc)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffff800010d4f248)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/ipv4/xfrm4_input.c (c0de14cc)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (c0df249c)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/xfrm6_input.c (c0e4a7b4)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (c0e50594)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/ipv4/xfrm4_input.c (c000000000df78e4)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (c000000000e0ddb8)
Location: include/linux/skbuff.h:2518
Inline: True
```
```
In net/xfrm/xfrm_output.c (c000000000e0f5a4)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/xfrm6_input.c (c000000000e7e9a0)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (c000000000e86eb0)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/ipv4/xfrm4_input.c (ffffffe000828064)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffe000837ef4)
Location: include/linux/skbuff.h:2518
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffe0008391cc)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/xfrm6_input.c (ffffffe0008828c6)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffe000888036)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/ipv4/xfrm4_input.c (ffffffff819bade2)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff819caec2)
Location: include/linux/skbuff.h:2518
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff819cc289)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a1d6c7)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a23151)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/ipv4/xfrm4_input.c (ffffffff81977bd2)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81987cb2)
Location: include/linux/skbuff.h:2518
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81989079)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/xfrm6_input.c (ffffffff819da487)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819dff11)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/ipv4/xfrm4_input.c (ffffffff81a25862)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81a35942)
Location: include/linux/skbuff.h:2518
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81a36d09)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a88147)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a8dbd1)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/ipv4/xfrm4_input.c (ffffffff81a30cf4)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81a412ad)
Location: include/linux/skbuff.h:2518
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81a42699)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a94d78)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a9a8d1)
Location: include/linux/skbuff.h:2518
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
</details>
</li>
</ul>

## Differences
