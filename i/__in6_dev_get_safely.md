# Function: <code>__in6_dev_get_safely</code>

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
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b4b28)
Location: include/net/addrconf.h:345
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv6/ip6_output.c (ffffffff819622ee)
Location: include/net/addrconf.h:345
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81964b7a)
Location: include/net/addrconf.h:345
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/route.c (ffffffff81970887)
Location: include/net/addrconf.h:345
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
```
```
In net/ipv6/reassembly.c (ffffffff81990b71)
Location: include/net/addrconf.h:345
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff819960b5)
Location: include/net/addrconf.h:345
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
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
In net/core/filter.c (ffffffff818da6e8)
Location: include/net/addrconf.h:353
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv6/ip6_output.c (ffffffff819972be)
Location: include/net/addrconf.h:353
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81999fdb)
Location: include/net/addrconf.h:353
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/route.c (ffffffff819a64b7)
Location: include/net/addrconf.h:353
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
```
```
In net/ipv6/reassembly.c (ffffffff819c72ac)
Location: include/net/addrconf.h:353
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff819cc9c5)
Location: include/net/addrconf.h:353
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
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
In net/core/filter.c (ffffffff81929e74)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv6/ip6_output.c (ffffffff81a03294)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81a05f2c)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/route.c (ffffffff81a12c1f)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
```
```
In net/ipv6/reassembly.c (ffffffff81a364a0)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a3b4a5)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
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
In net/core/filter.c (ffffffff8195c204)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv6/ip6_output.c (ffffffff81a39e64)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81a3ca9c)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/route.c (ffffffff81a4980f)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
```
```
In net/ipv6/reassembly.c (ffffffff81a6cfc0)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a72125)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
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
In net/core/filter.c (ffffffff81a2ffa4)
Location: include/net/addrconf.h:336
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv6/ip6_output.c (ffffffff81b2f6a0)
Location: include/net/addrconf.h:336
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81b3213c)
Location: include/net/addrconf.h:336
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/route.c (ffffffff81b4024e)
Location: include/net/addrconf.h:336
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
```
```
In net/ipv6/reassembly.c (ffffffff81b663e7)
Location: include/net/addrconf.h:336
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81b6bcd5)
Location: include/net/addrconf.h:336
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
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
In net/core/filter.c (ffffffff81a31ca4)
Location: include/net/addrconf.h:339
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv6/ip6_output.c (ffffffff81b3e0f0)
Location: include/net/addrconf.h:339
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81b40d5c)
Location: include/net/addrconf.h:339
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/route.c (ffffffff81b4ec39)
Location: include/net/addrconf.h:339
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
```
```
In net/ipv6/reassembly.c (ffffffff81b74c98)
Location: include/net/addrconf.h:339
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81b7a745)
Location: include/net/addrconf.h:339
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
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
In net/core/filter.c (ffffffff81a18b1b)
Location: include/net/addrconf.h:338
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv6/ip6_output.c (ffffffff81b2c884)
Location: include/net/addrconf.h:338
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81b2ec7c)
Location: include/net/addrconf.h:338
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/route.c (ffffffff81b3ca69)
Location: include/net/addrconf.h:338
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
```
```
In net/ipv6/reassembly.c (ffffffff81b637c6)
Location: include/net/addrconf.h:338
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81b69197)
Location: include/net/addrconf.h:338
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
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
In net/core/filter.c (ffffffff81aca32b)
Location: include/net/addrconf.h:338
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv6/ip6_output.c (ffffffff81bf29d8)
Location: include/net/addrconf.h:338
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81bf4fac)
Location: include/net/addrconf.h:338
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/route.c (ffffffff81c033b9)
Location: include/net/addrconf.h:338
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
```
```
In net/ipv6/reassembly.c (ffffffff81c2b286)
Location: include/net/addrconf.h:338
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81c30b17)
Location: include/net/addrconf.h:338
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
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
In net/core/filter.c (ffffffff81c47747)
Location: include/net/addrconf.h:340
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv6/ip6_output.c (ffffffff81d8b589)
Location: include/net/addrconf.h:340
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81d8ddfc)
Location: include/net/addrconf.h:340
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/route.c (ffffffff81d9d264)
Location: include/net/addrconf.h:340
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
```
```
In net/ipv6/reassembly.c (ffffffff81dc8539)
Location: include/net/addrconf.h:340
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
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
In net/core/filter.c (ffffffff81dfbe17)
Location: include/net/addrconf.h:340
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv6/ip6_output.c (ffffffff81f59599)
Location: include/net/addrconf.h:340
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81f5bf6c)
Location: include/net/addrconf.h:340
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/route.c (ffffffff81f6c194)
Location: include/net/addrconf.h:340
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
```
```
In net/ipv6/reassembly.c (ffffffff81f992c9)
Location: include/net/addrconf.h:340
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
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
In net/core/filter.c (ffffffff81e6f907)
Location: include/net/addrconf.h:340
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv6/ip6_output.c (ffffffff81fb9249)
Location: include/net/addrconf.h:340
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81fbbd1c)
Location: include/net/addrconf.h:340
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/route.c (ffffffff81fcc328)
Location: include/net/addrconf.h:340
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
```
```
In net/ipv6/reassembly.c (ffffffff81ff9c99)
Location: include/net/addrconf.h:340
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
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
In net/core/filter.c (ffffffff81f2f0d5)
Location: include/net/addrconf.h:348
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv6/ip6_output.c (ffffffff820867c9)
Location: include/net/addrconf.h:348
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff8208914c)
Location: include/net/addrconf.h:348
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/route.c (ffffffff82099b0b)
Location: include/net/addrconf.h:348
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
```
```
In net/ipv6/reassembly.c (ffffffff820c7909)
Location: include/net/addrconf.h:348
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
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
In net/core/filter.c (ffff800010bfe0fc)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv6/ip6_output.c (ffff800010cfae20)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffff800010cfddec)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/route.c (ffff800010d11f60)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
```
```
In net/ipv6/reassembly.c (ffff800010d359e4)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffff800010d3b284)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
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
In net/core/filter.c (c0d18840)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv6/ip6_output.c (c0e01714)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (c0e05858)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/route.c (c0e12de0)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
```
```
In net/ipv6/reassembly.c (c0e37c98)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (c0e3d064)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
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
In net/core/filter.c (c000000000ce5b74)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv6/ip6_output.c (c000000000e222a4)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (c000000000e26090)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/route.c (c000000000e37fc0)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
```
```
In net/ipv6/reassembly.c (c000000000e67b00)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (c000000000e6dfd8)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
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
In net/core/filter.c (ffffffe0007801b4)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv6/ip6_output.c (ffffffe0008459d8)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffe000848254)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/route.c (ffffffe000853f5a)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
```
```
In net/ipv6/reassembly.c (ffffffe000872ebe)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffe000877704)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
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
In net/core/filter.c (ffffffff818fc1d4)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv6/ip6_output.c (ffffffff819d94f4)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff819dc12c)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/route.c (ffffffff819e8e9f)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
```
```
In net/ipv6/reassembly.c (ffffffff81a0c650)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a117b5)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
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
In net/core/filter.c (ffffffff818b6004)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv6/ip6_output.c (ffffffff819962b4)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81998eec)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/route.c (ffffffff819a5c5f)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
```
```
In net/ipv6/reassembly.c (ffffffff819c9410)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff819ce575)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
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
In net/core/filter.c (ffffffff8194d204)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv6/ip6_output.c (ffffffff81a43f74)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81a46bac)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/route.c (ffffffff81a5391f)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
```
```
In net/ipv6/reassembly.c (ffffffff81a770d0)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a7c235)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
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
In net/core/filter.c (ffffffff8196ebc4)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv6/ip6_output.c (ffffffff81a4fc14)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81a5291d)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
```
```
In net/ipv6/route.c (ffffffff81a5f90f)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
```
```
In net/ipv6/reassembly.c (ffffffff81a836ee)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a88a85)
Location: include/net/addrconf.h:334
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
```
</details>
</li>
</ul>

## Differences
