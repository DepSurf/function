# Function: <code>csum16_add</code>

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
In net/core/filter.c (ffffffff81732459)
Location: include/net/checksum.h:74
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/ipv4/af_inet.c (ffffffff817934d8)
Location: include/net/checksum.h:74
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/ipv4/inet_lro.c (ffffffff817abb4d)
Location: include/net/checksum.h:74
Inline: True
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
In net/core/filter.c (ffffffff8179c85d)
Location: include/net/checksum.h:74
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/ipv4/af_inet.c (ffffffff81800a98)
Location: include/net/checksum.h:74
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
  - net/ipv4/af_inet.c:inet_gro_complete
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
In net/core/filter.c (ffffffff817cbafd)
Location: include/net/checksum.h:74
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/ipv4/af_inet.c (ffffffff818319ed)
Location: include/net/checksum.h:74
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
  - net/ipv4/af_inet.c:inet_gro_complete
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
In net/core/filter.c (ffffffff817eabdd)
Location: include/net/checksum.h:74
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/ipv4/af_inet.c (ffffffff81852f79)
Location: include/net/checksum.h:74
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
  - net/ipv4/af_inet.c:inet_gro_complete
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
In net/core/filter.c (ffffffff81866de9)
Location: include/net/checksum.h:74
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/ipv4/af_inet.c (ffffffff818d2dbd)
Location: include/net/checksum.h:74
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
  - net/ipv4/af_inet.c:inet_gro_complete
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
In net/core/filter.c (ffffffff818b6821)
Location: include/net/checksum.h:74
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/ipv4/udp_offload.c (ffffffff81920db4)
Location: include/net/checksum.h:74
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/af_inet.c (ffffffff81929366)
Location: include/net/checksum.h:74
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
  - net/ipv4/af_inet.c:inet_gro_complete
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
In net/core/filter.c (ffffffff818dba21)
Location: include/net/checksum.h:74
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/ipv4/udp_offload.c (ffffffff8194f921)
Location: include/net/checksum.h:74
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/af_inet.c (ffffffff81958fa3)
Location: include/net/checksum.h:74
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
  - net/ipv4/af_inet.c:inet_gro_complete
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
In net/core/filter.c (ffffffff81928eb9)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/ipv4/udp_offload.c (ffffffff819b4193)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/af_inet.c (ffffffff819bda71)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
  - net/ipv4/af_inet.c:inet_gro_complete
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
In net/core/filter.c (ffffffff8195b599)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/ipv4/udp_offload.c (ffffffff819eaec3)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/af_inet.c (ffffffff819f467d)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
  - net/ipv4/af_inet.c:inet_gro_complete
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
In net/core/filter.c (ffffffff81a2fa29)
Location: include/net/checksum.h:64
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/ipv4/udp_offload.c (ffffffff81ad8b34)
Location: include/net/checksum.h:64
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/af_inet.c (ffffffff81ae238d)
Location: include/net/checksum.h:64
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
  - net/ipv4/af_inet.c:inet_gro_complete
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
In net/core/filter.c (ffffffff81a322f9)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/ipv4/udp_offload.c (ffffffff81ae505e)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/af_inet.c (ffffffff81aef213)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2c856)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
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
In net/core/filter.c (ffffffff81a19455)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/ipv4/udp_offload.c (ffffffff81ad028a)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/af_inet.c (ffffffff81ada97d)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1a4a2)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
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
In net/core/filter.c (ffffffff81aca205)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/ipv4/udp_offload.c (ffffffff81b8eca7)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/af_inet.c (ffffffff81b99bbd)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/xfrm/xfrm_input.c (ffffffff81bdeac2)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
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
In net/core/filter.c (ffffffff81c46d5b)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/ipv4/udp_offload.c (ffffffff81d1f96f)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/af_inet.c (ffffffff81d2bb58)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/xfrm/xfrm_input.c (ffffffff81d7594a)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
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
In net/core/filter.c (ffffffff81dfb29b)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/ipv4/udp_offload.c (ffffffff81ee6b5f)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/af_inet.c (ffffffff81ef3768)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/xfrm/xfrm_input.c (ffffffff81f41f7a)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
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
In net/core/filter.c (ffffffff81e6d038)
Location: include/net/checksum.h:72
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/ipv4/udp_offload.c (ffffffff81f463a3)
Location: include/net/checksum.h:72
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/af_inet.c (ffffffff81f53210)
Location: include/net/checksum.h:72
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa17fb)
Location: include/net/checksum.h:72
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
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
In net/core/filter.c (ffffffff81f2c8a8)
Location: include/net/checksum.h:72
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/ipv4/udp_offload.c (ffffffff8200c4e3)
Location: include/net/checksum.h:72
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/af_inet.c (ffffffff820195c0)
Location: include/net/checksum.h:72
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/xfrm/xfrm_input.c (ffffffff8206eb1b)
Location: include/net/checksum.h:72
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm4_remove_tunnel_encap
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
In net/core/filter.c (ffff800010bfc5a4)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/ipv4/udp_offload.c (ffff800010ca0ab0)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/af_inet.c (ffff800010caa024)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
  - net/ipv4/af_inet.c:inet_gro_complete
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
In net/core/filter.c (c0d17394)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/ipv4/udp_offload.c (c0dadc58)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/af_inet.c (c0db68fc)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
  - net/ipv4/af_inet.c:inet_gro_complete
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
In net/core/filter.c (c000000000ce4ea0)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/ipv4/udp_offload.c (c000000000db3424)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/af_inet.c (c000000000dbf8ac)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
  - net/ipv4/af_inet.c:inet_gro_complete
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
In net/core/filter.c (ffffffe0007792d2)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/ipv4/udp_offload.c (ffffffe0007fd13e)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/af_inet.c (ffffffe000804b68)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
  - net/ipv4/af_inet.c:inet_gro_complete
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
In net/core/filter.c (ffffffff818fb569)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/ipv4/udp_offload.c (ffffffff8198ad33)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/af_inet.c (ffffffff8199441d)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
  - net/ipv4/af_inet.c:inet_gro_complete
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
In net/core/filter.c (ffffffff818b5399)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/ipv4/udp_offload.c (ffffffff819447f3)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/af_inet.c (ffffffff8194dedd)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
  - net/ipv4/af_inet.c:inet_gro_complete
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
In net/core/filter.c (ffffffff8194c599)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/ipv4/udp_offload.c (ffffffff819f5503)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/af_inet.c (ffffffff819fecbd)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
  - net/ipv4/af_inet.c:inet_gro_complete
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
In net/core/filter.c (ffffffff8196df59)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/ipv4/udp_offload.c (ffffffff819ff703)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/af_inet.c (ffffffff81a08d5c)
Location: include/net/checksum.h:70
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
  - net/ipv4/af_inet.c:inet_gro_complete
```
</details>
</li>
</ul>

## Differences
