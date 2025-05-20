# Function: <code>pskb_trim_rcsum</code>

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
In net/core/skbuff.c (ffffffff8170a23b)
Location: include/linux/skbuff.h:2739
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/ipv4/ip_input.c (ffffffff8175907a)
Location: include/linux/skbuff.h:2739
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff81759994)
Location: include/linux/skbuff.h:2739
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/udp.c (ffffffff8178a152)
Location: include/linux/skbuff.h:2739
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff817c8db1)
Location: include/linux/skbuff.h:2739
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/udp.c (ffffffff817e4af6)
Location: include/linux/skbuff.h:2739
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff817edf55)
Location: include/linux/skbuff.h:2739
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff817f2f26)
Location: include/linux/skbuff.h:2739
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pskb_trim_rcsum(struct sk_buff *skb, unsigned int len);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8177208b)
Location: include/linux/skbuff.h:2932
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/ipv4/ip_input.c (ffffffff817c540a)
Location: include/linux/skbuff.h:2932
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff817c5d74)
Location: include/linux/skbuff.h:2932
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/udp.c (ffffffff817f765d)
Location: include/linux/skbuff.h:2932
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff818360df)
Location: include/linux/skbuff.h:2932
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/udp.c (ffffffff8185298e)
Location: include/linux/skbuff.h:2932
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff8185c79c)
Location: include/linux/skbuff.h:2932
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81861d7e)
Location: include/linux/skbuff.h:2932
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
```
**Symbols:**

```
ffffffff817c59a0-ffffffff817c59fc: pskb_trim_rcsum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pskb_trim_rcsum(struct sk_buff *skb, unsigned int len);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8179f18b)
Location: include/linux/skbuff.h:2970
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/ipv4/ip_input.c (ffffffff817f4f1a)
Location: include/linux/skbuff.h:2970
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff817f5874)
Location: include/linux/skbuff.h:2970
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/udp.c (ffffffff81828570)
Location: include/linux/skbuff.h:2970
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81867bed)
Location: include/linux/skbuff.h:2970
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/udp.c (ffffffff8188468e)
Location: include/linux/skbuff.h:2970
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff8188e6ac)
Location: include/linux/skbuff.h:2970
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81893cee)
Location: include/linux/skbuff.h:2970
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
```
**Symbols:**

```
ffffffff817f54a0-ffffffff817f54fc: pskb_trim_rcsum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pskb_trim_rcsum(struct sk_buff *skb, unsigned int len);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817be5f7)
Location: include/linux/skbuff.h:3035
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/ipv4/ip_input.c (ffffffff818153ab)
Location: include/linux/skbuff.h:3035
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff81815d04)
Location: include/linux/skbuff.h:3035
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/udp.c (ffffffff81849830)
Location: include/linux/skbuff.h:3035
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff8188c3c7)
Location: include/linux/skbuff.h:3035
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/udp.c (ffffffff818aaa3f)
Location: include/linux/skbuff.h:3035
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff818b4cf3)
Location: include/linux/skbuff.h:3035
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff818ba277)
Location: include/linux/skbuff.h:3035
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
```
**Symbols:**

```
ffffffff81815910-ffffffff8181596a: pskb_trim_rcsum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff81837f97)
Location: include/linux/skbuff.h:3134
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/ipv4/ip_input.c (ffffffff8189457b)
Location: include/linux/skbuff.h:3134
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff81894efb)
Location: include/linux/skbuff.h:3134
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/udp.c (ffffffff818c9095)
Location: include/linux/skbuff.h:3134
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff8190d6bc)
Location: include/linux/skbuff.h:3134
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/udp.c (ffffffff8192d55b)
Location: include/linux/skbuff.h:3134
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81937a63)
Location: include/linux/skbuff.h:3134
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff8193d247)
Location: include/linux/skbuff.h:3134
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
```
**Symbols:**

```
ffffffff81894af0-ffffffff81894b3e: pskb_trim_rcsum.part.9 (STB_LOCAL)
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
In net/core/skbuff.c (ffffffff81882495)
Location: include/linux/skbuff.h:3147
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/ipv4/ip_input.c (ffffffff818e878d)
Location: include/linux/skbuff.h:3147
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/ip_fragment.c (ffffffff818e8f8f)
Location: include/linux/skbuff.h:3147
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/udp.c (ffffffff8191f18d)
Location: include/linux/skbuff.h:3147
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81964a14)
Location: include/linux/skbuff.h:3147
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
```
```
In net/ipv6/udp.c (ffffffff81986070)
Location: include/linux/skbuff.h:3147
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff819908cd)
Location: include/linux/skbuff.h:3147
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81996167)
Location: include/linux/skbuff.h:3147
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
In net/core/skbuff.c (ffffffff818a2f5e)
Location: include/linux/skbuff.h:3224
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/ipv4/ip_input.c (ffffffff8191522e)
Location: include/linux/skbuff.h:3224
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff8191615a)
Location: include/linux/skbuff.h:3224
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/udp.c (ffffffff8194dde7)
Location: include/linux/skbuff.h:3224
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff819993c5)
Location: include/linux/skbuff.h:3224
Inline: True
```
```
In net/ipv6/udp.c (ffffffff819bc93a)
Location: include/linux/skbuff.h:3224
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff819c7011)
Location: include/linux/skbuff.h:3224
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff819cca74)
Location: include/linux/skbuff.h:3224
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
In net/core/skbuff.c (ffffffff818edbe2)
Location: include/linux/skbuff.h:3311
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/ipv4/ip_input.c (ffffffff8197774e)
Location: include/linux/skbuff.h:3311
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff819782be)
Location: include/linux/skbuff.h:3311
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/udp.c (ffffffff819b25c8)
Location: include/linux/skbuff.h:3311
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81a052fe)
Location: include/linux/skbuff.h:3311
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a2b4d3)
Location: include/linux/skbuff.h:3311
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81a362ce)
Location: include/linux/skbuff.h:3311
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a3b569)
Location: include/linux/skbuff.h:3311
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
In net/core/skbuff.c (ffffffff8191fce2)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/ipv4/ip_input.c (ffffffff819ae0de)
Location: include/linux/skbuff.h:3376
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff819aec2e)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/udp.c (ffffffff819e9368)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81a3bee3)
Location: include/linux/skbuff.h:3376
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a62033)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81a6cdee)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a721e9)
Location: include/linux/skbuff.h:3376
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
In net/core/skbuff.c (ffffffff819f3295)
Location: include/linux/skbuff.h:3400
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/ipv4/ip_input.c (ffffffff81a97f86)
Location: include/linux/skbuff.h:3400
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81a9904e)
Location: include/linux/skbuff.h:3400
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/udp.c (ffffffff81ad74d2)
Location: include/linux/skbuff.h:3400
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81b31358)
Location: include/linux/skbuff.h:3400
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/udp.c (ffffffff81b5ad5b)
Location: include/linux/skbuff.h:3400
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81b65d64)
Location: include/linux/skbuff.h:3400
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/exthdrs.c (ffffffff81b6bda2)
Location: include/linux/skbuff.h:3400
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
In net/core/skbuff.c (ffffffff819f32c5)
Location: include/linux/skbuff.h:3426
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/ipv4/ip_input.c (ffffffff81aa1ee6)
Location: include/linux/skbuff.h:3426
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81aa2fbe)
Location: include/linux/skbuff.h:3426
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/udp.c (ffffffff81ae3b22)
Location: include/linux/skbuff.h:3426
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81b3ff83)
Location: include/linux/skbuff.h:3426
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/udp.c (ffffffff81b69502)
Location: include/linux/skbuff.h:3426
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81b744d4)
Location: include/linux/skbuff.h:3426
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/exthdrs.c (ffffffff81b7a812)
Location: include/linux/skbuff.h:3426
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
In net/core/skbuff.c (ffffffff819d9511)
Location: include/linux/skbuff.h:3490
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/ipv4/ip_input.c (ffffffff81a8ce11)
Location: include/linux/skbuff.h:3490
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81a8dfce)
Location: include/linux/skbuff.h:3490
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/udp.c (ffffffff81aced12)
Location: include/linux/skbuff.h:3490
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81b2ddaa)
Location: include/linux/skbuff.h:3490
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/udp.c (ffffffff81b57802)
Location: include/linux/skbuff.h:3490
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81b62f33)
Location: include/linux/skbuff.h:3490
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81b69265)
Location: include/linux/skbuff.h:3490
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
In net/core/skbuff.c (ffffffff81a894d1)
Location: include/linux/skbuff.h:3527
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/ipv4/ip_input.c (ffffffff81b47f61)
Location: include/linux/skbuff.h:3527
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81b491be)
Location: include/linux/skbuff.h:3527
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/udp.c (ffffffff81b8d702)
Location: include/linux/skbuff.h:3527
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81bf403f)
Location: include/linux/skbuff.h:3527
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/udp.c (ffffffff81c1ee09)
Location: include/linux/skbuff.h:3527
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81c2a9e3)
Location: include/linux/skbuff.h:3527
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81c30be2)
Location: include/linux/skbuff.h:3527
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
In net/core/skbuff.c (ffffffff81bfe805)
Location: include/linux/skbuff.h:3901
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/ipv4/ip_input.c (ffffffff81cd5204)
Location: include/linux/skbuff.h:3901
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81cd6f5d)
Location: include/linux/skbuff.h:3901
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_check_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/udp.c (ffffffff81d1e84c)
Location: include/linux/skbuff.h:3901
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81d8ccf7)
Location: include/linux/skbuff.h:3901
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/udp.c (ffffffff81dbb69d)
Location: include/linux/skbuff.h:3901
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81dc7ebe)
Location: include/linux/skbuff.h:3901
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81dce7ba)
Location: include/linux/skbuff.h:3901
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ip6_parse_tlv
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
In net/core/skbuff.c (ffffffff81dad215)
Location: include/linux/skbuff.h:3797
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/ipv4/ip_input.c (ffffffff81e956d4)
Location: include/linux/skbuff.h:3797
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81e974fd)
Location: include/linux/skbuff.h:3797
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_check_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/udp.c (ffffffff81ee598c)
Location: include/linux/skbuff.h:3797
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81f5af07)
Location: include/linux/skbuff.h:3797
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/udp.c (ffffffff81f8b7f9)
Location: include/linux/skbuff.h:3797
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81f98c30)
Location: include/linux/skbuff.h:3797
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81f9f9d7)
Location: include/linux/skbuff.h:3797
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ip6_parse_tlv
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
In net/core/skbuff.c (ffffffff81e1d115)
Location: include/linux/skbuff.h:3831
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/ipv4/ip_input.c (ffffffff81ef3edc)
Location: include/linux/skbuff.h:3831
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81ef5d2d)
Location: include/linux/skbuff.h:3831
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_check_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/udp.c (ffffffff81f4518c)
Location: include/linux/skbuff.h:3831
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81fbacb7)
Location: include/linux/skbuff.h:3831
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/udp.c (ffffffff81febed0)
Location: include/linux/skbuff.h:3831
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81ff9610)
Location: include/linux/skbuff.h:3831
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff8200051c)
Location: include/linux/skbuff.h:3831
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ip6_parse_tlv
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
In net/core/skbuff.c (ffffffff81eda805)
Location: include/linux/skbuff.h:3859
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/ipv4/ip_input.c (ffffffff81fb7e6f)
Location: include/linux/skbuff.h:3859
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffff81fb9cdd)
Location: include/linux/skbuff.h:3859
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_check_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/udp.c (ffffffff8200b1ec)
Location: include/linux/skbuff.h:3859
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff820880e7)
Location: include/linux/skbuff.h:3859
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/udp.c (ffffffff820b9aea)
Location: include/linux/skbuff.h:3859
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff820c7280)
Location: include/linux/skbuff.h:3859
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff820cf2b2)
Location: include/linux/skbuff.h:3859
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ip6_parse_tlv
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
In net/core/skbuff.c (ffff800010bba738)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/ipv4/ip_input.c (ffff800010c5e134)
Location: include/linux/skbuff.h:3376
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffff800010c5f828)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/udp.c (ffff800010c9ec54)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_input.c (ffff800010cfd454)
Location: include/linux/skbuff.h:3376
Inline: True
```
```
In net/ipv6/udp.c (ffff800010d2709c)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffff800010d35550)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/exthdrs.c (ffff800010d3b37c)
Location: include/linux/skbuff.h:3376
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
In net/core/skbuff.c (c0cd6efc)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/ipv4/ip_input.c (c0d6da44)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (c0d6e884)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/udp.c (c0dabeb8)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_input.c (c0e04750)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/udp.c (c0e2c0dc)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (c0e3760c)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/exthdrs.c (c0e3d1c8)
Location: include/linux/skbuff.h:3376
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
In net/core/skbuff.c (c000000000c932e8)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/ipv4/ip_input.c (c000000000d60d74)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (c000000000d61ddc)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/udp.c (c000000000db14ac)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_input.c (c000000000e24ff8)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/udp.c (c000000000e57f2c)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (c000000000e675a8)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/exthdrs.c (c000000000e6e0f0)
Location: include/linux/skbuff.h:3376
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
In net/core/skbuff.c (ffffffe0007499ca)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/ipv4/ip_input.c (ffffffe0007c6c94)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_fragment.c (ffffffe0007c76b0)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/udp.c (ffffffe0007fb7b0)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_input.c (ffffffe00084780e)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/udp.c (ffffffe000868f6a)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffe000872906)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/exthdrs.c (ffffffe000877800)
Location: include/linux/skbuff.h:3376
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
In net/core/skbuff.c (ffffffff818bfce2)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/ipv4/ip_input.c (ffffffff8194df4e)
Location: include/linux/skbuff.h:3376
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff8194ea9e)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/udp.c (ffffffff819891d8)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff819db573)
Location: include/linux/skbuff.h:3376
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a016c3)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81a0c47e)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a11879)
Location: include/linux/skbuff.h:3376
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
In net/core/skbuff.c (ffffffff81879c22)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/ipv4/ip_input.c (ffffffff81907a3e)
Location: include/linux/skbuff.h:3376
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff8190858e)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/udp.c (ffffffff81942c98)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81998333)
Location: include/linux/skbuff.h:3376
Inline: True
```
```
In net/ipv6/udp.c (ffffffff819be483)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff819c923e)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff819ce639)
Location: include/linux/skbuff.h:3376
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
In net/core/skbuff.c (ffffffff81910ce2)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/ipv4/ip_input.c (ffffffff819b871e)
Location: include/linux/skbuff.h:3376
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff819b926e)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/udp.c (ffffffff819f39a8)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81a45ff3)
Location: include/linux/skbuff.h:3376
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a6c143)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81a76efe)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a7c2f9)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
```
```
In net/ipv6/netfilter/nf_conntrack_reasm.c (ffffffff81a90a9b)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_queue
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
In net/core/skbuff.c (ffffffff81931e42)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_trimmed
```
```
In net/ipv4/ip_input.c (ffffffff819c1f7e)
Location: include/linux/skbuff.h:3376
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff819c2b5e)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/udp.c (ffffffff819fdb68)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
```
```
In net/ipv6/ip6_input.c (ffffffff81a51cc2)
Location: include/linux/skbuff.h:3376
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81a78753)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/reassembly.c (ffffffff81a8351e)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81a88b49)
Location: include/linux/skbuff.h:3376
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
</ul>
